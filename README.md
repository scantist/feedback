Last Updated: 6th April, 2018

# Feedback
A place to submit issues/bugs and feature requests for Scantist's tools and services.

# Overview
The Scantist SCA is source-code analysis tool for C/C++ that identifies vulnerabilities and compliance issues pertaining to the use of open-source components in your projects and applications.
•	Vulnerabilities – The tool looks for known vulnerabilities (CVEs) and developer-patched security fixes (Security Bugs), as well as partial-matches for the two (Vulnerable Clones). The tools also offers potential code-fixes for the same.
•	Licenses – The tool also looks for open-source libraries used in your project, and alerts you if there exist any potential license compliance issues i.e. if any of the open-source components are licensed in a way that disallows your use-case (distribution, liability etc) the tool will notify you of the same.

# User Guide

Step 1. Navigate to https://scantist.io
Step 2. Login using a Github account set-up for you.
Step 3. Once you log in, the application dashboard will be presented to you.
Step 4. To scan a project, you must add it first. Click on the ‘Projects’ tab on the left-sidebar menu.
Step 5. Click the green ‘Manage’ button next to the ‘Projects’ header on the mid-left of the screen.
Step 6. The list of available projects in the test Github account will now be shown. Click on the ‘Add’ button pertaining to the projects that you wish to scan – a pop-up will confirm the addition.
Step 7. Once the project is added, and you’ll be redirected back to the ‘Projects’ view. You can view the ‘Project Details’ by clicking on the project name from this view at any time. Also, at the ‘Project Details’ page you may set scan settings and policy for event-driven integrations and licensing conflicts.
Step 8a. To manually the scan, click the ‘Actions’ button at the right-end of the row containing the added project. From the drop-down menu that appears, click ‘Scan’.
Step 8b. To trigger scans every time a pull-request is made to your Github repository, go to the ‘Project Details’ and under the ‘Scan Settings’ turn on the Event-driven scan. 
Step 9. Once a scan has been initiated, the status of the project will now change to ‘Running’. Depending on the size of project, it can take about 10 minutes for the scan to finish.
Step 10. Click the ‘Vulnerabilities’ tab on the left-sidebar menu. You will now be presented with a ‘By Project’ and ‘By Issue’ overview of vulnerabilities found.
Step 11. To view the list of vulnerabilities detected in a project, click on the ‘View’ link at the right-end corner corresponding to the project you wish to view in the ‘By Project’ tab.
Step 12. You will now be shown a list of vulnerabilities found in the latest scan for the project, and some details regarding the same.
Step 13. To view details pertaining to a particular vulnerability found in the latest scan, click on the ‘View’ link corresponding to the vulnerability. The Issue details page will provide you more details, including the actual vulnerable code and patched code (if available).  
Step 14. To view potential licensing issues, click the ‘Licenses’ tab on the left-sidebar menu. You will now be presented with a ‘By Project’ and ‘By License’ overview.
Step 15. To view the list of library and corresponding licenses detected in a project, click on the ‘View’ link at the right-end corner corresponding to the project you wish to view in the ‘By Project’ tab.
Step 16. You will now be shown a list of libraries and their licenses found in the latest scan for the project, and some details regarding the same.

