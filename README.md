## 🛠️ **Script Description**

This script automates detailed service scanning with Nmap. Using an Nmap scan result file containing open ports, the script:

    🛡️ Extracts unique IP addresses from the scanned hosts.
    🔍 Identifies open ports and formats them appropriately for Nmap.
    🚀 Automatically runs a detailed scan (-sCV) for each IP and its open ports.
    📁 Saves results in organized files prefixed with versionScan_.

## ⚙️ **How to Use**

    🔓 chmod +x vscan            --> Grant execution permissions to the script.
    📂 mv vscan /usr/local/bin   --> OPTIONAL:  This allows you to run the script from any location. (Note: /usr/local/bin can be replaced with any directory included in the PATH)
    🖥️ vscan <file>              --> Where <file> is the output of an nmap scan in the -oG format.

## 🚨 **Requirements**

    Superuser privileges (sudo) to run Nmap.
    A valid input file with Nmap scan results in -oG format.
