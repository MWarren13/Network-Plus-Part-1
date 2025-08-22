# 7.2.7 Lab - View Network Device MAC Addresses

## Topology & Addressing Table

| Device | Interface | IP Address     | Subnet Mask     | Default Gateway |
|--------|-----------|----------------|------------------|------------------|
| S1     | VLAN 1    | 192.168.1.2    | 255.255.255.0    | N/A              |
| PC-A   | NIC       | 192.168.1.3    | 255.255.255.0    | 192.168.1.1      |

---

## Objectives

- **Part 1:** Configure Devices and Verify Connectivity  
- **Part 2:** Display, Describe, and Analyze Ethernet MAC Addresses

---

## Part 1: Configure Devices and Verify Connectivity

### Step 1: Cable the network as shown in the topology

**Screenshot Placeholder:**  
`![PC-A](Module 2\Physical Labs\Network Device MAC\PC-A.JPG)`

---

### Step 2: Configure the IPv4 address for the PC

- **Were the pings successful? Explain.**  
  _Answer: No_  

---

### Step 3: Configure basic settings for the switch

**Screenshot Placeholder:**  
`![Switch Configuration](Module 2\Physical Labs\Network Device MAC\Switch Config.JPG)

- **Were the pings successful?**  
  _Answer: Yes_  

---

## Part 2: Display, Describe, and Analyze Ethernet MAC Addresses

### Step 5: Analyze the MAC address for the PC-A NIC

1. **What is the OUI portion of the MAC address for this device?**  
   _Answer: 00-E0-4C_  

2. **What is the serial number portion of the MAC address for this device?**  
   _Answer: 68-07-86_  

3. **Using the example above, find the name of the vendor that manufactured this NIC.**  
   _Answer: REALTEK SEMICONDUCTOR CORP_  

4. **Identify the OUI portion of the MAC address for the NIC of PC-A.**  
   _Answer: 00-E0-4C_  

5. **Identify the serial number portion of the MAC address for the NIC of PC-A.**  
   _Answer: 68-0B-CD_  

6. **Identify the name of the vendor that manufactured the NIC of PC-A.**  
   _Answer: Realtek USB GbE Family Controller #2_  

---

### Step 6: Analyze the MAC address for the S1 VLAN 1 interface

1. **What is the MAC address for VLAN 1 on S1?**  
   _Answer:  192.168.1.2/24_  

2. **What is the MAC serial number for VLAN 1?**  
   _Answer: dc05.39ac.ae40_  

3. **What does BIA stand for?**  
   _Answer: Burned-In Address_  

4. **Why does the output show the same MAC address twice?**  
   _Answer: A single device uses multiple IP addresses on different VLANs_  

---

### Step 7: View the MAC addresses on the switch

1. **What Layer 2 addresses are displayed on S1?**  
   _Answer: 192.168.1.2    -   dc05.39ac.ae40_  

2. **What Layer 3 addresses are displayed on S1?**  
   _Answer: 192.168.1.3    -   00e0.4c68.0786_  

3. **Did the switch display the MAC address of PC-A? If yes, what port was it on?**  
   _Answer: No it did not._  

---

## Reflection Questions

1. **Can you have broadcasts at the Layer 2 level? If so, what would the MAC address be?**  
   _Answer: Yes, broadcasts can occur at the Layer 2 level, which involves sending data to all devices on a local network._  

2. **Why would you need to know the MAC address of a device?**  
   _Answer: It provides a unique, physical identifier essential for controlling network access, ensuring data packets reach the correct device on a local network, and diagnosing connectivity issues._  
