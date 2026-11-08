# Medicinas de Abuela

Grandma's daily medicine chart and appointments: https://abuela.marcos-rios.info

Static page on GitHub Pages; checks, appointments and the Tramadol log live in the `sofi-meds` Firebase project
(collections `ab_checks`, `ab_appts`, `ab_prn`, `ab_subs`). Reminders run from `functions/abuela.js` in the
private `sofi-meds-server` repo — keep its `DAY` schedule in sync with `DAY` in `index.html`.
