Google Forms Invoice Automation

Automate invoice generation using Google Forms, Google Docs, and Google Apps Script.
This project lets you submit a form, automatically generate a professional invoice PDF, and email it directly to the client.

Features:

Google Form to collect client and service details

Google Docs template for professional invoice layout

Auto-generated PDF invoice

Sends invoice via Gmail automatically

Works for freelancers, students, and small businesses

Project Structure:
Google-Forms-Invoice-Automation/

docs/ → contains proof and sample outputs

sample-invoice.pdf (example invoice)

form-screenshot.png (Google Form screenshot)

template-screenshot.png (Docs invoice template)

email-screenshot.png (Email sent via Gmail)

src/ → contains source code

invoice-automation.gs (Google Apps Script code)

README.md → documentation

LICENSE → MIT license

Setup Instructions:

Copy the Google Form. Create a new Google Form for invoice inputs (Client Name, Email, Service, Hours, Unit Price, Notes).

Create a Docs Template. In Google Docs, design your invoice template using placeholders like {{CLIENT_NAME}}, {{SERVICE}}, {{TOTAL}}.

Add Apps Script. Go to Google Form → Responses → Open in Sheet → Extensions → Apps Script. Copy the code from /src/invoice-automation.gs into the script editor.

Adjust Template ID. Update the TEMPLATE_ID and FOLDER_ID inside the script with your own Docs and Drive IDs.

Set Up Trigger. Go to Script Editor → Triggers → add onFormSubmit trigger, event source “From spreadsheet”.

Test. Fill out the form. A PDF invoice will be generated and emailed to the client.

Screenshots:
The /docs folder includes:

Google Form interface

Invoice template

Sample invoice PDF

Gmail email output

Why This Project?
Freelancers and small businesses often waste time creating invoices manually. This tool automates the entire process, saving time and ensuring professional, consistent invoices.

License:
This project is licensed under the MIT License.

Author:
Mahad A
Helping businesses automate operations and build data-driven solutions.
