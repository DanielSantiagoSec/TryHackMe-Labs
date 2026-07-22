What Is Networking?

A network is simply a collection of connected entities that can communicate with each other.

In computing, networks connect devices such as laptops, phones, servers, IoT devices, and infrastructure systems.

Networks exist everywhere in daily life (transportation, power grids, postal systems), making networking a foundational concept for cybersecurity.

Networks can range in size from two devices to billions of devices globally.

Understanding how networks function is critical because cybersecurity relies on protecting these interconnected systems.

🌐 What Is the Internet?

The Internet is a massive network composed of many smaller networks connected together.

These smaller networks are typically private networks, while the Internet itself is considered a public network.

Devices communicate across networks using shared rules and protocols, allowing different systems to “speak the same language.”

The Internet originated from ARPANET in the late 1960s and evolved into its modern form with the creation of the World Wide Web in 1989.

The Internet enables global communication, information sharing, and resource access.

🆔 Identifying Devices on a Network

Devices must be identifiable to communicate effectively.

Devices use two main identifiers, similar to how humans use names and fingerprints:

IP Address (changeable)

MAC Address (hardware-based, intended to be unique)

📍 IP Addresses

An IP address identifies a device on a network for a period of time.

IPv4 addresses consist of four numerical octets (e.g., 192.168.1.1).

A device cannot share the same IP address with another device on the same network simultaneously.

Devices may have:

Private IP addresses (used within local networks)

Public IP addresses (used to communicate on the Internet)

Multiple devices on a private network often share a single public IP address provided by an ISP.

IPv4 has a limited number of addresses (~4.29 billion), leading to the development of IPv6.

IPv6 greatly expands address capacity and improves efficiency.

🧬 MAC Addresses

A MAC address is a unique identifier assigned to a device’s network interface at the factory.

It is a 12-character hexadecimal value (e.g., a4:c3:f0:85:ac:2d).

The first half identifies the manufacturer; the second half uniquely identifies the device.

MAC addresses can be spoofed, which introduces security risks.

Poorly designed security controls that trust MAC addresses alone can be bypassed.

Public Wi-Fi networks often use MAC filtering to manage access and service levels.

⚠️ Security Insight

Trusting identifiers like MAC addresses without additional authentication is insecure.

Spoofing techniques can allow unauthorized devices to bypass access controls.

This highlights the importance of layered security and proper network design.

📡 Ping (ICMP)

Ping is a fundamental network diagnostic tool.

It uses ICMP echo requests and replies to test connectivity and measure response time.

Ping can determine:

Whether a device is reachable

How reliable or responsive a connection is

It works on both private networks and public Internet hosts.

Ping is commonly used in troubleshooting and network validation.

🧠 Key Takeaway
