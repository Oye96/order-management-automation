# Order-Management-Automation
Fully automated order management workflow built with n8n, Google Sheets, Gmail, and Telegram — handles order capture, stock tracking, and team/customer notifications automatically.
Here is the short video demo: https://drive.google.com/file/d/1oliymAs3fWG5s46-2BzGmGrRZBHeeOym/view?usp=drivesdk

🛒 Automated Order Management System (n8n + Google Sheets + Gmail + Telegram)

🔍 Overview
  A fully automated order management workflow built in n8n to eliminate manual order tracking for small stores.
This system automatically captures new orders, updates inventory, notifies customers, and alerts teams — all hands-free.

⚙️ Features

✅ Captures new orders instantly
✅ Updates product sheets in real-time
✅ Sends instant order confirmation emails
✅ Alerts team on low stock via Telegram
✅ Shares complete order details with your team
✅ Automatically generates order timestamps and IDs

🧠 Tech Stack
. n8n – Workflow automation
. Google Sheets – Product & order database
. Gmail – Customer communication
. Telegram – Team notifications

📂 Workflow Logic
. Order Capture: Takes input data (customer name, product, quantity, etc.)
. Stock Check: Verifies product availability and quantity
. Order Update: Adds new order to Google Sheets
. Low Stock Logic: Sends Telegram alert to team if stock ≤ threshold
. Customer Notification: Sends personalized email with delivery details
. Team Notification: Telegram message with order summary

🧾 Example Output

Customer Email Example:
Hi [Customer Name],
Thank you for your order!
🆔 Order ID: ORD-1234
📦 Product: Power Bank (x2)
💰 Total: $16,000
🏠 Delivery Address: [Address]
🕒 Ordered At: [Timestamp]

Your order will be delivered soon.

Telegram Notification Example:
🚨 Low stock alert!
. Product: Power Bank
. Remaining: 3 units
. Restock soon.

💡 Impact
. Small stores often lose 10+ hours weekly managing orders manually.
. This workflow automates the entire process — saving time, reducing errors, and keeping both the team and customers informed.


Oyero Ibrahim
linkedIn: https://linkedin.com/in/youngshallgrow
Proven AI Automation Specialist
