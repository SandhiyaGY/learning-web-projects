<!DOCTYPE html>
<html lang="en">
<body>
  <h1>Comprehensive Result Survey System</h1>

  <p>This project is a simple, user-friendly survey form designed to collect student information and feedback about their academic results and exam experience.</p>

  <h3>Overview</h3>
  <p>The survey form collects the following details from users:</p>
  <ul>
    <li>Name</li>
    <li>Email</li>
    <li>Register Number</li>
    <li>Department (CSC, IT, ECE, MECH, EEE)</li>
    <li>GPA</li>
    <li>Accommodation Type (Day-Scholar or Hosteller)</li>
    <li>Exam Feedback (multiple selectable options)</li>
    <li>Suggestions or comments</li>
  </ul>
  <p>The form is built with plain HTML and styled via an external CSS file (<code>style.css</code>). It includes form validation using HTML5 attributes and is ready for integration with backend services for data submission.</p>

  <h3>Features</h3>
  <ul>
    <li>Input validation for required fields like name, email, register number, and department</li>
    <li>User-friendly form with dropdowns, radio buttons, checkboxes, and text areas</li>
    <li>Accessible markup with labels linked to inputs</li>
    <li>External CSS for styling (not included here, you can customize)</li>
    <li>Favicon support for branding</li>
  </ul>

  <h3>File Structure</h3>
  <pre><code>
/result-survey-html-css
  ├── index.html          # Main survey form HTML file
  ├── style.css           # Stylesheet for the form (create this file)
  └── images/
        └── favicon.svg   # Favicon icon for browser tab
  </code></pre>

  <h3>Usage</h3>
  <ol>
    <li>Clone or download this repository.</li>
    <li>Open <code>index.html</code> in any modern web browser.</li>
    <li>Fill out the form fields and submit.</li>
    <li>Integrate the form with a backend or JavaScript to handle submissions and data storage as needed.</li>
  </ol>

  <h3>Customization</h3>
  <ul>
    <li>Modify <code>style.css</code> to change the appearance of the form.</li>
    <li>Extend the form with JavaScript to enhance validation, handle submissions asynchronously, or connect to APIs.</li>
    <li>Add server-side handling to process and store survey responses.</li>
  </ul>

  <h3>License</h3>
  <p>This project is open for personal and educational use. Feel free to adapt it for your own needs.</p>

  <hr />
  <p><em>If you want help creating CSS or JavaScript for this form, just ask!</em></p>

</body>
</html>
