# FlowVision Dashboard Specification

Version: 1.0

---

# Purpose

The dashboard is the operational command center of FlowVision.

Its primary objective is not to display as much data as possible.

Its objective is to provide immediate situational awareness.

A user should understand the state of the network within five seconds.

---

# Dashboard Goals

The dashboard must answer these questions immediately:

- Is my network healthy?
- Is there anything requiring immediate attention?
- Where is the problem?

---

# Layout

+-------------------------------------------------------------+
| Header                                                      |
+-----------+--------------------------------------+-----------+
| Sidebar   |                                      |           |
|           |                                      |           |
|           |        Live Network Topology         |  Events   |
|           |                                      |  Panel    |
|           |                                      |           |
+-----------+--------------------------------------+-----------+
| Network Health | Top Talkers | Interface Status             |
+-------------------------------------------------------------+
| Traffic Timeline                                            |
+-------------------------------------------------------------+

---

# Header

Contains:

- FlowVision Logo
- Current User
- Search
- Notifications
- Profile Menu

---

# Sidebar

Dashboard

Topology

Devices

Flows

Monitoring

Alerts

Reports

Settings

---

# Main Area

The center of the screen always displays the Live Network Topology.

This is the most important component in the entire application.

---

# Right Panel

Shows recent events.

Examples:

- Interface Down
- Device Offline
- High CPU
- Packet Loss
- New Device

Events should be ordered by severity.

---

# Bottom Widgets

Network Health

Displays:

- Online Devices
- Offline Devices
- Warning Devices
- Critical Devices

---

Top Talkers

Displays:

- Highest bandwidth consumers

---

Interface Health

Displays:

- Utilization
- Errors
- Packet Drops

---

Traffic Timeline

Displays traffic evolution during the last 24 hours.

---

# UX Rules

Never overload the screen.

Never show unnecessary charts.

Always prioritize operational visibility.

The topology is always the center of attention.

---

# Success Criteria

A first-time user should understand the network state without training.
