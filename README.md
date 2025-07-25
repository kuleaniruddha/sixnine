# 🌿 Skincare Web Page

This is a responsive skincare-themed webpage built using HTML and CSS. The project focuses on clean layout, soft colors, and minimal interactive animations to enhance the user experience.

## ✨ Features

- Hero banner with call-to-action
- Product category tags with hover effect
- FAQ section with scroll animation
- Footer section with slide-in animation
- Responsive design for mobile and tablets

---

## 🧩 Technologies Used

- HTML5
- CSS3
- JavaScript (only for animations)

---

## 💡 Animations

### FAQ Section
- Fades in with a soft slide-up animation when it scrolls into view.
- Implemented using CSS transitions and `IntersectionObserver`.

### Footer
- Fades in and slides upward when it becomes visible in the viewport.
- Ensures elegant loading without affecting layout or performance.

```css
/* Footer Animation */
.footer {
  opacity: 0;
  transform: translateY(40px);
  transition: opacity 0.8s ease, transform 0.8s ease;
}

.footer.footer-visible {
  opacity: 1;
  transform: translateY(0);
}
