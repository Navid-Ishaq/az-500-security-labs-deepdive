# 🎯 Real-World Thinking: Azure Job Scenario MCQs  
## Point 8 of 9 – Real-World Thinking: Azure Job Scenario MCQs  
### Interview Readiness Zone: 10+ Practical, Job-Focused Questions

**Q1. Omar at CloudCore Labs is trying to restrict the creation of resources outside the UK South region. What’s the best approach to enforce this policy in a repeatable, auditable way?**  
(a) Create a custom RBAC role that limits regional creation  
(b) Tag all existing resources with “UKSouthOnly”  
(c) Use Azure Policy to define allowed regions  
(d) Set up a Resource Lock on other regions  

✅ **Correct Answer:** (c)  
💡 **Explanation:** **Azure Policy** is the most effective tool for enforcing restrictions such as allowed regions. It ensures that resources created outside specified locations fail validation automatically.

**Q2. Sofia accidentally created a virtual machine in East US despite the team policy. What likely went wrong?**  
(a) The VM was not tagged properly  
(b) The Policy was in “Audit” mode instead of “Enforce”  
(c) The VM used a premium disk  
(d) The region was manually changed post-deployment  

✅ **Correct Answer:** (b)  
💡 **Explanation:** If a policy is set to **“Audit”** rather than “Enforce,” Azure won’t block the deployment — it will just log the violation. Enforce mode is needed to prevent incorrect deployments.

**Q3. Ayesha is setting up governance for rg-dataops-uk. What’s the best practice before assigning a new policy?**  
(a) Create a deployment template  
(b) Notify the finance team  
(c) Scope the policy to the correct resource group  
(d) Remove all current resources first  

✅ **Correct Answer:** (c)  
💡 **Explanation:** Always define **scope** before assigning a policy. Scoping ensures the policy affects only the intended resource group or subscription.

**Q4. Rohan needs to confirm whether a newly created network violated the “Allowed locations” policy. Where should he check?**  
(a) Azure Advisor  
(b) Azure Monitor Logs  
(c) Policy compliance tab  
(d) Cost Management  

✅ **Correct Answer:** (c)  
💡 **Explanation:** The **Policy compliance blade** in Azure clearly shows which resources are compliant or non-compliant, along with reasons.

**Q5. Taylor wants to write a policy that blocks public IPs. What is the best way to proceed?**  
(a) Use a predefined initiative  
(b) Edit the Azure Resource Manager template  
(c) Search for built-in policy definitions  
(d) Manually tag all public IPs  

✅ **Correct Answer:** (c)  
💡 **Explanation:** Azure offers many **built-in policy definitions** for common governance tasks like disallowing public IPs. Start there before customizing.

**Q6. Which of the following represents a typical use case for Azure Policy in a production setting?**  
(a) Encrypting all files at rest  
(b) Deploying web apps  
(c) Enforcing naming conventions across a department  
(d) Creating diagnostic settings  

✅ **Correct Answer:** (c)  
💡 **Explanation:** Enforcing consistent **naming standards** is a classic governance challenge that Azure Policy solves elegantly and at scale.

**Q7. At SkyBridgeTech, Sofia needs to prevent new deployments of unsupported VM SKUs. Which tool helps here?**  
(a) Azure Cost Management  
(b) Azure Policy with SKU restrictions  
(c) Defender for Cloud  
(d) Azure Arc  

✅ **Correct Answer:** (b)  
💡 **Explanation:** **Azure Policy** allows you to restrict or whitelist VM SKUs to avoid unexpected costs or unsupported configurations.

**Q8. Omar assigns a policy but nothing changes. What's a likely mistake?**  
(a) He forgot to delete old resources  
(b) He skipped the “Review + Create” step  
(c) He assigned the policy at the wrong scope  
(d) Azure policies only apply to virtual machines  

✅ **Correct Answer:** (c)  
💡 **Explanation:** Scoping is critical — assigning a policy at the wrong level (e.g., subscription vs. resource group) means it won't apply where intended.

**Q9. Which team role is most responsible for creating and enforcing Azure governance policies?**  
(a) DevOps Engineer  
(b) Azure Policy Author  
(c) Cloud Architect or Platform Engineer  
(d) Security Analyst  

✅ **Correct Answer:** (c)  
💡 **Explanation:** **Cloud Architects and Platform Engineers** often own platform-level governance, including Azure Policy, as part of enterprise design and control.

**Q10. What happens when you try to deploy a resource outside an allowed location enforced by Azure Policy?**  
(a) The deployment is auto-corrected to the nearest location  
(b) The resource is deployed and marked non-compliant  
(c) The validation step fails and blocks deployment  
(d) Azure raises a billing alert  

✅ **Correct Answer:** (c)  
💡 **Explanation:** With enforcement mode on, **Azure blocks deployments** that violate location rules during the validation phase.

**Q11. How could tagging help in combination with Azure Policy for better governance?**  
(a) Tags replace the need for policy  
(b) Tags allow exemptions to enforced policies  
(c) Tags enable better tracking and scope application  
(d) Tags increase deployment speed  

✅ **Correct Answer:** (c)  
💡 **Explanation:** Tags provide **contextual filtering**, reporting, and can be used with policies to target or exempt resources more precisely.

**Q12. Rohan wants to limit resource creation to UK South only for one team. What’s the best combination?**  
(a) RBAC + Audit Logs  
(b) Azure Policy + Resource Tag Filter  
(c) Log Analytics + Azure Sentinel  
(d) Network Watcher + Firewall  

✅ **Correct Answer:** (b)  
💡 **Explanation:** Using **Azure Policy** with **tag filtering** allows precise scoping and rules — ideal for controlling which teams create what, where.

---

> _You’re becoming who you were meant to be — one decision, one scenario, one policy at a time._  
> — Jamalu  
> — **Siraat AI Academy**

---
