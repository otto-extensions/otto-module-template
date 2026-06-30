# Otto Module Template

This repository provides the official template for building Otto modules.
It defines the recommended folder structure, manifest formats, and integration patterns for commands, UI panels, and backend logic.

## What This Template Includes
- Example ExtensionManifest
- Example CommandManifest
- Example UIManifest
- Recommended folder structure
- Sample commands and handlers
- Sample UI panel
- Documentation for module authors

## Folder Structure
```
my-module/
├── src/
│   ├── commands/        # Command handlers
│   ├── backend/         # Rust backend logic
│   └── ui/              # Optional UI components
├── manifests/
│   ├── extension.json   # Module metadata
│   ├── commands.json    # Command definitions
│   └── ui.json          # UI definitions
├── docs/                # Developer documentation
└── tests/               # Unit and integration tests`
```
## Getting Started
1. Fork this repository.
2. Rename your fork to match your module.
3. Update the manifests with your module’s details.
4. Implement your commands and UI.
5. Build and test your module.
6. Publish it to the otto-extensions ecosystem.
