# **Tech4Youth Cohort 1 - Module 1 Course Structure**

## **Welcome! 👋**

This guide explains how Module 1 is organized and how to use all the course materials in VS Code.

---

## **Module 1 Overview**

Module 1 is divided into **2 Topics**, each with **3 Lessons**, delivered on **two separate class days**:

### **Topic 01 (T01) — Wednesday Classes**
- **Date:** September 18, 2026 (Wednesday)
- **Focus:** Software Development Fundamentals
- **Lessons:** L1 (SDLC), L2 (Agile/Scrum), L3 (User Stories)
- **Duration:** 2 hours per lesson (6 hours total)

### **Topic 02 (T02) — Friday Classes**
- **Date:** September 20, 2026 (Friday)
- **Focus:** Web Development Essentials
- **Lessons:** L1 (HTML), L2 (CSS), L3 (Accessibility)
- **Duration:** 2 hours per lesson (6 hours total)

---

## **Files Included in This Course**

### **📋 Class Schedule & Lecture Guides**

| File                                | Purpose                                                                         | When to Use                                               |
| ----------------------------------- | ------------------------------------------------------------------------------- | --------------------------------------------------------- |
| `Module-1-Wednesday-Classes-T01.md` | Complete T01 course outline with learning objectives, activities, and key terms | Before Wednesday class; reference during/after for review |
| `Module-1-Friday-Classes-T02.md`    | Complete T02 course outline with learning objectives, activities, and key terms | Before Friday class; reference during/after for review    |

### **💻 HTML/CSS Project Files**

Each lesson in T02 has two versions:

#### **T02 - Lesson 1: Semantic HTML**
| File                    | Purpose                               | When to Use                              |
| ----------------------- | ------------------------------------- | ---------------------------------------- |
| `T02-L1-Starter.html`   | Template with TODO comments           | Start here in class; complete exercises  |
| `T02-L1-Completed.html` | Fully completed, professional example | Compare with starter; see best practices |

#### **T02 - Lesson 2: CSS Styling**
| File                    | Purpose                              | When to Use                             |
| ----------------------- | ------------------------------------ | --------------------------------------- |
| `T02-L2-Starter.html`   | HTML file with CSS TODOs             | Start here in class; add all CSS rules  |
| `T02-L2-Completed.html` | Fully styled, responsive, accessible | Check your work; learn professional CSS |

#### **T02 - Lesson 3: Accessibility (WCAG)**
| File                    | Purpose                              | When to Use                             |
| ----------------------- | ------------------------------------ | --------------------------------------- |
| `T02-L3-Starter.html`   | Buggy file with accessibility issues | Fix TODOs; identify and repair barriers |
| `T02-L3-Completed.html` | Fully accessible, WCAG AA compliant  | Verify your fixes; learn standards      |

---

## **How to Set Up in VS Code**

### **Step 1: Create Your Project Folder**

```bash
# Create a folder for this course (on your computer, not in VS Code)
mkdir tech4youth-module1
cd tech4youth-module1
```

### **Step 2: Organize Files**

Create this folder structure:

```
tech4youth-module1/
├── 📁 monday-reading/              # (if there are prep materials)
├── 📁 wednesday-class-T01/         # Topic 01 materials
│   └── Module-1-Wednesday-Classes-T01.md
├── 📁 friday-class-T02/            # Topic 02 materials
│   ├── Module-1-Friday-Classes-T02.md
│   ├── 📁 lesson-1-html/
│   │   ├── T02-L1-Starter.html
│   │   └── T02-L1-Completed.html
│   ├── 📁 lesson-2-css/
│   │   ├── T02-L2-Starter.html
│   │   └── T02-L2-Completed.html
│   └── 📁 lesson-3-accessibility/
│       ├── T02-L3-Starter.html
│       └── T02-L3-Completed.html
└── 📁 my-projects/                 # Your own work
    ├── project-1-semantic-html/
    ├── project-2-responsive-css/
    └── project-3-accessible-site/
```

### **Step 3: Open in VS Code**

1. Open VS Code
2. Click **File → Open Folder**
3. Navigate to `tech4youth-module1/` and open it
4. You'll see the full folder structure in the Explorer panel on the left

### **Step 4: Navigate Files**

- **Starter files:** Always start here in class
- **Completed files:** Check these after completing your work
- **Markdown files:** Read these for context and learning objectives

---

## **Daily Class Flow**

### **Wednesday (Topic 01) - 6 hours**

