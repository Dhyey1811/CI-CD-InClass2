# CI-CD-InClass2
# Jenkins CI/CD Integration using Polling-Based Approach

This project demonstrates how to integrate **Jenkins** with **GitHub** using a **polling-based approach** for continuous integration and delivery (CI/CD). Jenkins polls the repository every 5 minutes to check for changes and triggers a pipeline if changes are detected.

# 🛠 Project Details

- **CI Tool:** Jenkins
- **Source Control:** GitHub
- **Polling Method:** Jenkins `pollSCM` (every 5 minutes)
- **Application Type:** [Python script]
- **Pipeline Stages:** Checkout → Build → Test → Notification

---