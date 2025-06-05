# Qumu Cloud API Samples

This repository contains sample code demonstrating how to interact with the **Qumu Cloud** platform using its APIs. 

The examples provided can be used as standalone utilities for test purposes or as reference code for integration into other platforms.


---

## 🔹 `QC_BulkUpload.html`

**Purpose:**  
Bulk upload multiple videos to your Qumu instance.

**Key Features:**
- Automatically uses the original filename as the Qumu Presentation title, with option to add prefix (eg "BULK")
- Streamlines the upload process for batches of media files.
- Drag and drop video files onto the UI to start the process
- Works with Presentation Types that have custom metadata fields, including mandatory fields
- Provides CSV download of uploaded video

**Important Notes:**
Do not use Presentation Types that have **Creators Choice from All** in the workflow where there is no default defined. These will publish to **Draft** status and require manual processing to complete.

Approval workflows will require manual approval.


---

## 🔹 `QC_video-upload.html`

**Purpose:**  
Upload a **single video** to your Qumu instance.

**Use Case:**  
Can be used as sample code for integrating video uploads into platforms such as **WordPress** or other CMS solutions.

---


## 🔹 `QC_Analytics.html`
**Purpose:** 
Shows how the Reporting API may be used to provide custom reports. 
The sample also shows how to identify presentations that have not been viewed over a certain time period.
Sample Report:  [**Screenshot**](./Screenshots/Analytics_report.PNG)

---

## ⚠️ Disclaimer

These Proof of Concept samples show how you could utilise the Qumu API.

This code is provided **as-is**, with **no warranties or guarantees** of any kind.  


---
## 🔐 Security Note

These samples use **basic local authentication** for simplicity and demonstration purposes.  
For production use it is recommended to implement **OAuth 2.0** for secure, standards-based authentication and authorization with the Qumu Cloud platform.

