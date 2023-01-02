# Filecoin Plus Application Comment Templates

## LDN

## _Datacap Request Trigger Comment_

\-  This is a manual comment triggered by Root Key Holders. In order to trigger this comment, the necessary information in the application must be filled in completely and correctly. (v3)

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

\- This comment is created by the LDN bot after the Datacap Request Trigger message has been created.

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

\- This comment generated from filplus website by the operation of notaries. The first message is called the proposal message. 

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

## _Cancel Proposed Comment_

\- This comment generated from filplus website when notaries canceled their proposal request.

```
## Canceled Request
The following request has been canceled by the notary, thus should not be considered as valid anymore.
#### Message sent to Filecoin Network
>bafy2bzacebmk2f7qoydyzvas3sjdw3ib3nuwy324zqo2zjtkqyqlvh4xvq6rs 
#### Address 
> t1y6grz7kkjs5wyvg4mp5jqjl3unqt7t5ktqlrf2q
#### Datacap Allocated
> 50.00TiB
#### Signer Address
> t1fmqtnifrcnv4753hoyhjalgsv5klimrxmk7ekoq
#### You can check the status of the message here: https://filfox.info/en/message/bafy2bzacebmk2f7qoydyzvas3sjdw3ib3nuwy324zqo2zjtkqyqlvh4xvq6rs
```

## _Request Approved Comment_

\- This comment generated from filplus website by the operation of notaries. The second message is called the approval message. 

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

## _Issue Reconnection Request_

\- This is needed to reconnect a closed issue to the new one.

```
## Multisig Notary Reconnection Request
#### Multisig Notary Address
> f01105812
#### Client Address
> f1yswits4hd4zu6n2pl7nk7cspcuieuzl7btjn5ia
#### Notary Governance Issue
> https://github.com/keyko-io/filecoin-notaries-onboarding/issues/370
```

## _Weekly DataCap Allocation Update Comment_

\- This comment is used for updating the weekly datacap request.

```
## Weekly DataCap Allocation Update requested
#### Update to expected weekly DataCap usage rate
> 10TiB
```


## _Multisig Notary Requested Comment_

\- Old template used for creating multisig. **Not used anymore**. (v2)

```
## Multisig Notary requested

#### Total DataCap requested
> 5PiB

#### Expected weekly DataCap usage rate
> 500TiB
```


## _Subsequent  Allocation Comment_

\- This comment is created by the SSA bot with subsequent allocation number information.

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


## NOTARY APPLICATION

## _Notary Request Approved Comment_

\-  This is a manual comment triggered by Root Key Holders after the notary application has been created with necessary informations.

```
## Request Approved
#### Address
> f1111222333
#### Datacap Allocated
> 5PiB
```

## _Notary Confirmation Comment_

\- This comment is posted by bot when a RKH signed a transaction.

```
## The request has been signed by a new Root Key Holder
#### Message sent to Filecoin Network
>bafy2bzacedeu7ymgdg3gwy522gtoy4a6j6v433cur4wjlv2xjeqtvm4bkymoi
#### You can check the status of the message here: https://filfox.info/en/message/bafy2bzacedeu7ymgdg3gwy522gtoy4a6j6v433cur4wjlv2xjeqtvm4bkymoi
```

## _Notary Letger Verified Comment_

\- This comment checks ledger verification.

```
## Notary Ledger Verified
#### Message sent to Filecoin Network
> Message CID: bafy2bzacedeu7ymgdg3gwy522gtoy4a6j6v433cur4wjlv2xjeqtvm4bkymoi
 #### You can check the status of the message here: https://filfox.info/en/message/bafy2bzacedeu7ymgdg3gwy522gtoy4a6j6v433cur4wjlv2xjeqtvm4bkymoi
```


