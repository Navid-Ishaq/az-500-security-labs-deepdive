# 🎉 Azure Adventure: Tag It Like a Pro!

## Point 9 of 9 – Comic Recap: Tag Trouble and the VM Rescue Crew

### Today’s Lab: Working with Resource Tags

---

### 🌀 Uh-Oh! Where’d That VM Belong?

At **CloudCore Labs**, the team had a small but mighty problem: they spun up a new **Virtual Machine**, but no one knew which department it belonged to. **Ayesha** scratched her head, “Did we create this for Finance… or IT?”

Meanwhile, **Omar** sipped his coffee and said, “No tag, no trail. Let’s clean this up before the audit team gets curious.” ☕💻

---

### 🛠️ Tools to the Rescue!

The team jumped into the **Azure Portal**, created a new **VM** named `vm-ops-tagcheck01`, and placed it under a fresh **resource group**: `rg-cloudcore-it`. No fancy settings, just a lean **Windows Server 2019** box running on **B1s** — perfect for testing.

**Sofia** asked, “Wait — are we leaving this VM untagged too?”  
Everyone froze for a second. 😳

---

### 🏷️ Tag Time: Label It or Lose It!

They quickly went into the **Tags** panel and added:  
**Name:** `Department`  
**Value:** `IT`  
Boom — now that VM had an identity, like a name tag at a tech conference.

“This is actually kinda fun,” joked **Omar**, “Like giving each resource its Hogwarts house.” 🧙‍♂️

---

### 🔍 Tag Filters = Magic Glasses

Later, Ayesha showed the team how to filter all VMs with `Department=IT`. It was like putting on AR glasses — the clutter disappeared, and only relevant resources stayed visible.

“Whoa, this would’ve saved me hours last week,” Sofia admitted. The team nodded. Filtering by tags? Total game changer. 🎯

---

### 🧹 Cleanup, High-Fives, and Tagging Wisdom

Finally, after demoing the filter tool, they **deleted the resources**. No mess, no confusion, and they all agreed: tagging isn’t just optional — it’s essential.

Ayesha raised her mug, “To tags — our tiny heroes!” ☕  
Omar added, “And to not getting yelled at by Finance again.”

---

> _**You did great — and you had fun doing it. That’s how real learning sticks.**_  
> — Jamalu  
> — **Siraat AI Academy**

---
