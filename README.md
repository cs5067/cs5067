# Abid Hatim Abu Elgasim Mukhtar

Software developer in Cairo. I build business systems that people actually use — ERP modules, inventory and logistics workflows, and real-time platforms. Most of what's here I wrote because I wanted to understand something, not because someone paid me to.

## Odoo

I taught myself the framework to deliver a four-module ERP for an oil & gas client — Inventory, Maintenance, HR and Purchasing, in Python and XML on the Odoo ORM. I've kept building on it since, unpaid, and published the results:

**[odoo19-shipment-management](https://github.com/cs5067/odoo19-shipment-management)** — Odoo 19 logistics module. Shipment lifecycle guarded in the model layer rather than the UI, so no client can bypass it. Two-role security, grouped kanban, QWeb PDF reports with barcodes, sequences, computed totals. Shipped with a design document covering the architecture, the assumptions and the trade-offs.

**[odoo-lab-inventory](https://github.com/cs5067/odoo-lab-inventory)** — Odoo 17 inventory module. Batch and lot tracking with QC release status, a signed stock-movement ledger, consumption logging, QWeb reports and an OWL dashboard.

## Production work

A real-time fleet tracking platform for the American University in Cairo — three apps and a shared PostgreSQL backend, code-reviewed by the university's IT engineering team. I cut its projected running cost from thousands of dollars a day to under $200 a month by moving ETA computation server-side and fanning results out over WebSockets instead of calling the API once per user.

A full-stack operations platform for a pharmaceutical manufacturer, now in daily use, replacing manual spreadsheets across inventory, warehouse and quality control.

**[vibeswipe](https://github.com/cs5067/vibeswipe)** — a music discovery app where the interesting problem was building my own recommendation engine on top of an API that doesn't expose the data I needed.

## Stack

Python · JavaScript · TypeScript · Java · C++ · C# · SQL · XML

PostgreSQL and ORMs · Odoo (ORM, QWeb, OWL, security groups) · Next.js and React · Node.js · Docker · Linux, and I run my own Ubuntu server · Git

## How I work

I document what I build, including the parts I got wrong or deliberately left out. If you want to see how I think rather than just what I shipped, read the design notes in odoo19-shipment-management — they're more honest than a CV.

Reach me at abidhatim626@gmail.com
