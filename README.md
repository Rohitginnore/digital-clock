# digital-clock
# ⏰ Digital Clock | HTML | CSS | JavaScript

A clean and minimal **Digital Clock** web app built using **HTML, CSS, and JavaScript**.  
It displays the **current local time** and updates automatically every second using JavaScript’s `setInterval()` method.

---

## Demo
<img width="1894" height="885" alt="image" src="https://github.com/user-attachments/assets/51015c46-d4b4-4a78-9140-818c344e384c" />


## 🕒 Features

- 🧭 Displays real-time system clock  
- ⚡ Updates every second automatically  
- 💡 Uses simple JavaScript (no frameworks)  
- 🎨 Clean and responsive design  

---

## 🛠️ Technologies Used

- **HTML5** – structure  
- **CSS3** – styling  
- **JavaScript (ES6)** – functionality  

---

## 💻 JavaScript Code

```js
const clock = document.getElementById("clock");

setInterval(function () {
  let date = new Date();
  clock.innerHTML = date.toLocaleTimeString();
}, 1000);
