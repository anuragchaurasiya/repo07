# CineBook — Movie Ticket Booking Demo

<p align="center"><img src="assets/cinebook-banner.svg" alt="CineBook movie ticket booking demo banner" width="100%" /></p>

<p align="center"><strong>A responsive front-end movie booking demo built with HTML, CSS and vanilla JavaScript.</strong></p>

## Features

- Movie and show selection
- Silver, Gold and Diamond seat selection
- Snack selection and bill calculation
- Customer form validation
- Booking receipt and print view
- Booking history and cancellation
- Admin-style movie and show management
- Browser LocalStorage persistence
- Responsive layout

## Technology

HTML5, CSS3, JavaScript, DOM APIs and LocalStorage.

## Run locally

1. Clone the repository.
2. Open `index.html` in a modern browser.
3. Select a movie, show and seats to explore the demo.

No build step or backend is required for the current front-end demonstration.

## Screens and flow

<p align="center"><img src="assets/booking-flow.svg" alt="CineBook booking flow from movie selection to printable ticket" width="100%" /></p>

## Repository structure

```text
repo07/
├── assets/
│   ├── cinebook-banner.svg
│   └── booking-flow.svg
├── index.html
├── legacy-version.html
├── .nojekyll
├── LICENSE
└── README.md
```

## Security and data limitations

This is a browser-only learning demo. LocalStorage data is stored in the browser and is not a secure database. The admin check is implemented in client-side JavaScript and can be inspected or bypassed; it is not real authentication. Payment choices are simulated and no payment is processed. Do not enter real personal or payment information.

For production use, move authentication, authorization, booking validation and payment processing to a trusted backend, use a database, and implement server-side seat locking.

## Future improvements

- Split HTML, CSS and JavaScript into separate files
- Add automated tests and continuous integration
- Build a backend API and database
- Add accessible keyboard navigation and screen-reader testing
- Replace demo authentication with server-side identity management

## Maintainer

[Anurag Chaurasiya](https://github.com/anuragchaurasiya)