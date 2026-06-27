# Log Analyzer for SOC

Log Analyzer for SOC is an open-source Python-based desktop application designed to help security operations and system administrators analyze Apache web server logs efficiently. The project focuses on transforming raw log data into structured, searchable, and visually understandable information for monitoring web activity, identifying anomalies, and supporting operational reporting.

## Overview

This project demonstrates how log analysis can be used in a Security Operations Center (SOC) context. By parsing Apache access logs, storing relevant information in a local SQLite database, and presenting the results through a graphical user interface, the application makes it easier to inspect traffic patterns, detect suspicious behavior, and gain actionable insights from server events.

## Key Features

- Parse and analyze Apache access logs
- Store parsed entries in SQLite for structured querying
- Display log data in a tabular format
- Visualize trends and patterns through charts and graphs
- Support basic security monitoring and operational analysis workflows
- Provide a simple desktop experience using CustomTkinter

## Technologies Used

- Python
- SQLite3
- CustomTkinter
- Apache log analysis
- Data visualization
- Authentication system support

## Project Goals

The main objective of this project is to provide a lightweight and practical tool for:

- Monitoring web server activity
- Reviewing access patterns over time
- Supporting anomaly detection and incident investigation
- Improving visibility into system behavior for small-scale environments

## How It Works

1. The application reads Apache access log files.
2. Each log entry is parsed and extracted into meaningful fields such as IP address, request method, endpoint, status code, and timestamp.
3. The extracted data is stored in a SQLite database for efficient querying.
4. Users can view the structured records through the interface and analyze trends with visual charts.

## Installation

Ensure that Python is installed on your system.

```bash
pip install customtkinter
```

## Usage

Run the application with:

```bash
python main.py
```

If your project uses a different entry point, replace the command above with the appropriate script name.

## Project Structure

A typical structure for this repository may include:

- Source code for parsing and analysis
- Database handling for SQLite storage
- UI components built with CustomTkinter
- Visualization logic for charts and trends

## Future Enhancements

Possible future improvements include:

- Support for multiple log formats
- Advanced filtering and search capabilities
- Real-time log monitoring
- Alerting for suspicious activity
- Export options for reports and CSV/JSON output

## License

This project is open-source and intended for educational and study purposes.
