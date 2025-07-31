# 🎟️ Marine Ball Ticketing System (Power Apps + Power Automate)

This project is a digital ticketing solution built with **Power Apps** and **Power Automate** to manage ticket sales, attendee registration, and payment tracking for the U.S. Marine Ball event.

The app was designed to streamline the purchasing process for attendees and assist event coordinators with real-time tracking, approvals, and data management.

---

## 🧩 Key Features

- ✅ Canvas App for attendee registration and ticket selection  
- 💳 Payment status tracking and capacity control  
- 📬 Automated confirmation emails and notifications via Power Automate  
- 🧑‍💼 Role-based access (e.g., Admin vs. Guest views)  
- 📊 Optional Power BI dashboard for attendee counts and payment overview

---

## 🔧 Tech Stack

- **Power Apps (Canvas)** – App interface for registration and event details  
- **Power Automate** – Workflow for confirmation emails and updates  
- **Dataverse** or **SharePoint Lists** – For storing ticket and user data  
- **Outlook Connector** – Email integration  
- **Power BI** (optional) – Real-time dashboard and reports

---

## 📂 Project Structure

```text
marineball-ticketing/
├── README.md
├── PowerApp/
│   ├── MarineBallApp.msapp
│   ├── identity.json
│   ├── app-metadata.json
│   └── logoSmallFile.png
├── Flow/
│   ├── definition.json
│   ├── connectionsMap.json
│   └── apisMap.json
├── docs/
│   ├── screenshots/
│   │   ├── mainPage.png
│   │   ├── SeatingSelection.png
│   │   └── TicketGuestInfromation.png
│   └── videos/
│       └── MarineBall.mp4
