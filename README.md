# 🏟️ Tactical Style & Style Imposition Analysis  
## UEFA Champions League 2024–25

This project analyzes **how teams control matches** in the **2024–25 UEFA Champions League**, using squad-level data from **FBref**.

Instead of relying on possession or shot volume alone, the notebook introduces a framework that separates:

- **Tactical Style** → how teams *want* to play  
- **Style Imposition** → how effectively teams *force* that style onto opponents  

The result is a clearer, more tactical understanding of match control at the elite level.

---

## 📊 Key Concepts

### Tactical Style
Describes a team’s preferred way of playing, based on:
- Possession share  
- Shot and chance creation volume  
- Ball progression (progressive passes & carries)  
- Creative actions (KP, SCA, GCA)  
- Defensive involvement  

Teams are grouped into **style archetypes** (e.g. possession controllers, transitional attackers, defensive controllers).

---

### Style Imposition Index
A composite metric measuring **tactical authority**, not aesthetics.

It captures:
- Territorial control  
- Chance creation authority  
- Defensive disruption  
- Resistance to opponent influence  

**Interpretation**
- Positive values → team imposes its game  
- Near zero → adaptive / balanced  
- Negative values → opponent-driven matches  

---

## 🧠 Core Insight

> Tactical dominance ≠ possession  
> Tactical dominance ≠ attacking volume  
>  
> **Tactical dominance = Style × Imposition**

This framework explains why stylistically similar teams can experience very different match outcomes.

---

## 📁 Project Structure

```text
.
├── analysis.ipynb        # Main analysis notebook
├── SIData.csv            # Processed squad-level dataset
├── README.md             # Project documentation
