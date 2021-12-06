# MSBuild Test Action

Run a test command using MSBuild and create test result artifacts.

**Table of Contents**

- [How to use](#how-to-use)

  - [Basic usage](#basic-usage)
  - [Expected inputs](#expected-inputs)
  - [Expected outputs](#expected-outputs)
  - [Use it in a workflow](#use-it-in-a-workflow)

- [Licensing](#licensing)

## How to use

You can include this action in your workflows using this code:

```yaml
runs-on: windows-latest
steps:
  - uses: Daniele-Tentoni/msbuild-test-action@v1
```

This action is tested with any version of windows available in github hosted runners and works only on windows runners.

### Use it in a workflow

I've used this action in work projects, so I can't link you any repository using it. If you use this action, let me know it if is a public repository opening an issue or a discussion and I'll update this file or open a pr with your updates!

## Licensing

This action is created only with educational purpouses with any warranties.
