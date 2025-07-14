# 01 Creating Azure Resource Locks

### 🔹 Point 8 of 9: Interview-Ready Scenario MCQs — Real Decisions, Real Azure Practice

---

# 🎯 **Project Objective: Practice Professional Azure Scenarios with Real-World Insight**

You've done the lab. You've locked the VM. You've deleted it safely.  
But here comes the next challenge: **Could you explain what you did in a real job interview?** Or better yet — **make the right decision in a live enterprise setting**?

In this section, you’ll walk through **10+ professional MCQs**, based on scenarios faced by cloud admins like **Rohan**, **Ayesha**, and **Omar** at a fictional firm called **EdgeScale Technologies**.

Whether you're prepping for the **AZ-500**, interviewing for a cloud admin job, or just sharpening your practical skills — these questions are your next level-up moment. Let’s go! 🚀

---

## 🧩 Scenario-Based Multiple Choice Questions

---

**1. During a last-minute infrastructure cleanup, Jordan accidentally deleted a VM used by the DevOps pipeline. What could have helped prevent this situation from happening in the first place?**

(a) Creating a backup image of the VM  
(b) Disabling admin access  
(c) Assigning a lower-tier SKU  
(d) Applying a Delete Lock to the VM  

✅ **Correct Answer: (d)**  
**Explanation:** A **Delete Lock** ensures that a resource like a VM cannot be deleted — even accidentally — unless the lock is manually removed first.

---

**2. Ayesha wants to prevent changes to a resource group that houses multiple production VMs. However, she still wants monitoring systems to access them. What’s the best course of action?**

(a) Apply a Read-only Lock at the resource group level  
(b) Remove all contributors from the resource group  
(c) Enable BitLocker encryption  
(d) Move the VMs to another group  

✅ **Correct Answer: (a)**  
**Explanation:** A **Read-only Lock** allows read access (such as monitoring) but blocks any edits or reconfiguration — perfect for protecting stable environments.

---

**3. Rohan is reviewing permissions and notices that even contributors with high access cannot delete a locked VM. Why is this behavior expected?**

(a) RBAC permissions override resource locks  
(b) Resource locks override RBAC permissions  
(c) Locks only affect network interfaces  
(d) The VM is stored in a secure zone  

✅ **Correct Answer: (b)**  
**Explanation:** **Resource locks take precedence** over RBAC. Even users with full delete rights cannot delete a locked resource unless the lock is removed.

---

**4. Your team is preparing for a major deployment. To avoid misconfiguration during the launch window, which preventive step should the admin take?**

(a) Apply role-based access control  
(b) Remove write permissions temporarily  
(c) Apply Read-only Locks to critical resources  
(d) Set up auto-scaling rules  

✅ **Correct Answer: (c)**  
**Explanation:** **Read-only Locks** are perfect for protecting configurations during sensitive periods, such as product launches or maintenance windows.

---

**5. A junior admin at NextGenOps accidentally deleted a storage account. Now, management is asking for preventive action. Which of the following is the most effective step forward?**

(a) Provide training on VM creation  
(b) Migrate to a different Azure subscription  
(c) Use Azure Policy to enforce compliance  
(d) Apply Delete Locks to critical storage accounts  

✅ **Correct Answer: (d)**  
**Explanation:** A **Delete Lock** would’ve blocked the deletion attempt and prompted the admin to rethink the action — reducing human error risk.

---

**6. You’re asked to secure the Azure infrastructure without slowing down developers' ability to test and read configurations. What should you do?**

(a) Apply Read-only Locks on all VMs  
(b) Restrict access using NSGs  
(c) Apply locks only on production resources  
(d) Disable the Azure portal for developers  

✅ **Correct Answer: (c)**  
**Explanation:** In production, you want protection. But in dev/test environments, flexibility matters. **Selective locking** balances safety with speed.

---

**7. Sofia, a cloud analyst at BlueNova Systems, wants to audit all critical resource locks. Where should she begin her review?**

(a) Azure Monitor Logs  
(b) Resource Group settings under “Locks”  
(c) Azure Active Directory Sign-In Logs  
(d) Azure Pricing Calculator  

✅ **Correct Answer: (b)**  
**Explanation:** Locks can be reviewed and managed directly in the **“Locks” section** under each **resource or resource group** in the Azure Portal.

---

**8. What is the best reason to apply a Read-only Lock instead of a Delete Lock to a shared VM?**

(a) You want to allow restart but prevent deletion  
(b) You want to prevent all access  
(c) You want to reduce bandwidth usage  
(d) You want to disable auto-scaling  

✅ **Correct Answer: (a)**  
**Explanation:** **Read-only Locks** prevent any changes (including deletion), while **Delete Locks** only stop deletion. If you want to block all changes, go with read-only.

---

**9. Your team is planning to migrate resources to another subscription. What should be done with existing resource locks?**

(a) They will be removed automatically  
(b) You must manually remove them before moving  
(c) Locks will update automatically after migration  
(d) They convert into RBAC permissions  

✅ **Correct Answer: (b)**  
**Explanation:** **You must manually remove resource locks** before moving resources between subscriptions or resource groups — otherwise, the move is blocked.

---

**10. A client has asked you to ensure that their production environment remains unchanged for the next 30 days. Which feature best supports this request?**

(a) Azure Blueprints  
(b) Azure Policies  
(c) Resource Locks  
(d) Tags  

✅ **Correct Answer: (c)**  
**Explanation:** **Resource Locks** provide the quickest, simplest way to freeze changes — without redesigning permissions or policies.

---

**11. What’s the most reliable way to prevent accidental deletion across a shared Azure subscription with multiple contributors?**

(a) Add all users as Owners  
(b) Use tags for tracking  
(c) Apply Delete Locks to important resources  
(d) Move everything to one resource group  

✅ **Correct Answer: (c)**  
**Explanation:** Even contributors and owners can make mistakes. **Delete Locks protect resources at the infrastructure level** — regardless of role.

---

> _*"Mistakes teach us. But design that prevents them — now that’s wisdom in action."*_  
> — Jamalu  
> — **Siraat AI Academy**
---

