# What is Power BI CLI

The Power BI command-line interface (Power BI CLI) is a set of commands used to create and manage Power BI resources (e.g. reports, users and capacity). The CLI is designed to get you working quickly with Power BI, with an emphasis on automation.

## Key Characteristics

Power BI CLI capabilities make it easy to work with different programing languages and software environments. For example, Power BI CLI:

-   Is available to install in Windows, macOS, and Linux environments.

-   Offers command-line flexibility when managing an Power BI tentant.

## Installing

Open a cmd/bash/powershell prompt and type to install the `powerbi-cli`:

`npm i -g @powerbi-cli/powerbi-cli`

To install a preview version use the following command:

`npm i -g @powerbi-cli/powerbi-cli@preview`

## Usage

To use the `powerbi-cli` type

`pbicli [command] [options]`

To login to the Power BI REST API use:

`pbicli login`

For all available commands and options:

`pbicli --help`

For more information see [documentation](https://powerbi-cli.github.io/)

## Current Version

The current version of the Power BI CLI is 1.3.0. For information about the latest release, see the release notes. To find your installed version and see if you need to update, run `pbicli --version`.
