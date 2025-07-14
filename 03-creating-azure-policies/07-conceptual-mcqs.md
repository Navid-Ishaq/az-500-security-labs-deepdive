# 📘 Point 7 of 9 – Let’s Test It: Real-World Concept Checks

### Exam Readiness Boost: 10+ Scenario-Based Azure MCQs

---

**Q1. What is the core purpose of an Azure Policy like “Allowed Locations”?**

(a) To improve app performance in specific regions  
(b) To automatically back up all VMs  
(c) To enforce governance by restricting where resources can be deployed  
(d) To grant users access to Azure resources globally  

✅ **Correct Answer:** (c)  
💡 **Explanation:** Azure Policy helps enforce organizational standards. “Allowed Locations” ensures teams can only create resources in approved regions, which is critical for compliance and governance.

---

**Q2. When Sofia created a new virtual network in East US, deployment failed. Why?**

(a) The subnet name was invalid  
(b) Her account lacked permissions  
(c) An Azure Policy restricted that region  
(d) Azure was down in East US  

✅ **Correct Answer:** (c)  
💡 **Explanation:** A region-based policy (like "Allowed Locations") can block creation in disallowed locations. Sofia needed to select **UK South**, the only allowed region in this case.

---

**Q3. What happens if a resource doesn’t comply with an assigned policy during deployment?**

(a) Azure charges extra fees  
(b) Deployment is blocked or flagged  
(c) The policy is overridden automatically  
(d) Azure auto-corrects the configuration  

✅ **Correct Answer:** (b)  
💡 **Explanation:** Azure Policy can either deny or audit non-compliant actions. In this case, deploying to an unapproved region would be denied.

---

**Q4. Rohan wants to enforce tagging across resources. What should he use?**

(a) Azure Monitor  
(b) Azure Blueprints  
(c) Azure Policy  
(d) Azure Defender  

✅ **Correct Answer:** (c)  
💡 **Explanation:** **Azure Policy** can require certain tags (e.g., “Department”, “Environment”) on resources. It’s a core governance tool.

---

**Q5. Which of the following best describes the benefit of policy enforcement in a large organization like EdgeScale Technologies?**

(a) Enforces code quality before GitHub commits  
(b) Tracks CPU performance in real-time  
(c) Reduces human error by automating compliance  
(d) Improves internet bandwidth  

✅ **Correct Answer:** (c)  
💡 **Explanation:** Policy-based enforcement ensures all teams comply with organizational rules automatically — reducing human error and boosting security.

---

**Q6. Ayesha accidentally set up resources in multiple regions. What could’ve prevented this?**

(a) A lock on the resource group  
(b) Azure Firewall rules  
(c) A policy assignment for allowed locations  
(d) More admin training  

✅ **Correct Answer:** (c)  
💡 **Explanation:** A location-based policy would have restricted resource creation to specific regions — avoiding this misconfiguration entirely.

---

**Q7. What’s a key difference between Azure Policy and Role-Based Access Control (RBAC)?**

(a) RBAC defines permissions; Policy defines compliance rules  
(b) RBAC restricts networks; Policy handles authentication  
(c) Policy manages users; RBAC handles storage  
(d) They both do the same thing  

✅ **Correct Answer:** (a)  
💡 **Explanation:** **RBAC** is about *who can do what*. **Policy** is about *what should or shouldn’t be allowed* — even if users have permissions.

---

**Q8. Why would a team use “Audit” instead of “Deny” in a policy mode?**

(a) To trigger automatic backups  
(b) To allow testing without blocking resources  
(c) To enforce encryption settings  
(d) To reduce billing costs  

✅ **Correct Answer:** (b)  
💡 **Explanation:** **Audit** mode lets teams see non-compliant actions without stopping work — useful for trial runs or phased rollouts.

---

**Q9. Jordan wants to allow resources only in UK regions but still monitor global activity. Which combo works best?**

(a) Azure Policy for regions + Azure Monitor for tracking  
(b) Azure Key Vault + Azure Resource Graph  
(c) RBAC with location rules  
(d) Azure Lighthouse + Azure DNS  

✅ **Correct Answer:** (a)  
💡 **Explanation:** **Azure Policy** restricts deployment regions. **Azure Monitor** helps track activity, giving both control and visibility.

---

**Q10. If a policy is assigned at the subscription level, what scope does it affect?**

(a) Only that user’s session  
(b) Only resources created in the current month  
(c) All resource groups and resources in the subscription  
(d) Only VMs, not networks  

✅ **Correct Answer:** (c)  
💡 **Explanation:** Scope matters. Assigning a policy at the **subscription** level means it governs *all* resources and groups under that subscription.

---

**Q11. Which of the following is a direct benefit of applying region-based policies in Azure?**

(a) Automatically deletes unused VMs  
(b) Helps enforce data residency or legal requirements  
(c) Encrypts traffic between regions  
(d) Improves performance for all users  

✅ **Correct Answer:** (b)  
💡 **Explanation:** Some industries or governments require data to stay within specific geographic regions. Policies can help enforce this at the deployment level.

---

**Q12. What’s the best way to confirm that a policy is working as expected after assignment?**

(a) Wait for a week and see what happens  
(b) Create a test resource that should be denied  
(c) Ask a teammate to delete the policy  
(d) Apply the same policy twice  

✅ **Correct Answer:** (b)  
💡 **Explanation:** Testing policy behavior — like trying to create a resource in a disallowed region — immediately confirms that the policy is enforced.

---

> _The smartest systems don’t just move fast — they move wisely, together._  
> — Jamalu  
> — **Siraat AI Academy**

---
