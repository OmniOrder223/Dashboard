# 🖥️ IT Service Request Dashboard

An interactive web-based monitoring dashboard built using **Python**, **Streamlit**, **Pandas**, and **Plotly** to track IT support tickets, issue categories, engineer workloads, and resolution performance in real time directly from your Google Sheet.

---

## 🌟 Key Features

- 🔄 **Real-Time Data Sync:** Automatically pulls live form submissions and open tickets directly via Google Sheets CSV API.
- 📊 **Dynamic Status Tracking:** Overview of total, open/pending, and closed tickets accompanied by automated resolution rate calculations.
- 👨‍💻 **Engineer Workload Distribution:** Evaluates and breaks down individual technician assignments (handling multi-engineer tickets seamlessly).
- 🏷️ **Issue & Category Analytics:** Visualizes categories (Network, Software, CCTV, Other) and tracks daily ticket trends over time.
- 🔍 **Multi-Dimensional Filters:** Filter entire dashboard metrics and graphs by Status, Assigned Engineer, or Issue Category.
- 📋 **Smart Ticket Log Viewer:** Easily toggle between "Today's Data Only" and "All Data" views with an intelligent fallback for active support logs.

---

## 🛠️ Tech Stack

- **Frontend & App Framework:** [Streamlit](https://streamlit.io/)
- **Data Manipulation:** [Pandas](https://pandas.pydata.org/)
- **Visualizations:** [Plotly Express](https://plotly.com/python/plotly-express/)
- **Data Source:** Google Sheets (`Main` & `Open Ticket` sheets)

---

## 🚀 Quick Start (Local Setup)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/OmniOrder223/Dashboard.git
   cd YOUR-REPO-NAME
