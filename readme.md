# 🎨 Professional Portfolio (Advanced Flexbox Layout)

This project showcases a **more advanced responsive portfolio website** using Flexbox CSS. It includes a vertical fixed navigation bar, flexible content layout, pricing plans, and responsive image galleries.

---

## 🌐 Live Preview

<p align="center">
  <img src="https://github.com/rohitash-eng/smoke-portfolio-using-flex-css-right/blob/main/images/website.png?raw=true" alt="Portfolio Preview" width="700"/>
</p>

---

## 📘 What We Have Learned in Flex CSS Using This Tutorial

This tutorial dives deeper into real-world Flexbox layout techniques.

### 💡 Flex Container Properties

| Property                  | Description                                                             | Why We Use It                                                                 |
|--------------------------|-------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| `display: flex`          | Converts an element into a flex container.                             | Used in `.main-container`, `.plan`, `.header`, `.row`, etc.                   |
| `flex-direction: row`    | Default direction – items aligned horizontally.                        | Used in `.main-container`, `.plan`, `.repo-img-sec`.                          |
| `flex-direction: column` | Stacks children vertically.                                            | Used in `.header`, `.contact-wrapper`, `.photography`, etc.                   |
| `justify-content`        | Distributes space along the main axis.                                | Used in `.plan` to evenly space pricing cards.                                |
| `align-items`            | Aligns children along the cross axis.                                 | Used in `.plan`, `.header`, `.contact-wrapper`.                               |
| `flex-wrap: wrap`        | Allows items to wrap on smaller screens.                              | Used in `.row` to wrap columns responsively.                                  |
| `gap`                    | Adds consistent spacing between items.                                | Used in `.repo-img-sec`, `.plan`, `.header`, `.contact-wrapper`.              |

---

### 💡 Flex Item Properties

| Property              | Description                                                                 | Why We Use It                                                                 |
|----------------------|-----------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| `flex-basis: 100%`   | Sets the base width of a flex item.                                         | Used in `.basic` and `.white-div` to control initial sizing.                  |
| `width`              | Explicitly defines item width.                                              | Used in `.left-section`, `.right-section`, `.img-sec img`, `.column`.         |
| `flex: 25%`          | Sets column widths inside `.row`.                                           | Used to create 4 equal-width image columns.                                   |
| `max-width`          | Restricts maximum width of items.                                           | Used in `.column` for responsive image gallery.                               |

---

### 📱 Media Responsiveness with Flexbox

| Media Feature          | Description                                               | Why We Use It                                                                 |
|------------------------|-----------------------------------------------------------|--------------------------------------------------------------------------------|
| `flex-wrap: wrap`      | Allows layout to break onto new lines on smaller screens | Used in `.row` to wrap image grid.                                            |
| `width: calc(...)`     | Dynamically sets width based on other elements            | Used in `.right-section` to avoid overlap from fixed `.left-section`.         |
| `position: fixed`      | Keeps `.left-section` always visible during scroll       | Used for vertical sidebar layout.                                             |
| `overflow: auto`       | Enables scroll if `.left-section` content exceeds height | Ensures sidebar is scrollable on smaller devices.                             |

---

## 🧰 Components Built with Flex CSS

- 🔹 Fixed left sidebar menu with vertical stacking  
- 🔹 Right-side content that dynamically adjusts width  
- 🔹 Responsive header, about section, and pricing plans  
- 🔹 Image grid with equal column layout  
- 🔹 Contact form and location footer using column-based alignment  

---

## 🔗 Live Demo

➡️ [View Live Demo](https://github.com/rohitash-eng/smoke-portfolio-using-flex-css-right/blob/main/images/website.png)

---

## 👨‍💻 Author

**Rohtash Singh**  
Frontend Developer | CSS Layout Specialist

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
