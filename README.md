## spfx-codespaces

Repo to demonstrate the `.devcontainer` configuration for SPFx projects in Visual Studio Codespaces.

### Configuration files

[Configuring the codespace](https://docs.microsoft.com/en-us/visualstudio/online/reference/configuring) is accomplished via JSON files/scripts. This repository uses the folder approach.

```
workspace 
├── .devcontainer
│   ├── devcontainer.json
│   ├── spfx-setup.sh
```

The JSON file contains a reference to the script, which is run as a `postCreateCommand`.
