# Day_21_Mail_Merge_Project
<html>
<body>
  <h1>Mail Merge Project</h1>
  <h2>Overview</h2>
  <p>The Mail Merge Project is a Python-based program that automates the process of sending personalized emails to a list of recipients. The program uses a CSV (Comma Separated Values) file as input, which contains the recipient's information, and a template email that is customized for each recipient.</p>
  <h2>Prerequisites</h2>
  <ul>
    <li>Python 3.x installed on your system</li>
    <li>Basic understanding of Python programming language</li>
    <li>CSV file containing recipient information</li>
    <li>Template email in HTML format</li>
  </ul>
  <h2>Installation</h2>
  <p>1. Clone the Mail Merge Project repository from GitHub:</p>
  <code>git clone https://github.com/imbhav01/Day_21_Mail_Merge_Project.git</code>
  <p>2. Change to the project directory:</p>
  <code>cd mail-merge-project</code>
  <p>3. Install the required dependencies:</p>
  <code>pip install pandas</code>
  <p>4. Open the project in your preferred Python development environment.</p>
  <h2>Usage</h2>
  <p>1. Prepare your CSV file containing the recipient information. The CSV file should have column headers that correspond to the fields in the template email (e.g., name, email, etc.).</p>
  <p>2. Customize the template email in HTML format, including the placeholders for the recipient information (e.g., {{name}}, {{email}}, etc.).</p>
  <p>3. In your Python code, import the MailMerge class from the mail_merge module:</p>
  <code>from mail_merge import MailMerge</code>
  <p>4. Create an instance of the MailMerge class and provide the path to the CSV file and the template email file:</p>
  <code>mail_merge = MailMerge('recipients.csv', 'template.html')</code>
  <p>5. Use the <code>merge</code> method to perform the mail merge:</p>
  <code>mail_merge.merge()</code>
  <p>6. The program will generate individual email files for each recipient, with the placeholders replaced by the actual recipient information.</p>
  <p>7. You can then use your preferred method to send the emails, such as through a mail client or a third-party service.</p>
  <h2>Contributing</h2>
  <p>If you would like to contribute to the Mail Merge Project, please fork the repository on GitHub, create a new branch for your changes, and submit a pull request.</p>
  <h2>License</h2>
  <p>The Mail Merge Project is released under the MIT License. See the <code>LICENSE</code> file for more details.</p>
  <h2>Contact</h2>
  <p>If you have any questions or feedback, please contact us at <code>bhaveshab01@gmail.com</code>.</p>
</body>
</html>
