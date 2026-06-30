   # JUGGERNUT
   ## Big, Bold and Industry-Dominating
   * To become an unstoppable force of innovation that redefines the boundaries of our industry. Through relentless grit and groundbreaking solutions, we will empower businesses worldwide to crush their obstacles and achieve monumental growth. 

### The Executives
* **Princess Imelda Odato** - Chief Executive Officer
* **Peter  Wachira** - Vice Chair
* **Ryan Matu** - Chief Financial Officer
* **Samuel Kahiga** - Head of Operations
* **Mutunga Eric Musyimi** - Chief Technology Officer

---

## PHASE 2: THE "ABOUT ME" CODEBASE (index.html)

### Student 1 (The Architect)
1. Run: git pull origin main
2. Create a brand new file in VS Code named: index.html
3. Paste this exact structural HTML layout into the file:

<!DOCTYPE html>
<html>
<head>
    <title>Executive Team Profiles</title>
</head>
<body>
    <h1>Corporate Executive Directory</h1>
    <p>Meet the engineering minds driving our technical operations.</p>

    <!-- TEAM PROFILES GO BELOW THIS LINE -->

</body>
</html>

4. Save the file and push it up to the cloud:
   git add .
   git commit -m "feat: scaffold executive directory layout"
   git push origin main

### Students 2, 3, 4, & 5 (The Engineering Leads)
Execute this sequentially, one-by-one:
1. Run: git pull origin main
2. Open index.html. Find the <!-- TEAM PROFILES GO BELOW THIS LINE --> comment.
3. Paste your custom executive profile block directly underneath it using this exact structure:

<section style="margin-bottom: 20px; border-bottom: 1px solid #ccc; padding-bottom: 10px;">
    <h3>[Your Full Name]</h3>
    <p><strong>Professional Bio:</strong> [Write 1-2 sentences about your background and engineering mindset]</p>
    <p><strong>Core Tech Stack:</strong> [List 3-4 languages/frameworks you use, e.g., Python, Docker, PostgreSQL]</p>
    <p><strong>Key Project Focus:</strong> [Name 1 engineering objective or system you are responsible for optimizing]</p>
</section>

4. CRITICAL CHECK: Ensure all your HTML tags (<h3>, <p>, <section>) are closed correctly so you do not break your teammates' layouts.
5. Stage, commit, and deploy your profile live:
   git add .
   git commit -m "feat: integrate [Your Name] professional profile"
   git push origin main
