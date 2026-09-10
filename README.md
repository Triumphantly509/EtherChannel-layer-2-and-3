# EtherChannel - Layer 3


## Objective
- Configure Layer 3 EtherChannels between three multilayer switches using routed Port-Channel interfaces.
- Bundle multiple physical links into logical Port-Channel interfaces to provide increased bandwidth and redundancy.
- Configure inter-VLAN routing on the multilayer switches to enable communication between different VLANs.
- Assign IP addresses to the Layer 3 Port-Channel interfaces and establish routing between the three switches.
- Configure and verify connectivity between the two PCs connected to each multilayer switch.
- Verify EtherChannel formation, routing, and Port-Channel operational status using Cisco IOS verification commands.
- Demonstrate redundancy and fault tolerance by shutting down a member link while maintaining network connectivity.
- Validate end-to-end communication between hosts across the Layer 3 EtherChannel topology.

## Lab topology

<div>
 <img width="715" height="308" alt="image" src="https://github.com/user-attachments/assets/c713186f-3968-40c7-beec-04665afb623f" />
</div>

## Enable Ip routing on the switches.

<div>
 <img width="457" height="37" alt="image" src="https://github.com/user-attachments/assets/c930c9c6-8a94-4bbe-960b-839dbb2c0248" />
</div>

## Enable layer 3 routed interfaces on the switch 6.
 <div>
  <img width="743" height="361" alt="image" src="https://github.com/user-attachments/assets/c328f235-2cc2-4c6a-9042-a0fb7fa1f293" />
</div>

## Enable layer 3 routed interfaces on switch 5.

<div>
  <img width="598" height="353" alt="image" src="https://github.com/user-attachments/assets/a010ebf6-9f70-40eb-ae73-708b28154c62" />
</div>

## Enable layer 3 routed interfaces on switch 7.

<div>
  <img width="609" height="345" alt="image" src="https://github.com/user-attachments/assets/6db4f53a-6d7a-4dcf-9597-e0c96f44b864" />
</div>

## Create LACP EtherChannel group 1 on switch 6.

<div>
  <img width="625" height="263" alt="image" src="https://github.com/user-attachments/assets/e467b7af-a282-44f7-ad89-c1ec913fc2be" />
</div>

## Etherchannel summary Result on switch 6.

<div>
  <img width="491" height="169" alt="image" src="https://github.com/user-attachments/assets/1449757c-c26a-4ee3-8844-9d97895c3b30" />
</div>

## Create LACP EtherChannel group 1 on switch 5.

<div>
  <img width="528" height="306" alt="image" src="https://github.com/user-attachments/assets/08a942ab-f542-4454-9119-f1e04704ac65" />
</div>

## Etherchannel summary Result on switch 5.

<div>
  <img width="470" height="172" alt="image" src="https://github.com/user-attachments/assets/531708be-7f6a-4f62-9bf7-e4ca16eeb13c" />
</div>

## Create PAGP EtherChannel group 2 on switch 6.

<div>
  <img width="489" height="310" alt="image" src="https://github.com/user-attachments/assets/334af7e7-19c3-430d-9774-c2dcc96348a5" />
</div>

## Etherchannel summary Result on switch 6.

<div>
  <img width="493" height="181" alt="image" src="https://github.com/user-attachments/assets/2dd5e46e-132c-40bc-b5a4-55969aced8f2" />
</div>

## Create PAGP EtherChannel group 2 on switch 7.

<div>
  <img width="491" height="293" alt="image" src="https://github.com/user-attachments/assets/b4a086f1-ab25-4f90-883d-3d66c2757a25" />
</div>

## Etherchannel summary Result on switch 7.

<div>
  <img width="477" height="173" alt="image" src="https://github.com/user-attachments/assets/28cd4e28-fe3b-4fcf-ab46-a1202bfcf5bb" />
</div>

## Create Static EtherChannel group 3 on switch 7.

<div>
  <img width="491" height="179" alt="image" src="https://github.com/user-attachments/assets/137840ce-11a7-4125-b881-7b8a44760f70" />
</div>

## Etherchannel summary Result on switch 7.

<div>
  <img width="477" height="179" alt="image" src="https://github.com/user-attachments/assets/3cc18f19-a1c6-46e4-90e1-046bf1aabdb3" />
</div>

## Create Static EtherChannel group 3 on switch 5.

<div>
  <img width="491" height="182" alt="image" src="https://github.com/user-attachments/assets/092982d4-2d28-4e5e-9ad0-ea64eda58de6" />
</div>

## Etherchannel summary Result on switch 5.

<div>
  <img width="476" height="179" alt="image" src="https://github.com/user-attachments/assets/77f318a9-8fd5-43cf-bf02-58525a6c2f5d" />
</div>

## conclusion

