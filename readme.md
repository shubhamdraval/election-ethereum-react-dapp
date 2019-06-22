# Voting Project

## Introduction

This voting project is based on Indian Election Process.

There are 2 contracts. First is ElectionFactory and Second is Election.
All the Election will be created using ElectionFactory.

This Dapp is for education purpose not for any production.

Server side Web3js is used for this Dapp.
All the transaction will be signed by server.

Client side Web3js will be added soon.

Following are the work still not completed:

1. Revert message from contract is not replicated on React application.
2. It is assumed that in Every consituency one party must get majority votes.
3. Form Validation is not implemented.

## Election

Every election is active for n minutes. While deploying a new Election duration of election in mins and name of the election must be passed.

All the Create operation(Create Consituency, Voter, Candidate) and Close Election will be done by the Admin only.

Admin can't be a voter or a candidate.

### Step 1:

Compile and Deploy the Election Factory from the home page. http://localhost:3000

### Step 2:

Create new Election. Pass duration of election in mins and Name of the election.

### Step 3:

Go to new Election.
Create Consituencies for the election.
Pass the consituency Id. Integer
Pass the consituency number. String

### Step 4:

Register voters and candidates.

### Step 5:

Vote Tab: Cast Vote

### Step 6:

Result Tab:

1. Close Election : Close Election
2. Election Result : Get the Election Reult
