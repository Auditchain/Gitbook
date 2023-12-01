---
description: >-
  Pacioli: An AI logic and reasoning engine for financial and operational state
  external validation.
cover: ../.gitbook/assets/Pacioli Nodes.png
coverY: 0
---

# Pacioli Logic and Rules Engine

### **Pacioli Infrastructure**

Pacioli is the heart of the Auditchain Protocol infrastructure for artificial intelligence (AI) based financial and operational state external validation and information extraction. Pacioli is built on [SWI PROLOG](https://www.swi-prolog.org/), a proven standard and robust logic programming engine. &#x20;

Pacioli is a logic and rules engine and toolkit that is purpose built and understands global standard XBRL-based reporting scheme taxonomies, digital financial report models and financial reports.  Both API and GUI interfaces are available for Pacioli.  One GUI implementation available is an XBRL-based financial report verification toolkit, see [**Pacioli Power User Tool**](https://pacioli.auditchain.finance/tools/PowerUserTool.swinb)

### Real World Use Case

Pacioli is the network client software application on the Auditchain Protocol that understands the logic of financial reporting and the meaning conveyed by such financial reports that are represented using the XBRL global standard technical syntax.  Pacioli provides proof that XBRL-based financial reports are complete, consistent, and precise.&#x20;

Pacioli also detects internal control compliance. Internal controls are critical to a well functioning operating entity. Cryptographic reinforcements are read by Pacioli to determine if they have been tampered with or circumvented.

This [demo page](https://auditchain.infura-ipfs.io/ipfs/QmQB17k7ccp2m8NTLwyzmkTK8tJjZZea1vg54FgdsjJvC1/) is an output of a batch analysis of each of the S & P 100 annual reports filed with the Securities and Exchange Commission for all of the 100 reporting entities that comprise of the S & P 100.&#x20;

### State Condition&#x20;

Compliance with each internal and disclosure control is color coded for easy identification and remediation.&#x20;

<figure><img src="../.gitbook/assets/State Condition.png" alt=""><figcaption></figcaption></figure>

### Pacioli Agent - Web3 Enabled&#x20;

Pacioli can be deployed to perform tasks that are consistent with [CEAOB](https://commission.europa.eu/system/files/2021-11/211109-ceaob-esef-guidelines-auditors\_en.pdf) guidance for auditors in the European Union and as a Web3 tool to validate the articulation of the financial state of an operating entity or financial intermediary in machine-readable form, based on their financial reporting style within a financial reporting scheme.

The Pacioli Agent is a node.js application integrated with the Pacioli logic engine. Running a Pacioli Node on the Auditchain Protocol requires the Pacioli Agent which is included in a Docker image. The Pacioli Agent uses an algorithm designed to detect financial state validation requests from users on the Auditchain Protocol. Upon detection, the Pacioli Agent initiates a race to compete to fulfill validation service requests on the Auditchain Protocol.&#x20;

The Pacioli Agent also governs how consensus is reached by Pacioli node operators on the validation of financial state on the Auditchain Protocol. The Pacioli Agent also allocates the rewards to the winning validator and to Pacioli Nodes that reach consensus on compliance with internal controls and disclosure controls across standardized rules.&#x20;

### Logic Based

Pacioli is a Web3 logic and rules-based artificial intelligence software application.  Pacioli uses machine-readable controls and deductive reasoning to determine if internal controls are in compliance and if an XBRL-based financial report is a properly functioning logical system.  The following is a brief overview of the logic currently understood by the Pacioli software application which gives you an idea of the current capabilities of Pacioli:

* **XBRL Syntax**: First you have to be sure that the technical format used to deliver the meaning conveyed follows the prescribed technical specification, in our case the XBRL technical syntax.
* **Report Model Structure**: The report model created by the accountants representing a financial report needs to follow a prescribed logical structure for such report models.  XBRL does not specify these rules.  But good practices and logic does specify what is and is not permitted and Pacioli enforces these good practices.
* **Report Mathematics**:  Financial reports need to foot and cross cast; and ‘tick and tie’ mathematically.  Pacioli performs this part of XBRL technical syntax verification.
* **Relations between financial report line items**:  Reported financial line items need to have the proper relations with other financial report line items within the report.  Sometimes referred to as “wider-narrower” relations or “general-special” relations, Pacioli performs this function.
* **Fundamental Accounting Concepts Continuity Cross Checks:** Pacioli reveals contradictions and inconsistencies between reported financial line items in a financial report. Pacioli helps you make sure you don’t inadvertently miss these accounting details.
* **Disclosure Mechanics:** Each disclosure provided within a financial report requires a pattern and number of required disclosures.  Pacioli performs the function of validating the disclosure mechanics of a financial report.
* **Reporting Checklist:** Pacioli validates a reporting checklist to verify that reports are compliant and complete.  Sometimes these reporting checklists can be very extensive.  While Pacioli does not automate the reporting checklist completely, it does provide a significant level of automation in this regard.
* **Internal Controls:** Pacioli detects compliance with implemented internal controls as well as internal control over financial reporting in order to detect and preserve the integrity of financial state.     &#x20;

The Auditchain Protocol and "Pacioli Agent" is a decentralized application and provides the Pacioli Node Infrastructure for **Pacioli Node Operators**.  Pacioli leverages the open source [**Arelle**](https://arelle.org/arelle) XBRL processor and validation is provided for the base specification of XBRL 2.1, Dimensions, Inline XBRL, Generic Linkbases, Unit Types Registry, U.S. SEC Edgar Filer Manual, IFRS Global Filing Manual and HMRC, CIPC and ESMA Filing Checks. &#x20;

### Backwards Compatible

The Auditchain Protocol is also used for private companies and issuers of digital assets. Pacioli financial report validation is backwards compatible. This means that once implemented, users are one click away from filing with regulators in any jurisdiction that mandates XBRL based financial reporting.

### **Pacioli Toolkit**

* [Accounting Equation](http://accounting.auditchain.finance/demonstrations/ae/index.html)
* [FASB's SFAC 6, Elements of Financial Statements](http://accounting.auditchain.finance/demonstrations/sfac6/index.html)
* [SFAC 6 PLUS (includes Net Assets = Assets - Liabilities)](http://accounting.auditchain.finance/demonstrations/sfac6plus/index.html)
* [Common Elements of Financial Report (Four Statement Model)](http://accounting.auditchain.finance/demonstrations/common/index.html)
* [MINI Financial Reporting Scheme](http://accounting.auditchain.finance/demonstrations/mini/index.html)
* [PROOF](http://accounting.auditchain.finance/demonstrations/proof/index.html)

