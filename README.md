# SWE 642 – Assignment 1
### Web Application Development | George Mason University

**Student:** Chetana Patel  
**Email:** cpatel9@gmu.edu  
**Course:** SWE 642 – Software Engineering for the World Wide Web  
**Live Site:** http://swe642-hw1-chets.s3-website.us-east-2.amazonaws.com/

---

## Overview

This assignment demonstrates hands-on experience with **HTML5**, **CSS3**, and the **Bootstrap 5** framework. It consists of three web pages hosted as a static website on **AWS S3**.

---

## Pages

### 1. Student Homepage (`index.html`)
Personal homepage built using the **W3.CSS** framework template. Includes:
- Profile photo and bio
- Professional experience (Tesla, Bank of America, GMU)
- Technical skills with visual progress bars
- Projects and education
- Navigation links to the CS Department and Survey pages

### 2. CS Department Information Page (`cs-department.html`)
Informational page about the GMU Computer Science department. Includes:
- Department description
- List of MS degree programs
- Required courses table for each MS program
- Hyperlink to the Campus Survey page

### 3. CS Department Campus Survey (`survey.html`)
Feedback form for prospective students. Includes:
- Input fields: username, address, city, state, ZIP, phone, email, URL, date
- Checkboxes: students, location, campus, atmosphere, dorm rooms, sports
- Radio buttons: friends, television, internet, other
- Datalist for high school graduation month (Jan–Dec) + year field
- Dropdown: Very Likely / Likely / Unlikely recommendation likelihood
- Textarea for additional comments
- HTML5 validation with required fields visually indicated
- `autocomplete="on"` for the entire form
- Autofocus on the first field on page load

### 4. Error Page (`error.html`)
Custom 404 error page served by S3 when a URL is not found. Includes quick navigation links back to all main pages.

---

## Technologies Used

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Custom styling, GMU color scheme, animations |
| Bootstrap 5 | Navbar, grid layout, tables, form components |
| W3.CSS | Homepage template and layout |
| AWS S3 | Static website hosting |

---

## GMU Color Scheme

| Color | Hex |
|---|---|
| GMU Green | `#006633` |
| GMU Yellow | `#FFCC33` |

---

## File Structure

```
swe642-hw1/
├── index.html            # Part 1 – Student homepage
├── cs-department.html    # Part 2 – CS Department info page
├── survey.html           # Part 2 – Campus survey form
├── error.html            # Custom 404 error page
├── photo.jpg             # Student profile photo
├── url.txt               # Live S3 URL
└── README.md             # This file
```

---

## How to Run Locally

1. Clone or download this repository
2. Open `index.html` in any browser, or use **VS Code Live Server** for hot reload
3. No build steps or dependencies required — pure HTML/CSS/JS

---

## AWS S3 Hosting

The site is hosted as a static website on Amazon S3 (free tier):

- **Bucket:** `swe642-hw1-chets`
- **Region:** `us-east-2`
- **Index document:** `index.html`
- **Error document:** `error.html`
- **Live URL:** http://swe642-hw1-chets.s3-website.us-east-2.amazonaws.com/

---

*George Mason University · Volgenau School of Engineering · SWE 642 · 2025*
