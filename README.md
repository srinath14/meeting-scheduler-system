# 📅 Meeting Scheduler System

This project is a simple object-oriented **Meeting Scheduler** built in C++. It supports both **online** and **offline meetings** using a Factory design pattern.

---

## ✅ Features

- 🔐 User login system
- 📆 Book meeting slots with time range
- 👥 Manage list of participants
- ✏️ Cancel or update meetings
- 🏢 Supports Online & Offline meeting types
- 🏭 Uses **Factory Design Pattern** for meeting creation
- 📌 Metadata handling using `MeetingMetaData` class

---

## 🧩 Class Overview

- **User**: Represents a participant with their own calendar.
- **MeetingMetaData**: Contains time, date, subject, and participants info.
- **Meeting**: Abstract base class for meetings (with online/offline variants).
- **MeetingFactory**: Interface to create different types of meetings.
- **OnlineMeetingFactory / OfflineMeetingFactory**: Concrete factory classes.
- **BookingManager**: Handles booking logic.
- **MeetingScheduler**: Main component to book, update, cancel meetings.

---

## 🛠 Design Pattern Used

- **Creational Pattern**: Factory Pattern for meeting creation.
- Potential for future **Structural/Behavioral** patterns (e.g., Observer for notifications).

---

## 🗂 UML Diagram

👉 Click the link below to view the **Lucidchart UML Diagram**:

🔗 [View UML Diagram on Lucidchart](https://lucid.app/lucidchart/be2de95f-6e89-410c-b700-2cc9d5525280/edit?view_items=OcX7OTe9yzBt%2ChdX7npz6c3L2%2CmiX7XJ1HT15s%2CTiX7EdYM7zpb%2CblX7WGzgoC_X%2CymX7ZYCUqrJw%2CBnX7Lgttyjh2%2CDnX7NDtmuG6K%2CNnX7uotSubMK%2C5nX7h9IL1B0x%2CtsX7Nv49RBrh%2C8sX7vD64mCYn%2C.sX7LS4emGvq%2C5uX7YLOgB2~t%2ChvX7tuxMVuMt%2CDuX7GKQ4BbSO%2CusX7JH_EFrtS%2CepX7Fu_cM.mo%2CtwX7VOzReOpn%2CkyX7ICXtWrGJ%2CtzX7WlSrvS3W%2CMRX7HyQQ.w8T%2C~RX7_kjVLLYN&invitationId=inv_59a1e8b9-2eed-4f35-894f-2697b39eb3f3)

---

## 🧪 How to Run

1. Open the project in **VS Code**.
2. Make sure you have a C++ compiler installed.
3. Compile using:

```bash
g++ main.cpp -o MeetingScheduler
./MeetingScheduler
