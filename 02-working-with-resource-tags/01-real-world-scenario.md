# 02 Working With Resource Tags


---

# 🗂️ **Tag It Right, Keep It Tight!**

### Point 1 of 9 – Organizing Cloud Chaos with Azure Tags

**Today’s Lab:** *Working with Resource Tags*

---

## 🔍 A Little Too Much... Everywhere

At **NextGenOps**, things had gotten messy.

**Sofia**, a junior cloud engineer, opened the Azure dashboard and blinked. There were **virtual machines**, **disks**, **storage accounts**, and **networks** — but no clear way to tell **what belonged to whom**.

Meanwhile, her teammate **Rohan**, who recently transitioned from on-prem systems to Azure, sighed:

> "I spun up a VM for the **IT department** last week, but now I can't find it. Everything looks the same..."

Their team lead, **Ayesha**, stepped in with a smile.

> "Time to clean the cloud closet. Let’s try **Azure resource tags** — like sticky notes for your infrastructure.”

---

## 💼 The Real-World Problem

The organization was growing fast, and so were its cloud resources. But the lack of structure was slowing things down. Bills were getting hard to trace. Environments were overlapping. Audit reports? A nightmare.

That’s when **Ayesha** proposed they tackle this hands-on — starting with a small lab to understand how tagging could bring clarity to chaos.

This wasn’t just a lab — it was about **regaining control**.

---

## 🛠️ First Step: Build the Playground

**Sofia** started with creating a small test environment — a **virtual machine** in a new **resource group** called `rg-nextgen-sofia`.

Following best practices, she used:

* **Image**: Windows Server 2019
* **Size**: B1s (small but efficient)
* **Disk**: Standard SSD

Everything was clean, simple, and neatly named. No Azure Spot instance. No open ports. Just the basics — ready to be tagged.

---

## 🏷️ Tag It Like You Mean It

With the VM deployed, **Rohan** jumped in to test tagging.

They added a tag:

* **Name**: `Department`
* **Value**: `IT`

It was as easy as filling a sticky note — but this one actually worked at scale.

A quick smile spread across Sofia’s face.

> “Now we know who this belongs to — no more guessing games.”

They imagined a future where every resource in their company was tagged by **department**, **project**, and **owner**. Suddenly, the Azure world felt a little more manageable.

---

## 🔎 Filtering the Fog

To test it out, the team headed back to the **Resource Groups** view. Using the **filter tool**, they selected:

* **Tag**: `Department`
* **Value**: `IT`

Just like magic 🪄, only the relevant resources appeared.
What had once looked like a cloud jungle now felt like a **garden with paths and labels**.

---

## 🧹 One Last Task: Clean-Up with Confidence

Since this was a learning lab, the team deleted everything they had built — but this time, they **knew exactly what they were deleting**.

> “I finally feel like I can see my Azure environment clearly,” said Rohan, a little surprised.

Ayesha gave a thumbs up:

> “And that’s exactly why tags matter — not just for you, but for your team, your finance folks, your auditors… even your future self.”

---

## 🚀 Why This Lab Matters

This lab wasn’t about spinning up just another VM — it was about **teaching discipline in the cloud**.

In real-world cloud environments:

* **Tags reduce confusion**
* **Enable cost tracking**
* **Help with automation**
* And keep your environment **organized, accountable, and clean**

For a growing company like **NextGenOps**, this wasn’t optional — it was essential.

---

## 📣 Final Thoughts from the Team

As the team wrapped up the session, Sofia paused and said:

> “You know… this might be the first time Azure felt like *mine*. I can name it. Sort it. Search it.”

> “And *delete* it with confidence,” Rohan laughed.

The group shared a high-five.
A small lab. A big shift.

---

> **Clarity isn’t just a technical skill — it’s a leadership move. Keep building with intention.**
> — Jamalu
> — **Siraat AI Academy**

---


