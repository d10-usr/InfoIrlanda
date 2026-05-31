# Ghidul Românului în Irlanda — InfoIrlanda

Acest proiect este o resursă comunitară, non-profit, destinată comunității românești din Irlanda, oferind informații oficiale, drepturi legale și resurse practice.

## Găzduire (Hosting)

Proiectul este găzduit pe **Cloudflare Pages** (administrabil prin [dash.cloudflare.com](https://dash.cloudflare.com)).

Site-urile principale de producție sunt active la următoarele adrese:
- 🌐 [https://infoirlanda.pages.dev/](https://infoirlanda.pages.dev/)
- 🌐 [https://irlanda.pages.dev/](https://irlanda.pages.dev/)

Orice push efectuat direct pe ramura principală (**main** / mainline branch) va declanșa o actualizare automată în producție a ambelor site-uri web.

---

## Deployments Automate (Preview Deployments)

Pentru fiecare **Pull Request (PR)** deschis, Cloudflare Pages generează automat o subversiune (preview deployment) specifică acelui PR. 

Aceasta permite testarea și vizualizarea modificărilor înainte de a fi îmbinate (merged) în ramura principală (main branch).

- Fiecare preview are un URL unic generat de Cloudflare.
- Puteți găsi mai multe detalii despre configurarea și comportamentul acestor medii de preview în documentația oficială Cloudflare: [Cloudflare Pages Preview Deployments Documentation](https://developers.cloudflare.com/pages/configuration/preview-deployments/).
