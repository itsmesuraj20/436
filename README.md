# Control-M SAP R3 Job Scheduling – Step-by-Step Guide

---

## 1. Login
- Open Control-M URL:  
- Go to **Planning** tab.

---

## 2. Create Workspace
- Click **Home**
- Click **Add New Workspace**
- Click **Create**
- Enter workspace name and required details
- Click **Create**

---

## 3. Create Smart Folder
- Inside workspace:
  - Right-click
  - Select **Add Smart Folder**
  - Provide proper folder name

---

## 4. Add SAP R3 Job
- Right-click on the Smart Folder
- Select **Add Job → SAP R3**
- Duplicate page opens
- Click **Home → Folders and Jobs**

---

## 5. Take Reference Job (CLIENT6070)
- Scroll and find **CLIENTXXXX**
- Open workspace
- Select a similar job
- Click **Modify / Take Ownership**
- Review configuration details

---

## 6. Job Naming Convention

### Format:


---

## 7. General Configuration

- **Connection Profile:** `XXXXX`
- **Host / Host Group:** `XXXX.XXXX.XXXX`
- **SAP Job Name:** Enter actual SAP job name  
  (Do NOT paste Control-M job name here)

---

## 8. Add Program Details

- Click **Add**
- Fill:
  - Program
  - Variant
  - User → `S_CONTROLM`
- Click **OK**

---

## 9. Application Settings

- **Application:** `CLIENTXXXX`
- **Sub Application:**


(Use `JOBP` prefix)

---

## 10. Save Job

- Click **Check In**

> Until Check In, data is not saved in the database.

---

## 11. Scheduling Setup

- Click **Modify**
- Go to **Scheduling** tab
- Click **Advanced → Edit**

### Options:
- Single Run → Select `NONE`
- Weekly Run → Select specific weekday (e.g., Monday)

- Click **OK**

---

## 12. Validate Schedule

- Click **View Scheduler**
- Set:

---

## 13. Configure Failure Notification

- Go to **Actions → Add**

