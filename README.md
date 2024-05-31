# System-fetch
A simple script written in python to fetch system info

![script output](Sysfetch.png)

## Fetched System Information
### System Information

- System: Operating System Name
- Node Name: Hostname of the machine
- Release: Operating System Release
- Version: Operating System Version
- Machine: Machine Type
- Processor: Processor Type
- CPU Cores: Number of Physical CPU Cores
- Logical CPUs: Number of Logical CPUs
- RAM (Total): Total RAM in GB
- RAM (Used): Used RAM in GB
- RAM (Free): Free RAM in GB

### Disk Information

- Disk Space (Total): Total Disk Space in GB
- Disk Space (Used): Used Disk Space in GB
- Disk Space (Free): Free Disk Space in GB

### Network Information

- Bytes Sent: Total Bytes Sent over the Network
- Bytes Received: Total Bytes Received over the Network

### Battery Information

- Percentage: Battery Percentage (if applicable)
- Plugged: Whether the device is plugged in or running on battery (Yes/No)

### Process Information

- Current Processes: Number of Currently Running Processes


## Usage

1. Clone the repo
```bash
git clone https://github.com/ashish0kumar/System-fetch.git
```
  
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3 Run the sysfetch.py script:
```bash
python sysfetch.py
```

## License
This project is licensed under the MIT License.
