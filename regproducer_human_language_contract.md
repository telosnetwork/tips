# Telos regproducer Human-language Contract.   	

## 1. Intent of Action - {{ regproducer }}
The intent of the {{ regproducer }} action is to register an account as a block producer candidate, to enumerate the obligations and rules of block producer candidacy and operation, and to inform producers about the penalties and penalty process for violation of these rules and obligations.

## 2. Nomination
I, {{producer}}, hereby nominate myself for consideration as an elected block producer. This nomination includes the express agreement to all terms of this human-language contract by the block producer candidate entity and all of its owners.

## 3. Disclosure of Producer Key
If {{producer}} is selected to produce blocks by the eosio contract, I will sign blocks with {{producer_key}} and I hereby attest that I will keep this key secret and secure.

## 4. Penalty Enforcement via ‘enforecebprules’ Contract
I acknowledge that if I fail to fulfill the obligations or violate the rules set forth in this contract, that the other block producers shall impose upon me the penalties enumerated for the corresponding violation. The vehicle for this enforcement shall be the ‘enforcebprules’ contract which may be executed by any block producer to allege a violation of the rules and present evidence of the violation. The ‘enforcebprules’ contract shall alert me if I am accused of a violation and I will have a maximum of six hours to post a rebuttal to the evidence presented against me prior to other block producers voting. If a 2/3+1 majority of elected block producers votes that they are convinced the infraction did occur, then the associated penalty shall be imposed.

## 5. Obligation to Enforce Block Producer Rules
I acknowledge that at any time I serve as a block producer, I shall enforce the rules and associated penalties set forth in this human-language contract when another block producer reports evidence of an alleged violation in the form of executing the ‘enforcebprules’ contract. When ‘enforcebprules’ is executed by any block producer, I have the obligation to assess all evidence presented both by the accuser and the accused and vote whether the evidence persuades me that the alleged infraction has occurred. I shall, within 12 hours of the contract being first executed in the case, cast a definitive yes or no vote via the ‘enforcebprules’ contract as to whether I am convinced the violation occurred. Failure to vote within 12 hours shall place me in violation of the block producer minimum requirements until either I vote or the ‘enforcebprules’ contract is enacted by a majority of 2/3+1 of all block producers. If I discover evidence of a violation of this human-language contract by another block producer, I am obligated to execute the ‘enforcebprules’ contract and provide evidence of the alleged violation as quickly as I may fully investigate and collect evidence.

## 6. Resignation and Removal for Inability to Perform Obligations
If {{producer}} is unable to perform obligations under this human-language contract I will resign my position by resubmitting this contract with the null producer key. If {{producer}} fails to resign when unable to perform said obligations, {{producer}} shall be removed after 30 minutes of non-performance by automated contract or by actions of the remaining block producers.

## 7. Objectively Valid and Invalid Blocks
I acknowledge that a block is “objectively valid” if it conforms to the deterministic blockchain rules in force at the time of its creation, and is “objectively invalid” if it fails to conform to those rules.

## 8. Signing of Messages with Producer Key
{{producer}} hereby agrees to only use {{producer_key}} to sign messages under the following scenarios: proposing an objectively valid block at the time appointed by the block scheduling algorithm, pre-confirming a block produced by another producer in the schedule when I find said block objectively valid, confirming a block for which {{producer}} has received 2/3+1 pre-confirmation messages from other producers. Apparent intentional violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 90 days on first offence or 365 days on second or subsequent offenses. I may also be liable for liabilities due to this action.

## 9. Acceptance of Liability and Damages
I hereby accept liability for any and all provable damages that result from my: signing two different block proposals with the same timestamp with {{producer_key}}, signing two different block proposals with the same block number with {{producer_key}}, signing any block proposal which builds off of an objectively invalid block, signing a pre-confirmation for an objectively invalid block, signing a confirmation for a block for which I do not possess pre-confirmation messages from 2/3+1 other producers. Apparent intentional violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 90 days on first offence or 365 days on second or subsequent offenses. I may also be liable for liabilities due to this action.

## 10. Malicious Collusion
I hereby agree that double-signing for a timestamp or block number in concert with 2 or more other producers shall automatically be deemed malicious and subject to a fine equal to the past year of compensation received, and other damages. An exception may be made if {{producer}} can demonstrate that the double-signing occurred due to a bug in the reference software; the burden of proof is on {{producer}}. Apparent intentional violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 365 days on first offence or 5 years on second or subsequent offenses. 

## 11. Interference with Block Producer Election Process
I hereby agree not to interfere with the producer election process. I agree to process all producer election transactions that occur in blocks I create, to sign all objectively valid blocks I create that contain election transactions, and to sign all pre-confirmations and confirmations necessary to facilitate transfer of control to the next set of producers as determined by the system contract. Apparent intentional violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 90 days on first offence or 365 days on second or subsequent offenses. 

