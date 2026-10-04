# 📚 Digital Library System (DLS)

A full-stack library management application designed to seamlessly bridge offline library operations with digital access. 

---

## 🌟 Features

### 👨‍🎓 Student Portal
- **Book Catalog:** Browse available physical and digital books.
- **Request System:** Submit online requests for physical books.
- **Status Tracker:** Monitor real-time request status (Pending / Approved / Rejected).
- **Digital Downloads:** Access and download digital e-books once approved by the admin.

### 👨‍💼 Admin Portal
- **Dashboard:** View all pending student requests in real time.
- **Approval Workflow:** Approve or reject book requests with a single click.
- **Inventory & Digital Management:** Upload digital books and manage book availability for offline collection.

---

## 🛠️ Architecture & Workflow

```
[ Student Portal ]  --->  ( Book Request )  --->  [ Database / State ]
                                                        |
[ Admin Portal ]   <---  ( Pending Alerts ) <-----------+
        |
   ( Approve )
        |
        +---> [ Offline Pick-Up Enabled ] OR [ Digital Download Granted ]
```

---

## 💻 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend / Portal Logic:** Node.js / Python / PHP (Adjust according to your exact backend)
- **Database:** MySQL / SQLite / MongoDB

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/BogguAjayKumar/DLS-Digital-Library-System--.git
   cd DLS-Digital-Library-System--
   ```
2. Open `index.html` in your browser (or start your local server).

---

## 📸 Screenshots

*(Add screenshots of Admin & Student Portals here)*
