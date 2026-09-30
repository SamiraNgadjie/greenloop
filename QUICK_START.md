# GreenLoop – Quick Start Guide

This guide provides the minimum steps required to run and test the GreenLoop prototype locally.

## 1. Create a Virtual Environment

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

### macOS / Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

## 2. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

## 3. Run the Application

```bash
python app.py
```

## 4. Open GreenLoop

Open the following address in a web browser:

```text
http://localhost:5000
```

## Demo Login

**Username:** `demo`  
**Password:** `demo123`

## Test the Prototype

After logging in:

1. Open the dashboard to view the package fleet and KPI indicators.
2. Select a package to view its current status and lifecycle history.
3. Use the simulated scan endpoint to record lifecycle events.
4. Refresh the dashboard to observe the updated package status and indicators.

### Simulate a Shipment

```text
http://localhost:5000/scan/PKG010?action=shipped
```

### Simulate a Return

```text
http://localhost:5000/scan/PKG010?action=returned
```

### Windows PowerShell

If `curl` is interpreted as a PowerShell alias, use:

```powershell
curl.exe "http://localhost:5000/scan/PKG010?action=shipped"
```

Then:

```powershell
curl.exe "http://localhost:5000/scan/PKG010?action=returned"
```

## Additional Functions

The prototype also provides:

- Package search and filtering
- Individual package lifecycle histories
- CSV data export
- JSON API access
- Simulated package creation and lifecycle updates

### JSON API

```text
http://localhost:5000/api/packages
```

### CSV Export

The CSV export functionality can be accessed from the GreenLoop application.

## Prototype Scope

The scan functionality is simulated and does not require physical QR-code or RFID hardware.

The current prototype demonstrates the digital lifecycle-management logic of GreenLoop. Physical identification technologies, real-time tracking, ERP/carrier integrations, production infrastructure, and validated environmental calculations represent potential future development stages.

---

**GreenLoop – Smart Reusable Packaging Platform for E-Commerce Logistics**

Hochschule Bremerhaven  
GreenTech Project

**Project Team**

- Samira Yvana Ngadjie
- Trecy Diana Noumbo Nanfack
