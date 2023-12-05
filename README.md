# Jarkom-Modul-4-A07-2023

**Praktikum Jaringan Komputer Modul 4 Tahun 2023**

## Author

| Nama                  | NRP        | Github                      |
| --------------------- | ---------- | --------------------------- |
| Dimas Fadilah Akbar   | 5025211010 | https://github.com/dimss113 |
| Kevin Nathanael Halim | 5025211140 | https://github.com/zetsux   |

# Laporan Resmi

## CIDR Cisco Packet Tracer

### Topologi

<img width="671" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/92a6ff3c-f77f-4dc5-929f-a3934228e724">

### Pembagian Subnet

<img width="446" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/346bdfd7-b73b-4fa6-96ac-1513bc8a5b2c">

### Penggabugan dengan CIDR

- Penggabungan 1

<img width="393" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/aecac6c6-42fa-4a50-8aef-36325fce36a4">

- Penggabungan 2

<img width="393" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/c12866aa-1ef1-4f81-b982-721c01e49fb5">

- Penggabungan 3

<img width="534" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/fbcf39b2-881c-4442-8a43-4eea14d1ac37">

- Penggabungan 4

<img width="394" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/0ade391a-dc32-4fc3-94c4-cb9862b0e4a8">

- Penggabungan 5

<img width="670" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/665ee5aa-0f53-42bc-b124-3a57d09778bf">

- Penggabungan 6

<img width="394" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/7354f57e-aaff-4ecb-b463-20245a21e45f">

- Penggabungan 7

<img width="534" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/11c4b614-3a94-4b90-b3a2-33de4669f37c">

- Hasil Penggabungan

<img width="561" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/23e4be3b-95ab-43c8-8919-29704ed1fb72">

### CIDR Tree

<img width="835" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/2009189d-3c27-44aa-b2f2-c2a35afb4f9b">

### Pembagian IP CIDR

<img width="624" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/f02457a5-5dee-43ec-996a-9b6391d99cbd">

### Subnetting

- Subnet A1

  Router Eisen (Fa 0/1 ):

  - ipv4 = 192.172.80.9
  - netmask = 255.255.255.252

  Server PT Stark:

  - ipv4 = 192.172.80.10
  - netmask = 255.255.255.252

- Subnet A2

  Router Eisen (Eth 1/1 ):

  - ipv4 = 192.172.72.1
  - netmask = 255.255.255.252

  Router Lugner (Fa 0/0):

  - ipv4 = 192.172.72.2
  - netmask = 255.255.255.252

- Subnet A3

  Router Lugner(Fa 1/0):

  - ipv4 = 192.172.64.1
  - netmask = 255.255.252.0

  PC Turk-Region:

  - ipv4 = 192.172.64.2
  - netmask = 255.255.252.0

- Subnet A4

  Router Lugner (Fa 0/1):

  - ipv4 = 192.172.68.1
  - netmask = 255.255.255.0

  PC GrobeForest:

  - ipv4 = 192.172.68.2
  - netmask = 255.255.255.0

- Subnet A5

  Router Eisen (Eth 1/2):

  - ipv4 = 192.172.32.1
  - netmask = 255.255.255.252

  Router Linie (Fa 0/0):

  - ipv4 = 192.172.32.2
  - netmask = 255.255.255.252

- Subnet A6

  Router Linie (Fa 0/1):

  - ipv4 = 192.172.8.1
  - netmask = 255.255.255.252

  Router Lawine (Fa 0/0):

  - ipv4 = 192.172.8.2
  - netmask = 255.255.255.252

- Subnet A7

  Router Linie (Fa 1/0):

  - ipv4 = 192.172.16.1
  - netmask = 255.255.254.0

  PC GranzChannel:

  - ipv4 = 192.172.16.2
  - netmask = 255.255.254.0

- Subnet A8

  Router Lawine (Fa 0/1):

  - ipv4 = 192.172.4.1
  - netmask = 255.255.255.192

  PC BredtRegion:

  - ipv4 = 192.172.4.2
  - netmask = 255.255.255.192

  Router Heiter (Fa 0/0):

  - ipv4 = 192.172.4.3
  - netmask = 255.255.255.192

- Subnet A9

  Router Heiter (Fa 0/1):

  - ipv4 = 192.172.0.1
  - netmask = 255.255.252.0

  Server Sein:

  - ipv4 = 192.172.0.2
  - netmask = 255.255.252.0

  PC ReigelCanyon:

  - ipv4 = 192.172.0.3
  - netmask = 255.255.252.0

