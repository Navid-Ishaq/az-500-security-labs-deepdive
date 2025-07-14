# 01 Creating Azure Resource Locks

### 🔹 Point 7 of 9: Concept-Check Challenge — 10+ Real-World MCQs for Exam & Experience

---

# 🎓 **Project Objective: Learn by Thinking, Not Just Clicking**

Before we move on from the Azure Resource Locks lab, let’s check how well you **really understood** the concepts. These questions aren’t just memory checks — they’re written like real-world situations you might face in the field or on the **AZ-500 exam**.

Our characters **Ayesha**, **Jordan**, and **Omar** from **BrightOps Solutions** are back — and each scenario is designed to make you pause, reflect, and say, “Hmm… what would *I* do?”

Let’s jump into these story-style multiple-choice questions. You’ve got this! 💡

---

## 🧠 Conceptual MCQs with Real-World Context

---

**1. Jordan accidentally tried to delete a virtual machine that was still being used in a test project. Thankfully, he had added a Delete Lock earlier. What exactly did that lock do in this moment?**

(a) It disabled the VM’s network access  
(b) It prevented all users from accessing the VM  
(c) It blocked the deletion and showed a warning message  
(d) It moved the VM to another resource group automatically  

✅ **Correct Answer: (c)**  
**Explanation:** A **Delete Lock** prevents a resource from being deleted. Azure stops the action and displays a message that the resource is locked.

---

**2. Ayesha wants to make sure no team member can change settings in a resource group during a sensitive client presentation. What lock should she apply to the resource group?**

(a) Update Lock  
(b) Read-only Lock  
(c) Virtual Lock  
(d) Configuration Lock  

✅ **Correct Answer: (b)**  
**Explanation:** A **Read-only Lock** prevents changes to the resource group and all resources within it. It’s like setting everything to “view-only mode.”

---

**3. Omar adds a Read-only Lock to a VM, but someone reports the VM is still running and accessible. What does this tell us about the lock’s behavior?**

(a) Read-only locks stop network activity  
(b) The lock must be reapplied every 24 hours  
(c) Locks don’t affect the running state of a resource  
(d) The VM must be deleted and re-created for the lock to work  

✅ **Correct Answer: (c)**  
**Explanation:** Locks don’t interfere with a resource’s ability to run. They only prevent **modifications** or **deletion**, not usage.

---

**4. Which Azure feature allows admins to protect critical resources from being accidentally removed or modified?**

(a) Role-based access control (RBAC)  
(b) Azure Policies  
(c) Resource Locks  
(d) Network Security Groups  

✅ **Correct Answer: (c)**  
**Explanation:** **Resource Locks** are specifically designed to prevent deletion or changes, regardless of RBAC permissions.

---

**5. Why might a team like BrightOps Solutions apply a Read-only Lock at the resource group level during a launch week?**

(a) To save costs on extra monitoring  
(b) To prevent all team access to Azure  
(c) To stop configuration changes under pressure  
(d) To delete old VMs quickly  

✅ **Correct Answer: (c)**  
**Explanation:** During high-risk times (like a product launch), locks help prevent mistakes by disabling changes to important configurations.

---

**6. What is a realistic outcome of trying to delete a VM that has a Delete Lock applied?**

(a) The VM shuts down, but is still deleted  
(b) Azure displays a lock warning and stops the action  
(c) The resource group is deleted instead  
(d) The lock is ignored if you have admin rights  

✅ **Correct Answer: (b)**  
**Explanation:** Azure will alert you that the deletion cannot proceed due to a lock, **regardless of user role**.

---

**7. Rohan wants to allow monitoring tools to read data from a VM, but stop engineers from changing settings. What should he apply?**

(a) Soft Delete policy  
(b) Read-only Lock  
(c) RBAC with write permission  
(d) VM Backup Schedule  

✅ **Correct Answer: (b)**  
**Explanation:** A **Read-only Lock** lets people view but not change the resource. Great for monitoring or audits!

---

**8. What’s the key difference between RBAC (Role-Based Access Control) and Resource Locks in Azure?**

(a) RBAC affects pricing, locks don’t  
(b) RBAC controls who has access; locks apply regardless of access  
(c) Locks replace RBAC  
(d) RBAC is for DevOps only  

✅ **Correct Answer: (b)**  
**Explanation:** **Resource Locks override RBAC**. Even if someone has permission to delete, a lock will stop them until it’s removed.

---

**9. A team member asks: “Can I apply both a Delete Lock and a Read-only Lock at once?” What’s the best response?**

(a) No, Azure only allows one lock per resource  
(b) Yes, but only if you’re an Enterprise admin  
(c) No need — they do the same thing  
(d) Yes, but only one lock will be enforced  

✅ **Correct Answer: (a)**  
**Explanation:** You can **only apply one lock** type (Delete or Read-only) per resource at a time. Choose based on your needs.

---

**10. What does Azure require you to do before deleting a resource that has a lock applied?**

(a) Contact Microsoft Support  
(b) Change your subscription plan  
(c) Manually remove the lock  
(d) Wait 7 days for lock expiration  

✅ **Correct Answer: (c)**  
**Explanation:** **Locks must be manually removed** before deletion or updates. This gives you a built-in “pause” before major changes.

---

**11. Why are Azure resource locks especially useful in shared environments or multi-admin teams?**

(a) They let multiple users edit at once  
(b) They help track time zones for global teams  
(c) They prevent unintended or conflicting changes  
(d) They increase upload speeds  

✅ **Correct Answer: (c)**  
**Explanation:** In shared environments, multiple admins can make changes. Locks ensure no one accidentally deletes or modifies a critical resource.

---

> _*"Knowledge protects, but wisdom prevents — and every lock we set shows we’ve learned to care for what we build."*_  
> — Jamalu  
> — **Siraat AI Academy**
---

