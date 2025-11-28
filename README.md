# 🦷 Chandan Clove Dental Landing Page

This is a responsive, single-page website clone/recreation for a dental clinic, likely serving as a marketing or informational landing page focusing on services like **Root Canal Treatment** and featuring patient testimonials and clinic statistics.

## ✨ Features

* **Header Navigation:** Includes the brand logo/heading and direct links for **Booking an Appointment** and a **Phone Contact**.
* **Hero Section:** A prominent section featuring a specific promotion ("Painless Root Canal Treatment in Delhi") alongside a dedicated **Free Consultation Form** with CAPTCHA for lead generation.
* **Stats Marquee:** A horizontally scrolling display of key clinic statistics (Clinics, Dentists, Happy Patients, Cases, Implants). 
* **Treatment Information:** Dedicated section detailing Root Canal Treatment (RCT) types, descriptions, and starting prices.
* **Real Smiles/Patient Stories:** Galleries showcasing before/after transformations and patient testimonials.
* **Why Choose Clove Dental & FAQs:** Sections providing information on clinic value propositions and answers to frequently asked questions, including services, doctors, painless treatments, and payment options.
* **Footer:** Contains brand information, privacy/terms links, and a link to the developer's LinkedIn profile.

## 🛠️ Technology Stack

This project is built using fundamental web technologies:

* **HTML5:** Provides the structure and semantic content of the page.
* **CSS3:** Styles the page, including responsive design elements (`@media` queries), layout (Flexbox), and the marquee animation.
* **Font Awesome:** Used for the icons (`fa-solid` and `fa-brands`).
* **External Assets:** Relies on local images (e.g., `Doctor.png`, `Dental-lab.jpg`, `root-1.png`, `patient-1.gif`, etc.) and a local JavaScript file (`chandan-script.js`), though the JS code was not provided.

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

You only need a modern web browser to view the project.

### Installation

1.  **Clone the Repository:**
    ```bash
    git clone [Your Repository URL Here]
    cd chandan-clove-dental
    ```
2.  **Add Assets:** Ensure you have the necessary assets (images like `Doctor.png`, `Dental-lab.jpg`, `root-1.png`, etc., and the icon) in a folder named **`assets`** at the root of the project directory. The CSS and HTML heavily rely on these relative paths (`./assets/image-name.png`).
3.  **Open in Browser:** Open the `index.html` file in your preferred web browser.

    ```bash
    # Example command (may vary by OS)
    open index.html
    ```

## 📂 Project Structure

The project directory should look like this:

````

chandan-clove-dental/
├── index.html           \# Main landing page structure
├── chandan-style.css    \# All CSS styling and media queries
├── chandan-script.js    \# JavaScript file (client-side interactivity)
└── assets/
├── icon.png
├── Doctor.png
├── Dental-lab.jpg
├── root-1.png
├── root-2.png
├── smile-1.png
├── ... (other smile/patient images)
└── faq.png

```

## 📝 Notes

* **Styling:** The design uses a color palette centered around **Orange (`#F8943F`)** and a light beige background (`#FFF9F4`), giving it a professional and warm aesthetic suitable for a healthcare/dental site.
* **Interactivity:** The provided HTML/CSS suggests the presence of client-side interactivity managed by **`chandan-script.js`** (e.g., CAPTCHA generation, form submission handling, FAQ collapsing/expanding). This file needs to be implemented separately.
* **Responsiveness:** The CSS includes media queries (`@media (max-width: 768px)`, etc.) to ensure the layout is functional and appealing on smaller screens (e.g., mobile devices).

## 🔗 Contact

Developed by **Sai Chandan** (as noted in the footer).

* **LinkedIn:** [https://www.linkedin.com/in/saichandanyadav/](https://www.linkedin.com/in/saichandanyadav/)

