# 💰 E-Commerce Financial Reconciliation, Order Intake & Import Tax Billing

## 📌 Project Overview
This project demonstrates financial tracking, customer payment reconciliation, and import tax billing calculations for an international group-ordering and proxy-shopping business.

The system manages multi-service operations including Pre-Orders, Item Sharing, Event Lightstick Rentals, Jastip (proxy buying), and International Customs Tax Allocation across EMS and Handcarry freight routes.

---

## 🎯 Key Tasks & Financial Operations Handled
* **Order Payment Reconciliation:** Tracked down-payments (DP), full payments, and remaining balances (*Pelunasan*) across 500+ customer entries (`Rekap_Order_GROUP_ORDER.csv`, `PRE-ORDER.csv`).
* **Import Tax & Customs Duty Allocation:** Calculated per-customer tax obligations for international shipments arriving via EMS and Handcarry (`TAGIHAN_TAX_JP_*.csv`).
* **Multi-Revenue Stream Management:** Structured separate accounting tabs for distinct business models (Pre-Order, Item Sharing split costs, Rental deposits, Direct Jastip).
* **Payment Status Monitoring:** Applied visual tags to distinguish unpaid balances, verified payments, and pending bank transfers.

---

## 🛠️ Tools & Financial Formulas Used
* **Platform:** Google Sheets, CSV Data Accounting
* **Key Functions:** `SUMIFS`, `COUNTIF`, `VLOOKUP`, Arithmetic Tax Split Formulas `(Item Value / Total Shipment Value) * Total Tax Duty`, Dynamic Status Filters.

---

## 📁 Repository Files Included
[Rekap Order @theyeojastore - TAGIHAN PELUNASAN.csv](https://github.com/user-attachments/files/31438920/Rekap.Order.%40theyeojastore.-.TAGIHAN.PELUNASAN.csv)
[TAGIHAN TAX @theyeojastore - 🇯🇵JP 8 (EMS).csv](https://github.com/user-attachments/files/31438903/TAGIHAN.TAX.%40theyeojastore.-.JP.8.EMS.csv)
* `Rekap_Order_GROUP_ORDER.csv` — Master ledger for customer group orders and payment methods (MOP).
* `Rekap_Order_PRE-ORDER.csv` & `_SHARING.csv` — Payment logs for pre-order deposits and cost-sharing items.
* `Rekap_Order_RENTAL_LIGHTSTICK.csv` — Booking ledger and security deposit tracking for concert item rentals.
* `TAGIHAN_TAX_JP_*.csv` — Individual tax billing spreadsheets for Japan-to-Indonesia EMS & Handcarry shipments.

---

## 💡 Key Takeaway
Demonstrates high numerical accuracy, financial accountability, and the ability to process multi-tab order ledgers without revenue leakages or billing discrepancies.
