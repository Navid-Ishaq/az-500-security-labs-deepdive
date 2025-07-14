# 01 Creating Azure Resource Locks

### 🔹 Point 9 of 9: Comic-Style Wrap-Up — Learn, Lock, Laugh!

---

# 🎨 **Today Lab: Creating Azure Resource Locks**  
### 🛡️ Main Title: **“Lock It Like It’s Hot!” — A Cloudy Day at BrightOps Solutions**

---

## 😱 Uh-oh, a Problem!

At **BrightOps Solutions**, something tragic almost happened!  
**Jordan**, the ever-curious intern, *accidentally deleted a virtual machine* in the middle of a client demo. “Oops?” he whispered, sweat dripping.  
**Ayesha**, the senior cloud admin, sighed. “That’s the third one this week…”

So the team gathered around their laptops like tech Avengers, determined to make sure this *never* happens again.

---

## 🛠️ Time to Get to Work!

“Let’s spin up a safe test VM,” said **Omar**, the chill security analyst.  
They opened the **Azure Portal**, clicked **Create a Resource**, and chose **Virtual Machine**.

With a few clicks, they launched **Ubuntu Server 20.04**, named it `vm-brightops-lock01`, and placed it inside the friendly folder `rg-brightops-safezone`.

> “This is like building a house,” Jordan grinned. “Now we just need to lock the doors!”

---

## 🧰 Tools in Action!

Next up: adding a **Delete Lock**.

Under the VM’s **Settings > Locks**, they added one named **VMDeleteLock**.  
Boom 💥 — now nobody could delete it without manually removing the lock.

Then, for extra cloud armor, they added a **Read-Only Lock** called **RGReadOnly** on the whole **Resource Group**. That meant *no changes*, *no surprises*.

“Basically,” said Ayesha, “we just bubble-wrapped our VM.”

---

## 🧪 Test Time: The Intern Strikes Again

Jordan tried deleting the VM again — just to test.  
Azure popped up with a “NOPE! This resource is locked.” 🚫

> “That’s it!” Omar laughed. “Jordan-proof cloud protection, activated.”

The whole team high-fived. Not because someone made a mistake, but because now they had **a way to prevent it.**

---

## 🎉 Success and High-Fives!

In just 45 minutes, they:
- Created a secure **virtual machine** ✅  
- Applied a **Delete Lock** ✅  
- Locked down a **resource group** ✅  
- Tried deleting it for fun — and **Azure saved the day** ✅  

Ayesha closed her laptop. “We didn’t just build something… we protected it.”

---

> _*"Even the smallest locks can guard the biggest lessons — and the trust that grows with them."_  
> — Jamalu  
> — **Siraat AI Academy**
---
# 🧠 Smart Summary: Comic Recap of Azure Resource Locks Lab

---

## 🎯 **Lab in a Nutshell**
In this comic-style recap, we followed **Ayesha**, **Jordan**, and **Omar** at **BrightOps Solutions** as they faced a common cloud dilemma — **accidental deletion** of a virtual machine. Their fix? Resource locks in Azure.

---

## 🔧 **Key Tasks They Completed**
- ✅ Created a VM: `vm-brightops-lock01`  
- ✅ Placed it inside a resource group: `rg-brightops-safezone`  
- ✅ Applied a **Delete Lock** to the VM (`VMDeleteLock`)  
- ✅ Applied a **Read-Only Lock** to the Resource Group (`RGReadOnly`)  
- ✅ Tested it with a deletion attempt — and Azure blocked it successfully 🎉

---

## 💡 **What They Learned**
- **Delete Locks** prevent even admin-level deletion.
- **Read-Only Locks** protect all resources in a group from being changed.
- These simple tools can **protect real production environments** from human error.
- Testing the lock behavior builds confidence in real-world deployment.

---

## 🚀 **Why It Sticks**
The comic-style storytelling made technical tasks feel:
- 🧩 More relatable  
- 🤹 Easier to retain  
- 🧠 Emotionally memorable (Oops moments included!)

---

> _*"Even the smallest locks can guard the biggest lessons — and the trust that grows with them."_  
> — Jamalu  
> — **Siraat AI Academy**

---

