## Overview
`sysopctl` is a custom command-line tool for managing system resources and tasks on Linux. This tool provides functionalities to manage services, monitor processes, check system load, analyze logs, and backup files.

## Features
- Manage system services (start, stop, list)
- Monitor system load and processes
- Analyze system logs
- Backup files

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ravibhatt1810/sysopctl.git

    Navigate to the project directory:

    bash

cd sysopctl

Ensure the script is executable:

bash

    chmod +x scripts/sysopctl.sh

Usage

    To view the manual page:

    bash

man docs/manual/sysopctl.1

To run the script:

bash

./scripts/sysopctl.sh <command>

Example:

bash

./scripts/sysopctl.sh service list
