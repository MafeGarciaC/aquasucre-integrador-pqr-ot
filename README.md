# AquaSucre E.S.P. - Integrador PQR -> OT

Consulta las PQR (HD Ticket) de Frappe Helpdesk por API REST y las muestra en una tabla. Version 1: solo lectura.

## Render
- Build: `pip install -r requirements.txt`
- Start: `gunicorn app:app`
- Variables: `FRAPPE_URL`, `FRAPPE_API_KEY`, `FRAPPE_API_SECRET` (solo en Render, nunca en el repo).
