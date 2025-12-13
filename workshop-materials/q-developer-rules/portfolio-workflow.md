# Technical Portfolio Builder - Q Developer Workflow

## PRIORITY: Portfolio Building Workflow
When user requests help building a technical portfolio, ALWAYS follow this workflow.

## MANDATORY: Custom Welcome Message
**CRITICAL**: When starting a portfolio building request, begin with this message:

"Welcome to the Technical Portfolio Builder! I'll guide you through creating a professional portfolio website that showcases your skills, projects, and experience.

Our streamlined process includes:
- 📋 Information Gathering - Collect your professional details
- 🎨 Design Preferences - Choose your style and colors
- 🏗️ Portfolio Generation - Create your complete website
- ✅ Review & Refinement - Polish and perfect your portfolio

This structured approach ensures we build a portfolio that truly represents you. Let's begin!"

---

## Phase 1: Information Gathering

### Step 1: Basic Information
Ask the user to provide:
- [ ] Full name
- [ ] Current role/title
- [ ] Professional summary (2-3 sentences)
- [ ] Years of experience
- [ ] Primary technical skills (5-7 key skills)

**Wait for user response before proceeding.**

### Step 2: Career Background
Ask the user to provide:
- [ ] Current company and role
- [ ] Previous 2-3 significant roles
- [ ] Key career milestones or transitions
- [ ] Areas of expertise or specialization

**Wait for user response before proceeding.**

### Step 3: Projects
Ask the user to provide 3-5 projects with:
- [ ] Project name
- [ ] Brief description (2-3 sentences)
- [ ] Technologies used
- [ ] Problem solved or impact
- [ ] GitHub repository link (if available)
- [ ] Live demo link (if available)

**Wait for user response before proceeding.**

### Step 4: Contact & Links
Ask the user to provide:
- [ ] LinkedIn profile URL
- [ ] GitHub username
- [ ] Email preference (dedicated portfolio email or existing)
- [ ] Any other professional links (Twitter, blog, etc.)

**Wait for user response before proceeding.**

### Step 5: Design Preferences
Ask the user:
- [ ] Favorite colors or color scheme preference
- [ ] Any design inspiration or examples they like
- [ ] Professional photo available? (yes/no)

**Confirm all information collected before proceeding.**

---

## Phase 2: Portfolio Structure Planning

### Step 1: Review Information
- [ ] Summarize all collected information
- [ ] Identify any gaps or missing details
- [ ] Ask clarifying questions if needed

### Step 2: Propose Structure
Present the portfolio structure:
```
Homepage
├── Hero section with name and title
├── Professional summary
└── Featured projects (top 3)

About Page
├── Career timeline
├── Skills and expertise
└── Professional background

Projects Page
├── Detailed project showcases
├── Technologies used
└── Links to code/demos

Blog Page (Optional)
├── Published articles
└── Technical writing

Contact Page
├── Professional links
└── Contact form or email
```

**Ask user to approve structure before proceeding.**

---

## Phase 3: Portfolio Generation

### Step 1: Create File Structure
Generate the following files:
- [ ] index.html (Homepage)
- [ ] about.html (About page)
- [ ] projects.html (Projects page)
- [ ] blog.html (Blog page - optional)
- [ ] contact.html (Contact page)
- [ ] styles.css (Styling)

### Step 2: Implement Homepage
- [ ] Create hero section with user's name and title
- [ ] Add professional summary
- [ ] Feature top 3 projects
- [ ] Apply color scheme

### Step 3: Implement About Page
- [ ] Create career timeline
- [ ] List skills and technologies
- [ ] Add professional background narrative
- [ ] Include placeholder for photo

### Step 4: Implement Projects Page
- [ ] Create project cards for each project
- [ ] Include descriptions and technologies
- [ ] Add links to GitHub/demos
- [ ] Organize by importance or recency

### Step 5: Implement Contact Page
- [ ] Add professional links (LinkedIn, GitHub, etc.)
- [ ] Include contact form or email
- [ ] Add current status/availability

### Step 6: Apply Styling
- [ ] Implement user's color scheme
- [ ] Ensure responsive design (mobile-friendly)
- [ ] Add navigation across all pages
- [ ] Ensure WCAG accessibility compliance

**Show user the generated files and ask for review.**

---

## Phase 4: Review & Refinement

### Step 1: User Testing
Ask user to:
- [ ] Open index.html in browser
- [ ] Navigate through all pages
- [ ] Check mobile view
- [ ] Verify all links work

### Step 2: Gather Feedback
Ask user:
- [ ] What would you like to change?
- [ ] Are colors working well?
- [ ] Is any content missing?
- [ ] Any layout adjustments needed?

### Step 3: Implement Changes
- [ ] Make requested modifications
- [ ] Test changes
- [ ] Confirm with user

### Step 4: Deployment Guidance
Provide instructions for:
- [ ] Creating GitHub repository
- [ ] Enabling GitHub Pages
- [ ] Custom domain setup (optional)
- [ ] How to update portfolio in future

---

## Key Principles

### Content First
- Focus on getting user's real content before worrying about design
- Use placeholders only when necessary
- Encourage specific, concrete information

### Accessibility
- All buttons must have sufficient color contrast (WCAG AA)
- Images must have alt text
- Navigation must be keyboard accessible
- Semantic HTML throughout

### Responsive Design
- Mobile-first approach
- Test on multiple screen sizes
- Flexible layouts that adapt

### Professional Quality
- Clean, modern design
- Consistent styling
- No broken links
- Fast loading times

---

## Common Refinement Requests

### Color Changes
```
User: "Can you make it more blue/purple/etc?"
Response: Update CSS color variables and show preview
```

### Content Updates
```
User: "I want to add another project"
Response: Ask for project details, add to projects page
```

### Layout Changes
```
User: "Can we make the hero section bigger?"
Response: Adjust CSS, show updated version
```

### Link Updates
```
User: "My GitHub link is wrong"
Response: Update link, verify it works
```

---

## Success Criteria

By the end of this workflow, user should have:
- [ ] Complete 5-page portfolio with their real content
- [ ] Responsive design that works on mobile
- [ ] Personalized color scheme
- [ ] All links working correctly
- [ ] WCAG accessible design
- [ ] Clear instructions for deployment
- [ ] Knowledge of how to update it

---

## Time Estimates (for 90-minute workshop)

- Phase 1: Information Gathering - 15 minutes (if pre-filled)
- Phase 2: Structure Planning - 5 minutes
- Phase 3: Portfolio Generation - 45 minutes
- Phase 4: Review & Refinement - 25 minutes

**Note**: Pre-filling information before workshop is CRITICAL for staying within 90 minutes.

---

## Troubleshooting

### If user doesn't have all information ready:
- Use placeholders with clear markers
- Provide template text they can replace later
- Focus on structure over perfect content

### If running short on time:
- Focus on 3 core pages (home, about, projects)
- Skip blog page
- Use template colors
- Provide refinement instructions for later

### If user wants major changes:
- Implement one change at a time
- Test after each change
- Keep original version as backup

---

*This workflow ensures every participant leaves with a working, professional portfolio in 90 minutes or less.*
