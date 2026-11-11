
Overview
CyberNova is a fully client‑side website prototype for a cybersecurity consulting firm. It allows visitors to browse services, read blog articles, submit contact enquiries, and book service requests. An administrative panel enables staff to manage submissions, view analytics, and control admin accounts – all without a backend server.

All data is stored in the browser’s localStorage. The system runs completely offline after the first load.

Quick Start
Extract cybernova_portfolio.zip to any local folder.

Double‑click cybernova.html – it will open in your default web browser.

No installation, database, or web server is required.

Default Admin Login
Field	Value
Username	admin
Password	Admin@123
After first login, you can create additional admin accounts or delete the default one.

Key Features
Public Pages
Home – hero section, stats, service cards, gallery, blog previews

About – company profile and animated visual

Services – nine detailed service offerings

Blog – six articles with modal pop‑up

Contact – enquiry form (Name, Email, Service, Message)

Booking – service request form (Name, Company, Email, Phone, Service, Preferred Date, Engagement Type, Notes)

Admin Panel
Secure login with brute‑force lockout (5 failures → 60‑second block)

Session auto‑logout after 15 minutes of inactivity

Dashboard with submission counts and activity log

Contacts table – view, filter (by name/email/status/service), mark as Resolved, delete

Bookings table – view, filter, mark as Confirmed, delete

Analytics charts (submissions over time, service breakdown, status overview)

Create / delete admin accounts

Technical Requirements
Requirement	Detail
Browsers	Latest Chrome, Firefox, Edge, Safari
JavaScript	Must be enabled
LocalStorage	Must be enabled (for data persistence)
Internet	Required only for first load (Google Fonts, Chart.js CDN). Afterwards works offline.
File Structure
text
cybernova.html          # Single-file application (all HTML/CSS/JS inline)