here’s a sub-friendly lesson plan version of your HTML session, fully prepped for use with **GitHub Codespaces**, so anyone can teach it—even on short notice:

---

## LESSON PLAN: **Intro to HTML – Build a Multi-Page Website with Navigation**

### Class Time: 1 Hour  
**Platform:** GitHub Codespaces  
**Audience:** Beginner students  
**Format:** Live stream or classroom session with questions via chat  

---

### **Learning Goals (Students will be able to):**
- Understand how HTML is used to structure web content  
- Use HTML tags to build pages  
- Create a simple multi-page website with working navigation  
- Keep code organized with proper indentation  
- Insert images and use `alt` text for accessibility  

---

### **Tech Setup (DO THIS FIRST):**
1. **Log into GitHub**  
2. Open the [starter template repo] (or have them create a blank repo)  
3. **Launch GitHub Codespaces** from the repo  
4. Inside Codespaces, open a file called `index.html`  
5. Create 2 more files: `about.html` and `contact.html`

---

### **MATERIALS NEEDED:**
- A GitHub account (all students)
- Internet connection
- A starter folder structure (or sub can instruct students to create the files themselves)

```
/project-folder
  index.html
  about.html
  contact.html
```

---

### **Session Breakdown**

#### **0:00 – 0:10 | Warm-up + HTML Overview**
- Ask: “What do you think HTML does on a website?”
- Explain the difference between:
  - **HTML** = structure
  - **CSS** = style
  - **JavaScript** = behavior  
- Walk through this boilerplate and explain:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Website</title>
  </head>
  <body>
    <h1>Welcome!</h1>
    <p>This is my first web page.</p>
  </body>
</html>
```

#### **0:10 – 0:25 | HTML Elements in Action**
- Teach:
  - Headings: `<h1>` - `<h6>`
  - Paragraphs: `<p>`
  - Lists: `<ul>`, `<ol>`, `<li>`
- Define:
  - Elements vs attributes
  - Nesting + indentation  
- Activity: Have students build a simple “About Me” layout inside `index.html`

#### **0:25 – 0:35 | Semantic HTML + Layout Tags**
- Introduce semantic tags: `<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`
- Live demo: structure `index.html` with these tags  
- Prompt: “Why do you think these tags matter for accessibility/search engines?”

#### **0:35 – 0:45 | Navigation + Multi-Page Linking**
- Teach anchor tags:
```html
<a href="about.html">About</a>
```
- Students build a nav menu in each file:
```html
<nav>
  <a href="index.html">Home</a>
  <a href="about.html">About</a>
  <a href="contact.html">Contact</a>
</nav>
```
- Have them test clicking through their site using the preview tab in Codespaces

#### **0:45 – 0:55 | Images + Accessibility**
- Teach how to use:
```html
<img src="https://placekitten.com/300/200" alt="Cute kitten">
```
- Explain the importance of the `alt` tag  
- Optional: Have students add 1 image to each page

#### **0:55 – 1:00 | Recap + Chat Q&A**
- Review key tags learned
- Ask:
  - “What was the most surprising thing about HTML?”
  - “What else do you want to learn next?”  
- Optional Challenge: Have students add a custom section like “My Hobbies” or “Projects”

---

### **Back-up Instructions (for subs who need extra help):**
If stuck:
- Ask students to raise their hand or drop a question in chat  
- You can search [MDN Web Docs](https://developer.mozilla.org/en-US/) for tag references  
- Remind students: **it doesn’t have to be perfect**—focus on learning how HTML works

---

### ✅ Exit Ticket / Check for Understanding:
- Can the student click between all 3 pages?
- Do they use at least 3 different HTML tags (headings, paragraphs, images)?
- Is their code clean and readable with indentation?

---

want a printable version or google doc template of this too?