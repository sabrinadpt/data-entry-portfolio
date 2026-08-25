# 📦 E-Commerce Warehouse & Logistics Data Entry Management (Korea & Japan Operations)

## 📌 Project Overview
This project showcases real-world, end-to-end data entry, inventory tracking, and logistics record management for an international proxy shopping service (*The Yeoja Store*). 

The operational workflow handles customer order intake, matches local courier tracking numbers in South Korea and Japan, and monitors international shipping progress to Indonesia via EMS air freight and handcarry routes.

---

## 🎯 Key Operations & Tasks Handled
* **Form Response Consolidation:** Standardized and sanitized customer form responses from intake portals (Korea and Japan intake forms).
* **Inventory & Tracking Reconciliation:** Cross-referenced local tracking numbers against master warehouse arrival logs (`WAREHOUSE_KOREA.csv` and `WAREHOUSE_JEPANG.csv`).
* **Box Allocation & Flight Status:** Assigned verified packages to international shipping boxes (`EMS 69`, `EMS 70`, etc.) and updated logistics progression tags (*Arrived at WH*, *Customs Clearance*, *Delivered*).
* **Data Security & Anonymization:** Protected buyer privacy by sanitizing personal contact numbers and email addresses while preserving raw tracking integrity.

---

## 🛠️ Tools & Spreadsheet Functions Used
* **Platform:** Google Sheets, CSV Data Processing
* **Key Functions & Features:**
  * `VLOOKUP` / `XLOOKUP` (Matching tracking IDs to customer profiles)
  * `ARRAYFORMULA` & `IMPORTRANGE`
  * `TRIM`, `UPPER`, `PROPER` (Text standardization)
  * Data Validation (Custom drop-down status selection)
  * Pivot Tables & Conditional Formatting (Highlighting unlinked tracking IDs)

---

## 📂 Included Data Files
[WAREHOUSE by @theyeojastore.csv](https://github.com/user-attachments/files/31439287/WAREHOUSE.by.%40theyeojastore.-.RESPONSE.KOREA.1.csv)

* `WAREHOUSE_KOREA.csv` — Primary tracking database for South Korea warehouse intake.
* `WAREHOUSE_JEPANG.csv` — Primary tracking database for Japan warehouse intake.
* `WAREHOUSE_RESPONSE_KOREA_1.csv` & `_2.csv` — Intake response logs from buyers.
* `WAREHOUSE_RESPONSE_JEPANG.csv` — Customer order logs for Japan-sourced items.
* `WAREHOUSE_LIST_RESI_BOX.csv` — EMS box dispatch schedule, flight numbers, and Indonesian customs clearance milestones.

---

## 💡 Key Takeaway
Demonstrates high numerical and textual accuracy in managing cross-border e-commerce supply chain data, processing over 1,000+ individual SKU entries with zero duplicate logs.