- Subnet A10

  Router Eisen (Eth 1/0):

  - ipv4 = 192.172.80.1
  - netmask = 255.255.255.248

  Server Ritcher:

  - ipv4 = 192.172.80.2
  - netmask = 255.255.255.248

  Server Revolte:

  - ipv4 = 192.172.80.3
  - netmask = 255.255.255.248

- Subnet A11

  Router Aura (Fa 1/1):

  - ipv4 = 192.172.128.1
  - netmask = 255.255.255.252

  Router Eisen (Fa 0/0):

  - ipv4 = 192.172.128.2
  - netmask = 255.255.255.252

- Subnet A12

  Router Aura (Fa 1/0):

  - ipv4 = 192.174.1.1
  - netmask = 255.255.255.252

  Router Denken (Fa 0/0):

  - ipv4 = 192.174.1.2
  - netmask = 255.255.255.252

- Subnet 13

  Router Denken (Fa 0/1):

  - ipv4 = 192.174.0.1
  - netmask = 255.255.255.0

  PC RoyalCapital:

  - ipv4 = 192.174.0.2
  - netmask = 255.255.255.0

  PC WilleRegion:

  - ipv4 = 192.174.0.3
  - netmask = 255.255.255.0

- Subnet 14

  Router Aura (Fa 0/1):

  - ipv4 = 192.173.128.1
  - netmask = 255.255.255.252

  Router Freiern (Fa 0/0):

  - ipv4 = 192.173.128.2
  - netmask = 255.255.255.252

- Subnet 15

  Router Frieren (Fa 0/1):

  - ipv4 = 192.173.64.1
  - netmask = 255.255.255.224

  PC LakeCorridor:

  - ipv4 = 192.173.64.2
  - netmask = 255.255.255.224

- Subnet A16

  Router Frieren (Fa 1/0):

  - ipv4 = 192.173.32.1
  - netmask = 255.255.255.252

  Router Flamme (Fa 0/0):

  - ipv4 = 192.173.32.2
  - netmask = 255.255.255.252

- Subnet A17

  Router Flamme (Fa 0/1):

  - ipv4 = 192.173.8.1
  - netmask = 255.255.255.252

  Router Fern (Fa 0/0):

  - ipv4 = 192.173.8.2
  - netmask = 255.255.255.252

- Subnet A18

  Router Fern (Fa 0/1):

  - ipv4 = 192.173.0.1
  - netmask = 255.255.248.0

  PC LaubHills:

  - ipv4 = 192.173.0.3
  - netmask = 255.255.248.0

  PC AppetiteRegion:

  - ipv4 = 192.173.0.2
  - netmask = 255.255.248.0

- Subnet A19

  Router Flamme (Fa 1/0):

  - ipv4 = 192.173.16.1
  - netmask = 255.255.252.0

  PC RohrRoad:

  - ipv4 = 192.173.16.2
  - netmask = 255.255.252.0

- Subnet A20:

  Router Flamme (Fa 1/1):

  - ipv4 = 192.173.20.9
  - netmask = 255.255.255.252

  Router Himmel (Fa 0/0):

  - ipv4 = 192.173.20.10
  - netmask = 255.255.255.252

- Subnet A21:

  Router Himmel (Fa 0/1):

  - ipv4 = 192.173.20.1
  - netmask = 255.255.255.248

  PC SchewerMountains:

  - ipv4 = 192.173.20.2
  - netmask = 255.255.255.248

### Routing

- Router Aura

<img width="250" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/5d743910-0793-4b40-a90e-1cf03c6e6bfd">

<img width="251" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/46d807b9-6bf1-44ea-ba81-cdfca390c6d7">

<img width="250" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/61283f38-18ec-47a4-bab4-42a239f07f95">

- Router Denken

<img width="250" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/740153a4-914f-4dcb-bbb3-c7a2f6ce887f">

- Router Frieren

<img width="250" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/30211efa-31a2-4046-ba7a-62873f3e38b1">

- Router Flamme

<img width="251" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/52216a85-0c3c-477b-bc31-87a88077b6e6">

- Router Fern

<img width="255" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/6bc25dc4-b9bc-4c8f-b076-f67f65dc356a">

- Router Himmel

<img width="256" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/26ad770e-0466-454b-8f2f-aafdc76df2bf">

- Router Eisen

<img width="256" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/e266cf95-4916-4502-b391-88864681427d">

- Router Lugner

<img width="262" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/71de6b24-25e2-46b6-9ecc-9735c524400d">

- Router Linie

<img width="259" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/12de100a-af8d-45e8-a3f9-295d378bc771">

- Router Lawine

