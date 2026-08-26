# 💰 E-Commerce Financial Reconciliation, Order Intake & Import Tax Billing

## 📌 Project Overview
This project demonstrates financial tracking, customer payment reconciliation, and import tax billing calculations for an international group-ordering and proxy-shopping business.

The system manages multi-service operations including Pre-Orders, Item Sharing, Event Lightstick Rentals, Jastip (proxy buying), and International Customs Tax Allocation across EMS and Handcarry freight routes.

---

## 🎯 Key Tasks & Financial Operations Handled
* **Order Payment Reconciliation:** Tracked down-payments (DP), full payments, and remaining balances (*Pelunasan*) across 500+ customer entries (`Rekap_Order_GROUP_ORDER`, `PRE-ORDER`, `SHARING`, `RENTAL_LIGHTSTICK`).
* **Import Tax & Customs Duty Allocation:** Calculated per-customer tax obligations for international shipments arriving via EMS and Handcarry (`TAGIHAN_TAX`).
* **Multi-Revenue Stream Management:** Structured separate accounting tabs for distinct business models (Pre-Order, Item Sharing split costs, Rental deposits, Direct Jastip).
* **Payment Status Monitoring:** Applied visual tags to distinguish unpaid balances, verified payments, and pending bank transfers.

---

## 🛠️ Tools & Financial Formulas Used
* **Platform:** Google Sheets, CSV Data Accounting
* **Key Functions:** `SUMIFS`, `COUNTIF`, `VLOOKUP`, Arithmetic Tax Split Formulas `(Item Value / Total Shipment Value) * Total Tax Duty`, Dynamic Status Filters.

---

## 📁 Repository Files Included
Rekap Order [https://docs.google.com/spreadsheets/d/1EVxXSXNBN9i4O5g_YcI6fy1Md4A7bfcIGWj--z55j_E]
* `Rekap_Order_GROUP_ORDER` — Master ledger for customer group orders and payment methods (MOP).
* `Rekap_Order_PRE-ORDER` & `_SHARING` — Payment logs for pre-order deposits and cost-sharing items.
* `Rekap_Order_RENTAL_LIGHTSTICK` — Booking ledger and security deposit tracking for concert item rentals.

TAGIHAN TAX [https://docs.google.com/spreadsheets/d/1Vbo461sH0QFzQwQJkCNK-td6e2mbLbwFxpk8Cc3D9W8]
* `TAGIHAN_TAX` — Individual tax billing spreadsheets for Japan-to-Indonesia EMS & Handcarry shipments.

---

## 💡 Key Takeaway
Demonstrates high numerical accuracy, financial accountability, and the ability to process multi-tab order ledgers without revenue leakages or billing discrepancies.
