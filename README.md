Quick Meme Generator
A simple, lightweight meme generator that lets you create custom memes in seconds. No server-side processing required!
Features

8 popular meme templates included
Add custom top and bottom text
Download your memes as PNG images
Responsive design (works on mobile devices)
No dependencies except for html2canvas for image export

Demo
Try it live on Replit: Quick Meme Generator
How to Deploy on Replit

Create a GitHub repository:

Create a new repository on GitHub
Upload the HTML file as index.html
Add this README.md file


Deploy on Replit:

Go to Replit
Create a new Repl and select "Import from GitHub"
Paste your GitHub repository URL
Select the "HTML, CSS, JS" template
Click "Import from GitHub"
Press the "Run" button



Customization
Adding More Templates
To add more meme templates, edit the <select> element in the HTML:
html<select id="template" onchange="updateTemplate()">
    <option value="https://i.imgflip.com/4/1bij.jpg">One Does Not Simply</option>
    <!-- Add more templates here -->
</select>
Styling
The application uses simple CSS for styling. You can customize the appearance by modifying the CSS in the <style> section.
License
MIT License - feel free to use, modify, and distribute as you wish!
Credits

Meme templates sourced from imgflip.com
html2canvas library for image export functionality