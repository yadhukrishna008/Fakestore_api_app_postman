🛒 E-Commerce API Automation Suite
Tools: Postman, Newman, JavaScript, GitHub Actions

📌 Project Overview
Automated testing suite for an E-commerce platform (FakeStore API). This project validates critical user journeys including Authentication, Product Management, and Cart workflows.

🚀 Key Features
End-to-End Workflows: Covers the full lifecycle from Login to Checkout.
Data-Driven Testing: Uses environment variables to handle dynamic tokens and IDs.
Negative Testing: Robust assertions to handle 400/401 error codes and invalid data.
CI/CD Integration: Automated execution via GitHub Actions on every push.

🛠️ How to Run Locally
Install Newman: npm install -g newman
Run the tests:
Bash
newman run collection.json -e environment.json
