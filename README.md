# Django Starter

## Getting Started with Development

This project uses Visual Studio Code's Remote - Containers (ms-vscode-remote.remote-containers) plugin to build a consistent development environment across workstations.

### Docker

Ensure Docker is installed and running.

### Visual Studio Code

Ensure you have VS Code installed with the following plugins.

- Remote - Containers (ms-vscode-remote.remote-containers)

### Opening the Workspace

Open this directory in VS Code.
Upon launch, VS Code should detect this directory is configured to run in a container and you should be prompted to relaunch in that container.
If it does not, type Cmd-Shift-P (on macOS) to open the Command Palette.
Type "Remote-Containers: Reopen in Container" and hit Enter.

When relaunching, it might take a minute.
Your entire Python development environment is being installed, including Python and your project's dependencies.

### Debugging

This project uses Django so a launch configuration has been created to make running and debugging the application easier.
To launch the application, type Cmd-Shift-D or navigate to the "Run" section on the right.
At the top you'll see the green triangle to start the debug session and a terminal icon with a bug to open the debug console.
If you would like to test debugging, add a breakpoint in [settings.py](./mysite/mysite/settings.py) before launching; be sure to open the debug console to inspect variable values.
