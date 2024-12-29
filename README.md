Step by Ste Guide to pulish Github page or static website to showcase your profile.

# How to Create and Publish a Resume on GitHub Pages

This comprehensive guide walks you through publishing a professional resume as a static website using GitHub Pages. Whether you're showcasing your skills, sharing your experience, or creating a personal brand, this step-by-step tutorial will help you get started.

---

## **Introduction**
GitHub Pages is a free hosting service provided by GitHub for static websites. By following this guide, you’ll:
- Host a professional resume online.
- Use GitHub Pages for free, without any coding knowledge.
- Get a personal URL (e.g., `https://<your-username>.github.io`) to share your resume.

---

## **Prerequisites**
1. A GitHub account. Sign up at [github.com](https://github.com) if you don't have one.
2. Your resume content ready (in text, Markdown, or HTML format).

---

## **Steps to Publish Your Resume**

### **Step 1: Create a New GitHub Repository**
1. Log in to your GitHub account.
2. Click the **+** icon at the top-right corner and select **New Repository**.
3. Name the repository `<your-username>.github.io` (replace `<your-username>` with your actual GitHub username).
4. Set the repository to **Public** and add a description if you want (optional).
5. Click **Create Repository**.

---

### **Step 2: Prepare Your Resume HTML File**
- If you have a resume in Word or PDF format, convert it to HTML.
- Alternatively, you can use the sample HTML template provided below.
- Save the file as `index.html`.

---

### **Step 3: Upload Your HTML File**
1. Navigate to your new repository.
2. Click **Add File > Upload Files**.
3. Drag and drop your `index.html` file or use the file picker.
4. Commit the changes with a meaningful message, like "Added resume file."

---

### **Step 4: Enable GitHub Pages**
1. Go to the repository’s **Settings**.
2. Scroll down to the **Pages** section.
3. Under **Source**, select `main` (or your default branch) as the source branch.
4. Click **Save**.
5. Your resume will be live at `https://<your-username>.github.io` within a few minutes.

---

## **HTML Template Example**
Here’s a sample HTML template to use for your resume:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume - Your Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
        }
        header {
            text-align: center;
            background: #333;
            color: white;
            padding: 20px;
        }
        section {
            margin: 20px auto;
            max-width: 800px;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
        }
        h2 {
            color: #333;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Job Title | Location</p>
    </header>
    <section>
        <h2>Professional Summary</h2>
        <p>Write a short summary of your skills and achievements here.</p>
    </section>
    <section>
        <h2>Experience</h2>
        <ul>
            <li>Job 1: Details about your role and accomplishments.</li>
            <li>Job 2: Details about your role and accomplishments.</li>
        </ul>
    </section>
    <footer>
        <p>Connect with me: <a href="#">LinkedIn</a> | <a href="#">GitHub</a></p>
    </footer>
</body>
</html>



### **Tips for Customization**
Add Images: Use <img> tags to include your profile picture or company logos.
Use External Styles: Link a CSS file for more design flexibility.
Integrate Analytics: Add Google Analytics for visitor tracking.


### **Common Issues and Troubleshooting**
Website Not Loading: Ensure you’ve enabled GitHub Pages in the repository settings.
Incorrect URL: The repository must be named <your-username>.github.io to work.
HTML Errors: Validate your HTML file for syntax issues using tools like W3C Validator.

### **Final Thoughts**
Congratulations! Your resume is now live on GitHub Pages. Share the link with potential employers or include it in your LinkedIn profile.
Regularly update your repository to keep your resume current.
