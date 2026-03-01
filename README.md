# Control-M SAP R3 Job Scheduling – Step-by-Step Guide

---

## 1. Login
- Open Control-M URL:  
  `https://gevstage.us3.controlm.com/`
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
- Scroll and find **CLIENT6070**
- Open workspace
- Select a similar job
- Click **Modify / Take Ownership**
- Review configuration details

---

## 6. Job Naming Convention

### Format:


---

## 7. General Configuration

- **Connection Profile:** `ALTAIS_SAP`
- **Host / Host Group:** `HOSTG.SAP.ALTAIS`
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

- **Application:** `CLIENT6070`
- **Sub Application:**