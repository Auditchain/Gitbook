---
description: >-
  Game theoretical incentives for raising financial and operational integrity
  and aligning external validation behavior.
---

# Staking



### Validators

Validators may operate one or more Pacioli Nodes or delegate to Pacioli Node operators. Validators are required to stake a balance of AUDT in order to act as a validator on the Auditchain Protocol.

### Process Control Creators

Process Control creators must stake a balance of AUDT to act as a control creator on the Auditchain Protocol. Holders of AUDT may delegate to control creators and earn passive income each time controls are used.

### Reporting Entities

Reporting entities must stake a balance of AUDT to gain access to the [Luca Suite](https://docs.auditchain.finance/luca-suite/overview-of-luca-suite). See the diagrams and subtext below for a summary of the Auditchain Protocol architecture.

### Auditchain Protocol Infrastructure

<details>

<summary>Auditchain Infrastructure - Learn More </summary>

The diagram below illustrates the infrastructure of the Auditchain Protocol. The actors on the left are validators. Validators own and delegate AUDT to Pacioli Node operators on the right. They earn rewards for "backing" Pacioli Node operators. Validators may also run Pacioli Nodes.

Pacioli Node operators operate instances of the Pacioli Logic Engine on the Auditchain Protocol and validate Process Controls, financial reports and financial report models to detect inconsistencies. They also earn rewards for each validation and share the rewards with validators who delegate AUDT. See [Pacioli Logic and Rules Engine](https://docs.auditchain.finance/auditchain-protocol/pacioli-logic-and-rules-engine).&#x20;

</details>

![Auditchain Protocol Infrastructure](<../.gitbook/assets/Actors - INFRASTRUCTURE Gitbook.png>)

### Validators

<details>

<summary>The Role of a Validator - Learn More</summary>

A validator is an actor on the Auditchain Protocol who delegates AUDT to Pacioli Node operators. A validator may also act as a Pacioli Node operator and delegate to themself. A validator can be anyone who holds AUDT in their wallet. Validators play a critical role in the incentive system for supporting and expanding the Auditchain Protocol infrastructure which is supported by Pacioli Node operators.

</details>

![Validators - Delegators](<../.gitbook/assets/Actors - VALIDATORS Gitbook.png>)

###

### Pacioli Node Operators

<details>

<summary>The Role of a Pacioli Node Operator - Learn More</summary>

A Pacioli Node operator is an actor on the Auditchain Protocol who installs the [Pacioli Logic Engine ](https://docs.auditchain.finance/auditchain-protocol/pacioli-logic-and-rules-engine)and the Pacioli Agent on their own server. Pacioli Node operators make their instance of the Pacioli Logic Engine available on the Auditchain Protocol to detect and fulfill requests for validation. When a validation request is detected, the Pacioli Nodes "race" to compete with other Pacioli Node operators on the Auditchain Protocol to fulfil the validation request.

</details>

![Pacioli Node Operators](<../.gitbook/assets/Actors - NODE OPERATORS Gitbook.png>)

###

### Beta Launch - Early Enrollment - <mark style="color:red;">NOW CLOSED</mark>&#x20;

This summary describes an overview of the functional objectives of the Pacioli Node staking contracts for validator early enrollment. This version is in Beta. Use at your own risk.

You must have a Metamask wallet and be connected to Polygon mainnet.&#x20;

Delegating AUDT as a validator in this contract means that you are staking AUDT in an early enrollment period. It is reserved for those who wish to be among the first to become Pacioli Node operators or back other accountants and non-accountants who will run the [Pacioli Logic Engine](https://docs.auditchain.finance/auditchain-protocol/pacioli-logic-and-rules-engine) and node.js Pacioli Agent as a Pacioli Node operators on the Auditchain Protocol.&#x20;

The early enrollment period began on Monday 7 March, 2022 and it will end on 8 June, 2022 when the Pacioli Node infrastructure is deployed to Polygon mainnet. See [Terms and Conditions](staking-rewards.md#terms-and-conditions).

### **Security Audit**

Check out our [Certik Skynet Dashboard](https://www.certik.com/projects/auditchain) and vote safe!&#x20;

### Terms and Conditions

The enrollment period began at 16:00 UTC on Monday 7 March, 2022 and will end at 05:00 UTC on 8 June, 2022.&#x20;

Rewards for early enrollment will be captured upon deployment of the Pacioli Node infrastructure on 8 June, 2022 or earlier.&#x20;

When the enrollment period ends you will be required to migrate your stake to the newly deployed Pacioli Node staking contract referred to as `MembersHelper.sol`

You may examine the `MembersHelper.sol` contract [here](https://github.com/Auditchain/Core-Smart-Contracts-v1/blob/main/contracts/Auditchain/MemberHelpers.sol).&#x20;

After migrating your stake to `MembersHelper.sol` you may redeem your rewards.&#x20;

<mark style="color:red;">WARNING:</mark> If you redeem your AUDT during the early enrollment period, you will only be able to redeem the entire amount. You will also forfeit the rewards on the AUDT you redeem. Each address can only stake once during the enrollment period and you may only redeem the entire stake prior the expiration of the early enrollment period.&#x20;

[<mark style="color:purple;">**ENROLL NOW!**</mark>](https://auditchain.finance/staking)

### Staking Demo Video

<details>

<summary>Read More</summary>

Play the video to review the staking procedure. Did you read this entire page yet? If not please do so now.

</details>

{% embed url="https://youtu.be/Hvfv8FYc3KE" %}
Auditchain Protocol Staking
{% endembed %}

### FAQ

<details>

<summary>Frequently Asked Questions</summary>

**Q: How long do I have to remain staked?**

A: Until 8 June 2022.

**Q: What happens on 8 June 2022?**

A: You will be required to move your AUDT to the `MembersHelper.sol` contract.&#x20;

**Q: How do I move my AUDT to the MembersHelpers.sol contract?**

A: You will be prompted to click a function that automatically moves your stake to the new    contract.

**Q: When do I receive my rewards?**

A: After you move to the new `MembersHelpers.sol` contract you may redeem any amount of your stake and rewards.&#x20;

**Q: Do I still receive rewards if I redeem before 8 June, 2022?**

A: You forfeit your rewards on the AUDT you redeem before 8 June, 2022.

**Q: When will the new contracts launch?**

A: `MembersHelpers.sol` will launch on 8 June, 2022.

**Q: If I participate in early enrollment now, can I also operate a Pacioli Node?**

A: Yes. You may also operate a Pacioli Node at any time after deployment.

**Q: What is the reward for participating in early enrollment?**

A: The rate for rewards will be 12%. You will earn .002 AUDT per day for each AUDT staked.

**Q: What is the MembersHelpers.sol contract and how does it work?**

A: The MembersHelpers.sol contract is the contract that allocates rewards among validators and Pacioli Node operators.

</details>



