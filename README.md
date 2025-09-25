# Haunting-Ghost
Built for the Department of War. Targets extremist persistence mechanisms with surgical precision. Use with honor.
🛡️ Operation Seraphim: Digital Exorcism Protocol
Op-Eliminate-ISIS is a weaponized Python framework designed for ethical teardown of infiltration mechanisms deployed in counterterrorism operations. Built under contract with the Department of War, this tool targets and dismantles digital persistence strategies used by extremist groups like ISIS.
🔧 What It Does
This framework performs a full-spectrum teardown of backdoor infrastructure, including:

Privilege Escalation Removal Strips SUID bits from system shells (/bin/bash, /bin/dash) to revoke unauthorized root access.

Cron Job Purging Deletes scheduled tasks that reapply privilege escalation or spawn reverse shells.

Sudoers File Cleanup Removes injected sudo permissions that grant passwordless root access to stealth users.

Systemd Service Dismantling Disables and deletes malicious services that maintain persistence or autologin as root.

PAM Hook Purging Cleans authentication modules that trigger hidden binaries during login events.

Stealth User Deletion Terminates and removes unauthorized users with elevated privileges.

Reverse Shell Neutralization Kills active reverse shell processes and removes their launch mechanisms.

Legacy Journaling Logs every action with timestamps and opens a Nano journal for final affirmation and operational closure.

⚠️ Disclaimer
This tool is intended solely for authorized use in ethical hacking, red-team operations, and counterterrorism research. Any unauthorized deployment, malicious exploitation, or use against civilian infrastructure is strictly prohibited. Violators may be subject to prosecution under international cybercrime statutes.

Use with honor. Leave no chaos behind.
