-----

# Amjad Hussain - Personal Portfolio Website

This repository contains the source code for the personal portfolio website of **Amjad Hussain**, a Computer Science undergraduate at the University of Jaffna. It is a fully responsive, single-page application built with HTML, JavaScript, and Tailwind CSS.

## 📖 About The Project

This portfolio serves as a digital Curriculum Vitae (CV) designed to showcase academic history, technical skills, software projects, and volunteering experiences.

### Key Features

  * **Responsive Design:** Fully optimized for mobile, tablet, and desktop screens using Tailwind CSS.
  * **Interactive UI:** Includes scroll-reveal animations and a custom JavaScript image slider.
  * **Project Showcase:** Dedicated sections for projects like *AuctixLab*, *Complaint Management System*, and *Bad Cookie Detector*.
  * **Dynamic Navigation:** Sticky header with a mobile-friendly hamburger menu.
  * **Photo Album:** A custom-coded JavaScript slideshow to display community and volunteering photos.

## 🛠️ Built With

  * **HTML5:** Semantic markup.
  * **Tailwind CSS:** Utility-first CSS framework (implemented via CDN for simplicity).
  * **JavaScript (ES6+):** Logic for the image slider, mobile menu toggling, and scroll observers.
  * **Inter Font:** Typography served via Google Fonts.

## 🚀 Getting Started

Since this project uses the Tailwind CSS CDN, there is no need for a complex build step (like npm or webpack) to view it locally.

### Prerequisites

  * A modern web browser (Chrome, Firefox, Edge, Safari).
  * A code editor (VS Code, Sublime Text) if you wish to modify the code.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/amjadh27/Portfolio.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd your-repo-name
    ```
3.  **Run the project:**
      * Simply open the `index.html` file in your browser.
      * *Optional:* For a better experience, use a live server extension (like Live Server in VS Code) to serve the file.

## 📂 Project Structure

```text
.
├── index.html            # Main HTML file containing structure and JS logic
├── assets/               # Folder for static assets (profile pics, project screenshots)
│   ├── favicon.png
│   ├── Amjad Hussain CV.pdf
│   └── ...
└── album/                # Folder specifically for the JS slideshow images
    ├── IEEE day 2023 1.jpeg
    └── ...
```

## 📝 Customization

If you plan to fork this project to create your own portfolio, please note the following:

1.  **Tailwind CDN:** This project uses the Play CDN script for Tailwind. For a production environment, it is recommended to switch to the [Tailwind CLI build process](https://tailwindcss.com/docs/installation) for better performance.
2.  **Image Slider:** The album logic is located at the bottom of `index.html` within the `<script>` tags. You will need to update the `slides` array with your own image paths and captions.
3.  **Email Configuration:** The contact form currently uses a `mailto:` action. You may want to replace this with a backend service (like Formspree or EmailJS) for better functionality.

## ⚖️ License

This project is licensed under the **GNU General Public License v3.0**.

### GNU GENERAL PUBLIC LICENSE

**Version 3, 29 June 2007**

Copyright (C) 2025 Amjad Hussain

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).

### Summary of Permissions & Conditions

  * ✅ **Commercial use:** You may use this software for commercial purposes.
  * ✅ **Modification:** You may modify the source code.
  * ✅ **Distribution:** You may distribute copies of the original or modified code.
  * ⚠️ **License and Copyright Notice:** You must include a copy of the license and copyright notice with the code.
  * ⚠️ **State Changes:** You must state significant changes made to the code.
  * ⚠️ **Disclose Source:** Source code must be made available when distributing the software.
  * ⚠️ **Same License:** Modifications must be released under the same license (GPLv3).

## 👤 Author

**Amjad Hussain**

  * **GitHub:** [@amjadh27](https://github.com/amjadh27)
  * **LinkedIn:** [Amjad Hussain](https://linkedin.com/in/amjadhussain2k)
  * **Email:** zh.amjadhussain@gmail.com
