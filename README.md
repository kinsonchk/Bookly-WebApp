# Bookly-WebApp

McGill booking app where professors/TAs publish office-hour and meeting slots and students book, cancel, and message-plus invite links and Google/Outlook calendar export.

# Setup

python3 -m venv .venv
source .venv/bin/activate

Installing the requried modules
pip install -r requirements.txt

# Run the Project

python app.py

Visit: (http://127.0.0.1:5000)

# Database

The SQLite3 database file is stored at database/bookly.db
Database Schema: database/CreateTables.sql
Database Initialized: database/CreateTables.py

# Deployment

Deployed to the Render Hosting Service

Public URL: https://bookly-webapp.onrender.com/

## Team Contributions

| Team Member | Student ID | Code / Work Completed                                                                                                                |
| ----------- | ---------: | ------------------------------------------------------------------------------------------------------------------------------------ |
| Enoch       |          - | `Type1.py`, `Type2.py`, `Type3.py`, Zoom Link, Notifications, Database, `app.py`, `UserHomepage.js`, `OwnerHomepage.js`              |
| Brian       |          - | `Type3.py`, `OwnerHomepage.js`, `LandingLoginPage.html`, `CreateAccount.html`, `Homepage.html`, deployment and web hosting, `app.py` |
| Maxim       |          - | `Type1.py`, `Type2.py`, `CreateTable.sql`, `CreateTable.py`, `app.py`                                                                |
| Omer        |          - | `Homepage.html`, `OwnerHomePage.html`, `Type3.py`, `app.py`                                                                          |
| Kinson      |          - | `Type3.py`, `OwnerHomePage.html`, `HomePage.html`, `app.py`, `CreateTable.sql`                                                       |

## Code Not Written by Our Team

The approximately 30% of the website code not written directly by our team consisted mainly of the base skeletons for `OwnerHomepage.html` and `Homepage.html`, along with general frontend debugging support. This included asking Google AI Search clarifying questions to help resolve frontend issues and improve page structure.
