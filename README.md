<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png"
       alt="UNIWA"
       width="150"
       style="margin-bottom: 10px;" />
</p>

<p align="center" style="line-height: 1.5;">
  <strong style="font-size: 18px;">UNIVERSITY OF WEST ATTICA</strong><br>
  <span style="font-size: 14px;">SCHOOL OF ENGINEERING</span><br>
  <span style="font-size: 14px;">DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS</span>
</p>

<hr style="width: 60%; margin: 20px auto;"/>

<p align="center" style="font-size: 16px; font-weight: 600;">
  Analysis and Design of Information Systems
</p>

<h1 align="center" style="letter-spacing: 1px; margin-top: 10px;">
  Bank Transaction Analysis and Design
</h1>

<p align="center" style="margin-top: 20px; line-height: 1.8;">
  <strong style="font-size: 16px;">Vasileios Evangelos Athanasiou</strong><br>

  <a href="https://github.com/Ath21" target="_blank"
     style="text-decoration: none; margin: 0 6px; padding: 6px 12px;
            border-radius: 6px; background-color: #24292e; color: #ffffff;
            font-size: 13px;">
    GitHub
  </a>

  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank"
     style="text-decoration: none; margin: 0 6px; padding: 6px 12px;
            border-radius: 6px; background-color: #0a66c2; color: #ffffff;
            font-size: 13px;">
    LinkedIn
  </a>
  <br>

  <span style="font-size: 13px;">Student ID: 19390005</span>
</p>

<p align="center" style="margin-top: 16px; font-size: 14px;">
  <strong>Supervisor:</strong> Theodosios Pavlidis<br>
  <span style="font-size: 13px;">Special Technical Laboratory Staff</span><br>

  <a href="https://ice.uniwa.gr/emd_person/17586/" target="_blank"
     style="text-decoration: none; padding: 6px 14px;
            border-radius: 6px; border: 1px solid #555;
            color: #333; font-size: 13px; display: inline-block; margin-top: 6px;">
    UNIWA Profile
  </a>
</p>

<p align="center" style="margin-top: 20px; font-size: 13px; color: #555;">
  Athens, December 2022
</p>



## Overview

This repository contains a comprehensive study of a **Cash Withdrawal banking transaction procedure**, developed for the course **“Analysis and Design of Information Systems”** at the **University of West Attica (UNIWA)**.

The project analyzes the process from the **initial client arrival** to the **final cash delivery**, using multiple modeling techniques to represent **data flow**, **decision logic**, and **organizational roles**.

---

## Table of Contents

| Section | Folder | Description |
|------:|--------|-------------|
| 1 | `docs/` | Project documentation for the Bank Transaction system |
| 1.1 | `docs/Bank-Transaction.pdf` | English documentation describing the bank transaction process |
| 1.2 | `docs/Τραπεζική-Συναλλαγή.pdf` | Greek documentation of the bank transaction process |
| 2 | `diagrams/` | Exported diagrams illustrating system workflows |
| 2.1 | `diagrams/A2.png` – `A8.png` | PNG diagrams representing different stages of the transaction process |
| 3 | `visio/` | Editable Microsoft Visio diagrams |
| 3.1 | `visio/A2.vsdx` – `A8.vsdx` | Visio source files for process modeling diagrams |
| 4 | `idef3vssx-master/` | IDEF3 stencil and example resources |
| 4.1 | `idef3vssx-master/IDEF3_Example.vsdx` | Example IDEF3 process diagram |
| 4.2 | `idef3vssx-master/IDEF3.vssx` | IDEF3 stencil used for diagram creation |
| 4.3 | `idef3vssx-master/README.md` | Usage instructions for the IDEF3 stencil |
| 5 | `README.md` | Repository overview and project description |


---

## Methodologies Used

The documentation includes the following industry-standard system modeling techniques:

- **A1 – Verbal Analysis**  
  A detailed, step-by-step textual description of the withdrawal protocol.

- **A2 – Standard Flowchart**  
  Logical flow of actions from *Client Arrives* to either *Give Cash* or *Reject*.

- **A3 – Deployment Flowchart (Swim Lane Diagram)**  
  Separation of responsibilities between system components:
  - Client  
  - Teller  

- **A4 – EPC Chart (Event-Driven Process Chain)**  
  Representation of event sequences using logical operators such as **XOR**.

- **A5 – IDEF0 Diagram**  
  Functional analysis model focusing on:
  - Inputs  
  - Outputs  
  - Controls (e.g., Bank Policy)  
  - Mechanisms (e.g., Bank Database)

- **A6 – IDEF3 Workflow Diagram**  
  Description of the process flow and execution logic.

- **A7 – IDEF3 State Transition Diagram**  
  Modeling of state changes during the transaction lifecycle.

- **A8 – Data Flow Diagram (DFD)**  
  Visualization of how data moves through the system components.

---

## The Banking Process

The system is defined by two primary entities:

- **Client**
- **Teller**

The workflow includes the following critical checkpoints:

1. **Identity Verification**  
   The teller verifies the client’s identity using valid identification documents.

2. **Balance Check**  
   The banking system queries the database to confirm sufficient available funds.

3. **Policy Compliance**  
   The transaction is evaluated against bank policies (e.g., withdrawal limits).

4. **Finalization**  
   - If all checks pass:  
     - The transaction is logged  
     - Cash is dispensed to the client  
   - Otherwise:  
     - The request is rejected

---

## Installation Guide

Clone this repository to your local machine. 
```bash
git clone https://github.com/Analysis-of-Information-Systems/Bank-Transaction.git
``` 
