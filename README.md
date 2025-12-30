# Student Portfolio Template

A responsive personal portfolio website template built with HTML, CSS, and vanilla JavaScript. This template showcases a clean, modern design perfect for students and professionals to display their skills, projects, and contact information.

## 🌟 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional layout with smooth transitions
- **Sticky Navigation**: Easy navigation between pages that stays visible while scrolling
- **Project Showcase**: Grid layout to display projects with technology tags
- **Contact Form**: Functional contact form with validation
- **API Integration**: Dynamic profile image from Random User API
- **Cross-browser Compatible**: Works on Safari, Chrome, Firefox, and Edge

## 📁 Project Structure

```
student_portfolio_template/
├── index.html          # Home page with welcome message
├── resume.html         # Resume page with profile, education, skills, experience
├── projects.html       # Projects showcase page
├── contact.html        # Contact information and form
└── README.md          # Project documentation
```

## 🚀 How to Run

### Option 1: Direct File Opening
1. Clone or download this repository
2. Open any HTML file in your web browser
3. Navigate between pages using the top navigation menu

### Option 2: Local Web Server (Recommended)
For better development experience and to avoid CORS issues:

**Using Python (if installed):**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -S SimpleHTTPServer 8000
```

**Using Node.js (if installed):**
```bash
# Install a simple server globally
npm install -g http-server

# Run the server
http-server
```

**Using PHP (if installed):**
```bash
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

### Option 3: Live Server Extension (VS Code)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 🎨 Customization

### Personal Information
- Update name, age, address, and course in `resume.html`
- Modify contact details in `contact.html`
- Change the profile image by updating the API URL in `resume.html`

### Styling
- All styles are embedded in each HTML file's `<style>` section
- Color scheme uses CSS custom properties for easy theming
- Font family: System fonts for optimal performance and compatibility

### Content
- Add your real projects in `projects.html`
- Update skills and experience in `resume.html`
- Customize the welcome message in `index.html`

## 🔗 API Used

- **Random User API**: `https://randomuser.me/api/portraits/men/32.jpg`
  - Provides realistic profile images
  - Change the number (32) for different faces
  - Switch `/men/` to `/women/` for different options

## 🌐 Deployment

### GitHub Pages (Free)
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" → main branch
4. Your site will be live at: `https://yourusername.github.io/repository-name/`

### Other Options
- **Netlify**: Drag and drop your folder to netlify.com
- **Vercel**: Connect your GitHub repository
- **Firebase Hosting**: Use Firebase CLI to deploy

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Safari (latest)
- ✅ Firefox (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Flexbox, Grid, transitions, and responsive design
- **JavaScript**: Basic form validation (can be extended)
- **External APIs**: Random User API for profile images

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📧 Contact

For questions or suggestions, feel free to reach out:

- **Email**: johnmark.gabrentina@sorsu.edu.ph
- **GitHub**: [@johnmark14](https://github.com/johnmark14)

---

**Built with ❤️ for students and professionals looking to showcase their work online.**