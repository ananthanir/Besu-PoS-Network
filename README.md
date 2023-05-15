# Besu-PoA-2Nodes

The network is deployed and contract is also deployed address: 0x27Ea93DC304f7355B132EeFB2067B85171764976
stored data also


M2N1 - key: 0x09182a5112b28043073f6407470a04440479b06aa5ad1750610c869f83625cde


Steps For Migration

1. Create two nodes structure in the machine you want to migrate to
2. Make sure genesis files are correct
3. Make sure config file is correct - the second machines should have the bootnode id and ip updated
4. Start two new nodes
5. Wait for it to finish synching
6. Stop the entire system, ie stop all 4 nodes
7. Swap the data/key conent between node-1s of both systems
8. Change bootnode ids to new validator ip
9. up all nodes - first new validator set, then previous nodes
10. This is where you get it - i hope