# 🔍 Policy with Purpose: How Azure Keeps Teams on Track

## Point 5 of 9 – Inside the Lab: A Guided Azure Walkthrough

### Hands-On Moment: Executing the Steps in a Real Azure Environment

Welcome to the real world of **cloud governance** — where intentions meet enforcement. In this walkthrough, we join the team at **CloudCore Labs** as they take on a practical challenge: using **Azure Policy** to enforce location compliance for new resources.

Characters on this journey:

* **Ayesha** – Cloud Administrator, thoughtful and structured
* **Omar** – Junior Engineer, curious and quick on his feet
* **Rohan** – Lead Architect, always looking for governance gaps

Let’s dive into how this team tackled the lab!

---

### 🔹 Step 1: Logging Into the Azure Portal – The Starting Gate

The team began their day with coffee, laptops, and login screens.

**Ayesha** opened the **Azure Portal**, reminding Omar, “You’ll find everything in the search bar — it's your best friend here.”

With credentials ready, the team was inside their shared **CloudCore Labs** tenant, eager to enforce their location strategy for deployments.

---

### 🔹 Step 2: Navigating to Azure Policy – The Brain of Compliance

Using the portal’s top search bar, **Omar** typed `Policy` and landed inside **Azure Policy**, the brain of their organization’s compliance engine.

He clicked the **Scope selector** and chose their resource group: `rg-cloudcore-omar`. This scope ensures that only resources within this group are affected by the policy they’ll build.

> “It’s like telling Azure — only enforce this rule in *this room*, not the whole building,” said **Rohan**, clarifying the value of scoping.

---

### 🔹 Step 3: Finding the Right Policy – Built-In and Battle-Tested

Next, they searched the **Definitions** tab for "Allowed locations" and found the **built-in policy** that restricts resource creation to specific Azure regions.

They reviewed it briefly. “This makes sure our resources stay where compliance says they should,” noted **Ayesha**, referencing the UK-specific data residency requirements their company follows.

---

### 🔹 Step 4: Assigning the Policy – Tuning the Rule

After clicking on the policy, **Omar** chose **Assign policy**. In the **Basics tab**, they gave it a name: `Allow UK South for rg-cloudcore-omar`, and wrote a quick description.

They made sure **Policy enforcement** was turned **on**, then moved to the **Parameters tab**, choosing `UK South` as the only allowed location.

Review. Create. Policy deployed. ✅

> “Feels like we just set up a guardrail,” smiled Omar. “One that actually nudges us toward doing the right thing.”

---

### 🔹 Step 5: Testing the Policy – Trying to Break the Rules

Now it was time to test. They headed to **Virtual Networks**, clicked `+ Create`, and tried setting up a new VNet: `vnet-cloudcore-lab01` in the same resource group — but with **East US** as the region.

Boom. ❌ **Validation failed.** Azure rejected the deployment. They opened the error message, and sure enough, the **policy denied it**.

> “That’s policy-as-code in action,” said Rohan. “Clean. Quick. No confusion.”

---

### 🔹 Step 6: Fixing the Region – Letting the Good Pass Through

They changed the region to `UK South`, hit `Review + create`, and this time — success. 🚀

Azure accepted the deployment. The VNet was live. The team had proved that the policy both blocked and allowed as expected.

Ayesha nodded: “We just built something that helps others avoid mistakes. That’s a quiet kind of leadership.”

---

### 🔹 Step 7: Cleanup – Leaving No Trace

Once the test was validated, the team deleted all created resources to maintain a clean lab environment.

It wasn’t just about the test — it was about practicing discipline, even in temporary workspaces. Clean cloud, clear mind.

---

### 🔹 Why It All Mattered – Big Picture Reflections

This lab taught them how **Azure Policy** empowers teams to govern without micromanaging.

Instead of checking every resource manually, they created a framework that did the checking for them — saving time, enforcing compliance, and promoting best practices.

> “We didn’t just set rules,” said Rohan. “We set direction.”

---

> *It’s not just about controlling outcomes — it’s about creating clarity before chaos has a chance to form.*  
> — Jamalu  
> — **Siraat AI Academy**

---

