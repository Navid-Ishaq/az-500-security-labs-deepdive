# ✅ Let’s Test What We Know: Azure Policy Enforcement Concepts

## Point 7 of 9 – Let’s Test It: Real-World Concept Checks

### Exam Readiness Boost: 10+ Scenario-Based Azure MCQs

These conceptual questions are designed to challenge your thinking and mirror the kind of real-world decision-making tested in the **AZ-500** certification and actual Azure roles. Let’s reinforce your understanding of **Azure Policy**, **resource control**, and **real-world governance.**

---

**Q1. Why would a cloud governance team assign an 'Allowed locations' policy to a resource group?**

(a) To track network latency per region
(b) To block access from certain IP addresses
(c) To restrict where resources can be deployed geographically
(d) To encrypt the disks automatically

✅ **Correct Answer:** (c)
💡 **Explanation:** The 'Allowed locations' policy ensures all new resource deployments stay within approved Azure regions, supporting compliance and data residency.

---

**Q2. Sofia tried creating a VM in East US but received a validation error. What likely caused it?**

(a) Azure region was full
(b) Her subscription was disabled
(c) A location policy blocked East US for that resource group
(d) The VM image was unavailable

✅ **Correct Answer:** (c)
💡 **Explanation:** If the Azure Policy restricts allowed regions and East US isn’t permitted, validation fails to prevent non-compliant deployments.

---

**Q3. What is a benefit of applying policies at the resource group level instead of subscription-wide?**

(a) Policies run faster
(b) It applies only to selected scopes, allowing granular control
(c) It skips audit logging
(d) It’s cheaper to implement

✅ **Correct Answer:** (b)
💡 **Explanation:** Policies can be scoped narrowly to enforce tailored controls over specific workloads without affecting broader infrastructure.

---

**Q4. What happens if someone tries to deploy a resource outside the allowed region set by policy?**

(a) It triggers a soft warning only
(b) It automatically adjusts to the nearest allowed region
(c) Deployment fails during validation
(d) Azure charges extra for out-of-policy deployment

✅ **Correct Answer:** (c)
💡 **Explanation:** With policy enforcement enabled, non-compliant deployments are blocked during validation.

---

**Q5. Rohan wants to allow only 'UK South' for compliance. What should he configure?**

(a) Azure Lock on all VMs
(b) Location tagging in Cost Management
(c) Policy assignment with location restriction
(d) Role-based access control by region

✅ **Correct Answer:** (c)
💡 **Explanation:** An Azure Policy with a location parameter ensures only approved regions are used, aligning with governance.

---

**Q6. What does policy enforcement do when set to “Enabled”?**

(a) Logs activity for later audit
(b) Sends alerts only when violated
(c) Actively blocks non-compliant resources
(d) Assigns resources to backup groups automatically

✅ **Correct Answer:** (c)
💡 **Explanation:** Enforcement blocks the creation or update of non-compliant resources in real time.

---

**Q7. At **SkyBridgeTech**, Jordan wants to test policies without blocking users. What setting helps?**

(a) Audit mode for the policy definition
(b) Change policy scope to tenant root group
(c) Set enforcement to disabled and monitor
(d) Use Azure Blueprints instead of Policies

✅ **Correct Answer:** (a)
💡 **Explanation:** **Audit mode** helps assess compliance without blocking — useful for early testing.

---

**Q8. Which service is directly used to define and assign governance rules like location restrictions?**

(a) Azure Monitor
(b) Azure AD
(c) Azure Policy
(d) Azure Firewall

✅ **Correct Answer:** (c)
💡 **Explanation:** **Azure Policy** lets you define rules and control resource behavior proactively.

---

**Q9. Ayesha wants to prevent accidental changes to allowed locations. What should she do?**

(a) Set policy enforcement to disabled
(b) Add a management lock
(c) Move all resources to another region
(d) Archive the policy JSON

✅ **Correct Answer:** (b)
💡 **Explanation:** A **management lock** can prevent policy deletion or changes by accident.

---

**Q10. What’s the key reason many organizations use region restriction policies?**

(a) To increase cost savings automatically
(b) To test features across all regions
(c) To meet **data residency and compliance** rules
(d) To simplify user access

✅ **Correct Answer:** (c)
💡 **Explanation:** Restricting regions helps meet legal, compliance, and data residency requirements.

---

> **You’re not just checking boxes — you’re checking your understanding. That’s what real growth looks like.**  
> — Jamalu  
> — **Siraat AI Academy**

---