<img width="261" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/8d4faec0-a2e8-4ca8-a3b5-5e2973731fc8">

- Router Heiter

<img width="258" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/89715780/3e4f0ff0-7494-4278-b2d6-94cc69283c8b">

## VLSM Cisco Packet Tracer

### Topologi

<img width="671" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/05f51574-b6d8-4681-aa7e-fb1b92e67303">

### VLSM Tree

<img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/70e4def4-aebf-4810-8af3-aca621b7e654">

### Pembagian Subnet & IP

<img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/701b54dd-ba27-471c-b6ad-228ea707b33b">

### Subnetting

- Aura

  ```py
  # NAT1 (Internet)
  auto eth0
  iface eth0 inet dhcp

  # -> Subnet A12
  auto eth1
  iface eth1 inet static
    address 192.172.0.21
    netmask 255.255.255.252
    gateway 192.172.0.22

  # -> Subnet A14
  auto eth2
  iface eth2 inet static
    address 192.172.0.25
    netmask 255.255.255.252
    gateway 192.172.0.26

  # -> Subnet A11
  auto eth3
  iface eth3 inet static
    address 192.172.0.17
    netmask 255.255.255.252
    gateway 192.172.0.18
  ```

- Denken

  ```py
  # <- Subnet A12
  auto eth0
  iface eth0 inet static
    address 192.172.0.22
    netmask 255.255.255.252
    gateway 192.172.0.21

  # -> Subnet A13
  auto eth1
  iface eth1 inet static
    address 192.172.2.1
    netmask 255.255.255.0
  ```

- RoyalCapital (63 Hosts)

  ```py
  # <- Subnet A13
  auto eth0
  iface eth0 inet static
    address 192.172.2.2
    netmask 255.255.255.0
    gateway 192.172.2.1
  ```

- WilleRegion (63 Hosts)

  ```py
  # <- Subnet A13
  auto eth0
  iface eth0 inet static
    address 192.172.2.65
    netmask 255.255.255.0
    gateway 192.172.2.1
  ```

- Frieren

  ```py
  # <- Subnet A14
  auto eth0
  iface eth0 inet static
    address 192.172.0.26
    netmask 255.255.255.252
    gateway 192.172.0.25

  # -> Subnet A16
  auto eth1
  iface eth1 inet static
    address 192.172.0.29
    netmask 255.255.255.252

  # -> Subnet A15
  auto eth2
  iface eth2 inet static
    address 192.172.0.97
    netmask 255.255.255.224
  ```

- LakeCorridor (24 Hosts)

  ```py
  # <- Subnet A15>
  auto eth0
  iface eth0 inet static
    address 192.172.0.98
    netmask 255.255.255.224
    gateway 192.172.0.97
  ```

- Flamme

  ```py
  # <- Subnet A16
  auto eth0
  iface eth0 inet static
    address 192.172.0.30
    netmask 255.255.255.252
    gateway 192.172.0.29

  # -> Subnet A17
  auto eth1
  iface eth1 inet static
    address 192.172.0.33
    netmask 255.255.255.252

  # -> Subnet A20
  auto eth2
  iface eth2 inet static
    address 192.172.0.37
    netmask 255.255.255.252

  # -> Subnet A19
  auto eth3
  iface eth3 inet static
    address 192.172.12.1
    netmask 255.255.252.0
  ```

- RohrRoad (1000 Hosts)

  ```py
  # <- Subnet A19
  auto eth0
  iface eth0 inet static
    address 192.172.12.2
    netmask 255.255.252.0
    gateway 192.172.12.1
  ```

- Fern

  ```py
  # <- Subnet A17
  auto eth0
  iface eth0 inet static
    address 192.172.0.34
    netmask 255.255.255.252
    gateway 192.172.0.33

  # -> Subnet A18
  auto eth1
  iface eth1 inet static
    address 192.172.24.1
    netmask 255.255.248.0
  ```

- ApetitRegion (625 Host)

  ```py
  # <- Subnet A18
  auto eth0
  iface eth0 inet static
    address 192.172.24.2
    netmask 255.255.248.0
    gateway 192.172.24.1
  ```

- LaubHills (397 Host)

  ```py
  # <- Subnet A18
  auto eth0
  iface eth0 inet static
    address 192.172.26.115
    netmask 255.255.248.0
    gateway 192.172.24.1
  ```

- Himmel

  ```py
  # <- Subnet A20
  auto eth0
  iface eth0 inet static
    address 192.172.0.38
    netmask 255.255.255.252
    gateway 192.172.0.37

  # -> Subnet 21
  auto eth1
  iface eth1 inet static
    address 192.172.0.65
    netmask 255.255.255.248
  ```

