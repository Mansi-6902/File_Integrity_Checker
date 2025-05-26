# File_Integrity_Checker

## Overview
The File Integrity Checker is a Python-based tool designed to monitor and verify the integrity of files within a specified directory. It detects any unauthorized or unexpected changes to files by computing and comparing cryptographic hashes.

## Features
- Scan files in a target directory recursively.
- Generate SHA-256 hashes for all files.
- Store and maintain a baseline hash database.
- Detect and report any modifications, additions, or deletions of files.
- Easy to use command-line interface.

## How It Works
1. The tool scans the target directory and computes the SHA-256 hash for each file.
2. It compares the current hashes with a previously saved baseline.
3. Any discrepancies indicate potential unauthorized file changes.
4. Reports the integrity status of files, highlighting any tampered or missing files.

## Usage

```bash
python file_integrity_checker.py
