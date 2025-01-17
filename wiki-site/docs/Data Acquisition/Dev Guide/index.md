# Developer's Guide

This page was last updated: *{{ git_revision_date_localized }}*

## Dev Tools

The following are necessary and useful for developing the DAQ's firmware.

<div class="grid cards" markdown>

- :octicons-code-16: __[Code Editors]__ – Installing CubeIDE and/or VSCode.
- :fontawesome-solid-hammer: __[Build, Flash, and Debug]__ – Run the firmware on the microcontroller development board.
- :material-usb-port: __[View Serial Output]__ – Read logs transmitted from the device.
- :material-memory: __[View Threads, Queues, and Memory]__ – Extra debugging tools to examine data within concurrency.

</div>

  [Code Editors]: code-editors.md
  [Build, Flash, and Debug]: build-flash-debug.md
  [View Serial Output]: view-serial-output.md
  [View Threads, Queues, and Memory]: view-threads-queues-memory.md

## Automation and DevOps Tools

The following tools enable us to leverage DevOps to introduce automation for efficiently sustaining a long-term project.

<div class="grid cards" markdown>

- :material-test-tube: __[Unit Testing]__ – Test Driven Development (TDD) and Countinuous Integration (CI).
- :material-code-equal: __[Source Code Docs]__ – Writing API docs and Continuous Delivery (CD).

</div>

  [Unit Testing]: unit-testing.md
  [Source Code Docs]: source-code-docs.md


## Standardized Practices

Records of team-agreed standards to maintain consistency within our development. These are by no means a mandate, and may be modified overtime.

<div class="grid cards" markdown>

- :octicons-git-branch-16: __[Contributing and Version Control]__ – Maintaining traceability between branches and issues.
- :material-format-line-style: __[Style Guide]__ – Consistent code formatting patterns.

</div>

  [Contributing and Version Control]: contributing-version-control.md
  [Style Guide]: style-guide.md

## Project Configurations

<div class="grid cards" markdown>

- :octicons-gear-16: __[IDE Project Settings]__ – Records of settings that were made manually.
- :octicons-bug-16: __[Environment Troubleshooting]__ – Dev environment-related errors.

</div>

  [IDE Project Settings]: cubeIDE-cubeMX-settings.md
  [Environment Troubleshooting]: environment-troubleshooting.md