- SchwerMountain (5 Hosts)

  ```py
  # <- Subnet A20
  auto eth0
  iface eth0 inet static
    address 192.172.0.66
    netmask 255.255.255.248
    gateway 192.172.0.65
  ```

- Eisen

  ```py
  # <- Subnet A11
  auto eth0
  iface eth0 inet static
    address 192.172.0.18
    netmask 255.255.255.252
    gateway 192.172.0.17

  # -> Subnet A5
  auto eth1
  iface eth1 inet static
    address 192.172.0.9
    netmask 255.255.255.252

  # -> Subnet A2
  auto eth2
  iface eth2 inet static
    address 192.172.0.5
    netmask 255.255.255.252

  # -> Subnet A1
  auto eth3
  iface eth3 inet static
    address 192.172.0.1
    netmask 255.255.255.252

  # -> Subnet A10
  auto eth4
  iface eth4 inet static
    address 192.172.0.41
    netmask 255.255.255.248
  ```

- Stark

  ```py
  # <- Subnet A1
  auto eth0
  iface eth0 inet static
    address 192.172.0.2
    netmask 255.255.255.252
    gateway 192.172.0.1
  ```

- Richter

  ```py
  # <- Subnet A10
  auto eth0
  iface eth0 inet static
    address 192.172.0.42
    netmask 255.255.255.248
    gateway 192.172.0.41
  ```

- Revolte

  ```py
  # <- Subnet A10
  auto eth0
  iface eth0 inet static
    address 192.172.0.43
    netmask 255.255.255.248
    gateway 192.172.0.41
  ```

- Lugner

  ```py
  # <- Subnet A2
  auto eth0
  iface eth0 inet static
    address 192.172.0.6
    netmask 255.255.255.252
    gateway 192.172.0.5

  # -> Subnet A3
  auto eth1
  iface eth1 inet static
    address 192.172.8.1
    netmask 255.255.252.0

  # -> Subnet A4
  auto eth2
  iface eth2 inet static
    address 192.172.1.1
    netmask 255.255.255.0
  ```

- TurkRegion (1000 Hosts)

  ```py
  # <- Subnet A3
  auto eth0
  iface eth0 inet static
    address 192.172.8.2
    netmask 255.255.252.0
    gateway 192.172.8.1
  ```

- GrobeForest (250 Hosts)

  ```py
  # <- Subnet A4
  auto eth0
  iface eth0 inet static
    address 192.172.1.2
    netmask 255.255.255.0
    gateway 192.172.1.1
  ```

- Linie

  ```py
  # <- Subnet A5
  auto eth0
  iface eth0 inet static
    address 192.172.0.10
    netmask 255.255.255.252
    gateway 192.172.0.9

  # -> Subnet A6
  auto eth1
  iface eth1 inet static
    address 192.172.0.13
    netmask 255.255.255.252

  # -> Subnet A7
  auto eth2
  iface eth2 inet static
    address 192.172.4.1
    netmask 255.255.254.0
  ```

- GranzChannel (254 Hosts)

  ```py
  # <- Subnet A7
  iface eth0 inet static
    address 192.172.4.2
    netmask 255.255.254.0
    gateway 192.172.4.1
  ```

- Lawine

  ```py
  # <- Subnet A6
  auto eth0
  iface eth0 inet static
    address 192.172.0.14
    netmask 255.255.255.252
    gateway 192.172.0.13

  # -> Subnet A8
  auto eth1
  iface eth1 inet static
    address 192.172.0.129
    netmask 255.255.255.192
  ```

- BredtRegion (25 Hosts)

  ```py
  # <- Subnet A8
  auto eth0
  iface eth0 inet static
    address 192.172.0.130
    netmask 255.255.255.192
    gateway 192.172.0.129
  ```

- Heiter

  ```py
  # <- Subnet A8
  auto eth0
  iface eth0 inet static
    address 192.172.0.159
    netmask 255.255.255.192
    gateway 192.172.0.129

  # -> Subnet A9
  auto eth1
  iface eth1 inet static
    address 192.172.16.1
    netmask 255.255.252.0
  ```

- Sein

  ```py
  # <- Subnet A6
  auto eth0
  iface eth0 inet static
    address 192.172.18.2
    netmask 255.255.252.0
    gateway 192.172.16.1
  ```

- RiegelCanyon (510 Hosts)

  ```py
  # <- Subnet A6
  auto eth0
  iface eth0 inet static
    address 192.172.16.2
    netmask 255.255.252.0
    gateway 192.172.16.1
  ```

