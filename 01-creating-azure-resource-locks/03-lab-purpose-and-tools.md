# 01 Creating Azure Resource Locks

# 🔹 Point 3 of 9: Understanding the Purpose and Power Behind Azure Resource Locks

---

# 🔐 **“Hands Off!” — Why Resource Locks in Azure Are the Unsung Heroes of Cloud Safety**

When it comes to cloud computing, clicking “delete” shouldn’t feel like walking a tightrope without a net. That’s exactly why Microsoft Azure gives us a little-known but powerful feature called **resource locks** — and that’s what this lab is all about.

Join **Ayesha** (a cloud admin from Nairobi), **Jordan** (a DevOps intern from Toronto), and **Rohan** (a junior security analyst from Mumbai) as they explore how a 45-minute lab at **BrightOps Solutions** turned into a masterclass in protecting critical resources like pros.

Let’s break it down in a fun, friendly, and clear way — and show why this lab really matters!

---

## 🎯 **Project Objective: Lock What Matters, Before It Shatters**

The goal of this lab is simple:
👉 **Create a virtual machine** in Azure
👉 Apply **resource locks** to stop anyone from deleting or changing it by accident

Why? Because in real life, busy IT teams juggle dozens (or hundreds) of cloud resources. A single click from the wrong person can cause big problems. Think downtime, data loss, or angry clients.

As Ayesha told Jordan,

> “It’s like putting a ‘Do Not Disturb’ sign on something important — so nobody accidentally messes with it.”

---

## 🛠️ **Azure Portal — Your Cloud Command Center**

The first tool used in this lab is the **Azure Portal** — the friendly web dashboard where you can see and manage all your cloud resources.

**Think of it like a smart dashboard for your home:**
Lights, cameras, thermostats — everything’s in one place. That’s Azure Portal, but for your cloud.

In this lab, Jordan logged into the portal and clicked **“Create a resource”** to start building their virtual machine. It’s visual, guided, and beginner-friendly.

> “Way easier than I thought it’d be,” Jordan admitted. “It walks you through everything.”

---

## 🧱 **Virtual Machines — The Brains of the Operation**

Next up, they created a **Virtual Machine (VM)** — in this case, an **Ubuntu Server 20.04** machine named **MyLabVM**.

💻 **What’s a VM?**
Imagine it like a full computer that lives inside the cloud. You can log in, run apps, install software — all without needing a physical device.

Why was this step important? Because it gave them something real to **protect**. The VM became their test subject for applying locks later.

They chose a small, affordable size (**B2s**), added login credentials, selected **Standard SSD storage**, and hit **Create**. Azure handled the heavy lifting.

---

## 🔐 **Resource Locks — Like Padlocks for Your Cloud Stuff**

Now comes the star of the lab: **Resource Locks**.

There are two types:

* **Delete Lock** — stops people from deleting the resource
* **Read-Only Lock** — blocks changes to settings and configurations

Here’s how Rohan explained it in the team chat:

> “It’s like setting a phone to ‘No Delete’ or ‘View Only’ mode. It still works, but you can’t mess with it.”

Ayesha added a **Delete Lock** named **VMDeleteLock** to the VM. Then Jordan added a **Read-Only Lock** named **RGReadOnly** to the **Resource Group** (a container that holds related resources).

The idea? Even if someone’s in a rush, these locks make them slow down and think twice before changing anything.

---

## 📦 **Resource Groups — The Cloud’s Filing Cabinet**

You might wonder, *what’s a Resource Group*?

💡 Think of it like a **folder** that holds all the files related to a single project — VMs, storage, networks, and more.

By applying a **Read-Only Lock** to the Resource Group, Jordan ensured that **everything inside it is safe from changes**, unless someone removes the lock first (which requires admin access and intention).

> “It’s like locking an entire drawer, not just one file,” Ayesha said. “More coverage, less risk.”

---

## 🤝 **How These Tools Work Together**

Here’s the magic:

1. The **Azure Portal** helps you see and control all your stuff
2. The **Virtual Machine** gives you something to protect
3. The **Resource Group** keeps related things together
4. **Resource Locks** add safety layers on top — like locking the doors when you leave home

Together, they create a **secure, well-organized cloud environment**. You’re not just building — you’re **building responsibly**.

---

## 🎓 **Why It Matters in Real Life**

BrightOps Solutions recently had a client lose critical files after someone accidentally deleted a resource. Ever since, Ayesha has made it her mission to teach the team about **preventive protection**.

> “It’s not about trusting people less — it’s about supporting them better,” she said.

With Azure resource locks, you give your cloud the ability to say:
**“Are you sure?”** — before disaster strikes.

That’s the kind of safety every business needs.

---

> *"You don’t need to know everything to begin — just enough to take the first wise step."*
> — Jamalu
> — **Siraat AI Academy**

---


