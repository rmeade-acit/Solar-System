# 🚀 CSS Solar System Project Checklist

**Name:** ___________________________  
**Target Grade:** [ ] A  [ ] B  [ ] C

---

### **Grade: C (Space Cadet)**
*To earn a C, you must check every box in this section.*

- [ ] **8-9 Planets:** There are at least 8 planets defined in the HTML and styled in the CSS.
- [ ] **Circular Motion:** All planets move in a circular orbit around the Sun using `rotate()` and `translateX()` keyframes.
- [ ] **Shooting Star:** At least one shooting star is animated to "fly" across the screen.
- [ ] **Background:** The `body` has a space-themed background image that covers the entire viewport.
- [ ] **Basic Documentation:** The CSS and HTML include initial comments explaining what the code is doing.

---

### **Grade: B (Astrophysicist)**
*To earn a B, you must meet all Grade C requirements PLUS the following:*

- [ ] **Proportional Orbits:** Planet `animation-duration` values are mathematically calculated based on Earth’s 365.25-day orbit.

>[!Note]
>### Student Pro-Tip: The "Proportional" Formula
>
> To earn a **Grade B**, your orbits must be mathematically accurate. Use this formula to calculate the `animation-duration` for each planet:
>
>$$\text{Planet Orbit (s)} = \frac{\text{Actual Planet Days}}{365.25} \times \text{Student's Earth Speed (s)}$$
>
>**Example:**
>If you want your **Earth** to orbit in **10 seconds**, and you are calculating for **Mars** (687 days):
>1.  $687 / 365.25 = 1.88$
>2.  $1.88 \times 10 = 18.8$
>3.  **Mars duration:** `18.8s`
>
- [ ] **Shooting Star Timing:** Shooting stars use `animation-delay` and `infinite` repeats so they occur at different times rather than just once.
- [ ] **Upright Planets:** Keyframes include a "counter-rotation" (e.g., `rotate(-360deg)`) so planets do not appear upside down at the bottom of the orbit.
- [ ] **Grouped Styling:** CSS is organized with generalized styles (like `body` or `.planets`) grouped together.

---

### **Grade: A (Master Astronomer)**
*To earn an A, you must meet all Grade B requirements PLUS the following:*

- [ ] **Planet Spin:** The planets themselves rotate on their own axis (spin) while they move around the Sun.
- [ ] **Two Embellishments:** At least two extra items are included (e.g., a UFO on a bezier curve, a comet, or the ISS).
- [ ] **Top-Down Organization:** Try to take a “largest to smallest” approach, where the more generalized stylings (body, *, etc.) are higher up in the styling order.
- [ ] **Full Documentation:** Every section of code—especially logic adapted from online—is explained to Mr. Meade and Mr. Costantino via comments.

---