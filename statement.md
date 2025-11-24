Problem Statement:
Tracking stock manually with pen and paper is slow, messy, and leads to math errors. I wanted to build a simple digital tool to replace the physical register, automating the boring parts like counting stock and calculating bills.


Scope:
This is a lightweight Python console application for single users. It handles inventory tracking and billing without needing complex software. It uses a JSON file for storage, so all data is saved automatically and persists between sessions.


Target Users:
Small Shop Owners: For quick billing and stock tracking.
Beginners: Anyone wanting to learn how basic database operations work in Python.


High-Level Features:

Full Control (CRUD): Easily add new items, update prices/quantities, or delete old stock.

Smart Billing: Select items to create a bill. The system checks availability, calculates the total cost, adds 18% GST, and automatically deducts the sold items from inventory.

Instant Search: Type a name to check price and availability immediately.

Auto-Save: Every change is instantly saved to inventory.json, ensuring no data is ever lost.