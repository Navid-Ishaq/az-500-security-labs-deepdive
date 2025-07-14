# 01 Creating Azure Resource Locks

# 🔹 Point 2 of 9: Reflection — Did Ayesha and Jordan Truly Master the Art of Azure Locks?

---

# 🌈 **From Nervous Clicks to Confident Cloud Moves — Ayesha & Jordan Reflect**

The glow of a finished lab is something special — that quiet moment when you lean back, breathe out, and say, *“Wow, I actually did it.”*
At **BrightOps Solutions**, a small but mighty tech firm, **Ayesha** and **Jordan** just wrapped up their Azure lab on **resource locks**. But did they just *complete* the lab... or did they *learn* something deeper?

Let’s revisit their journey and see what really unfolded behind the scenes.

---

## 🌱 **Expectations vs Reality — “How Hard Could It Be?”**

Before diving into the lab, **Jordan** was feeling the usual “newbie nerves.” Azure still felt like a maze of menus and magic.

> “I thought it would be like setting a password and calling it a day,” Jordan admitted with a sheepish grin.
> Ayesha, always the steady voice, replied, “It’s simple, but it’s not silly. These locks protect real businesses.”

For Ayesha, this was more than a lab — it was a moment to guide someone and reinforce her own best practices. As a cloud administrator, she had seen too many *oops* moments that could’ve been avoided with a simple lock.

---

## 🧭 **Taking the First Step — Slow and Steady**

They opened the **Azure Portal**, took a deep breath, and began by creating the **MyLabVM**. Ayesha coached Jordan through the process, making sure he understood each choice.

From selecting the **Ubuntu Server 20.04 image** to choosing the **Standard SSD** and setting the strong password, they walked every step like a team hiking a new trail — double-checking the map but enjoying the scenery.

> “Hey, this isn’t so bad,” Jordan smiled after clicking “Create.”
> “Exactly,” Ayesha said. “It’s not about speed, it’s about clarity.”

---

## 💡 **Locking It Right — A Little Confusion, A Big Win**

The real moment of challenge came with **resource locks**.

> “Wait — is this lock going to freeze the whole VM?” Jordan asked nervously.
> “Good question,” Ayesha replied. “But no — a **Delete Lock** just stops accidental deletion. You can still use the VM normally.”

They clicked into **Settings → Locks**, added **VMDeleteLock**, and watched the confirmation appear. Success!

Then came the **Read-Only Lock** on the **resource group**. This one required a bit more thought.

> “So… no one can even change the tags now?” Jordan asked.
> “Right. Read-only means hands off — until we remove it,” Ayesha explained.

---

## 🎉 **The Moment of Truth — Delete Attempt Blocked!**

To test their work, they tried deleting the VM without removing the lock. Azure immediately stopped them with a friendly warning.

Jordan’s eyes widened.

> “It actually works! This is like... a superhero cape for resources.”

That small pop-up message from Azure felt like a **big milestone**. It wasn’t just code on a screen — it was **a safety net** in action. Mission accomplished.

---

## 📘 **Lessons They’ll Take Forward**

By the end of the 45-minute lab, both felt different.

**Jordan**, once hesitant, now felt empowered. He even asked Ayesha if they could apply locks to some real client resources next week. “Absolutely,” she smiled. “You’re ready.”

For **Ayesha**, this lab became more than a task. It reminded her how essential it is to bring newer teammates along — not just for knowledge, but for confidence.

> “I learned that protecting cloud resources isn’t just smart — it’s kind,” she reflected.
> “Kind to your team, your clients, and your future self.”

---

## 🌍 **What It Means in the Real World**

Later that week, the **BrightOps team** reviewed other high-risk Azure resources. Thanks to the lab, they spotted three virtual machines and two storage accounts without locks — and fixed them all in one go.

> “If we hadn’t done that lab,” said Ayesha, “we might’ve missed something important.”

It’s funny how one small lab can ripple outward — from classroom to client infrastructure.

---

## 🌟 **Confidence Level: Upgraded!**

Before:
Jordan → 😟 “I hope I don’t break something.”
Ayesha → 😊 “Let’s get through it.”

After:
Jordan → 😎 “I can explain locks to someone else now.”
Ayesha → 💪 “We’re building a stronger team.”

They didn’t just *do* the lab. They *owned* it.

---

> _"Growth doesn’t always come with noise — sometimes, it’s the quiet confidence after a job well done."_  
> — Jamalu  
> — **Siraat AI Academy**

---
# ✨ Reflection Summary: Did Ayesha & Jordan Succeed in the Lab?

---

## 🎯 **Mission Recap**
Ayesha and Jordan from **BrightOps Solutions** tackled the challenge of creating and protecting a VM in Azure using **resource locks** — and they nailed it! 💪

---

## 🧠 **What They Expected**
- **Jordan**: “It’ll be a quick task — probably just setting a password.”
- **Ayesha**: Knew the importance of locks from real-world experience, but was excited to mentor.

---

## 🛠️ **What They Actually Did**
- Created a **Virtual Machine** (`MyLabVM`) with Ubuntu.
- Applied a **Delete Lock** (`VMDeleteLock`) to prevent accidental deletion.
- Added a **Read-Only Lock** (`RGReadOnly`) to safeguard the **resource group**.
- Tried deleting the VM — and **Azure stopped them**. ✅

---

## 🚧 **Challenges Faced**
- **Understanding lock behavior**: What does "Read-Only" really block?
- Realized locks are **more powerful and specific** than they assumed.

---

## 🌱 **What They Learned**
- **Resource locks** are simple but deeply effective for protecting infrastructure.
- It’s not about avoiding mistakes — it’s about designing with safety in mind.
- **Mentorship matters** — Ayesha’s support helped Jordan go from unsure to confident.

---

## 📈 **Result**
✔️ Lab completed  
🔒 Locks applied and tested  
🌟 Confidence levels: **Leveled up!**

---

> _"What once looked like a wall was really just a door waiting for the right hands to open it."_  
> — Jamalu  
> — **Siraat AI Academy**

---


