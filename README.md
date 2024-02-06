# Hoppscotch

## Overview
- `Liyas Thomas` created Hoppscotch as an opensource alternative to Postman. Details are available [here](https://dev.to/liyasthomas/i-created-postwoman-an-online-open-source-api-request-builder-41md)

## Modules
- Scripting
  - The `pw` object provides access to request and response data and variables.
    - request
    - headers
    - body
  - Varaiables are created and removed using `pw.env.set` & `pw.env.unset()`.
  - Variables can be accessed using `pw.env.get`.
  - `<<variableName>>` notation is used to access variables in URL, Headers etc...
  - Tescases can be written using `pw.test` and `pw.expect` is used to run assertions.
- Cli
  - Can be downloaded using below
    ```bash
    npm i -g @hoppscotch/cli
    ```
  - Execution of collection can be done using
    ```bash
    hopp test [-e <environment file>] [-d <delay_in_ms> ] <hoppscotch collection file>
    ```
  
## Tutorial
- [Offical Documentation](https://docs.hoppscotch.io/)