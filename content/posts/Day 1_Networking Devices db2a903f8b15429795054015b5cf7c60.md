---
title: "CCNA: Networking Devices"
date: 2023-12-12T14:40:10-07:00
draft: false
tags: ["Networking"]
categories: ["CCNA"]
---


## **Networking Devices**

> Computer Network : a digital telecommunications network which allows nodes to share resources.
> 

```
    * Example of Computer Network *
            - Router
            - Switch
            - Firewall
            - Client
            - Server
```

## **Building a Network**

> Building a network can be as simply 2 PC’s connected together.
 

**Client** : is a device that accesses a service made available by a server. **Server** : is a device that provides functions or services for the clients.

```
The same device can be a client in some situation, and a server in other situation.
```

## Switches

- Switches have many network interfaces/ Ports for end host to connect to (usually upto 24+ ports).
- Switches provide connectivity to hosts within the same LAN (Local Area Network). *
- Switches do not provide connectivity between LANs/ over the internet.

```
```
 Examples of Switches | These are Cisco
    1. Catalyst 9200  |  appliances for enterprised network
    2. Catalyst 3650  |

```
```

![image](/Day%201_Networking%20Devices%20db2a903f8b15429795054015b5cf7c60/Untitled.png)

![image](/Day%201_Networking%20Devices%20db2a903f8b15429795054015b5cf7c60/Untitled%201.png)

### **Routers**

- Have fewer network interface than switches.
- Are used to provide connectivity between LANs.
- Routers are used to sent data over the internet.
    
    ```
    Examples of Routers
        1. ISR 1000 |  (ISR) stands for "Integrated Service Router"
        2. ISR 900  |  These are Cisco router appliances for enterprise network
        3. ISR 4000 |
    ```
    
    ![image](/Day%201_Networking%20Devices%20db2a903f8b15429795054015b5cf7c60/Untitled%202.png)
    

![image](/Day%201_Networking%20Devices%20db2a903f8b15429795054015b5cf7c60/Untitled%203.png)

![image](/Day%201_Networking%20Devices%20db2a903f8b15429795054015b5cf7c60/Untitled%204.png)

### **Firewall**

- Monitors and control network traffic based on configured rules.
- Can be placed ‘inside’ the network or ‘outside’ the network.
    - (Inside) ; filters traffic after it passes the router.
    - (Outside) ; filters traffic before it passes the router.
- Firewall are considered “Next-Generation” when they include more modern and advanced filtering capabilities.

```
    Examples of Firewalls
        1. ASA 550-x      | (ASA) stands for "Adaptive Security Appliances"
        2. Firepower 2100 |  These are Cisco firewall hardware appliances.
```

![image](/Day%201_Networking%20Devices%20db2a903f8b15429795054015b5cf7c60/Untitled%205.png)

![image](/Day%201_Networking%20Devices%20db2a903f8b15429795054015b5cf7c60/Untitled%206.png)

### **Types of Firewalls**

- Network Firewalls are “hardware devices” that filter traffic between networks.
- Host-Based Firewalls: “software applications” that filter traffic entering and exiting a host machine like a PC.