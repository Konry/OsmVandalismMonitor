# OsmVandalismMonitor
A tool shall monitor and inform for vandalism or items which are removed out of the area to check it manually again

## Overview

The OSM Change Monitor is a console-based application developed in C#, designed to monitor and detect changes in OpenStreetMap (OSM) data. This tool focuses on specific types of entries within user-defined regions, comparing current data against previous versions to identify potential vandalism or unauthorized modifications.

## Features

- **Region and Entry Type Filtering:** Users can specify regions and types of entries (e.g., buildings, roads, parks) to monitor.
- **Change Detection:** Automated comparison between the latest OSM data and previous snapshots to identify changes.
- **Console-Based Alerts:** Notifications and summaries of detected changes are displayed in the console.
- **Historical Data Review:** Capability to review historical data for a comprehensive understanding of changes over time.
- **Automated Data Retrieval:** Periodic and automated retrieval of the latest OSM data for specified regions and entry types.
- **Vandalism Identification Support:** Assists in identifying potential vandalism for further investigation.

## Getting Started

### Prerequisites

- .NET 7.0 or later
- Internet access for OSM data retrieval

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/osm-change-monitor-console.git
   Navigate to the cloned directory:
  cd osm-change-monitor-console```

### Configuration
Edit appsettings.json to configure your specific regions, entry types, and monitoring preferences.

### Build and Run
Build the project:

```bash
dotnet build
```
Run the application:
```bash
dotnet run
```
Follow the on-screen instructions in the console to start monitoring.


### Contributing
We encourage contributions! Please read CONTRIBUTING.md for guidelines on how to submit pull requests, report issues, and become a part of the development process.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgements
The OpenStreetMap Foundation and its contributors
The .NET community
