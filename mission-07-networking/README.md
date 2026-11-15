# Mission 7 — How Computers Communicate

## 1. Task / Objective

Understand basic computer networking concepts, perform network connectivity and DNS lookup tests using Terminal, and explain how computers communicate when opening a website.

## 2. Work Completed

- Studied LAN, MAN and WAN.
- Learned about DNS, routers and network protocols.
- Understood packet switching and the client-server model.
- Tested network connectivity using the `ping` command.
- Performed a DNS lookup using `nslookup`.
- Recorded the observations from both commands.
- Explained the process of opening a website step by step.

### Network Concepts

| Concept | Explanation | Example |
|---|---|---|
| LAN | Network covering a small geographical area. | Home Wi-Fi |
| MAN | Network covering a city or large campus. | City-wide network |
| WAN | Network covering large geographical areas. | Internet |
| DNS | Converts domain names into IP addresses. | Resolving example.com |
| Router | Connects networks and forwards data between them. | Wi-Fi router |
| Protocol | Rules followed by devices to communicate. | HTTP, HTTPS, TCP |
| Packet Switching | Divides data into smaller packets for transmission. | Sending a photo |
| Client-Server | Client requests a service and server provides it. | Browser and web server |

## 3. Commands / Tools Used

| Command / Tool | Purpose |
|---|---|
| `ping -c 4 example.com` | Tests connectivity by sending four packets. |
| `nslookup example.com` | Finds IP addresses associated with a domain name. |
| Terminal | Used to execute networking commands. |

## 4. My Understanding

A computer network connects devices so they can exchange information and share resources.

- LAN covers a small geographical area.
- MAN covers a city or large campus.
- WAN covers large geographical areas.
- DNS converts human-readable domain names into IP addresses.
- A router connects networks and forwards data.
- Protocols define rules for communication between devices.
- Packet switching transfers data in smaller packets.
- In the client-server model, a client requests information and a server responds.

### Connectivity Test Observation

Command executed:

`ping -c 4 example.com`

**Observed results:**

- Packets transmitted: 4
- Packets received: 4
- Packet loss: 0%
- Average round-trip time: approximately 9.05 ms

**Conclusion:** All four packets received responses, which showed that my computer could successfully reach example.com during the test.

### DNS Lookup Observation

Command executed:

`nslookup example.com`

**Observed results:**

- DNS lookup completed successfully.
- DNS server used: 8.8.8.8
- The domain resolved to two IP addresses.

**Conclusion:** DNS successfully found the IP addresses associated with example.com. This demonstrated how DNS helps browsers locate website servers using domain names.

## 5. What Happens When We Open a Website?

1. **User request:** The user enters a website address into a web browser.
2. **Client:** The browser acts as a client and prepares a request.
3. **DNS lookup:** DNS finds the IP address associated with the website's domain name.
4. **Network connection:** The request travels through the router and network towards the destination server.
5. **Protocol:** The browser and server communicate using protocols such as HTTPS.
6. **Server response:** The server processes the request and sends the requested website data back.
7. **Display:** The browser receives the response, processes the website content and displays it to the user.

## 6. Difficulties Faced

Initially, understanding DNS, packet switching and the client-server model was confusing. It was also difficult to understand how a website name gets converted into an IP address.

## 7. How I Resolved Them

Studied simple networking examples and performed connectivity and DNS lookup commands in Terminal. Observing the command outputs helped me understand how devices communicate and how DNS resolves domain names.

## 8. Evidence / Files

- `mission-07-networking/README.md` — Mission documentation.
- Ping command output showing 4 successful responses and 0% packet loss.
- DNS lookup output for example.com.
- Network concepts table.
- Seven steps explaining website communication.

## 9. Commit Details

**Suggested commit message:** `Explain networking concepts and website communication`

**Files included:** `mission-07-networking/README.md`

The README is prepared and saved locally. The Mission 7 commit and GitHub push are pending.