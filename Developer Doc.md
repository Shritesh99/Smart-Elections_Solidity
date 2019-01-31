# Devloper Documentation for Smart Election

This file consist of Etherum's Smart Contract Function documentation for interaction with the smart contract deployed in Decentralized Etherum Blockchain Network with Web3js and Metamask.

Below are the details of smart contract deployment details with superchair person.
```
Elections contract deployed at 0x2BCac02bAAEC39522ad7eC2fD1921854cE194134
Super Chair Person - 0xbc848c44a72D878aA935CccFe3e307c4e2DB0146
```

Check out the Solidity contract [here](contracts/Elections.sol)

### Smart Elections works on three steps

- [Pre Election day](https://github.com/Shritesh99/Smart-Elections_Solidity/blob/master/Developer%20Doc.md#1-pre-elections)
- [On Election day](https://github.com/Shritesh99/Smart-Elections_Solidity/blob/master/Developer%20Doc.md#2-on-election-day)
- [Post Election](https://github.com/Shritesh99/Smart-Elections_Solidity/blob/master/Developer%20Doc.md#3-post-election)

### 1. Pre Elections

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

Comming soon...

### 3. Post Election

Comming soon...
