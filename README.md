<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Analysis and Design of Information Systems</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  BANK TRANSACTION ANALYSIS AND DESIGN
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  Supervisor: Theodosios Pavlidis, Special Technical Laboratory Staff
</p>

<p align="center">
  Athens, December 2022
</p>


## Overview

This repository contains a comprehensive study of a **Cash Withdrawal banking transaction procedure**, developed for the course **“Analysis and Design of Information Systems”** at the **University of West Attica (UNIWA)**.

The project analyzes the process from the **initial client arrival** to the **final cash delivery**, using multiple modeling techniques to represent **data flow**, **decision logic**, and **organizational roles**.

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

## Contents

| Section | Title                               | Pages |
|--------:|-------------------------------------|:-----:|
| A1      | Verbal Analysis                     | 4–5   |
| A2      | Flowchart                           | 6–7   |
| A3      | Deployment Flowchart                | 7–8   |
| A4      | EPC Chart                           | 8–9   |
| A5      | IDEF0 Diagram                       | 9–12  |
| A6      | IDEF3 Workflow Diagram              | 12–13 |
| A7      | IDEF3 State Transition Diagram      | 13–14 |
| A8      | Data Flow Diagram                   | 14–15 |

---