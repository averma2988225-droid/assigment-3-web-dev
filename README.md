# assigment-3-web-dev

# Web Development Lab Assignment - Responsive Personal Portfolio (CSS + HTML)

This is my submission for **Lab Assignment 3**.  
The task was to create a simple personal portfolio website using only **HTML and CSS**.  
The website includes:  
- Header  
- Navigation bar  
- Hero section  
- About section  
- Skills section (Grid layout)  
- Projects section (Grid layout)  
- Contact form  
- Footer  

The main goal of the assignment was to learn **Flexbox, CSS Grid, Responsive Design and Basic Web Layout**.

---

## 🛠 Technologies Used

- HTML5  
- CSS3 (Flexbox + Grid)  
- Google Fonts  
- Basic Media Queries for responsiveness  

---

## 📱 Responsive Design Testing

I tested the layout on three viewport sizes to check how the design adjusts:

| Device Type | Tested Width | Behavior |
|-------------|-------------|----------|
| Mobile      | 375px–480px | Navigation stacks, hero layout becomes vertical, grids adjust to single-column |
| Tablet      | 768px       | Layout still centers and grids become 2-column |
| Desktop     | 1024px+     | Full layout visible with proper spacing, grids show multiple columns |

Breakpoints in media queries:

```css
@media (max-width: 768px) {
   /* Tablet and mobile adjustments */
}

@media (max-width: 480px) {
   /* Small mobile layout changes */
}
