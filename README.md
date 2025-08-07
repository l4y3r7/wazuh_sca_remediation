Titles: Fix Wazuh SCA Recomendations - Linux Version
Author: Luan Oliveira "l4y3r7"

## Overview
This Python script (`fix_sca.py`) run a list of commands to fix Security configurations based on Wazuh recomendations.

The script performs the following:

- Prompt the user if its desired to fix all issues or just some.
- Run a combination of commans to fix issues
- Validate if changes are needed and revert it if they were made.

## Purpose

This script was created to help IT Professionals like network administators and cybersecurity analyst to improve their SCA score quickly.

## Usage Instructions

1. **Run the script using python3:

   ```Python
   .\fix_sca.py

2. The script will:

 - Ask what type of changes the user want to do.
 - Run the commands to fix issues
 - Provided a simple report

### Important Warnings & Considerations

- Fist run on test or isolated environments.
This script could change important configurations in your system, that may break it.
Run it carefully and paying attention to every comments provided.

- Impact may vary by OS version and environment.
Results depend on system version, some commands may not work as expected.

- Elevated privileges required.
Script requires administrative rights to modify file system configurations.


### License & Disclaimer

The author and distributor disclaim all liability for any damage caused by misuse.

Use responsibly, and always obtain proper authorization before testing or running it on any system.

