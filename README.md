ServiceNow Project – Laptop Request Catalog Item
Project Overview

This project focuses on building a Laptop Request Catalog Item in ServiceNow to streamline the process of requesting laptops within an organization.

In most companies, laptop requests are usually managed through emails or manual approvals, which often cause delays, incomplete information, and inefficiencies.

By using the Service Catalog in ServiceNow, we provide employees with a simple, structured, and interactive request form. The form dynamically responds to user inputs, applies rules using UI Policies, and even offers a reset option for better usability.

Key Features
Catalog Item – Laptop Request

Available under the Hardware category of the Service Catalog.

Gives employees an easy-to-fill request form for laptops.

Dynamic Variables

Laptop Model – Single line text input.

Justification – Multi-line input for providing reasons.

Additional Accessories – Checkbox option.

Accessories Details – Displays and becomes mandatory when accessories are selected.

UI Policy & UI Policy Actions

Automatically shows or hides related fields.

Ensures required fields are completed when applicable.

UI Action (Reset Button)

Provides a reset button to clear all inputs.

Saves time by allowing users to restart without refreshing the page.

Update Set

Project is exported as an XML Update Set for easy migration across ServiceNow instances.

Setup & Usage
1. Import the Update Set

Navigate to All → Update Sets → Retrieved Update Sets.

Select Import Update Set from XML.

Upload Laptop_Request_UpdateSet.xml.

Preview and commit the update set.

2. Access the Catalog Item

Go to Service Catalog → Hardware.

Select Laptop Request.

Enter details such as model, justification, and accessories.

3. Test the Functionality

When Additional Accessories is checked, the Accessories Details field appears and becomes required.

Use the Reset Form button to instantly clear all fields.

Repository Structure

Documentation/ → Contains Word documents with step-by-step instructions.

UpdateSets/ → XML files of the catalog item for deployment.

README.md → Introduction and usage guide.

Documentation

The Documentation folder includes:

Stepwise instructions for building the catalog item.

Screenshots of every setup step.

Explanations of variables, UI Policies, and UI Actions.

Guide for deploying via Update Sets.

This ensures anyone can replicate the project or understand its configuration.

Benefits of This Project

Faster requests – eliminates manual follow-ups.

Reduced errors – form logic ensures complete and relevant data.

Reusable – can be exported and reused across environments.

Better user experience – reset functionality and guided form improve usability.

Conclusion

The Laptop Request Catalog Item demonstrates how ServiceNow Service Catalog can transform everyday IT requests into automated, efficient workflows.

By implementing this project, organizations can:

Speed up IT service delivery.

Improve employee satisfaction.

Save time and avoid manual mistakes.

This project reflects my learning and hands-on practice with ServiceNow, showing how real-world problems can be simplified with effective Service Catalog solutions.
