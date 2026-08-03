# Awesome-Facilities-Management

## Similar Projects to Facilities Management & CMMS Platforms

**Facilities Management / CMMS (Computerized Maintenance Management System)** platforms help organizations manage work orders, preventive maintenance, asset tracking, inventory, space management, and facility operations. Leading commercial tools include FMX, UpKeep, MaintainX, Limble CMMS, Hippo CMMS, Fiix, eMaint, IBM Maximo, Archibus, and OfficeSpace.

Below is a **curated list** of notable platforms and their open-source equivalents. The open-source CMMS and facilities management ecosystem offers several solid options, especially for organizations that want full data ownership and customization.

## 🏢 SaaS / Hosted Platforms

| Platform | Description | Pricing | Free Tier & Limits | Company Size (Revenue/Valuation) |
| :--- | :--- | :--- | :--- | :--- |
| **[IBM Maximo](https://www.ibm.com/products/maximo)** | Enterprise-grade Asset Management and CMMS solution. | Custom / Quote-based (typically starts at $40,000+/year via AppPoints) | No free tier (14-day free trial available) | **Enterprise Leader** (Parent IBM Revenue: ~$62B/year) |
| **[MaintainX](https://www.getmaintainx.com/)** | Modern, user-friendly CMMS focused on work orders and team collaboration. | Paid plans start at $10/user/month | **Free plan available** (max 2 active repeating work orders, 2 work orders with procedures, 1-month history limit) | **$2.5B Valuation** (Estimated Revenue: ~$115M/year) |
| **[Archibus](https://archibus.com/)** | Integrated Workplace Management System (IWMS) and facilities management platform. | Custom / Quote-based | No free tier | **$600M Valuation** (Estimated Revenue: ~$200M/year) |
| **[Limble CMMS](https://www.limblecmms.com/)** | Easy-to-use CMMS with strong preventive maintenance and asset tracking features. | Custom / Quote-based | No free tier (free trial, unlimited free requesters) | **$450M Valuation** (Estimated Revenue: ~$20M/year) |
| **[Fiix](https://www.fiixsoftware.com/)** (Rockwell Automation) | CMMS with strong asset performance and analytics capabilities. | Paid plans start at $45/user/month | **Free plan available** (max 3 users, 25 preventive maintenance tasks, no inventory management) | **Acquired** (Parent Rockwell Revenue: ~$8B/year) |
| **[OfficeSpace](https://www.officespacesoftware.com/)** | Space management and workplace experience platform. | Custom / Quote-based | No free tier | **Estimated Revenue: ~$30.9M/year** (owned by Eptura) |
| **[FMX](https://www.gofmx.com/)** | Facilities management software popular in education and multi-site organizations. | Custom / Quote-based | No free tier | **Estimated Revenue: ~$30.9M/year** |
| **[UpKeep](https://www.upkeep.com/)** | Popular mobile-first CMMS for work orders, asset management, and preventive maintenance. | Starts at $20–$24/user/month | No free tier (7-day free trial, unlimited free requesters) | **Estimated Revenue: ~$22.4M/year** (Valuation ~$100M+) |
| **[eMaint](https://www.emaint.com/)** (Fluke) | Established CMMS/EAM platform. | Starts at ~$69/user/month (3-user minimum) | No free tier | **Estimated Revenue: ~$15.6M/year** (owned by Fluke/Fortive) |
| **[Hippo CMMS](https://www.hippocmms.com/)** | Straightforward CMMS for maintenance teams. | Starts at ~$35/user/month | No free tier (free trial available) | **Estimated Revenue: ~$3.1M/year** (acquired by Eptura) |

## 🔓 Open-Source Software

### Dedicated Open-Source CMMS & Facilities Management
- **[openMAINT](https://www.openmaint.org/)** — The leading open-source CMMS and facilities management application. Built on the CMDBuild framework, it supports asset and building management, preventive and corrective maintenance, work orders, inventory, documents, and space-related processes. Excellent for facility and property maintenance teams.
- **[CalemEAM](https://github.com/calemeam)** — Open-source Enterprise Asset Management (EAM) / CMMS system. Provides asset tracking, work orders, preventive maintenance, and multi-site support.
- **SuperCMMS / Atlas CMMS-style projects** — Community and commercial-open-source CMMS solutions focused on work orders, assets, and preventive maintenance (check current GitHub activity for the most maintained forks).

### Broader Open-Source Platforms with Strong Maintenance Modules
- **[Odoo](https://github.com/odoo/odoo) (Maintenance / MRP modules)** — Open-source ERP with dedicated maintenance management capabilities. Can handle work orders, equipment, preventive maintenance schedules, and integrate with inventory and accounting.
- **[ERPNext](https://github.com/frappe/erpnext)** — Open-source ERP that includes asset management and maintenance features suitable for facilities and plant maintenance.
- **[GLPI](https://github.com/glpi-project/glpi)** — Primarily an IT Service Management and asset management tool, but frequently adapted for broader equipment and facilities tracking.

### Asset-Focused Supporting Tools
- **[Snipe-IT](https://github.com/snipe/snipe-it)** — Excellent open-source IT asset management system. Useful for tracking equipment, licenses, and consumables (pairs well with a full CMMS).
- CMDBuild (the framework behind openMAINT) — Highly configurable open-source environment for building custom asset and maintenance management applications.

### Typical Open-Source Stack
1. **Core CMMS / Facilities** — openMAINT or CalemEAM
2. **ERP + Maintenance** — Odoo or ERPNext (when broader business processes are needed)
3. **Asset registry** — Snipe-IT or the asset modules in the tools above
4. **Mobile / field use** — Progressive web apps or community mobile clients
5. **Reporting & IoT** — Custom dashboards + optional sensor integrations

These solutions provide full control over maintenance data, no per-user licensing fees, and the ability to tailor workflows to exact facility or industrial requirements.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to CMMS, facilities management, enterprise asset management (EAM), or maintenance work-order systems.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open maintenance tools help teams keep facilities running without proprietary lock-in! 🛠️
