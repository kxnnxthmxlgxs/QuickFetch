# QuickFetch
QuickFetch  QuickFetch — a delivery service web app that connects customers, drivers, and admins to make short-distance deliveries simple, fast, and reliable.


# QuickFetch

QuickFetch — a delivery service web app that connects customers, drivers, and admins to make short-distance deliveries simple, fast, and reliable.

## 📝 Problem Statement

Time-Consuming Trips and Long Queues
Many customers in South Africa purchase items from stores and must physically travel to collect them. Waiting in line or traveling long distances wastes time and can be costly, especially in areas with unreliable public transport. Studies indicate that long waiting times significantly reduce customer satisfaction (ScienceDirect, 2023
).

Limited Delivery Options for Smaller Orders
Current delivery services often focus on groceries or large shipments, leaving small-scale deliveries underserved. Mobile delivery adoption in South Africa heavily depends on speed, usability, and affordability (Scielo, 2023
).

Uncertainty and Inefficiency
Customers often do not know when their deliveries will arrive, which increases stress. Carrying cash for in-person collection also poses safety risks. Research shows perceived wait times and transparency directly impact the likelihood of repeated service use (Scielo, 2023
).

Driver Vetting and Workflow Management Gaps
Many delivery services lack structured processes for vetting drivers and managing deliveries, leading to unreliable service and low trust.

💡 Solution: QuickFetch

QuickFetch addresses these challenges by offering a transparent, reliable, and efficient delivery service:

## Feature	Benefit
Driver Application & Admin Approval	Ensures only qualified drivers are accepted, increasing reliability and safety.
Distance-Based Pricing	Fair pricing calculated per kilometer, with a base fee.
Customer Delivery Requests	Customers submit order details, eliminating the need to visit stores.
Order Tracking	Real-time status updates (Pending, Picked Up, Delivered, Missed).
Wait-Time Limit & Penalties	Drivers can leave if customers delay pick-up, ensuring accountability and timely service.
Role-Based System	Clear separation of responsibilities: Customers, Drivers, Admin.
🔍 Research & Justification

Performance & Reliability: South African studies show speed, ease of use, and reliability are critical to mobile delivery adoption (Scielo, 2023
).

Customer Satisfaction: Long waits reduce satisfaction; short, predictable waits increase adoption (ScienceDirect, 2023
).

Underserved Market: Many SMEs and customers are not effectively served by existing delivery platforms. QuickFetch fills this gap with a simple, low-cost solution.

## 🎯 MVP Scope

Customer: Request deliveries and track status.

Driver: Apply, view assigned deliveries, update status.

Admin: Approve drivers, manage deliveries, set distance-based rates.

Pricing: Base fee + per km rate.

Penalties: Applied for missed collections.

Focus: Core workflow, clean UX, mobile-first design.

## 🏗 Tech Stack

Frontend: React (JavaScript) + Tailwind CSS

Backend: .NET 8 MVC + Dapper

Database: SQL Server (or SQLite for prototype)

Authentication: Basic role-based login (Customer / Driver / Admin)
