# GreenLoop – Smart Reusable Packaging Platform for E-Commerce Logistics

GreenLoop is a digital prototype designed to support the lifecycle management of reusable packaging in e-commerce logistics.

The concept addresses an important challenge of reusable packaging systems: packaging must not only be durable, but also successfully returned, identified, monitored, and reintegrated into the logistics process.

## Project Overview

GreenLoop provides a retailer-facing digital platform for managing reusable packaging throughout its lifecycle.

The prototype demonstrates how individual packaging assets can be digitally identified, monitored, and associated with lifecycle events such as shipment and return.

The platform also provides selected fleet-level indicators to support operational monitoring and decision-making.

## Main Features

- Unique package identification
- Package lifecycle management
- Package status monitoring
- Lifecycle event history
- Dashboard with operational KPIs
- Package search and filtering
- CSV data export
- JSON API
- Simulated shipment and return events
- User authentication

## Prototype Workflow

A package can move through different lifecycle states.

For example:

1. A reusable package is prepared for shipment.
2. The package is assigned to an order.
3. The package is shipped to the customer.
4. The customer returns the packaging.
5. The return is recorded in GreenLoop.
6. The package can be prepared for another reuse cycle.

This lifecycle information can be used to monitor return behaviour, package availability, and circulation performance.

## Technology

The GreenLoop prototype was implemented using:

- Python 3
- Flask
- HTML
- CSS
- JavaScript
- JSON-based data storage
- Werkzeug password hashing

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/SamiraNgadjie/greenloop.git
cd greenloop

### 2. Create a virtual environment

Windows:

python -m venv .venv
.venv\Scripts\activate

3. Install the dependencies

pip install -r requirements.txt

4. Start the application

python app.py

5. Open the application

Open the following address in a web browser:

http://localhost:5000

Demo Login
Username: demo
Password: demo123

Prototype Scope

The current prototype demonstrates the digital lifecycle-management logic of GreenLoop.
It currently includes:

- package identification
- package status management
- lifecycle event history
- dashboard indicators
- package search
- basic data export
- simulated shipment and return events

The current version does not include:

- physical QR-code scanning
- RFID integration
- IoT hardware
- real-time package location
- live ERP integration
- live carrier integration
- production cloud infrastructure
- validated lifecycle assessment
- validated environmental-impact calculations

These functionalities represent potential future development stages.

Future Development

Potential future development of GreenLoop could include:

- QR-code or RFID-based identification
- integration with retailer ERP systems
- integration with logistics and parcel-carrier systems
- connection with return points and parcel lockers
- automated inspection and cleaning workflows
- packaging-agnostic interoperability
- advanced fleet analytics
- validated environmental-performance indicators

Academic Project

GreenLoop – Smart Reusable Packaging Platform for E-Commerce Logistics

Hochschule Bremerhaven
GreenTech Project

Project Team:
- Samira Yvana Ngadjie
- Trecy Diana Noumbo Nanfack

Disclaimer

GreenLoop is currently an academic prototype. The operational, economic, and environmental viability of the concept would need to be validated through a real-world pilot implementation
