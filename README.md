# 🖥️ IT Service Desk App

The **IT Service Desk App** is a comprehensive solution designed to streamline IT issue management within organizations. Built using Microsoft PowerApps, this app provides a user-friendly interface for logging, tracking, and resolving IT-related issues efficiently.

---

## 📋 Features

- **Responsive Design**: Optimized for desktops and tablets.
- **Device & Issue Management**: Track devices and log IT issues with ease.
- **SharePoint Integration**: Seamlessly connected with SharePoint for data storage and management.
- **Custom Forms**: Tailored forms for creating, viewing, and editing data.
- **Priority Handling**: Assign priorities and track the status of issues in real time.
- **Modern UI/UX**: Enhanced navigation and accessibility with modern controls.

---

## 🛠️ Tech Stack

- **Platform**: Microsoft PowerApps
- **Data Source**: SharePoint Online
- **UI Components**:
  - Buttons
  - Galleries
  - Forms
  - Labels
  - ComboBoxes
  - DatePickers
- **Development Tools**:
  - YAML-based source files for screens and forms.
  - JSON-based configurations for connections and data sources.

---

## 📂 Project Structure

```plaintext
IT-service-Desk/
├── README.md                     # Project documentation
├── Application/
│   ├── CanvasManifest.json       # Application metadata
│   ├── Connections/              # SharePoint connection details
│   ├── DataSources/              # Data source definitions
│   ├── Src/                      # PowerApps source files (YAML format)
│   ├── Assets/                   # Application assets
│   ├── Entropy/                  # Debugging and app state details
│   └── pkgs/                     # UI component definitions
└── .gitignore                    # Git ignore file
