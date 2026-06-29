# sample-ssis-package

This repository was created from the [SSIS Copilot Toolkit](https://github.com/samueltauil/sample-ssis-package) template and has the toolkit overlay pre-installed.

## Getting started

1. Build the managed-OM host (one-time):
   ```powershell
   .\tools\lib\SsisOmHost\Build-SsisOmHost.ps1
   ```
2. Open this repo in **Visual Studio 2026 (18.4+)** or **VS Code** with GitHub Copilot Chat enabled.
3. From Copilot Chat, select **ssis-author** from the agent picker to author SSIS packages from metadata JSON, or select **ssis-validator** to run the delivery gate against an existing `.dtsx`.

Detailed conventions live in [`.github/copilot-instructions.md`](.github/copilot-instructions.md) and [`AGENTS.md`](AGENTS.md).

> Adding the overlay to an existing SSIS repository instead?
> ```powershell
> iex (irm https://raw.githubusercontent.com/samueltauil/sample-ssis-package/main/install/Add-CopilotSsisToolkit.ps1)
> ```
