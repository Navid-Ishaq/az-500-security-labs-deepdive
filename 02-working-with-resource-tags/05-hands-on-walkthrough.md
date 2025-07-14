# 🛠️ From Creation to Clarity: The Power of Tagging in Action

### Point 5 of 9 – Inside the Lab: A Guided Azure Walkthrough

**Hands-On Moment:** *Executing the Steps in a Real Azure Environment*

---

## 🌐 Step 1: The Mission Begins

At **CloudCore Labs**, two junior cloud engineers, **Omar** and **Sofia**, gathered around their screens. Their mentor, **Ayesha**, handed them a lab brief titled:
**"Organizing Resources with Tags in Azure."**

> “This one’s more important than it sounds,” Ayesha said. “It’s the kind of thing that keeps your environment from turning into a spaghetti mess.”

With that, the team began their task: build a virtual machine, apply a meaningful tag, and filter it out like pros.

---

## 🧱 Step 2: Creating the Resource Group

Before any VM could be built, **Omar** created a new **resource group** in Azure named `rg-cloudcore-omar`.

> “It’s like a labeled folder for cloud stuff,” he explained to Sofia. “Everything inside stays together — cleaner and easier to manage.”

**Resource groups** help teams organize resources by project, department, or function — critical when scaling across dozens of environments.

---

## 🖥️ Step 3: Deploying the Virtual Machine

Sofia took the next step: launching a **Windows Server 2019 Datacenter** VM in the **East US** region.

She followed the checklist:

* **VM Name:** `vm-cloudcore-tagdemo01`
* **Size:** B1s (perfect for testing)
* **Security Type:** Standard
* **OS Disk Type:** Standard SSD
* **Username:** `LabUser`
* **Password:** `StrongPassword@123`

They skipped the **Azure Spot instance** and left **public inbound ports** at default — safe and simple.

> “Feels like assembling a remote PC,” Sofia grinned. “But without the hardware headaches.”

---

## 🏷️ Step 4: Applying the Tag

Once deployed, Omar clicked into the new VM and navigated to **Settings > Tags**.

Together, they added:

* **Name:** `Department`
* **Value:** `IT`

> “That’s our sticky note,” said Omar. “Except this one sticks through billing, filtering, and reporting.”

In larger organizations, tagging like this ensures that teams can:

* Assign ownership
* Group by business units
* Simplify cost reports and automation rules

This small act creates **order out of digital clutter**.

---

## 🔍 Step 5: Filtering by Tag

To test their work, Sofia returned to the **Resource Groups** view.

She clicked **Add filters**, selected:

* **Tag Name:** `Department`
* **Tag Value:** `IT`

And like magic — only their VM showed up.

> “Whoa… it's like Azure just listened to me,” Sofia said, impressed.
> “Now imagine this with hundreds of VMs,” Ayesha added. “Without tags, it’s chaos.”

This simple filter feature became their favorite part of the day.

---

## 🧼 Step 6: Clean-Up With Confidence

With the lab complete, the team needed to delete the resources — but this time, they felt in control.

They knew **exactly** what belonged to them, what was tagged, and what could safely be removed.

Omar deleted `vm-cloudcore-tagdemo01` and the `rg-cloudcore-omar` resource group, confident he wasn’t interfering with anything mission-critical.

> “I’ve never deleted something with this much peace of mind,” he laughed.

---

## 💡 Step 7: What the Team Learned

By the end of the lab, both engineers realized this wasn’t about just doing a task — it was about **learning to build responsibly**.

They learned:

* Tags aren’t cosmetic — they’re operational gold
* Azure is powerful, but structure is everything
* Small habits, like naming and tagging, scale beautifully

> “It’s like cleaning up as you go — but in the cloud,” Sofia said.

---

## 🌱 Step 8: Thinking Like Cloud Engineers

As they logged off, Ayesha left them with one final reflection:

> “Good engineers build. Great engineers **build and explain what they built**.”

This lab turned routine provisioning into an experience of **clarity, confidence, and control** — the foundation of every successful cloud project.

---



> _**Structure creates confidence. And confidence leads to clarity. One tag at a time.**_  
> — Jamalu  
> — **Siraat AI Academy**

---
