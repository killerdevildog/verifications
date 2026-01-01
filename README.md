# Verifications Repository

This repository serves as a timestamped record of work performed on various projects, particularly those developed offline.

## Purpose

When working on projects offline, there is no way to prove when specific work was completed. This repository provides a solution by storing verification records that include:

- **Timestamp**: When the verification was recorded (UTC)
- **Project Name**: The name of the project being verified
- **Git Commit Hash**: The current commit hash of the project
- **SHA-512 Hash**: A cryptographic hash of all project contents

## File Format

Each line in `verifications.txt` follows this format:
```
[TIMESTAMP] | Project: PROJECT_NAME | Commit: GIT_HASH | SHA-512: CONTENT_HASH
```
