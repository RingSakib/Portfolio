# Portfolio

### **HTML File (`index.html`)**
1. **Basic Structure**:
   - The HTML file is structured with a `DOCTYPE` declaration, `<html>`, `<head>`, and `<body>` tags.
   - It includes metadata for character encoding, viewport settings, and a title.

2. **Favicon and External Resources**:
   - A favicon is linked using `<link rel="shortcut icon">`.
   - External resources like Google Fonts (Poppins, Roboto, Saira Stencil One) and Ion Icons are included.

3. **Header**:
   - A fixed header with a logo, theme toggle button, and navigation menu.
   - The navigation menu includes links to different sections of the page: Home, About, Skills, Portfolio, and Contact.

4. **Hero Section**:
   - A hero section with a banner image, name, and a call-to-action button ("Get in touch").
   - Social media links (Facebook, GitHub, LinkedIn) are displayed with tooltips.

5. **Stats Section**:
   - Displays statistics like years of experience, completed projects, and happy clients.

6. **About Section**:
   - A brief introduction about MD. Mehedi Islam Sakib, his passion for web development, and his collaborative approach.
   - Buttons to hire him or download his CV.

7. **Skills Section**:
   - A toggle between **Skills** and **Tools**.
   - Skills include HTML5, CSS3, JavaScript, TypeScript, C++, Java, and Python.
   - Tools include Webpack, Git, Command Line, VS Code, and Photoshop.

8. **Education Section**:
   - Displays education details with a parallax background effect.
   - Includes information about **American International University-Bangladesh** and **Cumilla Residential School and College**.

9. **Certifications Section**:
   - Lists certifications like **Introduction to Cybersecurity** and **IT Essentials** from Cisco Networking Academy.

10. **Projects Section**:
    - Displays a list of projects with images, titles, and dates.
    - Projects include **AIUB Blood Donation Club**, **Hospital Management**, **Need A Shop**, and more.

11. **Contact Section**:
    - A contact form with fields for name, email, phone, and message.
    - Contact information (address, phone, email) and social media links are also provided.

12. **Footer**:
    - A footer with the logo and copyright information.

13. **JavaScript Integration**:
    - The file includes links to external JavaScript files (Ion Icons and a custom `script.js`).

---

### **CSS File (`style.css`)**
1. **Variables and Theme**:
   - CSS variables are defined for colors, typography, transitions, spacing, and radius.
   - Dark and light themes are implemented using `body.dark_theme` and `body.light_theme`.

2. **Reset and Reusable Styles**:
   - A reset is applied to remove default margins, paddings, and styles.
   - Reusable styles for buttons, headings, and sections are defined.

3. **Header**:
   - The header is fixed at the top and becomes sticky on scroll.
   - A theme toggle button switches between dark and light themes.

4. **Hero Section**:
   - The hero section is centered with a banner image and social media links.
   - A scroll-down indicator is included.

5. **Stats Section**:
   - Stats cards are displayed in a grid layout with hover effects.

6. **About Section**:
   - The about section includes a banner image and content with buttons.

7. **Skills Section**:
   - Skills and tools are displayed in a toggleable layout with tooltips.

8. **Projects Section**:
   - Projects are displayed in a grid layout with hover effects and animations.

9. **Contact Section**:
   - A contact form with input fields and social media links.

10. **Footer**:
    - The footer is styled with a centered layout.

11. **Responsive Design**:
    - Media queries are used to adjust the layout for different screen sizes (550px, 768px, 992px, 1200px).

---

### **JavaScript File (`script.js`)**
1. **Element Toggle Function**:
   - A reusable function `elemToggleFunc` toggles the `active` class on elements.

2. **Header Sticky and Go-to-Top Button**:
   - The header becomes sticky on scroll, and a "go to top" button appears.

3. **Navbar Toggle**:
   - A toggle button shows/hides the navigation menu on mobile devices.

4. **Skills Toggle**:
   - Toggles between **Skills** and **Tools** sections.

5. **Theme Toggle**:
   - Switches between dark and light themes and saves the preference in `localStorage`.

---

### **Key Features**:
- **Responsive Design**: The website is fully responsive, adapting to different screen sizes.
- **Dark/Light Theme**: Users can switch between dark and light themes.
- **Interactive Elements**: Tooltips, hover effects, and animations enhance user experience.
- **Dynamic Content**: Projects, skills, and certifications are dynamically displayed.
- **Contact Form**: A working contact form is integrated using Web3Forms.
