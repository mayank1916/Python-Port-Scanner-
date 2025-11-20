 Python Port Scanner
A simple and fast multi-threaded TCP Port Scanner built using Python's socket and threading modules.
This tool scans a range of ports on a target machine to identify open TCP ports, similar to the basic behavior of tools like Nmap.

Multi-threaded port scanning (fast)
TCP connect scanning using socket.connect_ex()
Command-line interface
Auto time measurement
Lightweight & beginner-friendly
Great for learning cybersecurity fundamentals
How It Works

The scanner attempts to connect to each port in the specified range.
If the connection is successful → the port is OPEN.

It uses:

socket for network connections
threading for fast parallel scanning
sys.argv for command-line arguments
time to track how long the scan took
Usage

Run the script from terminal or CMD:

python port_scan.py TARGET START_PORT END_PORT