```
09:00 - 11:00  Lesson 1: Software Roles, SDLC, and Agile
               ├─ What is software?
               ├─ Team roles (PM, Dev, QA, etc.)
               ├─ SDLC phases
               └─ Waterfall vs. Agile

11:00 - 13:00  Lesson 2: Agile Frameworks & Scrum
               ├─ Agile Manifesto
               ├─ Scrum roles and ceremonies
               ├─ Sprints and artifacts
               └─ Connecting roles + SDLC + Scrum

13:00 - 14:00  LUNCH BREAK

14:00 - 16:00  Lesson 3: User Stories & Documentation
               ├─ Writing user stories
               ├─ Acceptance criteria (Given/When/Then)
               ├─ Markdown formatting
               ├─ Branches and Pull Requests
               └─ Responsible AI use
```

**📚 Resources:** See `Module-1-Wednesday-Classes-T01.md`

### **Friday (Topic 02) - 6 hours**

```
09:00 - 11:00  Lesson 1: Tools Setup & Semantic HTML
               ├─ Developer tools (VS Code, DevTools)
               ├─ What HTML is (and isn't)
               ├─ Semantic elements
               ├─ Landmarks, headings, links, images
               └─ Accessible forms
               👉 FILE: T02-L1-Starter.html & Completed.html

11:00 - 13:00  Lesson 2: Styling with CSS
               ├─ CSS basics and selectors
               ├─ Box model
               ├─ Flexbox and Grid
               ├─ Responsive design
               └─ Accessibility in CSS
               👉 FILE: T02-L2-Starter.html & Completed.html

13:00 - 14:00  LUNCH BREAK

14:00 - 16:00  Lesson 3: Web Accessibility (WCAG)
               ├─ WCAG 2.1 Level AA standards
               ├─ POUR principles (Perceivable, Operable, Understandable, Robust)
               ├─ Common accessibility barriers and fixes
               ├─ Testing tools (Lighthouse, axe, etc.)
               └─ Building inclusive from the start
               👉 FILE: T02-L3-Starter.html & Completed.html
```

**📚 Resources:** See `Module-1-Friday-Classes-T02.md`

---

## **How to Use Starter and Completed Files**

### **Starter Files - Your Workspace**

The starter files have **TODO comments** and **placeholder code**. Your job is to:

1. **Open** the Starter file in VS Code
2. **Find** each TODO comment
3. **Replace** the TODO with working code
4. **Save** and test in your browser
5. **Compare** with Completed file to verify

**Example (T02-L1-Starter):**
```html
<!-- TODO: Add semantic header element with title -->
<!-- TODO: Add semantic nav element with navigation links -->
```

**Your task:**
```html
<header>
    <h1>My Website Title</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
</nav>
```

### **Completed Files - Reference & Learning**

The completed files show:

- ✅ All TODOs filled in correctly
- ✅ Best practices and professional code
- ✅ Comments explaining why choices were made
- ✅ Accessibility features implemented
- ✅ Responsive design patterns
- ✅ Modern CSS techniques

**How to use:**

1. **After you finish** your own version, open the Completed file
2. **Side-by-side comparison** (drag window to split VS Code)
3. **Notice differences** in structure, naming, comments
4. **Learn** from professional patterns
5. **Identify** any missing or different approaches

---

## **Testing Your Work**

### **View in Browser**

For each HTML file:

1. **Right-click** the file in VS Code
2. **Select** "Open with Live Server" (if installed)
   - Or manually open the file: `File → Open with...`
   - Or drag the file into your browser

2. **View** the rendered page

### **Check Code with DevTools**

1. In browser, **Right-click** on the page
2. Select **Inspect** (or press F12)
3. Explore:
   - **Elements tab** — see the HTML structure
   - **Styles tab** — see which CSS rules apply
   - **Console tab** — see any errors
   - **Accessibility tab** — check accessibility issues

### **Test Keyboard Navigation**

Press **Tab** to move through the page:
- Can you reach every link and button?
- Is focus indicator visible?
- Tab order makes sense?

### **Responsive Design Testing**

1. Press **F12** to open DevTools
2. Click the **device icon** (top-left of DevTools)
3. Select different device sizes (iPhone, iPad, Desktop)
4. Verify layout looks good at all sizes

---

## **Key Terminology**

