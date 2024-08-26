

---

# README
after cloning run this command to un zip the file
 
unzip scaner.zip


## Installation

```bash
pip install python-nmap termcolor
apt install python3.11-venv
```

## Update

```bash
sudo apt update && sudo apt upgrade
sudo nmap --script-updatedb
```

## Usage

### 1. Setup Virtual Environment

```bash
python3 -m venv myenv
source myenv/bin/activate
pip install python-nmap
```

### 2. Running Scans

- **Scan a single IP:**
  
  ```bash
  python scan.py 192.168.1.1
  ```

- **Scan an IP range with full scan:**
  
  ```bash
  python scan.py 192.168.1.1-10 -t full
  ```

- **Scan a network with vulnerability scan, JSON output, and 20 workers:**
  
  ```bash
  python scan.py 192.168.1.0/24 -t vuln -o json -w 20
  ```

### After All Installations

```bash
python3 -m venv myenv
source myenv/bin/activate
```

--- 

