---
description: Commands that can be called from within the Ethernal Elves Discord Server
---

# Discord Bot Commands

### Commands

You can use the following commands in the dapp bot commands channel:

```
!burn 
!burn [wallet address]
!ens [wallet Address]
!elf [tokenId]
!items [itemIndex]

//dont include [] when passing a parameter
```

| Command | Parameters     | Description                                                                                                               |
| ------- | -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| !burn   | none           | daily net emissions/burn Calculated from 00:00 to 23:59 UTC                                                               |
| !burn   | wallet address | gets daily burn and emissions for the selected wallet                                                                     |
| !elf    | tokenId        | returns information about the elf. Data may be delayed since it is being fetched from the database and not the blockchain |
| !ens    | wallet address | returns the .eth name for the selected address. returns nothing if no ens is found                                        |
| !items  | itemIndex      | returns information about the selected item                                                                               |
