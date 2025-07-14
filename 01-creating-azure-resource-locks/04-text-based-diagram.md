# 01 Creating Azure Resource Locks

# 🔹 Point 4 of 9: Visualizing the Lab Journey — From VM Creation to Lockdown

---

# 🧭 **Main Title: "Lock It In!" — A Visual Story of Azure Resource Protection**

At **BrightOps Solutions**, a busy tech support team is building a safer, smarter cloud. In this lab, **Ayesha**, **Jordan**, and **Rohan** walk through the process of creating an Azure Virtual Machine — and then protecting it using **resource locks**.

But instead of long paragraphs or dense documentation, let’s make things clearer with a **text-based visual diagram** first — and then we’ll walk through each step together, like you’re part of the team.

---

## 🖼️ **Text-Based Diagram: Visual Flow of the Lab**

```
+-------------------------------+
|     Azure Portal Login       |
+-------------------------------+
              |
              v
+-------------------------------+
|  Create Virtual Machine       |
|  - Name: MyLabVM              |
|  - OS: Ubuntu 20.04 LTS       |
|  - Size: B2s                  |
|  - Storage: Standard SSD      |
+-------------------------------+
              |
              v
+-------------------------------+
|  Apply Delete Lock to VM      |
|  - Lock Name: VMDeleteLock    |
|  - Lock Type: Delete          |
+-------------------------------+
              |
              v
+-------------------------------+
|  Apply Read-Only Lock to RG   |
|  - Lock Name: RGReadOnly      |
|  - Lock Type: Read-Only       |
+-------------------------------+
              |
              v
+-------------------------------+
|  Attempt to Delete Resources  |
|  - Azure blocks the action!   |
+-------------------------------+
```

---

## 🔧 **Step 1: Logging In — Gearing Up for the Task**

The day began with coffee and logins. **Jordan**, still new to Azure, turned to **Ayesha** and asked,

> “So… is it just clicking around or do we need code?”
> “Mostly clicks today,” Ayesha smiled. “But every click matters.”

They opened the **Azure Portal**, their mission control for the cloud. With one login, they gained access to everything from VMs to storage — like walking into a well-organized server room.

---

## 💻 **Step 2: Creating the Virtual Machine (MyLabVM)**

The next step was building their **Virtual Machine**, or “VM.” A VM is like a computer that lives in the cloud — it runs, stores, processes, and helps power apps or services.

Jordan selected:

* **Ubuntu Server 20.04 LTS**
* **B2s** size (perfect for labs)
* **Standard SSD** for storage

They named it **MyLabVM** and added a username/password combo. Azure made it easy with guided tabs and a “Review + Create” button.

> “Feels like building a PC in the sky,” Rohan joked.

---

## 🔐 **Step 3: Adding a Delete Lock to the VM**

Now came the “protection” part. Imagine you’ve just built a house. Wouldn’t you want a lock on the door?

They opened the **Settings > Locks** panel on the VM and added a lock:

* **Name**: VMDeleteLock
* **Type**: Delete

This means no one — not even an admin — can delete the VM unless they remove the lock first. It’s not about control — it’s about prevention.

> “It’s like child-lock for cloud resources,” Ayesha explained.

---

## 🗃️ **Step 4: Locking the Entire Resource Group**

Every Azure resource lives in a **Resource Group** — kind of like a folder that holds all the stuff for a project. So what if you want to protect everything in that folder?

That’s where the **Read-Only Lock** comes in.

Jordan navigated to the **Resource Group**, clicked on **Locks**, and added:

* **Name**: RGReadOnly
* **Type**: Read-only

Now, no one could change **anything** inside — unless they deliberately removed that lock.

> “We just locked a whole toolbox,” said Rohan, grinning.

---

## 🔄 **Step 5: Testing the Locks — What Happens When You Try to Delete?**

To test if the locks actually worked, they tried to delete the VM.

Bam! Azure popped up a warning:
**“This resource is locked and cannot be deleted.”**

Everyone nodded in relief. That lock wasn’t just a checkbox — it was a real-life safety switch. One that could protect against stress, downtime, and data loss in real-world projects.

---

## 🎓 **Step 6: Why This Lab Is a Big Deal**

At first, this lab might seem simple. But it carries big lessons:

* **Prevention is better than restoration.**
* **Resource Locks** are tiny settings with huge impact.
* **Cloud safety is everyone’s job — not just security teams.**

The team at BrightOps now makes resource locks part of every deployment checklist. What started as a 45-minute lab is now a company-wide practice.

> “Small locks, big peace of mind,” Ayesha whispered, smiling.

---

## ✅ **Final Thoughts: Clear Actions, Clear Protection**

By using a simple diagram and clear steps, this lab helped **demystify resource protection**. You don’t need to be a security expert to make your Azure environment safer.

You just need to **slow down**, **think ahead**, and **lock it down.**

---

> **"Even in the cloud, clarity is your strongest shield — one well-placed lock at a time."**
> — Jamalu
> — **Siraat AI Academy**

---