## 12. Adherence to Block Producer Minimum Requirements
I hereby acknowledge that violation of the block producer minimum requirements shall be cause for disqualification from service of {{producer}} as a block producer until {{producer}} is once again in compliance. Compliance with the block producer minimum requirements shall be monitored and enforced by smart contract, oracle, or other objective, disinterested party as the network shall initially designate on network launch or subsequently amend. The current block producer minimum requirements shall be recorded on chain at a publicly disclosed address.

## 13. Authentication of Network Peers
The community agrees to allow {{producer}} to authenticate peers as necessary to prevent abuse and denial of service attacks; however, {{producer}} agrees not to discriminate against non-abusive peers. Apparent intentional violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 30 days on first offence or 180 days on second or subsequent offenses. 

## 14. Fair Dealing in Processing Transactions
I agree to process transactions on a first-in, first-out, best-effort basis and to honestly bill transactions for measured execution time. Apparent intentional violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 30 days on first offence or 180 days on second or subsequent offenses.

## 15. No Reordering Transactions to Profit
I {{producer}} agree not to manipulate the contents of blocks in order to derive profit from the order in which transactions are included the hash of the block that is produced. Apparent intentional violation of the preceding, as judged by a 2/3+1 majority of all block producers, shall be cause for my removal from all service as a block producer for 90 days on first offence or 365 days on second or subsequent offenses.

## 16. Ownership
I, {{producer}}, hereby agree to disclose and attest under penalty of perjury all ultimate beneficial owners of my ownership entity who own more than 5% and all direct shareholders. I will not misrepresent ownership or the penalty status of any owners in an attempt to evade penalties. Misrepresentation includes misspelling or using an alternate writing of the same person or entity’s name, listing the name of an entity owned or controlled more than 5% by a listed owner, listing the name of any person or entity who is not the true beneficial owner or their fiduciary. Apparent intentional violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 90 days on first offence or 365 days on second or subsequent offenses.

## 17. Ownership of More than One Block Producer
I acknowledge that no entity, whether an individual, corporation, nonprofit, or decentralized organization, shall own any interest in more than one block producer candidate at any time. For the purpose of this paragraph, spouses, parents, children and siblings of an owner shall be considered the same as the owner. Any block producer with any owner currently under penalty by the ‘enforcebprules’ contract is disqualified for the entire term of the penalty.

## 18. Producing Blocks on Schedule
I, {{producer}}, agree not to produce blocks before my scheduled time unless I have received all blocks produced by the prior producer. Apparent intentional violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 30 days on first offence or 90 days on second or subsequent offenses.

## 19. Producing Blocks on Accurate Time
I, {{producer}}, agree not to publish blocks with timestamps more than 500ms in the past or future unless the prior block is more than 75% full by either CPU or network bandwidth metrics. Apparent intentional or negligent violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 30 days on first offence or 90 days on second or subsequent offenses.

## 20. Setting Accurate RAM Supply
I, {{producer}}, agree not to set the RAM supply to more RAM than my nodes contain. Apparent intentional violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer for 30 days on first offence or 90 days on second or subsequent offenses.

## 21. Voter-confusing Block Producer Names
Block producer candidates shall not register names intended or deemed likely to create confusion among Telos voters as to their identity compared to other Telos block producers. Priority of names will be granted to the block producer candidate who first registered on the Telos network or Telos pre-launch testnet. Until the Telos network has been activated for six months, the same priority will be granted to block producer candidates who registered a block producer name during the first 30 days of the original EOS mainnet. Violation of the preceding, as judged by a majority of 2/3+1 of all block producers, shall be cause for my disqualification from all service as a block producer until a new block producer name is registered. There shall be no further penalty for this violation.

## 22. Amending ‘regproducer’ Human-language Contract
I acknowledge that the terms of this human-language contract may be amended from time to time by Telos owners voting on the ‘ratifyamend’ contract as described in the Telos Network Operating Agreement. If I do not consent to the new terms of the amended human-language contract, I must remove my block producer candidate from service. Remaining registered as a block producer more than 24 hours after this human-language contract is amended indicates my acceptance of the new version.

## 23. Definitions
The term “block producer” shall be deemed to mean one of the up to 21 block producer candidates actually validating transactions on the Telos network, including any non-elected block producer candidate serving the validating function due to the failure of another block producer, or rotation schemes intended to aid network health, or any other reason. The term “second or subsequent offences” shall refer to violations of any offence described within the same paragraph of this human-language contract, but not to offences described in different paragraphs. A second or subsequence offence shall only apply if a majority of 2/3+1 block producers voted to impose a penalty on a previous alleged offence. A majority of “2/3+1” shall mean a number greater than or equal to 2/3rds of the total number plus one additional. For clarity, when the total is 21 block producers, a 2/3+1 majority would require the votes of 15 block producers. A “human-language contract” means the portion of a smart contract that is written in a human language such as English or Korean as opposed to a computer language such as C++, with the goal of clearly expressing the intent of the transaction between the user executing the contract and the person or entity that controls it.