### Routing

- Aura

  ```sh
  # Frieren
  route add -net 192.172.0.28 netmask 255.255.255.252 gw 192.172.0.26
  route add -net 192.172.0.96 netmask 255.255.255.224 gw 192.172.0.26

  route add -net 192.172.0.32 netmask 255.255.255.252 gw 192.172.0.26
  route add -net 192.172.24.0 netmask 255.255.248.0 gw 192.172.0.26

  route add -net 192.172.0.36 netmask 255.255.255.252 gw 192.172.0.26
  route add -net 192.172.0.64 netmask 255.255.255.248 gw 192.172.0.26

  route add -net 192.172.12.0 netmask 255.255.252.0 gw 192.172.0.26

  # Denken
  route add -net 192.172.2.0 netmask 255.255.255.0 gw 192.172.0.22

  # Eisen
  route add -net 192.172.0.0 netmask 255.255.255.252 gw 192.172.0.18
  route add -net 192.172.0.40 netmask 255.255.255.248 gw 192.172.0.18

  route add -net 192.172.0.4 netmask 255.255.255.252 gw 192.172.0.18
  route add -net 192.172.1.0 netmask 255.255.255.0 gw 192.172.0.18
  route add -net 192.172.8.0 netmask 255.255.252.0 gw 192.172.0.18

  route add -net 192.172.0.8 netmask 255.255.255.252 gw 192.172.0.18
  route add -net 192.172.0.12 netmask 255.255.255.252 gw 192.172.0.18
  route add -net 192.172.16.0 netmask 255.255.252.0 gw 192.172.0.18
  route add -net 192.172.0.128 netmask 255.255.255.192 gw 192.172.0.18
  route add -net 192.172.4.0 netmask 255.255.254.0 gw 192.172.0.18
  ```

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/0e963931-40ed-4346-b8dc-41cc653b0e5a">

- Denken

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/b22d81a1-fe71-4552-b7db-cae0dd093299">

- Frieren

  ```sh
  # Fern
  route add -net 192.172.0.32 netmask 255.255.255.252 gw 192.172.0.30
  route add -net 192.172.24.0 netmask 255.255.248.0 gw 192.172.0.30

  # Himmel
  route add -net 192.172.0.36 netmask 255.255.255.252 gw 192.172.0.30
  route add -net 192.172.0.64 netmask 255.255.255.248 gw 192.172.0.30

  route add -net 192.172.12.0 netmask 255.255.252.0 gw 192.172.0.30
  ```

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/a7193dda-951e-4411-a27c-cf767034d5fa">

- Flamme

  ```sh
  route add -net 192.172.24.0 netmask 255.255.248.0 gw 192.172.0.34
  route add -net 192.172.0.64 netmask 255.255.255.248 gw 192.172.0.38
  ```

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/486bb873-e752-43d6-a836-2f354eee11e0">

- Fern

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/06f129ed-af0e-42bc-b0b5-801498cec3a9">

- Himmel

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/1d76d497-61f3-477e-b241-f8407464ca94">

- Eisen

  ```sh
  # Lugner
  route add -net 192.172.1.0 netmask 255.255.255.0 gw 192.172.0.6
  route add -net 192.172.8.0 netmask 255.255.252.0 gw 192.172.0.6

  # Linie (Lawine)
  route add -net 192.172.0.12 netmask 255.255.255.252 gw 192.172.0.10
  route add -net 192.172.16.0 netmask 255.255.252.0 gw 192.172.0.10
  route add -net 192.172.0.128 netmask 255.255.255.192 gw 192.172.0.10
  route add -net 192.172.4.0 netmask 255.255.254.0 gw 192.172.0.10
  ```

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/5c7aa789-8950-49b4-b659-6232f2560b9f">

- Lugner

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/fa50d04b-37ea-4342-90ec-bc7a4a01368b">

- Linie

  ```sh
  route add -net 192.172.16.0 netmask 255.255.252.0 gw 192.172.0.14
  route add -net 192.172.0.128 netmask 255.255.255.192 gw 192.172.0.14
  ```

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/6a16bb08-9a57-4610-a97b-f5b1cb41aaa0">

- Lawine

  ```sh
  route add -net 192.172.16.0 netmask 255.255.252.0 gw 192.172.0.159
  ```

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/c9479ad9-1756-491e-bc0d-478bc2768b05">

- Heiter

  <img width="1000" alt="image" src="https://github.com/dimss113/Jarkom-Modul-4-A07-2023/assets/108170234/9df5c397-344e-45b3-a6c4-6cea6eb35141">
