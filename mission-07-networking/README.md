# Mission 7 — How Computers Communicate

## 1. Task / objective

The objective of this mission was to understand basic computer networking concepts, observe network connectivity and DNS lookup using Terminal, and explain how computers communicate when opening a website.

## 2. Work completed

- Studied LAN, MAN and WAN.
- Learned about DNS, routers and network protocols.
- Understood packet switching and the client-server model.
- Tested network connectivity using the ping command.
- Performed a DNS lookup using nslookup.
- Documented the steps involved in opening a website.

### Task 7.1 — Network concepts

| Concept | Explanation | Example |
|---|---|---|
| LAN | A network covering a small geographical area. | Home Wi-Fi network |
| MAN | A network covering a city or large campus area. | City-wide network |
| WAN | A network covering large geographical areas. | The Internet |
| DNS | Translates a domain name into an IP address. | google.com |
| Router | Connects networks and forwards data between them. | Home Wi-Fi router |
| Protocol | A set of rules devices follow to communicate. | HTTP, HTTPS |
| Packet switching | Data is divided into smaller packets that travel across a network. | Sending data over the Internet |
| Client-server | A client requests a service and a server provides it. | Browser requesting a webpage |

### Task 7.2 — Network observations

**Commands used:**

1. `ping -c 4 example.com`
2. `nslookup example.com`


**Connectivity test observations:**

- Packets transmitted: 4
- Packets received: 4
- Packet loss: 0%
- Average response time: 6.403 ms

The ping command checks whether a destination can be reached over the network and measures response time.

**DNS lookup observations:**

- Domain name: example.com
- DNS server: 8.8.8.8
- Resolved IP addresses:
  - 172.66.147.243
  - 104.20.23.154

The nslookup command displays DNS information and helps find the IP address associated with a domain name.

DNS is important because people can remember website names more easily than numerical IP addresses.

### Task 7.3 — What happens when you open a website?

1. The user enters a website address in the browser.
2. The browser acts as a client and requests the website.
3. DNS finds the IP address associated with the domain name.
4. The request travels through the network and router.
5. The server receives and processes the request.
6. The server sends the webpage data back using network protocols such as HTTPS.
7. The browser receives the response and displays the webpage to the user.

## 3. Commands / tools used

| Command / Tool | Purpose |
|---|---|
| `cd` | Moves into the assignment directory. |
| `ping -c 4 google.com` | Tests network connectivity using four packets. |
| `nslookup google.com` | Looks up DNS information for a domain. |
| Terminal | Used to execute network commands. |

## 4. My understanding

I learned that computer networks allow devices to communicate and share information. LAN, MAN and WAN describe networks based on their geographical coverage. DNS converts domain names into IP addresses, while routers forward data between networks. Packet switching divides information into smaller packets, and client-server communication allows clients to request services from servers.

## 5. Difficulties faced

Initially, I was learning how connectivity testing and DNS lookup work.

## 6. How I resolved them

I executed the ping and nslookup commands in macOS Terminal and studied their outputs to understand network connectivity and DNS resolution.

## 7. Evidence / files

- README.md
- Terminal output showing successful ping test.
- Terminal output showing DNS lookup for google.com.

## 8. Commit details

Commit message: Explain networking concepts and website communication.

The Mission 7 README and observations are ready to be committed and pushed to GitHub.