# Ballalyze ⚽📊

Ballalyze is a football data analytics demo project built with **HTML5** and **CSS3**.
The goal of this project is to practice semantic HTML structure, accessibility features (ARIA roles, labels), and modern layout techniques using **CSS Grid** and **Flexbox**.

Ballalyze enables users to explore player statistics, compare performance metrics, and gain insights through a clean and modern interface.
The project is intended for football enthusiasts and recruiters looking to analyze player performance.

![Am I Responsive Result](assets/images/readme/responsive.png)

*The project is deployed on GitHub Pages and can be viewed* [here](https://tarik-box.github.io/PP1-Idea-0/)

---

## Features:

### Existing Features

* **Navigation Bar**

The navigation bar is available across all pages. It helps users easily navigate between sections (Home, About, Reports, Contact, and Statistics 'on smaller Devices') .

The active page is highlighted and underlined for better orientation.

![Navbar](assets/images/readme/nav.png)

###### * The landing page

The landing page introduces the project with a clear headline and football-themed visuals, helping users immediately understand the website’s purpose.

![1759027014065](image/README/1759027014065.png)


* **Player Cards Section**

Displays featured players with quick insights. This provides users with a quick overview of performance highlights without requiring them to delve into detailed reports.

![Cards](assets/images/readme/cards.png)

* **Reports Page**

Provides a summarized performance report for 'Player of the week'. This feature helps recruiters and enthusiasts access quick evaluations of players.

![Report](assets/images/readme/report.png)

* **Statistics Section**

On large devices, it is integrated directly into the main page, while on smaller devices, it appears as a dedicated page. It highlights key player attributes in a visual way.

![Stats](assets/images/readme/stats.png)

* **About Page**

Explains the goal and scope of the project. This ensures new users understand the vision and target audience of Ballalyze.

![About](assets/images/readme/about.png)

* **Contact Page**

Includes a simple contact form where users can send messages. It improves communication and allows feedback or inquiries about the project.

![Contact](assets/images/readme/contact.png)

* **Responsive Design**

The site is fully responsive across devices (desktop, laptop, tablet, mobile). This ensures accessibility and usability for all screen sizes.

* **Footer Section**

Contains relevant information and links. It gives users a consistent closing element across the site, supporting navigation and project credibility.

![1759026848407](image/README/1759026848407.png)


---

## Project Structure

##### Assets:

│── assets/
│   ├── images/       # Project Images
│   ├── icons/        # Project Icons
│   └── css/style.css # CSS styling

##### Pages:

│── index.html       # Main HTML file
│── about.html       # About page
│── contact.html     # Contact page
│── reports.html     # Report page
│── statistics.html  # Statistics page

##### Documentation:

│── README.md        # Project documentation

---

## Technologies Used

- **HTML5**
- **CSS3** (Grid, Flexbox, animations)

---

## Validation

All HTML and CSS files have been checked using the official validators:

### HTML Validation

All HTML pages (`index.html`, `about.html`, `contact.html`, `reports.html`, `statistics.html`) were tested using the [W3C Markup Validation Service](https://validator.w3.org/).
All pages passed with no errors.

**Example:**

Index Page

![Index HTML Validation](assets/images/readme/validation/index-html.png)

Reports Page

![Report HTML Validation](assets/images/readme/validation/reports.png)

About Page

![About HTML Validation](assets/images/readme/validation/about.png)

Contact Page

![Contact HTML Validation](assets/images/readme/validation/contact.png)

Statistics Page

![Statistics HTML Validation](assets/images/readme/validation/statistics.png)

### CSS

The CSS file (`style.css`) was tested using the [W3C Jigsaw CSS Validation Service](https://jigsaw.w3.org/css-validator/).

- **Style File**

✅ Validation passed with **no errors**.
  ⚠️ *One minor warning is shown related to Google Fonts import, which is an external resource and not part of the authored CSS.*

![CSS Validation](assets/images/readme/validation/style.png)

---

## About

Ballalyze is designed as a learning project for front-end development training.
It simulates a small-scale football analytics platform where users can view statistics, player comparisons, and insights in a clean and modern interface.
It is also part of a larger personal project that will one day come to fruition.

---

## User Experience (UX)

##### User Stories:

- **As a football fan**, I want to see player statistics so I can compare players visually.
- **As a recruiter**, I want to navigate the site easily to find key player info.

---

### Wireframes

#### Home Page Wireframe

![Home Page Wireframe](assets/images/readme/home.png)

#### About Page Wireframe

![About Page Wireframe](assets/images/readme/about.png)

#### Report Page Wireframe

![Report Page Wireframe](assets/images/readme/report.png)

#### Contact Page Wireframe

![Contact Page Wireframe](assets/images/readme/contact.png)

---

## 📸 Preview / Responsiveness

Am I Responsive result:
[View Responsive Test](https://ui.dev/amiresponsive?url=https://tarik-box.github.io/PP1-Idea-0/index.html)

Example images:

![Responsive design 1](assets/images/readme/resp-1.png)
![Responsive design 2](assets/images/readme/resp-2.png)

Example images for different screen sizes:

Desktop / 4K: ![Responsive 4K](assets/images/readme/4k.png)

Desktop / 1440px: ![Responsive 1440](assets/images/readme/1440.png)

Laptop / 1024px:

![Responsive 1024](assets/images/readme/1024.png)

Tablet / 768px:

![Responsive 768](assets/images/readme/768.png)

Mobile / 320px:

![Responsive 320](assets/images/readme/320.png)

---

## Author

Created by *Tarik Ataia*
This project is part of my front-end development learning journey as well as a vision for a larger personal project.

---

## Disclaimer

All icons and images used on this website are provided strictly for **educational and learning purposes only**.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Tarik-Box/PP1-Idea-0.git
```

## Testing / How to Test

This section explains how to test the functionality, responsiveness, and overall usability of the **Ballalyze** project.

Open `index.html` in your browser to view the project locally.

### 1. Navigation Testing

* Click through all navigation links in the Navbar (`Home`, `About`, `Reports`, `Contact`, `Statistics > "on smaller devices"`) to ensure they direct to the correct pages.
* Check that the active page is highlighted and underlined in the Navbar.
* Note: Player cards are non-clickable and do not link to other pages.
* On the Reports page, users can view summaries of player performance.
* On the About page, users can learn about the project and its purpose.
* On the Contact page, users can view the contact form (if implemented) or contact information to reach out regarding the project.
* Ensure that headings, paragraphs, and layout display correctly across different screen sizes.

### 2. Responsiveness Testin

Open Chrome DevTools (F12) or any browser developer tools.

* Use the device toolbar to simulate different screen sizes:

  * Desktop (1920px, 1366px)
  * Laptop (1280px, 1024px)
  * Tablet (768px, 600px)
  * Mobile (375px, 320px)
* Verify that the layout adjusts correctly, text is readable, and images scale appropriately.
* Ensure the navigation and content remain usable at all breakpoints.

---

## Credits / Attributions

* *HTML5* and *CSS3* for structure and styling.
* Icons sourced from [FontAwesome](https://fontawesome.com/) under free-to-use license.
* Images sourced from Google Images (used for educational purposes only).
