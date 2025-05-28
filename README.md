# 🌐 Campus Connect Form

This web project was developed to simulate a modern, responsive university interface using **HTML5**, **CSS**, **Bootstrap**, and **JavaScript**. It includes a personal homepage and a CS Department information portal with a dynamic, fully featured student survey form.

---

## 🛠️ Technologies Used

- HTML5 + CSS3
- Bootstrap 4.5
- W3.CSS
- JavaScript (DOM, Events, Cookies, AJAX)
- JSON (Zipcode lookup)
- Hosted on AWS S3 (archived)

---

## 📁 Project Files

| File                             | Description                                  |
|----------------------------------|----------------------------------------------|
| `studentClassIndex.html`         | Personal homepage landing page               |
| `CSDepartmentInformationPage.html` | Info page about the CS department           |
| `CSDepartmentSurveyPage.html`    | Student survey form with advanced features   |
| `error.html`                     | Custom 404 error page                        |
| `myphoto.jpg`                    | Student image for homepage background        |
| `map2.jpg`                       | Embedded map image on contact page           |
| `Site Url.txt`                   | Archived AWS S3 URL (reference only)         |

---

## 🌟 Project Overview

This project simulates a full-featured, responsive university web experience and includes:

### 🏠 1. Student Homepage (`studentClassIndex.html`)
- Designed with W3.CSS templates
- Displays photo, bio, skill bars, and contact info
- Internal navigation to all subpages

### 🏫 2. CS Department Info & Survey Portal
- `CSDepartmentInformationPage.html`: degree info and course listing
- `CSDepartmentSurveyPage.html`: interactive form enhanced with:

#### 🚀 Advanced Features

- **Cookie-based Greeting**  
  Displays a personalized welcome (e.g., “Good Morning John”) using the name stored in a cookie based on the current time of day.

- **Data Processing**  
  Accepts 10 comma-separated numbers between 1–100, and automatically computes:
  - `Average`
  - `Maximum`
  Results are displayed in dedicated output fields.

- **Form Validation & Event Handling**  
  Uses custom JavaScript event handlers to validate:
  - Name field (only alphabets)
  - Address format
  - At least two checkboxes selected
  - One radio button selected
  - Email format
  Invalid inputs are caught with clear error alerts, and only problematic fields are cleared.

- **AJAX & JSON Zipcode Lookup**  
  When a user enters a Zipcode, an AJAX call fetches a JSON file and auto-fills:
  - `City`
  - `State`
  Invalid Zipcodes show an “invalid zip” message.

### 🧭 3. Navigation Bar & Styling
- Bootstrap navbar with dark theme and smooth scrolling
- GMU branding:
  - Green `#006633`
  - Yellow `#FFCC33`
- Custom border, box-shadow, background color
- Fully responsive layout

---

## 🖼️ Design Highlights

- Placeholder examples guide users on formats (e.g., date, email)
- `required` attribute ensures fields must be filled before submission
- Uses focus, autocomplete, and friendly design for accessibility
- External links and internal section linking for a seamless user experience

---

## 💡 Note

The project was originally hosted on AWS S3 as part of an academic assignment for SWE 642 at George Mason University. The current repository includes all HTML, CSS, JS, and asset files for local preview or deployment.

---

## 📬 Contact

📧 deepikatenduulkar5@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/deepika-tendulkar-a88bb8166/)

---

*Thanks for checking out this project!*
