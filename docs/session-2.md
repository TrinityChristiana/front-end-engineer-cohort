🔥 yes let’s gooo! here’s a **sub-ready, live stream-friendly lesson plan** for **Session 2: CSS Basics (Text & Colors)** that builds directly on the HTML session and hits *every one* of your learning objectives.

---

## LESSON PLAN: **Intro to CSS – Text, Fonts, and Colors**

### Class Time: 1 Hour  
**Platform:** GitHub Codespaces  
**Audience:** Beginners who’ve just finished HTML basics  
**Format:** Live stream with chat Q&A (replay-friendly)

---

### **Learning Goals (Students will be able to):**
- Style their existing multi-page site using external CSS  
- Apply fonts, colors, spacing, and alignment  
- Use the right CSS method (inline, internal, external)  
- Understand how the CSS cascade, specificity, and inheritance work  
- Use Google Fonts for better typography

---

### **Tech Setup (Prep First):**
1. Open GitHub Codespaces project from previous class  
2. Create a new file called `styles.css`  
3. Link it to `index.html` using:
```html
<link rel="stylesheet" href="styles.css">
```

---

### **MATERIALS NEEDED:**
- GitHub Codespaces access  
- Existing HTML files (`index.html`, `about.html`, `contact.html`)  
- Create `styles.css` (or include starter one if preferred)

---

### **Session Breakdown**

#### **0:00 – 0:10 | CSS = Style (Intro)**
- Quick recap: “Last time we built the structure. Now let’s make it look good.”  
- Define HTML vs CSS again (structure vs style)  
- Show how the browser renders HTML → now we enhance it with CSS  
- Explain 3 ways to add CSS:
  1. Inline (`style=""`)  
  2. Internal (`<style>` in `<head>`)  
  3. External (`.css` file + `<link>`)  

> ✅ Let them try all 3 briefly on one tag to *see* the difference. Emphasize external as the goal.

---

#### **0:10 – 0:25 | External Stylesheets FTW**
- Link to `styles.css` and remove any inline/internal styles  
- Add a simple body style:
```css
body {
  font-family: sans-serif;
  color: #333;
  background-color: #f9f9f9;
}
```
- Explain how styles are kept clean + separate

---

#### **0:25 – 0:35 | Selectors, Specificity, & Inheritance**
- Teach:
  - Tag selectors (`h1`, `p`)  
  - Class selectors (`.title`)  
  - ID selectors (`#main-heading`)  
- Explain inheritance (ex: font from `<body>` applies to children)
- Show specificity hierarchy: ID > Class > Tag
- Live demo: create 3 conflicting rules, and explain which wins

---

#### **0:35 – 0:45 | Fonts, Colors & Google Fonts**
- Visit [Google Fonts](https://fonts.google.com)
- Show how to:
  1. Choose a font
  2. Copy the `<link>` into `<head>`
  3. Add `font-family` in CSS
- Style headings + body text with different fonts
- Teach:
```css
h1 {
  font-size: 2rem;
  font-weight: 700;
  color: #2c3e50;
  text-align: center;
  margin-bottom: 1rem;
}
```

---

#### **0:45 – 0:55 | Spacing, Alignment, and Text Styling**
- Teach:
  - `margin`, `padding`, `line-height`  
  - `text-align: left/center/right`  
  - `letter-spacing`, `word-spacing`
- Let students apply styles to headings, paragraphs, and list items

---

#### **0:55 – 1:00 | Recap + Questions**
- Recap what they styled today:
  - Fonts
  - Colors
  - Text alignment
  - Google Fonts
  - CSS specificity and structure
- Encourage them to play with color palettes or make a “theme”

---

### ✅ Check for Understanding:
- Did the student link an external stylesheet?
- Can they style `h1`, `p`, and `ul` using class or tag selectors?
- Did they successfully add a Google Font?
- Can they explain why one rule overrides another?

---

### 🧪 Bonus Challenge (Optional)
- Style all 3 pages with a consistent theme  
- Make navigation links look different when hovered using `:hover`

---

want me to bundle sessions 1 + 2 into a single sub packet or slide deck too? or ready it for print/pdf export?