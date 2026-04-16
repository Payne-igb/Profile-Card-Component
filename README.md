This project is a **responsive, accessible Profile Card** built using **pure HTML, CSS, and vanilla JavaScript**.

It was developed as part of the **Frontend Wizards Stage 1B Task**, with a strong focus on:
* Semantic HTML
* Accessibility (WCAG considerations)
* Responsiveness
* Testability using `data-testid` attributes
---

##  Features

* 📄 Semantic HTML structure (`article`, `figure`, `nav`, `section`, etc.)
* ♿ Accessibility-focused (alt text, aria-live, keyboard navigation)
* 📱 Fully responsive design (mobile, tablet, desktop)
* ⏱️ Live updating **current time in milliseconds** using `Date.now()`
* 🧪 Test-friendly with required `data-testid` attributes
* 🔗 External social links with secure target behavior

---
## 🛠️ Technologies Used

* HTML5 (Semantic Markup)
* CSS3 (Flexbox & Responsive Design)
* Vanilla JavaScript (DOM Manipulation & Time Updates)

---

##  Requirements Implemented

The following elements were implemented according to specification:

* Profile Card Container → `data-testid="test-profile-card"`
* User Name → `test-user-name`
* Biography → `test-user-bio`
* Current Time (milliseconds) → `test-user-time`
* Avatar Image → `test-user-avatar`
* Social Links → `test-user-social-links`
* Individual Social Links → e.g. `test-user-social-twitter`
* Hobbies List → `test-user-hobbies`
* Dislikes List → `test-user-dislikes`

---

##  Time Implementation

The current time is dynamically generated using:

```javascript
Date.now()
```

It updates every second using `setInterval`, ensuring accuracy within an acceptable delta.

---

## ♿ Accessibility Considerations

* Meaningful `alt` text for images
* `aria-live="polite"` for dynamic time updates
* Keyboard-accessible links
* Visible focus states for navigation
* Proper semantic HTML structure

---

##  Responsiveness

* Mobile-first design
* Vertical stacking on smaller screens
* Side-by-side layout on larger screens using Flexbox
* Handles varying content lengths without breaking layout

---

##  How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/profile-card.git
   ```

2. Navigate into the project folder:

   ```bash
   cd profile-card
   ```

3. Open `index.html` in your browser:

   ```bash
   start index.html
   ```

---


##  Notes

* All required `data-testid` attributes were strictly followed to ensure compatibility with automated tests.
* The project avoids external libraries to demonstrate core frontend fundamentals.