| Term               | Meaning                                              |
| ------------------ | ---------------------------------------------------- |
| **Starter file**   | Template with TODOs; your workspace                  |
| **Completed file** | Reference solution; see best practices               |
| **TODO**           | Comment marking work to be done                      |
| **Semantic HTML**  | Tags that describe meaning (header, nav, main, etc.) |
| **CSS**            | Styling language; controls colors, layout, fonts     |
| **Responsive**     | Design that works on all screen sizes                |
| **Accessibility**  | Making sites usable by everyone (WCAG standards)     |
| **DevTools**       | Browser tool for inspecting code (F12)               |
| **Focus**          | Currently active element (keyboard navigation)       |
| **Alt text**       | Description of images for screen readers             |

---

## **Learning Objectives by File**

### **T02-L1-Starter.html & Completed.html**

By completing this lesson, you will:
- ✅ Write semantic HTML with landmarks (header, nav, main, footer, aside)
- ✅ Create proper heading hierarchy (h1, h2, h3 without skipping)
- ✅ Write meaningful link text
- ✅ Add alt text to images
- ✅ Create accessible forms with labels

### **T02-L2-Starter.html & Completed.html**

By completing this lesson, you will:
- ✅ Apply CSS to HTML for styling
- ✅ Use Flexbox for responsive layouts
- ✅ Create mobile-first responsive designs
- ✅ Implement color contrast for readability
- ✅ Style interactive elements with hover and focus states

### **T02-L3-Starter.html & Completed.html**

By completing this lesson, you will:
- ✅ Understand WCAG 2.1 Level AA standards
- ✅ Know the POUR principles (Perceivable, Operable, Understandable, Robust)
- ✅ Identify and fix accessibility barriers
- ✅ Test with automated tools (Lighthouse, axe DevTools)
- ✅ Use keyboard navigation and screen readers

---

## **Accessibility Checklist**

Before considering any lesson complete, verify:

### **HTML (Semantic & Structure)**
- [ ] Exactly one `<h1>` (page title)
- [ ] Heading hierarchy proper (1→2→3, no skips)
- [ ] Landmarks used (header, nav, main, footer)
- [ ] All images have alt text
- [ ] All links have meaningful text
- [ ] All form inputs have labels

### **CSS (Styling & Layout)**
- [ ] Text is readable (size ≥16px, line-height ≥1.5)
- [ ] Color contrast sufficient (4.5:1 WCAG AA)
- [ ] Layout responsive (mobile, tablet, desktop)
- [ ] Focus states visible on all interactive elements
- [ ] No color used alone to convey information

### **Accessibility (WCAG AA)**
- [ ] Keyboard navigation works (Tab through entire page)
- [ ] Focus indicator visible on every interactive element
- [ ] No keyboard traps
- [ ] Sufficient color contrast throughout
- [ ] Forms properly labeled and functional
- [ ] Runs Lighthouse audit (target: 90+)
- [ ] No violations in axe DevTools

---

## **Common Commands in VS Code**

| Command             | Action                           |
| ------------------- | -------------------------------- |
| `Ctrl+K Ctrl+V`     | Split editor (compare two files) |
| `Ctrl+/`            | Comment/uncomment code           |
| `Ctrl+F`            | Find text                        |
| `Ctrl+H`            | Find and replace                 |
| `Alt+Up/Down`       | Move line up/down                |
| `Shift+Alt+Up/Down` | Duplicate line                   |
| `Tab`               | Indent selection                 |
| `Shift+Tab`         | Unindent selection               |
| `Ctrl+S`            | Save file                        |
| `Ctrl+Shift+P`      | Open command palette             |

---

## **Browser Extensions Recommended**

Install these to help with development and testing:

1. **Live Server** (VS Code extension)
   - Auto-refresh browser when you save files
   - Install from VS Code Extensions

2. **axe DevTools** (Browser extension)
   - Automated accessibility checking
   - Available for Chrome, Firefox, Edge

3. **Lighthouse** (Built into Chrome)
   - DevTools → Lighthouse tab
   - Audits accessibility, performance, SEO

4. **WebAIM Color Contrast Checker** (Browser extension or web tool)
   - Verify text has sufficient contrast

---

## **Before Each Class**

### **Before Wednesday (T01)**

- [ ] Read: `Module-1-Wednesday-Classes-T01.md`
- [ ] Understand: What is SDLC, Agile, Scrum?
- [ ] Know the differences: Waterfall vs. Agile
- [ ] Have VS Code installed
- [ ] Have a modern browser (Chrome, Firefox, Edge, Safari)

### **Before Friday (T02)**

