# LEGACY LOOT

A digital archive management application for cataloging, organizing, and documenting legacy software artifacts.

## Overview

LEGACY LOOT provides a structured way to record historical software artifacts, versions, descriptions, file metadata, and preservation notes.

The application is designed to make archived materials easier to search, categorize, and maintain.

## Key Features

- Artifact cataloging
- Metadata management
- Search and filtering
- Category and tag management
- Version history records
- Preservation notes
- Archive status tracking
- Exportable catalog records
- Duplicate metadata detection, if implemented

## Technology Stack

- Python
- Flask
- SQLite or PostgreSQL
- HTML5 and CSS3
- Bootstrap

## Project Structure

```text
Legacy-Loot/
├── app.py
├── requirements.txt
├── README.md
├── database/
│   └── schema.sql
├── src/
│   ├── catalog.py
│   ├── metadata.py
│   └── search.py
├── templates/
├── static/
└── tests/
```

## Installation

```bash
git clone https://github.com/amoltathesoftwareengineer/Legacy-Loot.git
cd Legacy-Loot
python -m venv .venv
```

Activate on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Initialize the configured database and run the application:

```bash
python app.py
```

## Data Management

Catalog records may include artifact name, version, format, creation date, description, checksum, and preservation status.

Store only artifacts that you have the right to archive or distribute. Metadata records should distinguish verified information from estimates.

## Future Enhancements

- File checksum verification
- Advanced metadata search
- Archive import and export
- Version comparison
- Preservation activity logs
- Access control and audit history

## Author

Amol Tathe

GitHub: https://github.com/amoltathesoftwareengineer

## License

Add an appropriate open-source license before permitting reuse.
