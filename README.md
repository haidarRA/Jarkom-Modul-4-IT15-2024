# Jarkom-Modul-4-IT15-2024

## ***KELOMPOK IT15***
| Nama      | NRP         |
|-----------|-------------|
| M. Abhinaya Al Faruqi | 5027231011  |  
| Haidar Rafi Aqyla | 5027231029   |

## Routing:
![image](https://github.com/user-attachments/assets/9000ec51-7417-45af-8499-1037e2a4ee5f)

## Topologi jaringan di GNS3:
![image](https://github.com/user-attachments/assets/effe40b7-61c6-428b-b065-de4d390690b6)

## Topologi jaringan di Cisco Packet Tracer:
![step 1](https://github.com/user-attachments/assets/0f2e60db-f887-4ece-bbc3-da0ad55e6872)

# VLSM (GNS3)
## Pembagian IP:
![image](https://github.com/user-attachments/assets/63ca8d20-40d3-4977-a3a5-4f41e8a15012)

## VLSM Tree:
![VLSM tree revisi 3](https://github.com/user-attachments/assets/7536b36e-165b-49ba-8ea4-be75bf2aa31e)

## Konfigurasi Router:
### Hololive:
```
auto lo
iface lo inet loopback

auto eth1
iface eth1 inet static
	address 10.71.17.82
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.71.17.106
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.71.17.90
	netmask 255.255.255.252
```

### Holo-EN:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.81
	netmask 255.255.255.252
	gateway 10.71.17.82

auto eth1
iface eth1 inet static
	address 10.71.17.66
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.71.17.70
	netmask 255.255.255.252
```

### Holo-JP:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.89
	netmask 255.255.255.252
	gateway 10.71.17.90

auto eth1
iface eth1 inet static
	address 10.71.17.3
	netmask 255.255.255.248
```

### Holo-ID:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.105
	netmask 255.255.255.252
	gateway 10.71.17.106

auto eth1
iface eth1 inet static
	address 10.71.17.94
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.71.17.98
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.71.17.102
	netmask 255.255.255.252
```

### Holo-Myth:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.65
	netmask 255.255.255.252
	gateway 10.71.17.66

auto eth1
iface eth1 inet static
	address 10.71.3.254
	netmask 255.255.254.0

auto eth2
iface eth2 inet static
	address 10.71.17.75
	netmask 255.255.255.248
```

### HoloAdvent:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.69
	netmask 255.255.255.252
	gateway 10.71.17.70

auto eth1
iface eth1 inet static
	address 10.71.17.62
	netmask 255.255.255.224
```

### DEV_IS:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.2
	netmask 255.255.255.248
	gateway 10.71.17.3

auto eth1
iface eth1 inet static
	address 10.71.17.30
	netmask 255.255.255.240
```

### GEN:0
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.1
	netmask 255.255.255.248
	gateway 10.71.17.3

auto eth1
iface eth1 inet static
	address 10.71.15.254
	netmask 255.255.248.0
```

### AREA15:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.93
	netmask 255.255.255.252
	gateway 10.71.17.94

auto eth1
iface eth1 inet static
	address 10.71.7.254
	netmask 255.255.252.0
```

### holoro:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.97
	netmask 255.255.255.252
	gateway 10.71.17.98

auto eth1
iface eth1 inet static
	address 10.71.16.126
	netmask 255.255.255.192
```

### holoh3ro:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.101
	netmask 255.255.255.252
	gateway 10.71.17.102

auto eth1
iface eth1 inet static
	address 10.71.19.254
	netmask 255.255.254.0
```

### Holo-Council:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.73
	netmask 255.255.255.248
	gateway 10.71.17.75

auto eth1
iface eth1 inet static
	address 10.71.16.62
	netmask 255.255.255.192
```

### Router4:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.74
	netmask 255.255.255.248
	gateway 10.71.17.75

auto eth1
iface eth1 inet static
	address 10.71.17.14
	netmask 255.255.255.248
```

### GEN:1
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.8.1
	netmask 255.255.248.0
	gateway 10.71.15.254

auto eth1
iface eth1 inet static
	address 10.71.1.254
	netmask 255.255.254.0

auto eth2
iface eth2 inet static
	address 10.71.17.86
	netmask 255.255.255.252
```

### GAMERS:
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
	address 10.71.17.85
	netmask 255.255.255.252
	gateway 10.71.17.86

auto eth1
iface eth1 inet static
	address 10.71.16.254
	netmask 255.255.255.128
```

## Konfigurasi Node/Client:
### A1
#### Bae_Fauna:
```
auto eth0
iface eth0 inet static
	address 10.71.16.1
	netmask 255.255.255.192
	gateway 10.71.16.62
```

#### Kronii_Mumei:
```
auto eth0
iface eth0 inet static
	address 10.71.16.2
	netmask 255.255.255.192
	gateway 10.71.16.62
```

### A2
#### Irys:
```
auto eth0
iface eth0 inet static
	address 10.71.17.9
	netmask 255.255.255.248
	gateway 10.71.17.14
```

### A4
#### Gura_Ame_Ina:
```
auto eth0
iface eth0 inet static
	address 10.71.2.1
	netmask 255.255.254.0
	gateway 10.71.3.254
```

#### Kiara_Calli:
```
auto eth0
iface eth0 inet static
	address 10.71.2.2
	netmask 255.255.254.0
	gateway 10.71.3.254
```

### A6
#### FuwaMoco:
```
auto eth0
iface eth0 inet static
	address 10.71.17.33
	netmask 255.255.255.224
	gateway 10.71.17.62
```

#### Shiori_Nerissa:
```
auto eth0
iface eth0 inet static
	address 10.71.17.34
	netmask 255.255.255.224
	gateway 10.71.17.62
```

#### Biboo:
```
auto eth0
iface eth0 inet static
	address 10.71.17.35
	netmask 255.255.255.224
	gateway 10.71.17.62
```

### A9
#### Korone:
```
auto eth0
iface eth0 inet static
	address 10.71.16.129
	netmask 255.255.255.128
	gateway 10.71.16.254
```

#### Okayu:
```
auto eth0
iface eth0 inet static
	address 10.71.16.130
	netmask 255.255.255.128
	gateway 10.71.16.254
```

#### Mio:
```
auto eth0
iface eth0 inet static
	address 10.71.16.131
	netmask 255.255.255.128
	gateway 10.71.16.254
```

### A11
#### FBK_Matsuri:
```
auto eth0
iface eth0 inet static
	address 10.71.0.1
	netmask 255.255.254.0
	gateway 10.71.1.254
```

#### Aki_Hachama:
```
auto eth0
iface eth0 inet static
	address 10.71.0.2
	netmask 255.255.254.0
	gateway 10.71.1.254
```

### A12
#### MiComet:
```
auto eth0
iface eth0 inet static
	address 10.71.8.2
	netmask 255.255.248.0
	gateway 10.71.15.254
```

#### Sora_Robo_AZKi:
```
auto eth0
iface eth0 inet static
	address 10.71.8.3
	netmask 255.255.248.0
	gateway 10.71.15.254
```

### A13
#### Ririka_Raden:
```
auto eth0
iface eth0 inet static
	address 10.71.17.17
	netmask 255.255.255.240
	gateway 10.71.17.30
```

#### Ao:
```
auto eth0
iface eth0 inet static
	address 10.71.17.18
	netmask 255.255.255.240
	gateway 10.71.17.30
```

#### Hajime_Kanade:
```
auto eth0
iface eth0 inet static
	address 10.71.17.19
	netmask 255.255.255.240
	gateway 10.71.17.30
```

### A16
#### Risu:
```
auto eth0
iface eth0 inet static
	address 10.71.4.1
	netmask 255.255.252.0
	gateway 10.71.7.254
```

#### Moona:
```
auto eth0
iface eth0 inet static
	address 10.71.4.2
	netmask 255.255.252.0
	gateway 10.71.7.254
```

#### Iofi:
```
auto eth0
iface eth0 inet static
	address 10.71.4.3
	netmask 255.255.252.0
	gateway 10.71.7.254
```

### A18
#### Ollie:
```
auto eth0
iface eth0 inet static
	address 10.71.16.65
	netmask 255.255.255.192
	gateway 10.71.16.126
```

#### Anya:
```
auto eth0
iface eth0 inet static
	address 10.71.16.66
	netmask 255.255.255.192
	gateway 10.71.16.126
```

#### Reine:
```
auto eth0
iface eth0 inet static
	address 10.71.16.67
	netmask 255.255.255.192
	gateway 10.71.16.126
```

### A20
#### Zeta:
```
auto eth0
iface eth0 inet static
	address 10.71.18.1
	netmask 255.255.254.0
	gateway 10.71.19.254
```

#### Kaela:
```
auto eth0
iface eth0 inet static
	address 10.71.18.2
	netmask 255.255.254.0
	gateway 10.71.19.254
```

#### Kobo:
```
auto eth0
iface eth0 inet static
	address 10.71.18.3
	netmask 255.255.254.0
	gateway 10.71.19.254
```

## Routing:
### Hololive:
```
#from Holo-EN
route add -net 10.71.16.0 netmask 255.255.255.192 gw 10.71.17.81
route add -net 10.71.17.8 netmask 255.255.255.248 gw 10.71.17.81
route add -net 10.71.17.72 netmask 255.255.255.248 gw 10.71.17.81
route add -net 10.71.2.0 netmask 255.255.254.0 gw 10.71.17.81
route add -net 10.71.17.32 netmask 255.255.255.224 gw 10.71.17.81
route add -net 10.71.17.64 netmask 255.255.255.252 gw 10.71.17.81
route add -net 10.71.17.68 netmask 255.255.255.252 gw 10.71.17.81

#from Holo-JP
route add -net 10.71.17.16 netmask 255.255.255.240 gw 10.71.17.89
route add -net 10.71.8.0 netmask 255.255.248.0 gw 10.71.17.89
route add -net 10.71.17.84 netmask 255.255.255.252 gw 10.71.17.89
route add -net 10.71.16.128 netmask 255.255.255.128 gw 10.71.17.89
route add -net 10.71.0.0 netmask 255.255.254.0 gw 10.71.17.89
route add -net 10.71.17.0 netmask 255.255.255.248 gw 10.71.17.89

#from Holo-ID
route add -net 10.71.4.0 netmask 255.255.252.0 gw 10.71.17.105
route add -net 10.71.16.64 netmask 255.255.255.192 gw 10.71.17.105
route add -net 10.71.18.0 netmask 255.255.254.0 gw 10.71.17.105
route add -net 10.71.17.92 netmask 255.255.255.252 gw 10.71.17.105
route add -net 10.71.17.96 netmask 255.255.255.252 gw 10.71.17.105
route add -net 10.71.17.100 netmask 255.255.255.252 gw 10.71.17.105
```

### Holo-Council
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.71.17.75
```

### Router4
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.71.17.75
```

### Holo-Myth
```
route add -net 10.71.17.8 netmask 255.255.255.248 gw 10.71.17.74
route add -net 10.71.16.0 netmask 255.255.255.192 gw 10.71.17.73
```

### HoloAdvent
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.71.17.70
```

### Holo-EN
```
route add -net 10.71.16.0 netmask 255.255.255.192 gw 10.71.17.65
route add -net 10.71.17.8 netmask 255.255.255.248 gw 10.71.17.65
route add -net 10.71.17.72 netmask 255.255.255.248 gw 10.71.17.65
route add -net 10.71.2.0 netmask 255.255.254.0 gw 10.71.17.65
route add -net 10.71.17.32 netmask 255.255.255.224 gw 10.71.17.69
```

### GAMERS
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.71.17.86
```

### GEN:1
```
route add -net 10.71.16.128 netmask 255.255.255.128 gw 10.71.17.85
```

### GEN:0
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.71.17.3
route add -net 10.71.17.84 netmask 255.255.255.252 gw 10.71.8.1
route add -net 10.71.16.128 netmask 255.255.255.128 gw 10.71.8.1
route add -net 10.71.0.0 netmask 255.255.254.0 gw 10.71.8.1
```

### DEV_IS
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.71.17.3
```

### Holo_JP
```
route add -net 10.71.17.16 netmask 255.255.255.240 gw 10.71.17.2
route add -net 10.71.8.0 netmask 255.255.248.0 gw 10.71.17.1
route add -net 10.71.17.84 netmask 255.255.255.252 gw 10.71.17.1
route add -net 10.71.16.128 netmask 255.255.255.128 gw 10.71.17.1
route add -net 10.71.0.0 netmask 255.255.254.0 gw 10.71.17.1
```

### AREA15
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.71.17.94
```

### holoro
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.71.17.98
```

### holoh3ro
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.71.17.102
```

### Holo-ID
```
route add -net 10.71.4.0 netmask 255.255.252.0 gw 10.71.17.93
route add -net 10.71.16.64 netmask 255.255.255.192 gw 10.71.17.97
route add -net 10.71.18.0 netmask 255.255.254.0 gw 10.71.17.101
```

## Testing:
https://github.com/user-attachments/assets/192bb9c7-efde-4511-93f7-eca6d32c4444

# CIDR (CPT)
## Pembagian 1 (A):
![step 2](https://github.com/user-attachments/assets/fe73fddd-f169-4e4d-b405-d90f4a126a78)

## Pembagian 2 (B):
![image](https://github.com/user-attachments/assets/7655819b-d9c6-4f6c-a633-c5b0208746f0)
![step 3](https://github.com/user-attachments/assets/aa61ec52-e6bd-424b-bfcd-09dd7aac8284)

## Pembagian 3 (C):
![image](https://github.com/user-attachments/assets/d200cc08-ace6-4766-98d3-d4c9c64ad7fb)
![step 4](https://github.com/user-attachments/assets/27ac4a89-df14-44bf-a6d1-3d9957309439)

## Pembagian 4 (D):
![image](https://github.com/user-attachments/assets/d312e67d-be18-4a03-985d-02090a009395)
![step 5](https://github.com/user-attachments/assets/4776a293-055f-4f38-a770-5b91d7448886)

## Pembagian 5 (E):
![image](https://github.com/user-attachments/assets/2af92e6a-c89d-484b-8ef5-f7968279e120)
![step 6](https://github.com/user-attachments/assets/f43feff4-ec6b-408c-a7f5-b42647ade12f)

## Pembagian 6 (F):
![image](https://github.com/user-attachments/assets/1b034781-1301-491d-82a7-a821e11e5078)
![step 7](https://github.com/user-attachments/assets/fb8f3c62-e6bb-404c-b4be-27f6fa37f6d7)

## Pembagian 7 (G):
![image](https://github.com/user-attachments/assets/88a698ec-438e-4bb3-abea-5c23460f1499)
![step 8](https://github.com/user-attachments/assets/da7701f9-8d4c-4d66-be2c-172c31c7fcfa)

## Pembagian 8 (H):
![image](https://github.com/user-attachments/assets/c213dd5b-0006-4a7c-8fdc-eb38e7c9acab)
![step 9](https://github.com/user-attachments/assets/955db6fd-f03a-404a-9c41-f68f08c9d5a3)

## Pembagian 9 (I):
![image](https://github.com/user-attachments/assets/f46f719a-55cd-43c8-9fa3-4e139268674a)
![step 10](https://github.com/user-attachments/assets/4ce3ebc3-0352-4849-9fe6-e040e18b9086)

## Hasil Akhir:
![cidr done](https://github.com/user-attachments/assets/51823922-e5e1-4f86-9a87-0ab6bf4ce858)

## CIDR Tree:
![CIDR tree revisi](https://github.com/user-attachments/assets/acc94284-1025-406b-b578-602d6fc8813a)

## Pembagian IP:
![image](https://github.com/user-attachments/assets/da3b5c6c-26ea-4f54-a8dc-e3c78b3f5936)

## Testing:
https://github.com/user-attachments/assets/35ffccdc-b4f6-41ca-9a16-482f10fcac8d

