# Filecoin Plus Application Comment Templates

## LDN

## _Datacap Request Trigger Comment_

\-  This is a manual comment triggered by Root Key Holders. In order to trigger this comment, the necessary information in the application must be filled in completely and correctly.

```
## Datacap Request Trigger

#### Total DataCap requested 
> 5PiB

#### Expected weekly DataCap usage rate 
> 100TiB 

#### Client address
> f1o7z3hrmxthl2311k31hnoabk2bmmveg6aoomatv52hq
```

## _DataCap Allocation Requested Comment_

\- This comment is made by the LDN bot after the Datacap Request Trigger message has been created.

```
## DataCap Allocation requested

#### Multisig Notary address
> f01858410

#### Client address
> f172zurpjgt321213j11oka5q3e375zakyihqw5uhdia

#### DataCap allocation requested
> 200TiB

#### Id
> 6bbdae0f-c6fc-498f-a587-cb6a534d99a2
```

## _Request Proposed Comment_

\- This comment is triggered by the notaries using the filplus website. The first message is called the proposal message. 

```
## Request Proposed
Your Datacap Allocation Request has been approved by the Notary

#### Message sent to Filecoin Network
>bafy2bzacec7gf6x131241w3fzgs76ppn3mgtojntd5tvqrrmedvcqciw5tghjps

#### Address 
> t1rbfyvy12313131zd5xcouqjx22juucdj3xbwtro2crwq

#### Datacap Allocated
> 50TiB

#### Signer Address
> t1gechnbs312312bqan4q2dwjsicbh25n5xvvdzhqd3y

#### Id
> ffbab51c-2c7c-4a0e-b0b7-e2d4e7f86875

#### You can check the status of the message here: https://filfox.info/en/message/bafy2bzacec7gf6xycdqw3fzgs76ppn3mgtojntd5tvqrrmedvcqciw5tghjps
```

## _Request Approved Comment_

\- This comment is triggered by the notaries using the filplus website. The second message is called the approval message. 

```
## Request Approved
Your Datacap Allocation Request has been approved by the Notary

#### Message sent to Filecoin Network
>bafy2bzacec7gf6w3fz321gs76ppn3mgtojntd5tvqrrmedvcqciw5tghjps

#### Address 
> t1rbfyvybljzd5xcouqjx22juucdj3xbwtro2crwq

#### Datacap Allocated
> 50TiB

#### Signer Address
> t1ge31nbsl123123an4q2dwjsicbh25n5xvvdzhqd3y

#### Id
> ffbab51c-2c7c-4a0e-b0b7-e2d4e7f86875


#### You can check the status of the message here: https://filfox.info/en/message/bafy2bzacec7gf6xycdqw3fzgs76ppn3mgtojntd5tvqrrmedvcqciw5tghjps
```
## _Multisig Notary Requested Comment_

\- Old template used for creating multisig. **Not used anymore**.

```
## Multisig Notary requested

#### Total DataCap requested
> 5PiB

#### Expected weekly DataCap usage rate
> 500TiB
```


## _Subsequent  Allocation Comment_

\- This comment is made by the bot with subsequent allocation number information.

```
## DataCap Allocation requested

### Request number 2
#### Multisig Notary address
> f01858410

#### Client address
> f166erfrtv2i31231312mmr7rykcxrz5pkzrcv5a7ry

#### DataCap allocation requested
> 100TiB

#### Id
> 9ee93a68-16e9-4b1e-b7c8-bdd16a953160
```

## _Stats & Info Comment_

\- This comment gives stats and information about the request.

```
## Stats & Info for DataCap Allocation
    
#### Multisig Notary address
> f01858410
    
#### Client address
> f166erfrtv2iggp1223fsaayk43cxrz5pkzrcv5a7ry 

    
#### Last two approvers
> **test1** & **test2** 

    
#### Rule to calculate the allocation request amount
> 100% of weekly dc amount requested
    
#### DataCap allocation requested
> 100TiB
    
#### Total DataCap granted for client so far
> 50TiB
    
#### Datacap to be granted to reach the total amount requested by the client (5PiB)
> 4.95PiB
    
#### **[Stats](https://filplus.d.interplanetary.one/clients?filter=f01993597 "Go to stats")**
| Number of deals  | Number of storage providers | Previous DC Allocated  |  Top provider | Remaining DC
|---|---|---|---|---|
| 1166  | 6  |  50TiB | 21.01  | 10.84TiB
    
```
