okayyy session 3 is gonna be that moment when stuff finally *clicks* for folks—they start to really *see* how layout works. here’s your **plug-and-play lesson plan** for **CSS Layout & Positioning**, sub-friendly and fully tied to all the learning objectives:

---

## LESSON PLAN: **CSS Layout & Positioning – Box Model, Display, and Positioning**

### Class Time: 1 Hour  
**Platform:** GitHub Codespaces  
**Audience:** Beginner/intermediate (after Sessions 1 & 2)  
**Format:** Live stream + Q&A via chat, replay-ready  

---

### **Learning Goals (Students will be able to):**
- Visually break down the box model  
- Adjust padding, margins, borders, width, and height  
- Use float and clear to create basic layouts  
- Experiment with positioning: static, relative, absolute, fixed  
- Understand and apply display types: block, inline, inline-block, and flex

---

### **Tech Setup:**
1. Open the same GitHub Codespaces project used in Sessions 1 & 2  
2. Continue using the `styles.css` file  
3. Encourage preview tab use to see layout changes in real time  

---

### **Session Breakdown**

#### **0:00 – 0:10 | Intro to the Box Model**
- Use visuals or draw on a virtual whiteboard if you can (or share a screenshot)  
- Break down:
  - `content`
  - `padding`
  - `border`
  - `margin`  
- Add borders to all major sections of a webpage:
```css
section {
  border: 2px solid #444;
  padding: 1rem;
  margin-bottom: 1.5rem;
}
```
- Teach how margins create space *outside*, padding creates space *inside*

---

#### **0:10 – 0:20 | Sizing Elements (width, height, max-width)**
- Show:
  - `width: 300px;`
  - `height: 200px;`
  - `max-width: 100%;` for responsive design  
- Encourage students to:
  - Add images or divs and size them  
  - Add background colors to see sizing in action

---

#### **0:20 – 0:30 | Float & Clear (Classic Layouts)**
- Create a layout with two floated divs:
```css
.left {
  float: left;
  width: 45%;
  background: lightblue;
}
.right {
  float: right;
  width: 45%;
  background: lightgreen;
}
.clearfix::after {
  content: "";
  display: table;
  clear: both;
}
```
- Teach `.clearfix` to prevent layout breakage  
- Good historical context even if Flex/Grid are preferred later

---

#### **0:30 – 0:40 | Positioning: Static, Relative, Absolute, Fixed**
- Use a basic example:
```css
.box {
  position: relative;
  top: 20px;
  left: 20px;
}
```
- Cover all types:
  - `static` (default)
  - `relative` (moves from normal position)
  - `absolute` (relative to nearest positioned ancestor)
  - `fixed` (relative to viewport)
- Add a sticky nav example for ✨real-life context✨

---

#### **0:40 – 0:50 | Display Types: Block, Inline, Inline-block, Flex**
- Teach the difference:
  - `block`: full-width
  - `inline`: fits content, no margin/padding
  - `inline-block`: like inline but allows box model styles  
- Introduce `display: flex` with a simple row layout:
```css
nav {
  display: flex;
  justify-content: space-between;
}
```
- Let students apply it to their nav bars or image sections

---

#### **0:50 – 1:00 | Recap + Open Q&A**
- Review:
  - What’s the Box Model?
  - What’s the difference between `position: relative` vs `absolute`?
  - When would you use `flex` over `float`?
- Encourage them to experiment by creating “cards” or section boxes

---

### ✅ Check for Understanding:
- Can they explain what `margin`, `padding`, and `border` do?
- Did they float 2 divs side-by-side and clear them?
- Can they apply different `position` values and describe the results?
- Did they try at least one `display` type like `flex` or `inline-block`?

---

### 💡 Bonus Practice:
- Create a “hero banner” with a fixed nav at the top  
- Make a 3-column layout using float *and* then redo it with `flex`

---

want all 3 lessons bundled into a printable or editable Google Doc master packet? or need slide templates for each session? just say the word.