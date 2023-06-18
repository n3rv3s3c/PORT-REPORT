# PORT-REPORT
This is an automated python tool for writing a report on ports scan

In this script, the scan_ports function takes a target IP address, start port, and end port as input, and performs a port scan on the specified range. It returns a list of open ports.

The generate_report function takes the target IP address and the list of open ports as input, and generates a report string containing the target IP, scan date, and the list of open ports (or a message if no open ports are found).

The save_report function saves the generated report to a file.

To use this script, you can specify the target IP, start port, end port, and output file name in the provided variables. The script will perform a port scan, generate a report, and save it to the specified file.

Note: Port scanning without proper authorization is potentially illegal and unethical. Make sure you have the necessary permissions and use this tool responsibly and only for authorized purposes.
