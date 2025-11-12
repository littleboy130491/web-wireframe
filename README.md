# Web Wireframe LLM Instructions

Quick prompts to generate professional website wireframes using AI assistants.

---

## 🏗️ Create Project Structure

**Brief Explanation**: Sets up the standard folder structure for web wireframe projects.

**Expected Input**:
- Project name (optional)
- Any specific folder requirements

**Output**: Complete folder structure with all necessary files and folders.

**Prompt**:
```
Create a web wireframe project with this structure:

project-name/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
└── assets/
    ├── images/
    ├── fonts/
    └── other/

Requirements:
- HTML5 semantic elements
- Tailwind CSS CDN
- Mobile-first responsive design
- Proper meta tags and viewport
```

---

## 📄 Generate Single Page

**Brief Explanation**: Creates a complete HTML page with all sections and functionality.

**Expected Input**:
- Page purpose/type (home, about, contact, etc.)
- Brand colors and style preferences
- Required sections/content blocks
- Any specific features needed

**Output**: Complete HTML file with embedded structure and styling.

**Prompt**:
```
Create a [PAGE TYPE] page for [BRAND/PROJECT NAME]:

Content sections:
- [List required sections]

Style requirements:
- Colors: [primary, secondary colors]
- Typography: [font preferences]
- Layout: [layout preferences]

Features needed:
- [List interactive features]
- [Form requirements]
- [Navigation requirements]

Use semantic HTML5, Tailwind CSS, and include responsive design with mobile menu.
```

---

## 🎨 Create Multi-Page Website

**Brief Explanation**: Generates multiple interconnected pages from a single-page design or sitemap.

**Expected Input**:
- Sitemap (markdown list or screenshot)
- Original single-page HTML (if splitting existing)
- Navigation structure
- Page hierarchy and flow

**Output**: Multiple HTML files with consistent navigation and proper linking.

**Prompt**:
```
Create a multi-page website from this sitemap:

[SITEMAP HERE - either markdown list or describe]

Pages to create:
- [List all pages from sitemap]

Requirements:
- Split content logically into separate pages
- Update all navigation links to point to correct pages
- Maintain consistent header/footer across all pages
- Add breadcrumbs where appropriate
- Include responsive navigation with mobile menu
- Use semantic HTML5 and Tailwind CSS

Each page should have unique content while keeping consistent branding.
```

---

## 📝 Add Specific Section

**Brief Explanation**: Adds a new content section to an existing page.

**Expected Input**:
- Section type (hero, features, testimonials, etc.)
- Content requirements
- Styling preferences
- Placement in page

**Output**: Complete section HTML with styling and any required JavaScript.

**Prompt**:
```
Add a [SECTION TYPE] section to the existing page:

Section content:
- [Describe content needed]
- [Number of items/cards]
- [Required headings/text]

Styling:
- [Color scheme]
- [Layout preferences]
- [Animation requirements]

Features:
- [Interactive elements]
- [Responsive behavior]
- [Accessibility requirements]

Use semantic HTML5 and Tailwind CSS classes. Make it responsive and accessible.
```

---

## 🔧 Fix/Modify Existing Code

**Brief Explanation**: Modifies or fixes issues in existing HTML/CSS/JS code.

**Expected Input**:
- The problematic code
- Description of the issue
- Desired outcome
- Any constraints

**Output**: Fixed code with explanation of changes.

**Prompt**:
```
Fix this [HTML/CSS/JS] code:

[CODE HERE]

Issues:
- [List specific problems]
- [What's not working]
- [Expected behavior]

Requirements:
- [Any constraints or preferences]
- [Maintain existing functionality]
- [Keep responsive design]

Provide the fixed code with brief explanation of changes made.
```

---

## 🎯 Create Component

**Brief Explanation**: Creates a reusable component (card, form, modal, etc.).

**Expected Input**:
- Component type and purpose
- Styling requirements
- Interactive features needed
- Responsive behavior

**Output**: Complete component HTML with CSS and JavaScript if needed.

**Prompt**:
```
Create a [COMPONENT TYPE] component:

Purpose:
- [What the component should do]
- [Where it will be used]

Content:
- [Text/elements needed]
- [Number of variations]

Styling:
- [Colors and design]
- [Size and spacing]
- [Hover/active states]

Features:
- [Interactive behavior]
- [Responsive requirements]
- [Accessibility needs]

Make it reusable and follow semantic HTML5 with Tailwind CSS.
```

---

## 📱 Optimize for Mobile

**Brief Explanation**: Ensures existing design works perfectly on mobile devices.

**Expected Input**:
- Current HTML/CSS code
- Specific mobile issues (if any)
- Target breakpoints

**Output**: Optimized code with mobile-first responsive design.

**Prompt**:
```
Optimize this code for mobile devices:

[HTML/CSS CODE HERE]

Current issues:
- [List any mobile problems]
- [What needs improvement]

Requirements:
- Mobile-first approach
- Touch-friendly interactions
- Proper breakpoints for tablet/mobile
- Maintain desktop functionality

Fix responsive issues and ensure great mobile UX.
```

---

## 🚀 Best Practices

**For Best Results**:
1. **Be Specific**: Include colors, fonts, and exact requirements
2. **Provide Context**: Share brand guidelines or reference designs
3. **Iterate**: Ask for refinements if the first result isn't perfect
4. **Test**: Always check the output in different browsers
5. **Validate**: Use HTML/CSS validators to check code quality

**Input Tips**:
- Use screenshots for visual reference
- Provide existing code when modifying
- Include brand colors in hex format
- Specify exact content requirements
- Mention target devices/browsers

**Output Review**:
- Check semantic HTML structure
- Verify responsive behavior
- Test interactive features
- Validate accessibility
- Ensure cross-browser compatibility