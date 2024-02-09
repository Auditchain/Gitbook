---
description: Democracy is a full time job so don't forget to vote!
---

# Governance

The core contracts in this version feature on chain governance which allows the community of AUDT users to propose changes to be made to the protocol. The governance contract deployed in this version is a fork of [Compound](https://compound.finance/docs/governance).

Proposals may be made through the delegation of a minimum of 1% of the number of AUDT in circulation to a delegate. A holder of AUDT may delegate to themselves or to another delegate.&#x20;

### Member Contract&#x20;

The Member contract is the contract that governs the terms of the engagement between economic entities or curators and validators.&#x20;

The governance functions for engagements between economic entities, curators and validators allow the following changes:&#x20;

* Amount of rewards paid to validators through subsidies
* Amount of rewards paid by the reporting entity with the amount emitted through subsidies&#x20;
* The percentage of the proceeds from data subscriptions allocated between economic entities and validators&#x20;
* Changes to the minimum amount of AUDT required to be on deposit for continued compliance by a reporting entity (fair warning) - This function provides a warning to the reporting entity to top up or add additional AUDT when the balance of a reporting entity account decreases to a certain level

### Cohort Factory

Governance allows changes to the minimum number of validators in a cohort for each category of assurance. The initial number is set at three.

### Cohort

Changes may be made to the percentage of validators in a cohort that are required to perform a validation in order for a validation to occur.
