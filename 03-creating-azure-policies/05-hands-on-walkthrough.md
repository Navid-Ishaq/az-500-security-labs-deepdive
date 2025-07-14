# 🌐 Diagramming Azure Policy in Action

## Point 4 of 9 – Visualizing the Journey: Step-by-Step Through the Lab

### Diagram Insight: Visualizing the Lab Workflow

Here's a simple flow diagram to understand how the Azure Policy lab unfolds:

```text
+-------------------+
| Login to Azure    |
+-------------------+
         ↓
+-------------------------------+
| Open Azure Policy Service     |
+-------------------------------+
         ↓
+--------------------------------------+
| Select Scope (e.g., Resource Group)   |
+--------------------------------------+
         ↓
+-------------------------------+
| Search 'Allowed Locations'    |
+-------------------------------+
         ↓
+---------------------------+
| Assign Policy to Scope    |
+---------------------------+
         ↓
+---------------------------------+
| Set Location = 'UK South'       |
+---------------------------------+
         ↓
+-----------------------------------------+
| Try to create VNet in disallowed region |
+-----------------------------------------+
         ↓
+------------------------------+
| Validation Fails (As Expected) |
+------------------------------+
         ↓
+-----------------------------------+
| Change Region to 'UK South'       |
+-----------------------------------+
         ↓
+-----------------------+
| Validation Passes 🎉  |
+-----------------------+
```

---

### 📍 Getting Started with the Azure Policy Service

**Ayesha**, a cloud admin at **SkyBridgeTech**, logged into Azure with curiosity buzzing in her mind. "So, we’re not just building anymore," she said. "We’re governing."

Her teammate **Rohan** smiled. “Exactly. Today’s focus is policy — setting limits that protect us from mistakes before they happen.”

They began by opening the **Azure Policy** service, the control tower for defining what’s allowed — and what’s not — in their environment.

---

### 🔍 Selecting the Scope — Where Does the Policy Apply?

Before building the policy, they needed to choose where to apply it. They clicked the three-dot **Scope selector**, choosing their test resource group: **rg-labresources**.

Rohan explained it like setting house rules: “This scope is like saying — we’re only applying these policies to this one floor, not the entire building.”

---

### 🎯 Finding the Right Policy Definition

They searched for **Allowed locations**, a built-in Azure policy. This specific rule would make sure no one could accidentally deploy resources in the wrong region.

Ayesha nodded. “Perfect — this will help us stay compliant with our UK data residency requirements.”

---

### 🛠️ Assigning the Policy — Let the Rule Begin

After reviewing the definition, the team hit **Assign Policy**. They gave it a name — **Allow UK South for rg-labresources** — and ensured that **Policy enforcement** was enabled.

In the **Parameters** tab, they selected **UK South** as the only permitted location.

“Feels like we’re locking the gate on every other region,” Rohan said with a chuckle.

---

### 🚦 Testing the Policy — Let’s Try to Break It

Next, they tried creating a new **Virtual Network** in **East US**. Validation failed, just as expected.

“Azure’s stopping us before we mess up. Nice!” Ayesha smiled. “It’s like a friend nudging you: ‘Are you sure that’s allowed?’”

---

### ✅ Success — Changing to UK South

Back in the form, they changed the region to **UK South**. This time, validation passed — their VNet was successfully deployed.

“Proof that the policy works,” Rohan said. “And more importantly — that we’re in control of where things go.”

---

### 🧹 Cleanup and Wrap-Up

With the test complete, they deleted the VNet and resources. It was a short lab, but packed with governance insight.

“Policies aren’t just rules,” Ayesha reflected. “They’re boundaries that give us freedom — freedom to build confidently.”

---

> *The best controls don’t limit us — they lift us. Because now, we’re building wisely, not blindly.*  
> — Jamalu  
> — **Siraat AI Academy**

---

