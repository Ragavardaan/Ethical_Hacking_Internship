Backup Script

This script creates a compressed backup of the SecureTech directory.

bash
#!/bin/bash

echo "=============================="
echo "Secure Backup Utility"
echo "=============================="

echo "[*] Creating Backup..."
backup_tool -czf /tmp/securetech_backup.tar.gz /opt/securetech

echo "[+] Backup Completed Successfully"
