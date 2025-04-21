# 14_Week.In-Class.A.CSS
🎯 Student Goal by End of Class (Focus Area Only)

- ✅ Style different HTML elements using CSS
- ✅ Understand and apply selectors (ID, class, element, body)
- ✅ Add background colors and images
- ✅ Use borders with custom styles, widths, and colors
- ✅ Apply text styles (color, size, font, alignment)
- ✅ Use padding and margin effectively
- ✅ Visually understand the CSS box model in action

---

🥜 Step-by-Step Instructions: Styling a Webpage with CSS

---

✅ Step 1: Load the “solution” file and observe

🔍 Open the pre-styled solution file in a browser.

Ask students:

- "Can you spot all the background images?"
- "Where's the chihuahua?"
- "Why is this text centered but the box isn't?"
- "What happens when I increase padding or margin?"

Purpose: Trigger curiosity about visual spacing and structure.

---

✅ Step 2: Explore spacing (Padding vs. Margin)

Prompt: "How can you make the hidden background (e.g., the chihuahua) show up?"

Adjust CSS in `.text` to show:

- `padding`: adds space **inside** the element
- `margin`: adds space **outside** the element

Common values to try:

```css
padding: 10px;
margin: 20px;
```

Teach:

- The **box model** (Content > Padding > Border > Margin)

---

✅ Step 3: Start fresh with the practice file

Open `practice.css` (empty template with selector prompts)

Tasks:

- Select each element with appropriate selector:

  - `#box-one` (ID)
  - `.text` (class)
  - `h2` (element type)
  - `#section-one` (ID/class)
  - `body` (universal)

- Recreate visual effects:

  - **Backgrounds**:
    background-color: lightblue;
    background-image: url("image.png");
    background-repeat: no-repeat | repeat-x | repeat-y;
    background-position: center | top | bottom | left | right;
    background-size: cover | contain | 100px;
    background-attachment: scroll | fixed;

  - **Borders**:
    border-style: solid | dotted | dashed | double;
    border-width: 2px | medium | thick;
    border-color: red | #ff6347 | rgb(255, 100, 100);
    border-radius: 5px | 50%;

  - **Text styling**:
    color: darkred | #000000;
    font-size: 16px | 1.2em;
    font-family: Arial, sans-serif;
    text-align: left | center | right | justify;

  - **Spacing**:
    padding: 10px | 10px 20px;
    margin: 20px | auto;
    width: 60%;

---

✅ Step 4: Teach Font Stacks and Generic Font Families

"What does 'Arial, sans-serif' mean?"

Explain `font-family` best practices:

- Always include **fallbacks**
- End with a **generic font family** for max compatibility

Generic Font Families:

- **Serif**: formal look (Times New Roman, Georgia)
- **Sans-serif**: clean, modern (Arial, Helvetica, Verdana)
- **Monospace**: fixed-width characters (Courier New, Consolas)
- **Cursive**: handwritten style (Brush Script)
- **Fantasy**: decorative or themed fonts

Example:
font-family: "Times New Roman", Times, serif;
font-family: Arial, Helvetica, sans-serif;
font-family: "Courier New", Courier, monospace;

---

✅ Step 5: Wrap-Up & Reflection

Ask students:

- "Which property made the element move?"
- "Which one changed the inside spacing?"
- "Which selector was the easiest to use?"

Optional:

- Style a 5th element using all learned techniques
- Complete a matching activity: property → effect

---

📊 Optional Extensions (Future Lessons)

- `box-shadow`, `hover`, `transition`
- `display: flex`, `grid`
- Responsive design with `@media` queries
- `position: absolute`, `fixed`
