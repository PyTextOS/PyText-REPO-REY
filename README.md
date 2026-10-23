# PyText-REPO-REY
The official PyTextOS 1.0 Applications Repository for PyTextOS Applications. Here, you can upload your own application files. Using the `.mpy` file format. Official applications developed by PyTextOS will use the `.sysrey` file extension.

## Guidelines
Applications may be removed from the repository if it violates one of these guidelines.
1. The application name must not be illegal.
2. The code cannot be desrtuctive towards the operating system.
3. Source code cannot contain illegal content.
4. No copyrighted materials are allowed

## Publication requirements for community-made apps and packages
- Is compatible with Linux
- Installs to PyTextOS' `/C/programs` directory
- The application is command line

## How to use REY package manager
| Command | Action | Example |
|:--|:--|:--|
| `rey upgrade` | Upgrades all installed apps to the latest version | `rey upgrade` |
| `rey update` | Updates the repository list | `rey update` |
| `rey add` | Installs an app to your computer | `rey add calculator` |
| `rey remove` | Uninstalls and app | `rey remove calculator` |
| `rey list` | Lists all packages and apps | `rey list` |
| `rey search` | Search for a specific package or app| `rey search texteditor` |

Use the `-c` flag to only see community-made apps.
Use the `-o` flag to only see official PyTextOS apps.
