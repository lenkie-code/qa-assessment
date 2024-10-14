
At Lenkie, we prioritize seamless experiences for both brokers and the customers they refer. As part of the Lenkie team, the Broker Portal is a critical tool, allowing brokers to manage referrals, agreements, and interactions with ease. We are currently looking for a QA engineer to help us uphold the quality and functionality of this portal as it continues to evolve.

In this practical assessment, you will focus on manual testing of the Lenkie Broker Portal, which includes features such as broker account creation, broker agreement signing, and customer referrals. The goal is to see how well you can test core features, document issues, and propose improvements.

We are specifically looking for a candidate who:

- Documents processes and findings in a clear and detailed manner.
- Performs thorough and systematic manual testing across different scenarios.
- Can formulate a comprehensive test plan for an existing product.

Assessment Instructions:

You have been given User Acceptance Testing (UAT) access to the Lenkie Broker Portal. Your task is to perform a set of manual tests based on the features listed below. For each section, document your test cases, results, and any issues you encounter. Afterward, you will create a test plan and bug reports based on your findings.

Section 1: Scenario-Based Practical Tasks

Task 1: Broker Account Creation

- Context: Brokers start by creating their accounts, selecting an authorized signatory, and submitting the necessary details to receive a broker agreement. This step must be completed before they can refer customers
Instructions:

- Test the account creation flow, focusing on both valid and invalid inputs
- Validate form submissions and handle error scenarios (e.g., invalid email format).
- Document your test cases and findings.

Tip: When specifying the email address of the signatory, use an email address that belongs to you to for contract signing later.

Question: How would you approach testing the broker account creation process to ensure no errors or missing details go unnoticed?

Task 2: Broker Agreement Signing

- Context: After creating a broker account, the system sends an agreement to the authorized signatory for signing. Once the contract is signed, brokers can refer customers.
Instructions:

- Test the flow of sending the broker agreement and receiving it via email.
- Test what happens in both successful and error scenarios (e.g., failure to receive the email, issues with signing).
- Document the steps to reproduce any errors and your findings.

Question: What kind of scenarios would you test when handling the signing and submission of a broker agreement to ensure smooth functionality?

Task 3: Customer Referrals

- Context: Once a broker account is set up and the agreement is signed, brokers can submit customer referrals. This involves providing customer information, funding details, and uploading required documents.
Instructions:

- Test the customer referral form, validating both correct and incorrect data entries.
- Check that document uploads (e.g., management accounts) work as expected, including handling different file types and sizes.
- Document test cases and any issues you find.

Question: How would you test the customer referral process to ensure that all data is correctly handled and that files are uploaded without issues?

Section 2: Test Plan Formulation

After completing the practical tasks, formulate a comprehensive test plan for the Lenkie Broker Portal. Your test plan should cover the following:

- Scope: Outline the areas of the portal to be tested.
- Test Strategy: Specify types of tests (e.g., functional, regression, UAT).
- Test Case Design: How would you prioritize test cases?
- Tools: Mention any tools or methods you would use to track and manage test cases.

Question: How would you go about designing a test plan for the Broker Portal, and what would be your top priorities when ensuring test coverage?

Section 3: Bug Reporting Exercise

Based on the practical tasks, identify and report at least 3 bugs. Use a structured bug reporting template that includes:

- Steps to reproduce the issue.
- Expected vs. actual behavior.
- Supporting evidence (e.g., screenshots or logs).

Question: How do you ensure that your bug reports are clear, reproducible, and actionable for developers?
