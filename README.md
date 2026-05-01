# Power Automate Workflow: File Handling & Application Validation

## 📌 Overview
This project automates a complete workflow using **Microsoft Power Automate** with supporting `.bat` and `.ps1` scripts.  
It handles file operations, runs an application, and validates execution via HTTP status codes.

## ⚙️ Workflow Steps
1. Copy files into a target folder
2. Extract folder contents
3. Replace a file from another folder
4. Run an application via `.bat` script
5. Validate execution by browsing a URL:
   - Success → HTTP 200
   - Failure → flagged

## 🛠️ Scripts
- `scripts/fileOps.ps1` → Handles file copy and replacement  
- `scripts/runApp.bat` → Launches the application  
- `scripts/validateUrl.ps1` → Checks URL status for success/failure  

## 📂 Project Structure
