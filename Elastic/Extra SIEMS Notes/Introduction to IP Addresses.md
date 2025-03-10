## Introduction to IP Addresses

- **What is an IP Address?**: An IP address is a unique numerical identifier assigned to devices connected to a network. It allows devices to communicate with each other over the internet or local networks.
    
- **Format**: IP addresses are typically expressed in a dotted-decimal format, such as `192.168.1.1`, for IPv4. IPv6 addresses are longer and use hexadecimal notation, like `2001:0db8:85a3:0000:0000:8a2e:0370:7334`.
    

## Public vs. Private IP Addresses

1. **Public IP Addresses**:
    
    - **Definition**: Public IP addresses are unique and globally routable. They are assigned by Internet Service Providers (ISPs) and are visible to the internet.
        
    - **Use**: Public IP addresses are necessary for devices that need to be accessed from the internet, such as web servers.
        
    - **Example**: `8.8.8.8` is a public IP address used by Google's DNS server.
        
2. **Private IP Addresses**:

	**Definition**: Private IP addresses are reserved for use within private networks and are not routable on the internet. The most common private IP address ranges are defined by RFC 1918 and include:

1. **10.0.0.0 to 10.255.255.255** (Class A)
    
    - Number of Addresses: 16,777,216
        
    - Subnet Mask: 255.0.0.0
        
    - Use: Large networks.
        
2. **172.16.0.0 to 172.31.255.255** (Class B)
    
    - Number of Addresses: 1,048,576
        
    - Subnet Mask: 255.240.0.0
        
    - Use: Medium-sized networks.
        
3. **192.168.0.0 to 192.168.255.255** (Class C)
    
    - Number of Addresses: 65,536
        
    - Subnet Mask: 255.255.0.0
        
    - Use: Small networks.

## IP Address Classes

Historically, IP addresses were divided into five classes (A, B, C, D, and E) based on the first octet of the IP address. This system is less commonly used today due to the introduction of Classless Inter-Domain Routing (CIDR), but it's still useful for understanding IP address allocation:

1. **Class A**:
    
    - **Range**: `0.0.0.0` to `127.255.255.255`.
        
    - **Network ID**: First octet.
        
    - **Host ID**: Last three octets.
        
    - **Use**: Large networks with many hosts.
        
2. **Class B**:
    
    - **Range**: `128.0.0.0` to `191.255.255.255`.
        
    - **Network ID**: First two octets.
        
    - **Host ID**: Last two octets.
        
    - **Use**: Medium-sized networks.
        
3. **Class C**:
    
    - **Range**: `192.0.0.0` to `223.255.255.255`.
        
    - **Network ID**: First three octets.
        
    - **Host ID**: Last octet.
        
    - **Use**: Small networks.
        
4. **Class D**:
    
    - **Range**: `224.0.0.0` to `239.255.255.255`.
        
    - **Use**: Multicast addresses.
        
5. **Class E**:
    
    - **Range**: `240.0.0.0` to `254.255.255.255`.
        
    - **Use**: Reserved for future use.
        

## Key Points for Remembering

- **Public IP Addresses**: Globally unique and visible to the internet.
    
- **Private IP Addresses**: Not globally routable, used within local networks.
    
- **IP Address Classes**: A way to categorize IP addresses based on their first octet, though less commonly used today.