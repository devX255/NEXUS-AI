# Nexus-AI (AUDIT)

Nexus-AI is an automation tool designed to simplify the process of running audit scripts according to the CIS Benchmark on various operating systems, including Ubuntu, Windows, and RHEL.

## Overview

Nexus AI aims to provide a user-friendly interface for IT administrators and security professionals to ensure compliance with the CIS Benchmark standards. By automating the audit process, EasyAudit saves time and reduces the risk of human error.

## Features

* Supports audit scripts for Ubuntu, Windows, and RHEL operating systems
* Automated audit process for CIS Benchmark compliance
* User-friendly interface built with PySide6 and Qt

## Requirements

* Python 3.x
* Qt

## Usage

### Installation

To install EasyAudit, follow these steps:

1. Clone the repository: `git clone https://github.com/your-repo/easy-audit.git`
2. Create a virtual environment: `python -m venv`
3. Activate the virtual environment:
    * On Windows: `venv\Scripts\activate`
    * On Linux/Mac: `source easy-audit-venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Run the application: `python main.py`

### Running an Audit

1. Launch Nexus-AI and select the operating system you want to audit
2. Choose the CIS Benchmark standard you want to comply with
3. Click "Run Audit" to start the automated audit process


