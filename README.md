# test-payroll

*description of the project*

**Timeframe** 2026-06-16 - 2026-09-22

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/test-payroll-2026-baseline](https://cra-test-arc.canada.ca/test-payroll-2026-baseline)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-06-30

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Payroll)
    node4(Receiving payroll correspondence from the CRA)
    node5(Determine the relationship with the employer or the payer)
    node6(Calculate payroll deductions and contributions)
    node7(Remit #40;pay#41; payroll deductions and contributions)
    node8(File payroll information returns #40;slips and summaries#41;)
    node9(Payroll compliance and enforcement)
    node10(What's new and updated for payroll)
    node11(Open or manage a payroll account)
    node12(Set up and manage employee payroll information)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node3 --> node5
    node3 --> node6
    node3 --> node7
    node3 --> node8
    node3 --> node9
    node3 --> node10
    node3 --> node11
    node3 --> node12
    click node1 "https://cra-test-arc.canada.ca/test-payroll-2026/en.html" _blank
    click node2 "https://cra-test-arc.canada.ca/test-payroll-2026/en/services/taxes.html" _blank
    click node3 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll.html" _blank
    click node4 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll/file-information-returns-slip-summaries/receiving-payroll.html" _blank
    click node5 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll/determine-relationship-employer-payer.html" _blank
    click node6 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll/calculating-deductions.html" _blank
    click node7 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll/remitting-source-deductions.html" _blank
    click node8 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll/file-information-returns-slip-summaries.html" _blank
    click node9 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll/payroll-compliance-enforcement.html" _blank
    click node10 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll/whats-new-payroll.html" _blank
    click node11 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll/open-manage-payroll-account.html" _blank
    click node12 "https://cra-test-arc.canada.ca/test-payroll-2026/en/revenue-agency/services/tax/businesses/topics/payroll/set-up-new-employee.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node3,node4,node5,node6,node7,node8,node9,node10,node11,node12 inscope
    classDef ismoved fill:#eab308,color:#000
    class node10,node11,node12 ismoved
```
