# YouTube_Traking Manual

## Overview

`YouTube_Traking` is the project repository for a YouTube tracking application. The repository is ready for GitHub synchronization, but the current workspace does not yet contain application source files.

## Installation

No installable application package or dependency manifest was found in the workspace yet.

This project is intended to be built as a Windows-only Python desktop application using PySide6, then distributed to employees as an executable file.

After adding source code, document the required setup here, for example:

```powershell
# Example only
python -m venv .venv
.\.venv\Scripts\pip install -r requirements.txt
python main.py
```

## Database Connection Policy

The application must use a Google Drive based `Config_DB.db` configuration database.

All database connection logic should be implemented through the shared `DB_conn.py` module. Feature modules, screens, and worker classes should not create independent database connection code.

## Basic Usage

Application-specific usage cannot be verified until source files are added.

Recommended manual sections to complete after source import:

- Login or authentication flow
- YouTube channel or video registration
- Tracking interval and collection settings
- Data export or reporting workflow
- Error handling and recovery steps

## Maintenance Workflow

1. Add or update source files in the project directory.
2. Keep shared database access in `DB_conn.py`.
3. Update `README.md` and this manual when behavior changes.
4. Run the project test or build command.
5. Build the Windows executable before employee distribution.
6. Commit the verified changes.
7. Push to the GitHub repository.

## Troubleshooting

- If the application does not start, check whether dependencies are installed.
- If YouTube data cannot be collected, check API keys, quota limits, and network access.
- If database connection fails, check Google Drive availability and the `Config_DB.db` path/configuration.
- If GitHub synchronization fails, check Git authentication and remote repository permissions.
