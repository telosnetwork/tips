    Title: Telos Block Producer Minimum Requirements
    Authors: J.T. Buice, Mark Cohen, Azad Halim, Jim Hewitt, Douglas Horn, Jerry Huff, Josep Rosich, Syed Mushabbar Sadiq, Sukesh, Adam Zientarski
    Adoption: Adopted by Telos Launch Group 2018-10-09
    Voting: 2018-10-09 Yes - 25, No - 0, Abstain - 0 
    Amendment: Amended by Telos Launch Group 2018-12-06
    Voting: 2018-12-06 Yes - 33, No - 0, Abstain - 1


# Telos Block Producer Minimum Requirements:
 
The intent of this document is to clarify the minimum requirements for Block Producer’s to participate in the Telos Blockchain Network (herein referred to as the “TBN”). There are multiple phases of participation, with each level having more stringent requirements than the previous - this is intended to address the growing requirements of the network over time.

The specifications stated herein are subject to revision, as well as when the network will move from stage to stage - as determined by a vote of  ⅔ + 1 of the current Block Producers at the time of the proposed revisions.

Regardless of their level of participation, to participate in the TBN at any phase - Block Producers candidates are required to provide, and abide by the following:

### A. Disclosures:

#### 1.  Block Producer Account Name

#### 2.  Block Producer Public Key

#### 3.  Block Producer Organization Info:

a. Candidate Name
          
b. Candidate Website URL
          
c. Candidate country of registration for registered entity or residence of primary owner if not a registered entity as 2-letter ISO country coded. 

d. Candidate server location(s)
         
i. Location name
                      
ii. Country as 2-letter country code
                      
iii. latitude
                      
iv. Longitude
                      
#### 4: Network Emergency Contact(s)

a. Name
          
b. email address
          
c. phone number - in a non-public, password protected, repository commonly accessible to any of the 51 paid Block Producers and Standbys.

#### 5. Block Producer Entity Ownership

Disclosure of each beneficial owner of block producer entity along with percentage of ownership. [enforced by smart contract]

Disclosure of accepted third-party identification verification service and identification hash for each beneficial owner (* to be implemented).

### B. Practices:

1. Sync with an approved NTP server at least once per 24 hours.

2. Adoption of account blacklist maintained by the Elected Arbitrators.  

## Phase One - Minimum Requirements

#### 1. Endpoints: 

a. P2P endpoint 
          
b. HTTP API endpoint
          
c. HTTPS API endpoint

#### 2: Nodes: 

a.  Testnet Node

i. Minimum RAM (per node): 8GB
          
ii. Minimum Disk (per node): 100GB

iii. A minimum of 1,200,000 blocks (approximately 7 days) of synched and registered operation of a Telos testnet block production node.

iv. Ongoing operation of a synched, registered, and publicly accessible Telos testnet block production node within 500,000 blocks (approximately 70 hours).

v. A maximum total of 1,000,000 blocks of Telos testnet non-operational time within the most recent 5,000,000 blocks (approximately 29 days). Enforcement of which commences at Telos mainnet block height 5,000,000.

   
b.  Producing Node

i. Minimum RAM (per node): 16GB
          
ii. Minimum Disk (per node): 100GB
          
iii. Firewall: Active
            
iv. Plugins: chain, producer.
      
c.  Full Node 

i. Minimum RAM (per node): 16GB
          
ii. Minimum Disk (per node): 100GB
          
iii. Firewall: Active
            
iv. Plugins: chain, chain_api
 
 
## Phase Two - Minimum Requirements
 
### 1. Endpoints:        	

a. P2P endpoint 

b. HTTP API endpoint
          
c. HTTPS API endpoint
 
### 2. Nodes

a.  Testnet Node

i. Minimum RAM (per node):  =/> current set ram + 2GB 
          
ii. Minimum Disk (per node): 150GB
          
iii. Firewall: Active

iv. A minimum of 1,200,000 blocks (approximately 7 days) of synched and registered operation of a Telos testnet block production node.

v. Ongoing operation of a synched, registered, and publicly accessible Telos testnet block production node within 500,000 blocks (approximately 70 hours).

vi. A maximum total of 1,000,000 blocks of Telos testnet non-operational time within the most recent 5,000,000 blocks (approximately 29 days).   

b.  Staging Net Node

i. Minimum RAM (per node): =/> current set ram + 2GB
          
ii. Minimum Disk (per node): 150GB
          
iii. Firewall: Active

iv. Operation of a synched, registered, and operational staging net block producer node for a period of at least 150,000 blocks (approximately 21 hours) during the most recent staging net deployment. Any period of time that a block producer’s node is unregistered or otherwise disabled or removed as the direct result of a staging net test operation shall contribute to this minimum requirement period.
 
c.  Producing Node

i. Minimum RAM (per node): =/> current set ram + 2GB
          
ii. Minimum Disk (per node): 150GB
          
iii. Firewall: Active

iv. Plugins: chain, producer
          	
d.  Full Node 

i. Minimum RAM (per node): =/> current set ram + 2GB
          
ii. Minimum Disk (per node): 150GB
          
iii. Firewall: Active
          
iv. Plugins: chain, chain_api

v. SSL Proxy


## Phase Three - Minimum Requirements

##### 1. Endpoints
 
a. P2P endpoint 
  
b. HTTP API endpoint
          
c. HTTPS API endpoint
 
##### 2. Nodes

a.  Testnet Node

i. Minimum RAM (per node):  =/> current set ram + 2GB
          
ii. Minimum Disk (per node): 300GB
          
iii. Firewall: Active

iv. A minimum of 1,200,000 blocks (approximately 7 days) of synched and registered operation of a Telos testnet block production node.

v. Ongoing operation of a synched, registered, and publicly accessible Telos testnet block production node within 500,000 blocks (approximately 70 hours).

vi. A maximum total of 1,000,000 blocks of Telos testnet non-operational time within the most recent 5,000,000 blocks (approximately 29 days).
 
b.  Staging Net Node

i. Minimum RAM (per node):  =/> current set ram + 2GB
          
ii. Minimum Disk (per node): 300GB
          
iii. Firewall: Active

iv. Operation of a synched, registered, and operational staging net block producer node for a period of at least 150,000 blocks (approximately 21 hours) during the most recent staging net deployment. Any period of time that a block producer’s node is unregistered or otherwise disabled or removed as the direct result of a staging net test operation shall contribute to this minimum requirement period.

c.  Producing Node

i. Minimum RAM (per node):  =/> current set ram + 2GB
          
ii. Minimum Disk (per node): 300GB
          
iii. Firewall: Active
          
iv. Plugins: chain, producer

d.  Full Node 

i. Minimum RAM (per node): =/> current set ram + 2GB
          
ii. Minimum Disk (per node): 300GB
          
iii. Firewall: Active
          
iv. Plugins: chain, chain_api
  
v. SSL Proxy

# Copyright:

This document is in the public domain.