- [ ] Read: `Module-1-Friday-Classes-T02.md`
- [ ] Understand: What is semantic HTML?
- [ ] Know: What makes an image accessible?
- [ ] Understand: What is responsive design?
- [ ] Have test files downloaded and organized
- [ ] Have browser DevTools accessible (F12)

---

## **Practice Schedule**

### **During Class**
- Follow along with instructor
- Complete Starter files as directed
- Ask questions when confused
- Help classmates

### **After Class (Same Day)**
- Finish any uncompleted Starter files
- Compare your work with Completed files
- Fix any issues found
- Save your work

### **Next Day (Before Next Lesson)**
- Review yesterday's lesson
- Look at Completed files again
- Do one small practice project combining skills
- Prepare any questions for instructor

---

## **Turning in Your Work**

At the end of each lesson, you'll have:

1. **Your version** of the Starter file (completed TODOs)
2. **Notes** on what you learned
3. **Questions** about parts you didn't understand

**How to share:**

Option A: Email your HTML files
Option B: Push to GitHub (if using Git)
Option C: Share via classroom platform

**Name your files:**
- `T02-L1-YourName-Completed.html`
- `T02-L2-YourName-Completed.html`
- `T02-L3-YourName-Completed.html`

---

## **Helpful Resources**

### **Documentation**
- 🔗 **MDN Web Docs:** https://developer.mozilla.org/
- 🔗 **W3C WCAG 2.1:** https://www.w3.org/WAI/WCAG21/quickref/
- 🔗 **WebAIM:** https://webaim.org/

### **Tools**
- 🔗 **Lighthouse:** Built into Chrome DevTools
- 🔗 **axe DevTools:** https://www.deque.com/axe/devtools/
- 🔗 **Color Contrast Checker:** https://webaim.org/resources/contrastchecker/
- 🔗 **NVDA Screen Reader:** https://www.nvaccess.org/

### **Learning**
- 📹 **A11ycasts by Google Chrome:** https://www.youtube.com/playlist?list=PLNYkxOF6rcICWx0C9Xc-RgEzwLvePLCVZ
- 📹 **Web.dev by Google:** https://web.dev/learn/
- 📚 **Lecture Guides:** Included in each class markdown file

---

## **Troubleshooting**

### **File won't open in browser**
- Ensure it's an `.html` file (not `.md`)
- Use Live Server extension (VS Code)
- Or drag file directly into browser

### **Styling not showing**
- Check for typos in CSS (selectors, properties)
- Refresh browser (Ctrl+R or Cmd+R)
- Clear cache (Ctrl+Shift+Delete)
- Use DevTools to inspect (F12)

### **Changes not appearing**
- Save file (Ctrl+S or Cmd+S)
- Refresh browser (F5)
- If using Live Server, auto-refresh should work

### **Can't find a file**
- Check folder structure is correct
- Use Ctrl+P in VS Code to quick-open files
- Search by filename

### **Accessibility issues**
- Run Lighthouse audit (DevTools → Lighthouse)
- Use axe DevTools to identify problems
- Compare with Completed file
- Ask instructor

---

## **Getting Help**

### **During Class**
1. Raise your hand
2. Ask in real-time
3. Work with classmates

### **After Class**
1. Review Completed file
2. Check troubleshooting section
3. Email instructor with specific question
4. Include:
   - What you tried
   - What went wrong
   - What you expected to happen

### **Class Slack/Forum**
- Post your question
- Share relevant code
- Help other classmates

---

## **Next Steps After Module 1**

Once you complete all three lessons in each topic:

- ✅ You'll have a portfolio of accessible HTML/CSS projects
- ✅ You'll understand software development fundamentals
- ✅ You'll be ready for Module 2 (JavaScript and beyond)
- ✅ You'll know how to build inclusive websites

Keep these files for reference!

---

## **Contact & Questions**

- **Instructor:** [Instructor Name/Email]
- **Class Slack:** [Slack Workspace]
- **Office Hours:** [Times]
- **Course Repository:** [GitHub/GitLab Link]

---

**Welcome to tech4youth! Let's build an accessible, inclusive web together. 🚀**

---

### **Quick Start Checklist**

- [ ] Download all course files
- [ ] Create folder structure (see above)
- [ ] Open folder in VS Code
- [ ] Install Live Server extension
- [ ] Test by opening a file in browser
- [ ] Run Lighthouse audit to see DevTools work
- [ ] Read T01 or T02 class markdown depending on today
- [ ] Ready for class! 🎉

**Let's go!**