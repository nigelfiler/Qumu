# Qumu Cloud API Samples

This repository contains sample code demonstrating how to interact with the **Qumu Cloud** platform using its APIs. 

The examples provided can be used as standalone utilities for test purposes or as reference code for integration into other platforms.


---

## 🔹 `QC_BulkUpload.html`

**Purpose:**  
Bulk upload multiple videos to your Qumu instance.

**Key Features:**
- Automatically uses the original filename as the Qumu Presentation title.
- Streamlines the upload process for batches of media files.
- Drag and drop video files onto the UI to start the process

**Important Notes:**
- Do not use Presentation Types that:
  - Require mandatory metadata
  - Use approval workflows

  These workflows will cause the publishing process to fail, requiring manual user action in the Qumu portal to complete the publishing process

---

## 🔹 `QC_video-upload.html`

**Purpose:**  
Upload a **single video** to your Qumu instance.

**Use Case:**  
Can be used as sample code for integrating video uploads into platforms such as **WordPress** or other CMS solutions.

---


## 🔹 `QC_analytics_with_CSV_Chart.html`
**Purpose:** 
Shows how the Reporting API may be used to provide custom reports. 
The sample also shows how to identify presentations that have not been viewed over a certain time period.

---

## ⚠️ Disclaimer

These Proof of Concept samples show how you could utilise the Qumu API.

This code is provided **as-is**, with **no warranties or guarantees** of any kind.  


---
## 🔐 Security Note

These samples use **basic local authentication** for simplicity and demonstration purposes.  
For production use or public deployments, it is recommended to implement **OAuth 2.0** for secure, standards-based authentication and authorization with the Qumu Cloud platform.

