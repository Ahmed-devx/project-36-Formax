 
---

# Formax

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=flat-square)

*A simple Sign Up / Login form project with email/password authentication, built using HTML, CSS (and/or Bootstrap) and JavaScript.*

---

## Table of Contents

* [Project Overview](#project-overview)
* [Features](#features)
* [Demo / Preview](#demo-preview)
* [Technologies Used](#technologies-used)
* [Getting Started](#getting-started)
* [Folder Structure](#folder-structure)
* [Authentication Flow](#authentication-flow)
* [Screenshots](#screenshots)
* [Styling Guidelines](#styling-guidelines)
* [Roadmap](#roadmap)
* [FAQ](#faq)
* [Known Issues](#known-issues)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

---

## Project Overview

Formax is a practical web form application allowing users to **register** and **log in** using email and password. Designed with a clean, responsive UI, it’s perfect as a learning tool or starter template for web authentication projects.

## Features

* User **Registration** (email & password)
* User **Login** with credentials
* Navigation links between forms
* Responsive layout using Bootstrap (or similar CSS framework)
* Basic client-side validation
* Clean and modern UI design

## Demo / Preview

Live demo: [https://ahmed-devx.github.io/project-36-Formax/](https://ahmed-devx.github.io/project-36-Formax/)

## Technologies Used

* HTML5
* CSS3 / Bootstrap
* JavaScript

## Getting Started

### Prerequisites

* Modern web browser (Chrome, Firefox, Edge, Safari)

### Installation

```bash
git clone https://github.com/Ahmed-devx/project-36-Formax.git
cd project-36-Formax
```

### Running the Project

* Open `index.html` in your browser to access the Sign Up / Login forms.

## Folder Structure

```
project-36-Formax/
├── images/           # UI screenshots or assets
├── app.js            # JavaScript functionality
├── home.css          # Home page styles
├── home.html         # Landing page after login
├── index.html        # Sign Up / Login page
├── style.css         # Global styles
└── README.md         # This file
```

## Authentication Flow

1. User lands on **Login** page.
2. If new, navigates to **Sign Up** page.
3. Registration saves credentials (local/session storage placeholder).
4. Login with credentials redirects to `home.html`.
5. Optional logout navigation from home page.

> ⚠️ **Note:** This project is for demo purposes. It does **not** implement secure backend authentication.
 
## Styling Guidelines

* **Colors:** Light and neutral for forms; highlight buttons with primary color
* **Typography:** Use sans-serif fonts for readability
* **Borders & Shadows:** Use soft shadows and border-radius for modern UI feel
* **Responsiveness:** Ensure forms scale on mobile and tablet devices
* **Consistency:** Maintain consistent padding, margins, and button styles
 
## FAQ

**Q: Is this project production-ready?**
A: No, it’s a learning/starter template. Security and backend integration are not implemented.

**Q: Can I use this template for my own project?**
A: Yes! You can extend, modify, and integrate backend systems as needed.

**Q: Does it work on mobile devices?**
A: Yes, the UI is responsive using Bootstrap.

## Known Issues

* No backend or database; credentials are stored temporarily on client side
* Passwords are **not hashed** (not secure)
* No email verification implemented

## Contributing

1. Fork the repository
2. Create a branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push branch: `git push origin feature/YourFeature`
5. Open a pull request

 
## Contact

Created by [Ahmed-devx](https://github.com/Ahmed-devx). Questions or suggestions? Reach out via GitHub.

---

 
