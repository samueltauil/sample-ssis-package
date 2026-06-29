<!-- BEGIN: ssis-copilot-toolkit (managed; do not edit between markers) -->
## SSIS Copilot Toolkit

This repo has the [SSIS Copilot Toolkit](https://github.com/samueltauil/sample-ssis-package) overlay installed.

- The custom agent **ssis-author** is the only sanctioned entry point for SSIS work.
- Hand-editing `.dtsx`, `.dtproj`, `.conmgr`, or `.params` is forbidden — packages regenerate from metadata JSON.
- Every SSIS change must pass the [`ssis-delivery-gate`](.github/skills/ssis-delivery-gate/SKILL.md) skill (run by **ssis-validator**).
- Detailed conventions live in [`.github/copilot-instructions.md`](.github/copilot-instructions.md).

Works in Visual Studio 2026 (18.4+) and VS Code with GitHub Copilot Chat.
<!-- END: ssis-copilot-toolkit -->