# Promotion Process

After validating your product layout, documentation, and APIs through Developer Studio on our QA environment you may create a Github issue ticket to be promoted to our production environment. Here are some steps you'll need to go through to be successfully promoted.

## **1. Prerequisites**

Before promoting your product to production, ensure the following:

- **Configurations**: Product layout and configurations have all the proper product descriptions, tags, and spec files listing + ordering.
- **Documentation**: Product documentation is complete and up-to-date. This include release notes for every API version you have.
- **API Validation**: All APIs have been validated using Developer Studio's built-in tools and the sandbox run request works as expected.
- **Testing**: Read through the documentation and check your mock APIs to make sure the flow works and makes sense.

---

## **2. Steps to Promote a Product**

### **Step 1: Finalize Your Product**
- Ensure all required features are implemented and tested.
- Verify that the product tags (e.g., capabilities, business types) are accurate and relevant.
- Confirm that all API specifications (YAML files) are up-to-date.

### **Step 2: Submit a Promotion Request**
- Open a new [GitHub Issue](https://github.com/Fiserv/Support/issues) using the **Promoting a tenant** template.
  - Provide details such as the product name and other relevant information needed for promotion as indicated on the form

As part of our ongoing support requirement, products going to `production` MUST have a Client 360 assignment group within Fiserv to field any questions from customers visiting Developer Studio.

Please review the [Client 360 guide](client360.md) for more information.

### **Step 3: Validate CI/CD Pipelines**

A Developer Studio team member will be assigned to follow-up on the Github issue with any additional questions and provide a timeline for the expected date you can expect your product to be deployed.

Please note that if any issues are found with the pre-requisite before or during the deployment process, we may have to rollback and hence cause a delay in the date of promotion.

---

## **3. Best Practices**

- **Use Tags Effectively**: Ensure your product is tagged with relevant capabilities and business types to improve discoverability for customers in production.
- **Leverage Mock Servers**: Test your APIs using the Prism Mock Server before deploying to production. This includes both if you are using DevStudio's API explorer or providing your own mock server.
- **Update Release Notes**: Add release notes to highlight new features or changes in the production environment. Documents are updated in real-time on all environments and should always feature the latest API changes for compliance within the company.
- **Follow Standard Git Practices**: Make sure to use Pull Requests to commit changes in `develop`, validate, and only then push changes to `stage` and subsequently `main` to ensure stability and functionality of your product page.

---

## **4. Frequently Asked Questions**

### **How long does it take for changes to reflect in production?**
- Documentation updates are reflected immediately via GitHub webhooks.
- API updates may take longer depending on the environment. Refer to the [Frequency of Updates](search.md#frequency-of-updates) section for details.

### **Can I test my product in a live environment before full production deployment?**
- This is what our `stage` environment is for. Please request the credentials to access it and validate that the Github branch promotion (`develop` -> `stage`) content looks good before moving from `stage` -> `main`.

### **What if I encounter issues during promotion?**
- Contact the Developer Studio team via your Teams channel or GitHub Issue for assistance. Our team will also keep an eye on the deployment process and double check that your product at least shows up correctly.

---

By following these steps and best practices, you can ensure a seamless promotion of your product to production in Developer Studio.