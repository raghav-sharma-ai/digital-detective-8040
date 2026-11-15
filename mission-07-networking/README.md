# MISsION 7 — How Computers Communicate

## 1. Task

The objective of this mission was to understand how computers communicate with each other through networks. I learned about different types of networks, DNS, routers, protocols, packet switching and the client-server model.

I also used Terminal to perform a connectivity test and a DNS lookup. Finally, I studied the steps involved when a user opens a website in a browser.

## 2. Work completed

In this mission, I completed the following activities:

- Studied the basic concepts of computer networking.
- Understood the differences between LAN, MAN and WAN.
- Learned the roles of DNS, routers and network protocols.
- Understood packet switching and the client-server model.
- Used Terminal to check connectivity with a public example website.
- Performed a DNS lookup for `example.com`.
- Studied how a browser communicates with a web server.
- Prepared a step-by-step explanation of how a website opens.

### Task 7.1 — Network concepts

A computer network is a group of connected devices that communicate and exchange information with each other.

The following table explains the important networking concepts:

| Concept | Explanation | Example |
|---|---|---|
| LAN (Local Area Network) | A network that connects devices within a small geographical area. | Computers connected to the same home, college lab or office network. |
| MAN (Metropolitan Area Network) | A network that covers a larger area, such as a city or a large campus. | A network connecting different branches of an organisation across a city. |
| WAN (Wide Area Network) | A network that covers large geographical areas and connects smaller networks. | The Internet is the biggest example of a WAN. |
| DNS (Domain Name System) | DNS converts a website's domain name into an IP address that computers use to locate the server. | Converting `google.com` into its corresponding IP address. |
| Router | A router connects different networks and forwards data towards its destination. | A home Wi-Fi router connecting devices to the Internet. |
| Protocol | A protocol is a set of rules that devices follow to communicate and exchange data. | HTTP and HTTPS are used for communication between browsers and websites. |
| Packet switching | It is a method in which data is divided into smaller units called packets before being sent across a network. | A webpage's data travelling through a network in multiple packets. |
| Client-server | A communication model where a client requests a service and a server provides the requested service. | A browser requesting a webpage from a website's server. |

### Task 7.2 — Network observations using Terminal

I used Terminal to check whether my computer could reach a public website and to understand how DNS finds the network address of a domain.

#### A. Connectivity test

**Command used:**

`ping -c 4 example.com`

**Purpose:**

The `ping` command sends network messages to another device or server to check whether it can be reached.

The `-c 4` option tells the command to send four test messages and then stop.

**What I observed:**

- The domain `example.com` was successfully resolved to an IP address.
- Four packets were transmitted.
- All four packets were received.
- Packet loss was 0%.
- The minimum response time was approximately 5.706 milliseconds.
- The average response time was approximately 8.609 milliseconds.
- The maximum response time was approximately 15.968 milliseconds.

**What I understood:**

My computer was able to communicate with the example website during this test. Since all four packets were received and there was no packet loss, the connectivity test was successful.

The response time shows how long it took for the test messages to travel to the destination and for the replies to return.

#### B. DNS lookup

**Command used:**

`nslookup example.com`

**Purpose:**

The `nslookup` command is used to find DNS information about a domain name. It helps us see which IP addresses are associated with the domain.

**What I observed:**

- The DNS server used for the lookup was `8.8.8.8`.
- The lookup returned two IPv4 addresses for `example.com`:
  - `172.xx.xxx.xxx`
  - `104.xx.xx.xxx`
- The result was labelled as a non-authoritative answer.

**What I understood:**

DNS works like the phonebook of the Internet. Humans generally remember website names more easily than IP addresses.

When we enter a website name in a browser, DNS helps find the corresponding IP address so that the computer can contact the correct server.

The non-authoritative answer means the response was provided by a DNS resolver using its available DNS information, rather than directly by the domain's authoritative DNS server.

#### Difference between ping and nslookup

| Command | Purpose |
|---|---|
| `ping` | Checks whether a destination responds to network messages. |
| `nslookup` | Looks up DNS information for a domain name. |

Both commands help us understand different parts of networking. `ping` is used for connectivity testing, while `nslookup` is used for DNS information.

### Task 7.3 — What happens when you open a website?

When a user enters a website address in a browser, several steps happen in the background.

1. **User enters the website address:** The user types a domain name, such as `example.com`, into the browser. The browser acts as a client because it requests information from another computer.

2. **Browser checks DNS:** The browser needs the server's IP address. DNS helps translate the domain name into an IP address.

3. **Computer connects to the network:** The computer uses its network connection and router to send data towards the destination.

4. **Request reaches the server:** The browser sends a request to the website's server using suitable network protocols, such as HTTPS.

5. **Server processes the request:** The server receives the request, processes it and prepares the required webpage information.

6. **Server sends a response:** The server sends the requested data back through the network in packets.

7. **Browser displays the webpage:** The browser receives the response, processes the website's content and displays the webpage to the user.

This process allows users to access websites and exchange information with servers located anywhere in the world.

## 3. Commands 

| Command / Tool | Purpose |
|---|---|
| `ping -c 4 example.com` | Sends four connectivity test messages to a public example domain. |
| `nslookup example.com` | Looks up DNS information for the example domain. |
| Terminal | Used to execute networking commands and observe their output. |
| Web browser | Used to understand how clients request webpages from servers. |
| Markdown / README | Used to document networking concepts and observations. |

## 4. My understanding

Before this mission, I knew that computers could connect through the Internet, but I did not understand what happens behind the scenes.

I learned that networks allow devices to communicate and share information. LAN, MAN and WAN describe networks based on the geographical area they cover.

I understood that DNS converts domain names into IP addresses, while routers help forward data between networks. Protocols provide rules for communication, and packet switching allows data to travel in smaller packets.

I also learned about the client-server model. A browser works as a client that sends requests, while a server processes those requests and sends responses.

The most interesting part was understanding that opening a website involves several networking operations even though the process looks very simple to the user.

## 5. Difficulties faced
I was also confused about the roles of DNS and routers because both are involved when a computer connects to a website.

Understanding the difference between a connectivity test and a DNS lookup also required some practice.

## 6. How I resolved them

I used `ping` and `nslookup` in Terminal to observe how connectivity testing and DNS lookup work differently.

I also broke down the website-opening process into smaller steps to understand how the browser, DNS, router and server communicate.

## 7. Evidence 

- `README.md` — Contains the networking concepts, command explanations and website communication process.
- Terminal connectivity test — Output of `ping -c 4 example.com`, showing four packets received and 0% packet loss.
- DNS lookup observation — Output of `nslookup example.com`, showing the DNS resolver and the IP addresses returned for the domain.

## 8. Commit details
- **Commit Message**: "Explained networking concepts and website communication"
- **Pushed to GitHub**: Yes (Verified visible on GitHub repository)