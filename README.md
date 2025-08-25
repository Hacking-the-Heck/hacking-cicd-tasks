# TechFlow Solutions - Company Website

A modern, responsive company website built with HTML, CSS, and JavaScript. This project is designed for students to practice Git workflows and collaborative development.

## 🚀 Project Structure

```
company-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 📋 Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Navigation**: Mobile-friendly hamburger menu
- **Smooth Scrolling**: Enhanced user experience
- **Professional Sections**: Home, About, Services, Team sections

## 🎯 Student Assignment: Contact Us Page

### Task Overview
Students will add a "Contact Us" page to this website following proper Git workflows.

### Assignment Steps

#### 1. Clone the Repository
```bash
git clone [YOUR_REPO_URL]
cd company-website
```

#### 2. Configure Git
```bash
git config user.name "Your Name"
git config user.email "your.email@example.com"
```

#### 3. Create Feature Branch
```bash
git checkout -b feature/contact-us-page
```

#### 4. What to Implement

Students should create a **contact.html** file with the following features:
- Contact form with fields: Name, Email, Subject, Message
- Company contact information (address, phone, email)
- Embedded map (can use placeholder or Google Maps iframe)
- Same header/footer as main site for consistency

**Files to modify:**
- Create `contact.html`
- Update `index.html`: Add "Contact" link to navigation
- Update `styles.css`: Add styles for contact page
- Update `script.js`: Add form validation (optional)

#### 5. Example Contact Link Addition
In `index.html`, students should add this to the navigation:
```html
<li><a href="contact.html" class="nav-link">Contact</a></li>
```

#### 6. Git Workflow
```bash
# After making changes
git add .
git commit -m "feat: add contact us page with form and company info"

# Push feature branch
git push origin feature/contact-us-page

# Create pull request via GitHub web interface
```

## 🔧 Development Setup

1. **Clone the repository**
2. **Open `index.html`** in a web browser
3. **Use Live Server** (VS Code extension) for development
4. **Make changes** and test in browser

## 📝 Suggested Contact Page Content

### Contact Information
- **Address**: 123 Tech Street, Digital City, DC 12345
- **Phone**: (555) 123-TECH
- **Email**: hello@techflowsolutions.com
- **Business Hours**: Monday-Friday, 9AM-6PM EST

### Form Fields
- Name (required)
- Email (required)
- Subject (required)
- Message (required, textarea)
- Submit button

## 🎨 Design Guidelines

- **Colors**: Primary blue (#007bff), accent red (#ff6b6b)
- **Fonts**: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Spacing**: Consistent with existing design
- **Responsiveness**: Must work on mobile devices

## 📚 Learning Objectives

Students will practice:
- Git branching and merging
- HTML form creation
- CSS styling and layout
- JavaScript form validation
- Pull request workflow
- Code review process

## 🤝 Pull Request Guidelines

When creating a pull request, students should:
1. Use descriptive title: "feat: add contact us page"
2. Include description of changes made
3. Reference any issues if applicable
4. Ensure all files are properly formatted
5. Test the contact page on different screen sizes

## 🌟 Bonus Challenges

For advanced students:
- Add form validation with JavaScript
- Implement smooth animations on form focus
- Add a success message after form submission
- Create a confirmation page
- Add social media links
- Implement dark mode toggle

---

**Instructor Note**: This project provides a realistic codebase for students to practice Git workflows while building a practical web development skill.