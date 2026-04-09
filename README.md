# Hospital Order Management — Frontend

## Live Site

<https://isutariy-p532-spring2026.github.io/hospital-order-management-frontend-version-2/>

## Backend Repo

<https://github.com/isutariy-P532-SPRING2026/hospital-order-management-backend-version-2>

## Render- deployed backend

<https://hospital-order-backend-p2.onrender.com/>

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks — per project spec)
- Deployed via GitHub Pages

## Features

- Submit orders (Lab, Medication, Imaging) with priority
- Live triage queue sorted by STAT > URGENT > ROUTINE
- Fulfilment staff claim and complete orders
- Cancel pending orders with confirmation dialog
- Audit trail of all commands
- Auto-polls backend every 3 seconds
- Toast notifications for all actions

## Run Locally

Open `index.html` directly in your browser.  
Make sure the backend is running on `http://localhost:8080`.

## Switch Between Local and Production Backend

In `index.html`, find this line near the top of the script:

```javascript
const API = 'https://hospital-order-backend-p2.onrender.com/';
```

Change to `http://localhost:8080/api` for local development.
