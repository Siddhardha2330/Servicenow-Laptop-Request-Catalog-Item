💻 ServiceNow Project – Laptop Request Catalog
🚀 Project Overview

The Laptop Request Catalog Item is built in ServiceNow to make laptop requests fast, simple, and automated.

Traditionally, employees raise laptop requests through emails or manual processes — which often leads to delays, missing details, and inefficiencies.
This project changes that by providing a smart Service Catalog item where employees can quickly submit requests.

The form is dynamic, interactive, and rule-driven with UI Policies and includes a handy reset button to start fresh anytime.

🔑 Key Highlights
📂 Catalog Item – Laptop Request

Listed under Hardware in the Service Catalog.

Easy-to-use structured request form.

🎛️ Dynamic Form Variables

Laptop Model – Single line text field.

Justification – Multi-line text input for reason.

Additional Accessories – Checkbox option.

Accessories Details – Auto-appears and becomes mandatory if accessories are selected.

🛠️ UI Policies & Actions

Show/hide related fields automatically.

Enforce mandatory inputs when required.

🔄 UI Action – Reset Button

One-click option to clear all fields instantly.

Saves time by avoiding page refresh.

📦 Update Set

Exported as XML Update Set for smooth migration across ServiceNow instances.

⚙️ Setup Guide
Step 1: Import Update Set

Navigate to All → Update Sets → Retrieved Update Sets.

Click Import Update Set from XML.

Upload Laptop_Request_UpdateSet.xml.

Preview → Commit.

Step 2: Access the Catalog Item

Go to Service Catalog → Hardware → Laptop Request.

Fill in required details (model, justification, accessories).

Step 3: Test Functionality

Selecting Additional Accessories will display and mandate the Accessories Details field.

Hit Reset Form to clear everything in one go.

📁 Repository Layout

Documentation/ → Step-by-step project guide with screenshots.

UpdateSets/ → Ready-to-import XML file.

README.md → Project summary and usage.

📘 Documentation Includes

Full build guide from scratch.

Screenshots for each configuration.

Clear explanations of variables, UI Policies, and UI Actions.

Deployment steps using Update Sets.

🌟 Why This Project Matters

✔ Speeds up the request process – no more waiting for manual approvals.
✔ Eliminates errors – form rules ensure only valid details are submitted.
✔ Reusable across instances – plug-and-play with Update Sets.
✔ User-friendly – simple design + reset option = smooth experience.

🏆 Conclusion

The Laptop Request Catalog Item is a real-world ServiceNow use case that converts a routine IT request into a fast, structured, and automated workflow.

With this, organizations can:

Improve IT service delivery.

Save time and reduce errors.

Make the employee experience smoother and faster.

This project reflects my ServiceNow learning journey and shows how simple catalog items can create big impacts in daily IT operations.
