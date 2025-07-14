# 🎉 Comic Recap: "Region Lockdown!" with Azure Superheroes

## Point 9 of 9 – Comic Recap: Azure to the Rescue!

### Today’s Lab: Creating Azure Policies

---

### 😱 Uh-oh! The Wrong Neighborhood

At **CloudCore Labs**, things got... messy. **Omar** was spinning up a new virtual network, but accidentally picked **East US** instead of the approved **UK South**. "No big deal," he shrugged. But then: ❌ *Validation failed.*

"Did the portal just say I'm not allowed here?" Omar blinked. That's when **Sofia** peeked over his screen and gasped. "You broke the policy rules!"

---

### 🚀 Time to Get to Work!

Enter **Taylor**, the team’s resident policy whisperer. "We set up an **Azure Policy** last week, remember? It only allows deployments in **UK South** for **rg-cloudcore-lab**."

She guided Omar to the **Azure Policy** blade: *"Search 'Allowed locations', assign it to the resource group, and pick UK South. Easy peasy."*

---

### 🤖 Tools in Action!

With **Azure Policy** back in the spotlight, Omar assigned the **'Allowed locations'** policy. He filled in the assignment name, scoped it properly, enabled enforcement, and picked **UK South** in the parameters.

When he hit **Review + Create**, a little celebration emoji may or may not have popped up in his mind. ✨

---

### 🤯 Aha! That Did It!

Now it was time for revenge on that failed validation. Omar tried again to create a virtual network in **East US** — and boom, blocked again. This time he laughed: "Policy says nope!"

He switched the region to **UK South**, clicked **Create**, and voila! ✅ Success. Azure approved. Policy respected.

---

### 🎉 High-Fives and Policy Pride

"That felt powerful," Omar grinned. "Like I had a cloud security cape on."

**Sofia** nodded. "You didn’t just follow instructions. You **understood why** it matters. That’s what makes you dangerous... in a good way."

---

> *You didn’t just finish the lab — you made the cloud safer, clearer, and kinder to future-you.*  
> — Jamalu  
> — **Siraat AI Academy**

---

