# SabkaCollege - College Landing Pages

Landing pages for top Bangalore engineering colleges, built for [sabkacollege.com](https://www.sabkacollege.com/).

## Pages

| File | College | Estd | NAAC |
|------|---------|------|------|
| `bmsce.html` | BMS College of Engineering | 1946 | A+ |
| `ramaiah.html` | MS Ramaiah Institute of Technology | 1962 | A++ |
| `rvce.html` | RV College of Engineering | 1963 | A++ |
| `dsce.html` | Dayananda Sagar College of Engineering | 1979 | B++ |

## Features

- Blue-themed responsive design (mobile-first, 3 breakpoints)
- Tabbed content: Overview, Courses & Fees, Eligibility, Admissions, Placements, Facilities, Contact, Reviews
- Lead capture forms (sidebar + modal) posting to backend API
- Chart.js pie charts for seat distribution
- FAQ accordions with JSON-LD structured data
- Sticky tab navigation
- WhatsApp floating button + mobile quick-connect bar
- SEO meta tags + Open Graph + JSON-LD schema

## Tech Stack

- HTML5 / CSS3 (inline, single-file pages)
- Google Fonts (Poppins)
- Font Awesome 6.4.0
- Chart.js 4.4.0
- Vanilla JavaScript (no frameworks)

## Lead API

Forms submit to `https://backend-plum-one-76.vercel.app/api/leads` via POST.

## Running Locally

Open any HTML file directly in a browser, or use a local server:

```bash
npx serve .
```
