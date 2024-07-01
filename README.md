# Personal Website - Stage One Task Project

This project is a simple single page website outlining my goals for the next two years in the tech field.
The webiste is created using only HTML, CSS, and JavaScript and it is designed to be visually appealing and responsive.

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Demo

You can view the live demo of the website [here](https://yourusername.github.io/personal-website-hng)

## Features

- Displays my Slack display name, email, and profile picture
- Shows the current time in UTC and the current day of the week
- Outlines my tech goals for the next two years
- Provides useful links
- Fully responsive and mobile-friendly
- Visually appealing desing with smooth scrolling and hover effects on links

## Technologies

- HTML
- CSS
- JavaScript

## Setup

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://yourusername.github.io/personal-website-hng
    ```

2. **Navigate to the project directory:**

    ```bash
    cd personal-website-hng
    ```

3. **Open `index.html` in your browser**

    You can simply open the `index.html` file in your web browser, or use a live server extension in your code editior.

## Usage

Once the project is set up, you can vieww the website in your browser. The website will display the current time in UTC and the current day of the week, as well as my Slack Display name, email, and profile picutre. It alsooutlines my tech goalsfor the next two yearsand provides useful links.

## Project Structrure

repository-name/
│
├── assets/
│ ├── profile-img/
│ │ └── slack_profile_picture.jpg
│ ├── styles.css
│ └── scripts.js
│
├── index.html
└── README.md

## License
This project is licensed under the MIT License.

## Criteria Fulfillment

This project meets the following criteria:

- **Languages Used:** HTML, CSS, and JavaScript
- **Responsiveness:** Fully responsive and functions well on all devices (desktop, tablet, mobile)
- **Images:** All images used on the website have natural dimensions
- **Data-Attributes:**
  - Slack Name: `data-testid="slackDisplayName"`
  - Current Time in UTC: `data-testid="currentTimeUTC"`
  - Current Day of the week: `data-testid="currentDay"`
  - Slack Email: `data-testid="slackEmail"`
  - Slack Profile Picture: `data-testid="slackProfilePicture"`
  - Links: `data-testid="hngLink"`, `data-testid="keywordLink"`, `data-testid="scrapeanywebLink"`
- **Content:** Clearly outlines my tech goals for the next 2 years
- **Visuals:** Visually appealing and well-organized design
- **Functionality:** All links function properly and direct users to the specified websites
