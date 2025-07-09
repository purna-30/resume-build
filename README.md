# 💼 Digital Resume Builder

The **Digital Resume Builder** is a responsive and interactive web application that allows users to create a professional resume with ease. Users can input their details, preview the resume in real time, and download it as a PDF—all from the browser without any backend.

---

## 📌 How to Use

1. **Open** `main.html` in your preferred browser.

2. **Fill in** the form with your:

   - **Personal Information** (Name, Email, Phone, Address)
   - **Professional Summary**
   - **Education Details** (Add multiple entries if needed)
   - **Work Experience** (Add multiple entries if needed)
   - **Skills** (comma-separated)

3. **Live preview** updates automatically as you type.

4. Click **“Download Resume as PDF”** to generate and save your resume.

---

## 🧰 Technologies Used

- **HTML5**
- **CSS3** (Grid & Flexbox for responsive layout)
- **JavaScript** (Vanilla ES6)
- **[jsPDF](https://github.com/parallax/jsPDF)** (for PDF export)

---

## 📦 CDN Resources

The project uses the following CDN:

- [jsPDF v2.5.1](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js)

---

## 📱 Responsive Design

The layout is optimized for both desktop and mobile screens:

- **Desktop**: Two-column layout – form on the left, live preview on the right.
- **Mobile**: Stacked layout – form and preview appear one below the other.

Built with responsive CSS Grid and media queries.

---

## 🛠️ Customization

You can easily tailor the app to your needs:

- **Change Styles**: Edit the `<style>` block inside `main.html` for colors, fonts, spacing, etc.
- **Add More Sections**: Duplicate and modify the dynamic sections (`Education`, `Experience`) to include:
  - Certifications
  - Awards
  - Projects
- **Modify PDF Output**: Edit the `exportToPDF()` JavaScript function to rearrange or format PDF elements.

---

## ❗ Form Validation

The application validates the following fields:

- **Full Name** (Required)
- **Email** (Valid format)
- **Phone Number** (Valid format)

If any of the required fields are missing or invalid, they are highlighted with red borders and corresponding error messages.

---

## 📤 Export to PDF

- PDF is generated using `jsPDF`.
- Includes all entered sections and formats them cleanly.
- The PDF includes:
  - Header with name and contact info
  - Professional summary
  - Education
  - Work experience
  - Skills
- Automatically named as: `Your_Name_Resume.pdf`

---

## 📄 License

This project is licensed under the **MIT License**.  
Feel free to modify, distribute, and use for personal or commercial purposes.

---

## 🙋‍♂️ Author

Developed by V.Purna sri.  
You’re welcome to contribute or suggest improvements.


