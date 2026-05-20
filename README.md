# Network Simulator (Python)

A lightweight, visual network topology simulator built with Python, Tkinter, and NetworkX. Design your own network by placing devices on a canvas, linking them together, and running simulated ping tests — all through a clean graphical interface.

## ✨ Features

- Add three device types: **PC**, **Router**, and **Switch**
- Draw connections between any two devices with a click
- Assign custom IP addresses and rename devices via the Properties panel
- Run **Ping Tests** between any two nodes — shows the shortest path
- Right-click context menu for quick actions (ping, delete, properties)
- Real-time **Event Log** to track all actions

## 🖥️ Screenshot

> *(Add a screenshot of the app here)*

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3 installed, then install the required library:

```bash
pip install networkx
```

> Tkinter is included with most Python installations by default.

### Run the app

```bash
python project.py
```

## 🛠️ How to Use

1. Select a device type from the toolbar (PC / Router / Switch)
2. Click anywhere on the canvas to place the device
3. Switch to **Link Devices** mode and click two devices to connect them
4. Right-click any device to rename it, assign an IP, delete it, or ping from it
5. Use the **Ping Test** button to test connectivity between any two nodes

## 📦 Dependencies

| Library | Purpose |
|---|---|
| `tkinter` | GUI framework |
| `networkx` | Graph structure & shortest-path algorithm |

## 📁 Project Structure

```
network-simulator-py/
│
├── project.py       # Main application file
└── README.md
```

## 📜 License

MIT License — free to use and modify.
