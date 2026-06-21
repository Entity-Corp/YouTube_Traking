# YouTube_Traking

YouTube tracking project workspace.

## Current Status

This repository has been prepared for source control and GitHub synchronization. At the time of repository initialization, no application source files were present in the project directory, so the functional documentation is limited to the repository structure and operating notes below.

## Repository Structure

```text
.
|-- README.md
|-- docs/
|   `-- MANUAL.md
`-- .gitignore
```

## Features

- GitHub-ready project structure
- Project documentation entry point
- User manual template for future application source

## Development Requirements

- Target platform: Windows only
- Runtime language: Python
- Desktop UI framework: PySide6
- Distribution format: Windows executable file for employees
- Database connection:
  - Use a Google Drive based `Config_DB.db` configuration database.
  - Centralize database access through the shared `DB_conn.py` module.

## Documentation

- [Manual](docs/MANUAL.md)

## Notes

When the completed application source is added to this directory, update this README with:

- application purpose
- installation requirements
- configuration values
- run/build/test commands
- main screens or workflows
- troubleshooting notes

Keep database connection logic out of individual screens or feature modules. New code should call the common `DB_conn.py` module so connection behavior remains consistent across the packaged Windows executable.
