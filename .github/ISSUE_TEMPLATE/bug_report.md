## Issue Name

### Instructions for Template Use:

- [ ] **Replace all example text** in the template with details of the issue you're reporting.
- [ ] **Provide as much detail as possible** to help the team diagnose the issue.
- [ ] **Screenshots and logs** can be very helpful if applicable.

### Description

<!-- REPLACE THIS TEXT WITH YOUR DESCRIPTION -->
[The "Export to PDF" functionality in the invoice section fails to generate a PDF file for invoices containing more than 100 items.]  

### Steps to Reproduce

<!-- REPLACE THIS EXAMPLE WITH THE STEPS TO REPRODUCE YOUR ISSUE -->
**1.** [Go to the "Invoices" section of the application.]  
**2.** [Open an invoice that contains more than 100 line items (e.g., an order with many products).]  
**3.** [Click the "Export to PDF" button.]

### Expected Behavior

<!-- REPLACE THIS EXAMPLE WITH WHAT YOU EXPECTED TO HAPPEN -->
[The system should generate a PDF file that contains all 100+ items and allow the user to download the file.]

### Actual Behavior

<!-- REPLACE THIS EXAMPLE WITH WHAT ACTUALLY HAPPENED -->
[The system shows a loading spinner for several seconds and then returns an error: "Failed to generate PDF." No PDF is created, and the invoice is not exported.]

### Screenshots

<!-- ADD SCREENSHOTS HERE, IF APPLICABLE, TO HELP EXPLAIN THE PROBLEM -->
[Include a screenshot showing an error message."
Example error: *"Failed to generate PDF. Please try again later."*]

### Environment

<!-- REPLACE THIS EXAMPLE WITH THE ENVIRONMENT DETAILS WHERE THE ISSUE OCCURRED -->
- **Operating System**: [macOS 11.6]  
- **Browser/Version**: [Firefox 92.0]  
- **Version**: [2.5.1]

### Additional Context

<!-- REPLACE THIS EXAMPLE WITH ANY ADDITIONAL CONTEXT THAT MAY BE RELEVANT TO THE ISSUE -->
[This issue only occurs when the invoice contains more than 100 items.]  

### Suggested Fix

<!-- REPLACE THIS EXAMPLE WITH YOUR SUGGESTION FOR FIXING THE ISSUE, IF APPLICABLE -->
[Investigate the PDF generation process for large invoices and optimize for handling larger datasets.]
