# Bankist - Fictional Banking Application

A simple frontend banking app built with vanilla JavaScript, part of "The Complete JavaScript Course 2023".

## Features

- **User Authentication** — login with username + PIN
- **Account Dashboard** — view balance, transaction history, and summary (in/out/interest)
- **Money Transfer** — send funds to another account
- **Loan Request** — request a loan (approved if 10% of loan exists in deposit history)
- **Close Account** — delete account with confirmation
- **Auto Logout** — 30-second countdown timer
- **Sorting** — toggle transaction sorting
- **Multi-currency** — supports UAH, USD with locale-aware formatting (`Intl.NumberFormat`, `Intl.DateTimeFormat`)

## Project Structure

```
├── index.html      # Main HTML layout (nav, dashboard, forms)
├── script.js       # All application logic (data, DOM, events)
├── style.css       # Styles (CSS Grid, gradients, animations)
├── logo.png        # Brand logo
└── icon.png        # Favicon
```

## Tech Stack

- Vanilla JavaScript (ES6+)
- HTML5
- CSS3 (Grid, Flexbox, gradients)
- `Intl` API for date & currency formatting

## Usage

Open `index.html` in a browser. No build tools or server required.
