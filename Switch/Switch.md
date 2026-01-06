# Switch Configuratie

<details class="details-section">
	<summary class="section-summary">Switch Configuratie</summary>

```
[Switch1 configuraties:  
Building configuration...

Current configuration : 1300 bytes
!
version 15.0
no service timestamps log datetime msec
no service timestamps debug datetime msec
service password-encryption
!
hostname Sw1
!
enable secret 5 $1$mERr$9cTjUIEqNGurQiFU.ZeCi1
spanning-tree mode pvst
spanning-tree extend system-id
!
interface FastEthernet0/1
!
interface FastEthernet0/2
!
interface FastEthernet0/3
!
interface FastEthernet0/4
!
interface FastEthernet0/5
!
interface FastEthernet0/6
!
interface FastEthernet0/7
!
interface FastEthernet0/8
!
interface FastEthernet0/9
!
interface FastEthernet0/10
!
interface FastEthernet0/11
!
interface FastEthernet0/12
!
interface FastEthernet0/13
!
interface FastEthernet0/14
!
interface FastEthernet0/15
!
interface FastEthernet0/16
!
interface FastEthernet0/17
!
interface FastEthernet0/18
!
interface FastEthernet0/19
!
interface FastEthernet0/20
!
interface FastEthernet0/21
!
interface FastEthernet0/22
!
interface FastEthernet0/23
!
interface FastEthernet0/24
!
interface GigabitEthernet0/1
switchport mode access
!
interface GigabitEthernet0/2
interface Vlan1
ip address 192.168.1.126 255.255.255.128
!
ip default-gateway 192.168.1.1
line con 0
password 7 0822455D0A16
login
!
line vty 0 4
password 7 0822455D0A16
login
transport input ssh
line vty 5 15
password 7 0822455D0A16
login
end
Switch2 configuraties:  
Building configuration...

Current configuration : 1302 bytes
!
version 15.0
no service timestamps log datetime msec
no service timestamps debug datetime msec
service password-encryption
!
hostname Sw2
!
enable secret 5 $1$mERr$9cTjUIEqNGurQiFU.ZeCi1
!
spanning-tree mode pvst
spanning-tree extend system-id
!
interface FastEthernet0/1
!
interface FastEthernet0/2
!
interface FastEthernet0/3
!
interface FastEthernet0/4
!
interface FastEthernet0/5
!
interface FastEthernet0/6
!
interface FastEthernet0/7
!
interface FastEthernet0/8
!
interface FastEthernet0/9
!
interface FastEthernet0/10
!
interface FastEthernet0/11
!
interface FastEthernet0/12
!
interface FastEthernet0/13
!
interface FastEthernet0/14
!
interface FastEthernet0/15
!
interface FastEthernet0/16
!
interface FastEthernet0/17
!
interface FastEthernet0/18
!
interface FastEthernet0/19
!
interface FastEthernet0/20
!
interface FastEthernet0/21
!
interface FastEthernet0/22
!
interface FastEthernet0/23
!
interface FastEthernet0/24
!
interface GigabitEthernet0/1
switchport mode access
!
interface GigabitEthernet0/2
!
interface Vlan1
ip address 192.168.1.254 255.255.255.128
!
ip default-gateway 192.168.1.129
!
!
!
!
line con 0
password 7 0822455D0A16
login
!
line vty 0 4
password 7 0822404F1A0A
login
transport input ssh
line vty 5 15
password 7 0822455D0A16
login
end
]
```
</details>
