# 01 Creating Azure Resource Locks

# 🔹 Point 5 of 9: Hands-On in Azure — A Step-by-Step Walkthrough of Resource Protection

---

# 🚀 **Main Title: From Clicks to Confidence — A Friendly Walkthrough in the Live Azure Portal**

Welcome to the heart of the action! In this hands-on lab, we’ll follow three cloud learners — **Ayesha**, **Jordan**, and **Leo** — as they take on a real Azure challenge at their company, **CloudCore Labs**. Their mission? Deploy a virtual machine, then protect it using **resource locks** to prevent accidental deletion or changes.

They’re working in a live Azure environment, not a sandbox — so every click counts. Let's walk through each step together like you're right there with them!

---

## 🎯 **Project Objective: Build It, Then Guard It**

The goal of this lab is twofold:

1. **Deploy a Virtual Machine (VM)** to simulate a cloud-based server.
2. Apply **two resource locks**:

   * A **Delete Lock** on the VM itself
   * A **Read-Only Lock** on the Resource Group

Why? Because in a real business setting, one misstep — like deleting a production VM — could lead to downtime, lost data, or frantic 2AM support calls. These locks act like your cloud’s seatbelt system.

---

## 🔐 **Step 1: Log In to the Azure Portal**

Ayesha kicked things off by heading to the [Azure Portal](https://portal.azure.com). Jordan, still fresh to the platform, followed along.

> “It’s kind of like the control panel for everything cloud,” she explained.
> “You’ll love how visual it is.”

Once signed in with their credentials, they were ready to get started!

---

## 🧱 **Step 2: Create a Virtual Machine**

They clicked on **Create a resource** and chose **Virtual Machine**.

Here’s what they filled in:

| Setting                  | Value                           |
| ------------------------ | ------------------------------- |
| **Resource Group**       | `rg-cloudcore-ayesha`           |
| **VM Name**              | `vm-cloudcore-leo01`            |
| **Region**               | (Select your preferred region)  |
| **Availability Options** | No infrastructure redundancy    |
| **Security Type**        | Trusted launch virtual machines |
| **Image**                | Ubuntu Server 20.04 LTS Gen2    |
| **Size**                 | B2s                             |
| **Authentication Type**  | Password                        |
| **Username**             | `cloudadmin`                    |
| **Password**             | `StrongPassword@123`            |

They clicked **Next > Disks**, selected:

* **OS Disk Type**: Standard SSD (Locally-redundant storage)

Then hit **Review + Create**, confirmed the details, and clicked **Create**.

> “It’s like provisioning a full Linux server in minutes,” Leo grinned.

---

## 🔒 **Step 3: Add a Delete Lock to the Virtual Machine**

Once the VM was deployed, the team navigated to the new VM (`vm-cloudcore-leo01`).

In the **left-hand menu**, under **Settings**, they clicked on **Locks** and selected **+ Add**.

| Lock Setting  | Value          |
| ------------- | -------------- |
| **Lock Name** | `VMDeleteLock` |
| **Lock Type** | Delete         |

They saved the lock.

> “Now, no one can delete this VM unless they remove the lock first,” Ayesha explained.
> “It's like putting a sticker that says ‘Do not trash!’ on something important.”

---

## 🗂️ **Step 4: Add a Read-Only Lock to the Resource Group**

Next, they opened the **Resource Group** (`rg-cloudcore-ayesha`) from the main portal dashboard.

Under **Settings > Locks**, they clicked **+ Add** again.

| Lock Setting  | Value        |
| ------------- | ------------ |
| **Lock Name** | `RGReadOnly` |
| **Lock Type** | Read-only    |

This lock prevents users from changing or moving **any** resources inside the resource group — including the VM.

> “We just locked the whole container,” Jordan said.
> “That’s some serious protection!”

---

## 🧪 **Step 5: Try Deleting the VM (On Purpose 😈)**

To test it, they tried deleting the VM. But Azure stopped them cold.

> “Error: This resource is locked and cannot be deleted.”

> “Boom. That’s how we know the lock is working,” Leo laughed.
> “Accidents avoided.”

They also tried editing settings — and the **Read-Only Lock** blocked it too.

---

## 🧹 **Step 6: Remove the Locks, Then Clean Up**

Before ending the lab, they had to clean up the resources. But first, they removed the two locks manually:

1. Go to **Locks** on the VM → Delete `VMDeleteLock`
2. Go to **Locks** on the Resource Group → Delete `RGReadOnly`

Then they were able to delete everything safely.

> “Now we know how to lock and unlock when needed,” Ayesha nodded.
> “That’s cloud admin 101.”

---

## ✅ **Final Thoughts: Clicks That Count**

This wasn’t just about clicking buttons in Azure. It was about learning how **to work responsibly in the cloud**.

* Jordan learned how to protect cloud resources with simple tools.
* Ayesha mentored her team and reinforced solid operational practices.
* Leo got hands-on experience — and now volunteers to help with client onboarding at CloudCore Labs.

---

> **"In every step you take to secure the cloud, you're really protecting the people behind it."**
> — Jamalu
> — **Siraat AI Academy**

---

# 🧠 Smart Summary: Azure Resource Locks — Step-by-Step in a Live Environment

---

## 🚀 **What Happened**
Ayesha, Jordan, and Leo from **CloudCore Labs** went hands-on in the **Azure Portal** to:

- Create a secure **Virtual Machine**
- Apply **resource locks** to prevent accidental deletion or changes
- Learn the power of tiny safeguards in real cloud operations

---

## 🛠️ **Key Tools & Resources**
- **Azure Portal** — the central dashboard for all Azure actions
- **Virtual Machine** (`vm-cloudcore-leo01`) — Ubuntu-based server in the cloud
- **Resource Group** (`rg-cloudcore-ayesha`) — folder that organizes all related resources
- **Locks**:
  - 🔒 `VMDeleteLock` — prevents deletion of the VM
  - 📘 `RGReadOnly` — stops edits to anything inside the resource group

---

## 💡 **Why It Matters**
Resource locks help prevent human error — especially in shared cloud environments.  
One misplaced click could cause real damage. These locks act like **cloud seatbelts**.

> “We’re not just managing resources. We’re managing trust.” — Ayesha

---

## 🧪 **Steps in Action**
1. Created a VM with standard settings  
2. Applied a **Delete Lock** to the VM  
3. Applied a **Read-Only Lock** to the resource group  
4. Tried to delete the VM — blocked by Azure (✅ success!)  
5. Removed the locks, then cleaned up safely

---

## 🌱 **Lessons Learned**
- Even beginner-friendly tools like locks can protect big business outcomes.
- Testing safeguards helps build **real confidence** in cloud operations.
- Azure makes it easy to blend **learning with impact**.

---

> _*"Security isn’t always loud — sometimes, it’s in the quiet discipline of doing the small things right."*_  
> — Jamalu  
> — **Siraat AI Academy**

---

