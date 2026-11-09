# WashSync – Campus Laundry Tracking Prototype

WashSync is a front-end website prototype designed to make campus laundry tracking simpler for students living in residential hostels. It gives students a clear view of their current laundry status and their annual wash allowance.

> **Project status:** UI prototype / demonstration. This version uses sample data and browser-side interactions; it is not connected to a backend or a live campus laundry system.

## Features

- **Student dashboard:** Displays a personalised student view and a summary of laundry activity.
- **Current laundry tracking:** Shows the status of the student's current laundry order.
- **One order at a time:** Supports a maximum of one order in the washing process at any moment.
- **Pickup-only workflow:** Once washing is complete, the order is marked as ready for pickup. There is no delivery stage.
- **Order history:** Lets students review previous and completed laundry orders.
- **Annual wash allowance:** Tracks a maximum allowance of 44 washes per academic year.
- **Automatic wash-count update:** A wash is deducted from the remaining allowance when the order is completed, not while it is still being washed.
- **Clothes-based load classification:** Determines the load category from the number of clothes submitted.

## Load classification

| Number of clothes | Load category |
| ---: | --- |
| 1–13 | Small load |
| 14–17 | Medium load |
| 18 or more | High load |

## Wash allowance

Each student has an allowance of **44 washes per academic year**.

- Completed washes count towards the annual allowance.
- Orders that are still being washed do not reduce the remaining allowance.
- The remaining count is calculated as:

  `Washes remaining = 44 − Completed washes`

## Getting started

No installation or package setup is required.

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a modern web browser.

The prototype is designed as a standalone page, with its styling, JavaScript, and logo embedded in the HTML file.

## Run with GitHub Pages

You can publish the prototype as a static website using GitHub Pages:

1. Push `index.html` and this `README.md` to the root of your GitHub repository.
2. Open the repository's **Settings**.
3. Select **Pages** from the sidebar.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder.
6. Save the settings and wait for GitHub Pages to publish the site.

GitHub will display the published website URL in the Pages settings.

## Technology used

- HTML5
- CSS3
- JavaScript
- GitHub Pages (optional static hosting)

## Current prototype limitations

- Uses demonstration/sample data.
- Does not include user authentication.
- Does not connect to a database or server.
- Does not send real-time notifications.
- Data changes are not permanently saved and may reset when the page is refreshed.
- It is a visual and interactive prototype, not a production-ready laundry management system.

## Future improvements

Possible next steps for a full application include:

- Student and laundry-admin authentication.
- Backend and database integration.
- Persistent order records and wash-allowance tracking.
- Admin controls for updating laundry status.
- Real notifications when an order is ready for pickup.

## Project objective

WashSync aims to improve the campus laundry experience by giving hostel students better visibility into their laundry status, reducing uncertainty, and helping them keep track of their yearly wash allowance.
