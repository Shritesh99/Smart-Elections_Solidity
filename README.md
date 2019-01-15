# Smart Elections.

### Smart Elections Based on Decentralised Ethereum Blockchain Network.

### An attempt to improve India's current election system using Ethereum Blockchain Network.

### Server side Repository [here](https://github.com/siddharthshah3030/Smart-Elections-Server)

### Voting Machine Repository [here](https://github.com/utkarshchandrakar/smart-elections)

<p align="center">
  <img src="https://github.com/Shritesh99/Smart-Elections_Solidity/blob/master/imgs/Canvas%202.jpg" />
</p>

### This Repository consist of etherum side smart contract code for Smart Elections.

<p align="center">
  <img src="https://github.com/Shritesh99/Smart-Elections_Solidity/blob/master/imgs/Canvas%204.jpg" />
</p>

## Workflow:-

### 1. Pre Elections

#### Election Commision of India's Head or Admin creates a smart contact.

```
Elections contract deployed at 0x07913931574f9291fB3a469a073b4BC3Ae3bAA46.
Super Chair Person - 0xbc848c44a72D878aA935CccFe3e307c4e2DB0146
```

#### For Getting Super Chaiperson

```
getSuperChairperson()
```

##### Returns:

```
0xbc848c44a72D878aA935CccFe3e307c4e2DB0146 # Address of Super Chair Person
```

#### For Changing Super Chaiperson

```
setSuperChairperson(address superChairPersonNew) # Called by Super Chair Person Only
```

#### For Adding Party

```
addParty(uint partyID) # Called by Super Chair Person Only
```

#### For Updating Party Id

```
updateParty(uint partyID, uint partyIDnew) # Called by Super Chair Person Only
```

#### For Getting All Parties

```
getParties() # Called by Super Chair Person Only
```

##### Returns:

```
uint[]: 100,200,300 # Party ids
```

#### For Adding Party

```
addParty(uint partyID) # Called by Super Chair Person Only
```

#### For Number of parties

```
getNumOfParties() # Called by Super Chair Person Only
```

##### Returns:

```
uint: 10 # Number of parties
```

#### For Geting Party Votes By Campaign

```
getPartyVotesByCampaign(uint partyID, address Campaign) # Called by Super Chair Person Only
```

##### Returns:

```
uint: 100 # Votes
```

#### For Geting Party All Votes

```
getPartyVotes(uint partyID) # Called by Super Chair Person Only
```

##### Returns:

```
uint: 1000 # Votes
```

#### For Geting Party's Candidate By Campaign

```
getPartyCandidatesByCampaign(uint partyID, address campaing) # Called by Super Chair Person Only
```

##### Returns:

```
uint: 1000004 # Candidate ID
```

#### For Geting Number of Party Candidates

```
getPartyCandidatesCount(uint partyID) # Called by Super Chair Person Only
```

##### Returns:

```
uint: 8 # Party candidates
```

#### For Get Party's All Candidates

```
getPartyCandidates(uint partyID, address campaing) # Called by Super Chair Person Only
```

##### Returns:

```
uint[]: 1000004,1000005 # Candidate IDs
```

#### For All Chairpersons

```
getChairpersons() # Called by Super Chair Person Only
```

##### Returns:

```
address[]: scdcmskdmc,sdsjncjd # Chairperson's addresses
```

#### For Getting all Campaigns

```
getElectionCampaigns() # Called by Super Chair Person Only
```

##### Returns:

```
address[]: sdsfcsdfd,sadsaasd  # Campaing addresses
```

#### For Creating Election Campaigns

```
crateElectionCampaign(address campaign) # Called by Super Chair Person Only
```

##### Returns:

```
address: scmsdknckdnkcn  # Campaign addresses
```

### 2. On Election Day

### 3. Post Election
