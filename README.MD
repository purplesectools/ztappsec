Zero Trust Enabled AppSec Maturity Assessment
This is a self-contained, single-file web application for assessing an organization's application security (AppSec) maturity. The assessment is unique because it integrates two leading security frameworks: the OWASP Software Assurance Maturity Model (SAMM) v2.1 and the NIST Special Publication (SP) 800-207 Zero Trust Architecture.

The tool is designed to be highly portable and requires no server-side components. It is accessible directly via the following URL:

➡️ http://ztappsec.aimlthreats.com/

Features
Dual-Framework Alignment: The assessment questions are mapped to both OWASP SAMM practices (e.g., Governance, Design, Implementation) and key NIST Zero Trust tenets (e.g., Identity, Data, Workloads).

Intuitive Interface: A clean, user-friendly interface powered by React and Tailwind CSS makes it easy to navigate the assessment.

Actionable Reporting: After completing the questionnaire, the tool generates a comprehensive, visual report including:

An overall AppSec maturity score.

A weighted scoring model that respects SAMM category and practice importance.

An evidence-confidence score that highlights how much of the assessment is based on known answers versus "I Don't Know" responses.

Radar and bar charts to visualize maturity across SAMM categories and practices.

A breakdown of maturity by each NIST Zero Trust tenant.

A SAMM-to-NIST mapping matrix to show where maturity is strong or weak across both frameworks.

A prioritized list of recommendations based on your responses to help you build a practical roadmap for improvement.

Portable and Self-Sufficient: The entire application is contained within a single HTML file.

PDF Report Generation: You can easily download the generated report as a PDF for sharing with stakeholders.

How to Use
Access: Open the assessment tool directly by visiting http://ztappsec.aimlthreats.com/.

Assess: Answer each question based on your organization's current AppSec practices. You can select from Yes, Partial, Planned, or No.

Report: Once all questions are answered, click the "Generate Executive Report" button to view your results.

Share: Use the "Download PDF" button in the report view to save a copy of your assessment.

Frameworks & Technologies
Assessment Frameworks:

OWASP SAMM v2.1

NIST SP 800-207 Zero Trust Architecture

Core Technologies:

React: For building the dynamic user interface.

Babel Standalone: To compile the JSX/ES6 React code in the browser.

Tailwind CSS: For rapid, utility-first styling.

Chart.js: For generating the visual maturity charts.

html2canvas & jsPDF: For capturing the report and generating the downloadable PDF.

Contributions
This is an open-source tool. We welcome contributions to improve the assessment questions, reporting, or overall functionality. Please feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.
