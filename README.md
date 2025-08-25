# Topic 1: Pactise - Git Workflow Assignment: Contact Us Page

## 🎯 Task Overview
Add a "Contact Us" page to this company website following proper Git workflows.

#### 1. Clone the Repository
```bash
git clone https://github.com/Hacking-the-Heck/hacking-cicd-tasks.git
cd Topic_1
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
git commit -m "feature: add contact us page with form and company info"

# Push feature branch
git push origin feature/contact-us-page

# Create pull request via GitHub web interface
```

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
