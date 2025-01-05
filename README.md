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


🚀 Getting Started
Prerequisites
Access to Microsoft PowerApps and SharePoint Online.
A SharePoint site configured to store data for the app.
Steps to Set Up the App
Clone the Repository

bash
Copy code
git clone https://github.com/premshah06/IT-service-Desk.git
cd IT-service-Desk
Import into PowerApps

Open PowerApps Studio.
Click on Apps > Import and upload the CanvasManifest.json file.
Configure SharePoint Connections

Update the Connections.json file with your SharePoint site URL and credentials.
Ensure data sources like Devices, Issues are mapped to SharePoint lists.
Run the App

Preview the app in PowerApps Studio or publish it for use within your organization.
📊 Key Screens and Functionalities
Device Management:

Add, view, and update device details.
Integrated with SharePoint to track devices.
Issue Log:

Log IT issues with details like priority, status, and description.
Assign issues to team members and track resolution.
Custom Forms:

Dynamic forms for creating and updating devices and issues.
Real-time Updates:

Leverage PowerApps' live data capabilities for instant updates.
🤝 Contribution Guidelines
We welcome contributions to enhance the app! Here's how you can get involved:

Fork the repository.
Create a feature branch.
Submit a pull request with a clear explanation of your changes.
