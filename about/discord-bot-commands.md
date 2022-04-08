---
description: Commands that can be called from within the Ethernal Elves Discord Server
---

# Discord Bot Commands

### Commands

You can use the following commands in the dapp bot commands channel:

```
!burn 
!burn [wallet address]
!degen [actionIndex]
!degen [actionIndex] daily
!ens [wallet Address]
!elf [tokenId]
!me [tokenId] [actionIndex]
!items [itemIndex]

//dont include [] when passing a parameter
```

| Command | Parameters           | Description                                                                                                               |
| ------- | -------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| !burn   | none                 | daily net emissions/burn Calculated from 00:00 to 23:59 UTC                                                               |
| !burn   | wallet address       | gets daily burn and emissions for the selected wallet                                                                     |
| !degen  | action index         | refer to actions list below. Returns the token Ids and latest owners for top 5 by frequency of action                     |
| !degen  | action index, daily  | adding the word "daily" after the action index will return stats for today                                                |
| !elf    | tokenId              | returns information about the elf. Data may be delayed since it is being fetched from the database and not the blockchain |
| !ens    | wallet address       | returns the .eth name for the selected address. returns nothing if no ens is found                                        |
| !me     | tokenId, actionIndex | returns frequency of action by token id and current owner                                                                 |
| !items  | itemIndex            | returns information about the selected item                                                                               |

### Action Index

```
  {action: 0, text: 'unstake'}
  {action: 1, text: 'stake'}
  {action: 2, text: 'campaign'}
  {action: 3, text: 'passive mode'}
  {action: 4, text: 'return from passive mode'}
  {action: 5, text: 're-roll weapon'}
  {action: 6, text: 're-roll item'}
  {action: 7, text: 'healing'}
  {action: 8, text: 'polygon'}
  {action: 9, text: 'synergize'}
  {action: 10, text: 'bloodthirst'}
  {action: 11, text: 'rampage'}
  {action: 12, text: 'buy item'}
  {action: 13, text: 'sell item'}
  {action: 14, text: 'crusade'}
  {action: 15, text: 'return crusade'}
```
