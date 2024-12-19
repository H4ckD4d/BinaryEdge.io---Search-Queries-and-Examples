# BinaryEdge.io---Search-Queries-and-Examples
BinaryEdge.io - Search Queries and Examples

BinaryEdge provides powerful search capabilities to query data for cybersecurity investigations. Below is a guide to the key fields, syntax, and examples to help you maximize its potential.

---

## **Fields and Syntax**

| **Field**    | **Description**                                                                 | **Example Syntax**                           | **Details**                                                                 |
|--------------|---------------------------------------------------------------------------------|----------------------------------------------|-----------------------------------------------------------------------------|
| **ip**       | Query by target IP or CIDR (in quotes).                                         | `ip:"149.202.178.130/16"`                    | Search for specific IP or range.                                           |
| **port**     | Filter by port number.                                                         | `port:80`                                    | Identify services running on specific ports.                               |
| **country**  | Filter results by country ISO code.                                            | `country:FR`                                 | Search for results originating from France.                                |
| **ASN**      | Query by Autonomous System Number (ASN).                                       | `asn:1234`                                   | Analyze assets or traffic associated with a specific ASN.                  |
| **type**     | BinaryEdge module type.                                                        | `type:mongodb`                               | Search for exposed MongoDB instances.                                      |
| **product**  | Filter by product name.                                                        | `product:apache2`                            | Look for assets running a specific product or service.                     |
| **ipv6**     | Filter IPv6 results.                                                          | `ipv6:true`                                  | Set `true` for IPv6 results or `false` for IPv4.                           |
| **tag**      | Use available tags for specific categories.                                    | `tag:web`                                    | Explore tagged data for specific categories like `web`, `iot`, or `ssl`.   |

---

## **Examples**

| **Use Case**                                  | **Query**                                                | **Description**                                                                 |
|-----------------------------------------------|----------------------------------------------------------|---------------------------------------------------------------------------------|
| SSL from a specific organization              | `"Example Org" type:ssl`                                 | Search for SSL certificates associated with "Example Org".                     |
| CIDR and Port                                 | `ip:"149.202.178.130/16" port:80`                        | Search for assets in a CIDR range on port 80.                                  |
| Country with specific port                    | `country:FR port:443`                                    | Locate HTTPS services (port 443) in France.                                    |
| Exposed Dropbear SSHD                         | `product:"Dropbear sshd"`                                | Identify systems running Dropbear SSH daemon.                                  |
| Exposed MongoDB Databases                     | `type:mongodb`                                           | Query for open MongoDB instances.                                              |
| IPv6 Assets                                   | `ipv6:true`                                              | Filter results to show only IPv6 assets.                                       |
| Open RDP Ports                                | `port:3389`                                              | Find exposed Remote Desktop Protocol services.                                 |
| Cloud Provider Usage                          | `tag:cloud`                                              | Explore cloud-based resources.                                                 |
| Specific HTTP Headers                         | `header:"X-Content-Type-Options: nosniff"`               | Search for assets with specific HTTP headers in responses.                     |

---

## **Historical Data Access**

- **Query Historical IP Data**: Retrieve up to 6 months of historical data for an IP address.  
  Example:  
  ```url
  https://docs.binaryedge.io/api-v2/#v2queryiphistoricaltarget





# Community Collaboration Message

## About Me

Hi everyone! I’m **Ch312 C3uZ**, also known as **H4ckd4d** or **The Bond of Brazil**, an ethical hacker and cybersecurity expert with decades of experience in uncovering hidden threats and defending those who can’t defend themselves. My career has been dedicated to dismantling criminal networks, rescuing victims, and creating innovative technologies to combat global threats.

From uncovering government corruption to developing tools that expose child predators and human traffickers, my journey combines **advanced cybersecurity expertise, AI innovations, and a deep commitment to humanitarian causes**. I’ve been on the front lines of digital and real-world operations, where my knowledge of cryptography, ethical hacking, and cyber-forensics has saved lives and made our online spaces safer.

My mission is clear: **protect the vulnerable, stop the predators, and build a better, more secure world.**

## Why I Need Your Help

I’m reaching out to the global hacking community and anyone passionate about making a difference. Together, we can tackle some of the most critical challenges, from child safety to fighting trafficking and cybercrime. The power of community is unmatched, and your contributions can save lives.

### How You Can Contribute:
- **Develop Tools:** Collaborate on building advanced AI systems, detection algorithms, and cyber monitoring tools.
- **Spread Awareness:** Share tips, resources, and educational content to empower others with knowledge.
- **Volunteer Your Skills:** Whether you’re an ethical hacker, coder, educator, or advocate, your unique abilities can make an impact.
- **Join the Mission:** Help uncover threats, provide intelligence, and be part of a network committed to humanitarian defense.

Let’s turn our skills into a force for good. Together, we can protect children, expose criminals, and make the internet—and the world—a safer place for everyone.

---

### My Slogan

**"Predators and child traffickers, you will be found, and the children will be saved! This is my mission: to find you!"**

  
