# 🚀 Aeron Systems – Internship Journey (R&D Hardware, IoT Division)

This document presents a detailed overview of my **6-month internship at Aeron Systems** as an **R&D Hardware Intern** in the IoT division.  
It reflects both the **technical case studies** I completed and the **learnings** that shaped my growth as an engineer.

---

## 📅 Timeline of My Internship

### 📌 Months 1–2: Learning & Documentation
- Transitioned from an academic lab environment to a **corporate engineering workflow**  
- Worked on **schematics, BOMs, Hardware Design Documents (HDDs), requirement sheets**  
- Supported my mentor (**Sagar Rathod**) on projects nearing dispatch (e.g., MT1K10)  
- Learned the importance of **standardized documentation, traceability, and collaboration**  
- Studied a wide range of **IoT hardware projects** to understand company portfolio  

**Key takeaway:** Documentation and process rigor are as critical as design itself.

---

### 📌 Month 2: CE Standards & Compliance
- Introduced to **CE testing protocols (IEC61000)** for product safety and compliance  
- Studied surge protection, EMC/EMI immunity, and design-for-compliance strategies  
- Worked on qualifying **SPIM1000 device** for CE certification  
- Assisted in **in-house surge protection testing**, then visited **TÜV labs** for official compliance testing  
- Observed professional compliance testing equipment and workflows  

**Key takeaway:** Learned how **safety, compliance, and reliability** are engineered into products.

---

### 📌 Months 2–4: Altium Library Development
- Assigned to consolidate fragmented **Altium component libraries**  
- Challenges: multiple versions, inconsistent parameters, duplicate parts, higher costs  
- Created a **central integrated library (~500 components)**:
  - Standardized **nomenclature and naming formats**  
  - Defined **parameter fields** (RoHS, AEC-Q200, ESD, etc.) for easier BOM generation  
  - Verified and corrected **symbols and footprints**  
  - Reviewed datasheets, checked availability, and eliminated redundant/obsolete parts  

**Outcome:** Reduced duplication, streamlined procurement, and built company-wide consistency.  
**Learning:** Deep understanding of **component selection, packages, standards, and sourcing**.

---

### 📌 Months 3–5: Solar R&D – SIMPS Method
- Assigned lead role on **SPIM1000 enhancement project**:
  - Goal: allow measurement **within solar grid** (instead of separate panels)  
  - Upgrade from basic Isc/Voc to full **IV/PV curves and Pmax** extraction  
- Conducted 20 days of research to propose **3 architectures** → presented to senior managers  
- After evaluation, **SIMPS method** chosen for simplicity and cost-effectiveness  
- Simulated designs in **Multisim**:
  - IV curve extraction  
  - Panel switching (SSR vs relays)  
- Decided on **Solid-State Relays (SSR)** over mechanical relays for reliability and speed  
- Compiled **BOM for PoC** and started hardware prototyping  

**Outcome:** 70% of PoC completed, including panel integration and partial IV curve circuit.  
**Learning:** Exposure to **corporate decision-making, trade-offs, and real-world R&D constraints**.

---

### 📌 Month 5–6: Accessory Product Development
- Independent project: design an **accessory board** for Aeron dataloggers  
- Requirements: connect **arbitrary sensor outputs** to logger inputs  
- Delivered in **1 month**:
  - Schematic in **Altium** (2–3 days)  
  - PCB routing with pours, via stitching, and industrial standards  
  - Mechanical clearance adjustments  
  - Ordered prototypes and supported testing  
  - Prepared **handover docs** for production  

**Outcome:** Accessory validated and released as a production-ready board.  
**Learning:** Understood **full product lifecycle** – concept → design → prototyping → testing → production.

---

## 🌟 Key Learnings
1. **Documentation discipline** → From BOMs to HDDs, clarity drives collaboration.  
2. **Compliance awareness** → Designing with CE/IEC61000 standards in mind.  
3. **Component selection** → Trade-offs in availability, cost, grade, and reliability.  
4. **Simulation-driven design** → Validating concepts early with Multisim.  
5. **Corporate decision-making** → How managers balance **price, performance, and feasibility**.  
6. **End-to-end product flow** → From idea to production, across multiple departments.  

---

## 📂 Case Studies in This Repo
- 📚 **Library Development** → Centralized Altium library creation  
- ☀️ **Solar R&D (SIMPS)** → Simulation + PoC for advanced solar monitoring  
- 🔌 **Accessory Product** → Full accessory board lifecycle  
- 🛡️ **Compliance Support** → Assisted in CE testing of SPIM1000  

---

## 🎯 Final Reflection
My internship at Aeron Systems transformed me from a **student engineer** into a **professional hardware engineer**.  
I learned not just how to build circuits, but how to design products that are:  
- Documented,  
- Compliant,  
- Cost-conscious,  
- Manufacturable,  
- And most importantly, **reliable in the real world**.  

This experience laid the foundation for my long-term goal of building **next-generation IoT and automation systems**.

