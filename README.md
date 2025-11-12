# Web Wireframe LLM Instructions

Quick prompts to generate professional website wireframes using AI assistants.

---

## 🎨 Create Multi-Page Website

**Brief Explanation**: Generates multiple interconnected wireframe pages from a sitemap.

**Expected Input**:
- Sitemap (markdown list or screenshot)
- Navigation structure
- Page hierarchy and flow

**Output**: Multiple HTML wireframe files with consistent navigation and proper linking.

**Prompt**:
```
Create a multi-page website WIREFRAME from this sitemap:

[SITEMAP HERE - either markdown list or describe]

This is a WIREFRAME project - not final designs. Use:
- Placeholder content throughout
- Simple, clean layouts
- Basic Tailwind CSS styling
- Focus on structure and navigation flow

Pages to create:
- [List all pages from sitemap]

Requirements:
- Split content logically into separate wireframe pages
- Update all navigation links to point to correct pages
- Maintain consistent header/footer across all wireframes
- Add breadcrumbs where appropriate
- Include responsive navigation with mobile menu
- Use semantic HTML5 and basic Tailwind CSS

Each wireframe page should demonstrate layout and user flow with placeholder content.
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
Create a [PAGE TYPE] wireframe page for [BRAND/PROJECT NAME]:

This is a WIREFRAME - not a final design. Use:
- Placeholder content (Lorem Ipsum text)
- Simple layout and structure
- Basic styling with Tailwind CSS
- Focus on functionality and layout, not visual design

Content sections:
- [List required sections]

Style requirements:
- Colors: [primary, secondary colors - simple palette only]
- Typography: [basic font preferences]
- Layout: [layout preferences]

Features needed:
- [List interactive features - basic functionality only]
- [Form requirements - wireframe structure, not final forms]

Create a functional wireframe that demonstrates layout and user flow.
```

---



## 📝 Add Specific Section

**Brief Explanation**: Adds a new content section wireframe to an existing page.

**Expected Input**:
- Section type (hero, features, testimonials, etc.)
- Content requirements
- Styling preferences
- Placement in page

**Output**: Complete section wireframe HTML with basic styling.

**Prompt**:
```
Add a [SECTION TYPE] wireframe section to the existing page:

This is a WIREFRAME section - use placeholder content and simple styling.

Section content:
- [Describe content structure needed]
- [Number of items/cards]
- [Required headings/text structure]

Styling:
- [Color scheme - simple palette]
- [Layout preferences]
- [Basic hover states if needed]

Features:
- [Basic interactive elements]
- [Responsive behavior]
- [Accessibility structure]

Use semantic HTML5 and basic Tailwind CSS classes. Create a functional wireframe section.
```

---

## 🔧 Fix/Modify Existing Code

**Brief Explanation**: Modifies or fixes issues in existing HTML/CSS/JS wireframe code.

**Expected Input**:
- The problematic wireframe code
- Description of the issue
- Desired outcome
- Any constraints

**Output**: Fixed wireframe code with explanation of changes.

**Prompt**:
```
Fix this [HTML/CSS/JS] wireframe code:

[CODE HERE]

Issues:
- [List specific problems]
- [What's not working]
- [Expected behavior]

Requirements:
- [Any constraints or preferences]
- [Maintain existing wireframe functionality]
- [Keep responsive design]
- [Preserve wireframe nature - don't over-design]

Provide the fixed wireframe code with brief explanation of changes made.
```

---

## 📱 Optimize for Mobile

**Brief Explanation**: Ensures existing wireframe design works perfectly on mobile devices.

**Expected Input**:
- Current HTML/CSS wireframe code
- Specific mobile issues (if any)
- Target breakpoints

**Output**: Optimized wireframe code with mobile-first responsive design.

**Prompt**:
```
Optimize this wireframe code for mobile devices:

[HTML/CSS CODE HERE]

Current issues:
- [List any mobile problems]
- [What needs improvement]

Requirements:
- Mobile-first approach
- Touch-friendly interactions
- Proper breakpoints for tablet/mobile
- Maintain desktop functionality
- Keep wireframe simplicity - don't over-design for mobile

Fix responsive issues and ensure great mobile UX while maintaining wireframe aesthetic.
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

**Output Review**:
- Check semantic HTML structure
- Verify responsive behavior
- Test interactive features
- Validate accessibility