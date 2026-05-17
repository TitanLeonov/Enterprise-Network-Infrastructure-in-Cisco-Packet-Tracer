# Enterprise Network Infrastructure in Cisco Packet Tracer

## Описание проекта

Данный проект представляет собой корпоративную сеть, реализованную в Cisco Packet Tracer с использованием VLAN-сегментации, межвлановой маршрутизации, DHCP, ACL, DNS, WEB и FTP сервисов.

---

# Используемое оборудование

## Маршрутизатор
- Cisco 2911 Router

## Multilayer Switch
- Cisco Catalyst 3560-24PS

## Access Switches
- 6 × Cisco Catalyst 2960-24TT

## End Devices
- ПК пользователей
- Принтеры
- DNS/WEB Server
- FTP/File Server

---

# Топология сети

```text
                     Router 2911
                          |
                       Fa0/7
                    CORE-SW 3560
   ___________________________________________________
  |        |        |         |         |            |
ADMIN    SALES      IT    WAREHOUSE   SUPPORT     SERVERS
2960      2960     2960      2960      2960        2960
  |         |        |          |         |           |
PCs      PCs      PCs       PCs      PCs       DNS/WEB
Printer  Printer  Printer   Printer             FILE
```

---

# VLAN Архитектура

| VLAN | Department | Network |
|------|------------|----------|
| 10 | ADMIN | 192.168.10.0/24 |
| 20 | SALES | 192.168.20.0/24 |
| 30 | IT | 192.168.30.0/24 |
| 40 | WAREHOUSE | 192.168.40.0/24 |
| 50 | SUPPORT | 192.168.50.0/24 |
| 60 | SERVERS | 192.168.60.0/24 |

---


# Реализованные технологии

- VLAN
- Inter-VLAN Routing
- DHCP
- ACL
- DNS
- HTTP/HTTPS
- FTP
- SSH
- Layer 2 Switching
- Layer 3 Switching

---


---

# Цели проекта

Проект создавался для:
- изучения Cisco Networking
- практики VLAN и ACL
- понимания enterprise architecture
- подготовки к CCNA/CCNP
- моделирования корпоративной сети

---

# Возможные улучшения

В будущем планируется добавить:

- NAT/PAT
- Internet Simulation
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection
- EtherChannel
- STP Hardening
- OSPF/EIGRP
- Syslog
- NTP
- SNMP

---

# Леонов А.С.

Проект выполнен в рамках изучения сетевых технологий Cisco и enterprise network infrastructure.
