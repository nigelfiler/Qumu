# Qumu Cloud API Samples

This repository contains sample code demonstrating how to interact with the **Qumu Cloud** platform using its APIs. 

The examples provided can be used as standalone utilities or as reference code for integration into other platforms.

---

## 🔹 `Qc_BulkUpload.html`

**Purpose:**  
Bulk upload multiple videos to your Qumu instance.

**Key Features:**
- Automatically uses the original filename as the Qumu Presentation title.
- Streamlines the upload process for batches of media files.
- Drag and drop video files onto the UI to start the process

**Important Notes:**
- Do **not** use Presentation Types that:
  - Require mandatory metadata
  - Use approval workflows
    
  These workflows will cause the publishing process to fail, requiring manual user action in the Qumu portal to complete.

---

## 🔹 `QC_video-upload.html`

**Purpose:**  
Upload a **single video** to your Qumu instance.

**Use Case:**  
Can be used as sample code for integrating video uploads into platforms such as **WordPress** or other CMS solutions.

---

## ⚠️ Disclaimer

This code is provided **as-is**, with **no warranties or guarantees** of any kind.  
Use at your own risk.

---
## 🔐 Security Note

These samples use **basic local authentication** for simplicity and demonstration purposes.  
For production use or public deployments, it is recommended to implement **OAuth 2.0** for secure, standards-based authentication and authorization with the Qumu Cloud platform.

