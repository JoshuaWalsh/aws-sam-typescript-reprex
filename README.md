This is a reproducible example to demonstrate the issue aws/aws-toolkit-vscode#2570.

Steps to reproduce:

1. Clone this repo and open it in VSCode.
2. Ensure that VSCode has the "AWS Toolkit" extension installed.
3. Open a terminal in the project's root directory and run `npm install`.
4. Run either of the configured launch configurations.
5. Observe the following error:

> Error: Cannot find module 'dotenv'