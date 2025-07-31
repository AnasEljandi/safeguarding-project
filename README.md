# Safeguarding Awareness Website

## Table of Contents

1. [Design & Planning](#design--planning)  
   - [User Stories](#user-stories)  
   - [Wireframes](#wireframes)  
   - [Typography](#typography)  
   - [Colour Scheme](#colour-scheme)  
2. [Features](#features)  
   - [Navigation](#navigation)  
   - [Footer](#footer)  
   - [Home Page](#home-page)  
   - [Other Features](#other-features)  
3. [Technologies Used](#technologies-used)  
4. [Testing](#testing)  
   - [Google Lighthouse Performance](#google-lighthouse-performance)  
   - [Browser Compatibility](#browser-compatibility)  
   - [Responsiveness](#responsiveness)  
   - [Code Validation](#code-validation)  
   - [Manual Testing](#manual-testing)  
5. [Bugs](#bugs)  
6. [Deployment](#deployment)  
7. [Credits](#credits)  

---

## Design & Planning

### User Stories
## User Stories

### 🟢 User Story 1: Understand What Safeguarding Is (Must-Have)
**As a** concerned visitor,  
**I want** a simple explanation of what safeguarding is,  
**So that** I can quickly understand its purpose and importance.

**Acceptance Criteria:**
- Clear definition of safeguarding shown near the top of the site.
- Avoids complex terms or jargon.
- Includes who safeguarding applies to (e.g., children, vulnerable adults).

---

### 🟢 User Story 2: Recognise the Signs of Abuse or Neglect (Must-Have)
**As a** parent, teacher, or carer,  
**I want** to see a list of common signs of abuse or neglect,  
**So that** I can identify if someone may be at risk.

**Acceptance Criteria:**
- “Signs to Watch For” section includes visual cues or bullet points.
- Covers emotional, physical, and behavioral signs.
- Content is accessible and readable across devices.

---

### 🟢 User Story 3: Know What Steps to Take in a Safeguarding Situation (Must-Have)
**As a** member of the public,  
**I want** to know what to do if I have a safeguarding concern,  
**So that** I can respond correctly and responsibly.

**Acceptance Criteria:**
- “Action Steps” section includes clear, numbered instructions.
- Includes contact details or guidance for escalation.
- Reassures user that acting on concern is the right thing to do.

---

### 🟢 User Story 4: Access the Website Easily on Any Device (Must-Have)
**As a** mobile or tablet user,  
**I want** the site to work smoothly on all devices,  
**So that** I can read and scroll without any layout issues.

**Acceptance Criteria:**
- Site uses responsive Bootstrap layout.
- Text, buttons, and links are sized for small screens.
- No horizontal scrolling or layout breaks on mobile.

---

### 🟡 User Story 5: Contact the Right Person in a Crisis (Should-Have)
**As someone** with an urgent safeguarding concern,  
**I want** to quickly find contact details for relevant safeguarding authorities,  
**So that** I can report my concern without delay.

**Acceptance Criteria:**
- Contact section includes phone numbers, email, or links to local authorities.
- Easy to find from any point on the page (via navbar or link).
- Styled clearly to draw attention.

---

### 🟡 User Story 6: Learn Who Safeguarding Protects (Should-Have)
**As a** curious visitor,  
**I want** to know who is protected by safeguarding policies,  
**So that** I understand why it's necessary and who benefits from it.

**Acceptance Criteria:**
- The “What is Safeguarding?” section or a callout box mentions groups at risk (e.g., children, elderly, disabled).
- May include short examples or icons for clarity.

---

### 🔵 User Story 7: Feel Empowered to Act (Could-Have)
**As a** bystander,  
**I want** to feel encouraged and confident about reporting concerns,  
**So that** I don’t second-guess myself or stay silent.

**Acceptance Criteria:**
- Action section includes a positive, encouraging message.
- *Optional:* Include a real-life quote or testimonial about successful safeguarding intervention.

### Wireframes

This wireframe shows the **mobile layout** for the Safeguarding Awareness website. It includes:

- A fixed logo area at the top  
- Navigation buttons for key sections  
- A central hero image area  
- Space for content and imagery below

![Mobile Wireframe](assets/wireframes/{53535655-5B09-44A1-9528-988405F67227}.png)


### Typography

- **Headings**: Montserrat – for clarity and impact  
- **Body Text**: Roboto – for readability and accessibility

### Colour Scheme

| Element         | Colour   | Hex Code   |
|----------------|----------|------------|
| Primary Color   | Teal     | `#005A66`  |
| Accent Color    | White    | `#FFFFFF`  |
| Text Color      | Dark Gray| `#333333`  |
| Buttons         | Light Gray | `#f5f5f5`  |

> Screenshot of palette can be added here.

---

## Features

### Navigation

- A fixed navigation bar
- Four main links: What is Safeguarding?, Signs to Watch For, Action Steps, Contact
- Mobile responsive menu

### Footer

- Social media icons
- Legal disclaimer or safeguarding hotline (optional)
- Copyright notice

### Home Page

- Hero section with motivational headline:  
  _"Everyone should always have the right to be safe"_
- Supporting text and "Learn More" CTA button
- Full-screen background image for emotional impact

### Other Features

- Scroll animations
- Clickable anchor links for quick access
- External resource links
- Responsive design across all devices

---

## Technologies Used

- HTML5  
- CSS3  
- Bootstrap 5  
- Google Fonts  
- Git & GitHub  
- Gitpod  
- Font Awesome

---

## Testing

### Google Lighthouse Performance

> Add screenshots of results (mobile & desktop)

### Browser Compatibility

Tested on:

- Chrome  
- Firefox  
- Safari  
- Edge  
- Mobile browsers (Samsung Internet, iOS Safari)

### Responsiveness

Screenshots taken for:

- iPhone SE (320px)  
- iPad (768px)  
- Surface Laptop (1024px)  
- Desktop (1920px)

### Code Validation

- [W3C HTML Validator](https://validator.w3.org/)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

> Screenshots of validation results to be included

### Manual Testing

| User Story | Test Description | Pass |
|------------|------------------|------|
| US1        | Loads homepage on mobile | ✓ |
| US2        | All nav links scroll to correct section | ✓ |
| US3        | Contact form (if included) works | ✓ |

---

## Bugs

| Bug | Fix |
|-----|-----|
| Navigation menu not collapsing on mobile | Fixed with Bootstrap JS |
| Image not loading in hero | Corrected path and file name |
| Text overlap in smaller screens | Added media queries |

---

## Deployment

### GitHub Repository Creation

1. Forked Code Institute's template  
2. Created a new repository from template  
3. Opened project in Gitpod  
4. Pushed code regularly with meaningful commits

### GitHub Pages Deployment

1. Navigate to your repository  
2. Go to **Settings > Pages**  
3. Select `main` branch as source  
4. Click **Save**  
5. Your site will be published at:  
   `https://yourusername.github.io/safeguarding-project/`

---

## Credits

### Code & Text Content

- Definitions from NSPCC & Gov.uk  
- Code snippets referenced from MDN Web Docs  
- Structure inspired by Bootstrap examples

### Media

- Hero image from [Unsplash](https://unsplash.com)  
- Icons from [Font Awesome](https://fontawesome.com)

### Acknowledgments

- Code Institute for template  
- Mentors and classmates for feedback  
- Online communities like Stack Overflow