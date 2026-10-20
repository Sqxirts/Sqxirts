# James Cherny IV

Cyber Defense student at the University of Arizona. I like building things to find out how they work and where they break, and I'm looking to learn as much of the field as I can. Open to entry-level roles in security and engineering.

## Projects

**[lectern](https://github.com/Sqxirts/lectern)**
An add-on for Obsidian, a popular note-taking app, that lets you open Word, Excel, and PowerPoint files right inside your notes. Slides are rebuilt as web pages, so you can select and copy their text. To check accuracy, I compare screenshots of my version against PowerPoint's own output pixel by pixel instead of judging by eye. Comments you leave are saved as ordinary text files, so they stay readable even without the add-on. It's approved and listed in Obsidian's official plugin directory.

**[homelab-hardening](https://github.com/Sqxirts/homelab-hardening)**
I run a small server at home that hosts several isolated mini-servers. This project is the set of security rules they all follow (who can log in, what network traffic is allowed, how repeated failed logins get blocked), written as scripts so every machine gets the same setup. It also includes a checker that inspects each machine's current settings and flags anything that has quietly changed. Setting security up once is easy; this confirms it still holds months later.
- [Write-up: why routing my internet through my home VPN cut my download speed by 40%](https://github.com/Sqxirts/homelab-hardening/blob/main/writeups/exit-node-bandwidth.md)
- [Write-up: finding that every device on my VPN could reach every server, and locking it down](https://github.com/Sqxirts/homelab-hardening/blob/main/writeups/vpn-access-review.md)

**kraken-trader** (private)
A research tool for testing cryptocurrency trading strategies on the Kraken exchange. It's built to prove a strategy wrong before it costs money: tests run on historical prices with no way to peek at future data, trading fees are counted, and anything new runs with fake money first. No strategy has passed yet, so it doesn't trade with real money.

## Smaller projects

- [video-transcriber](https://github.com/Sqxirts/video-transcriber): turns video and audio into text, running entirely on my own hardware
- [pihole-tui](https://github.com/Sqxirts/pihole-tui): a text-based dashboard for Pi-hole, a network-wide ad blocker
- [minecraft-docker-server](https://github.com/Sqxirts/minecraft-docker-server) and [palworld-docker-server](https://github.com/Sqxirts/palworld-docker-server): game servers packaged so they can be rebuilt with one command, with passwords kept out of the code
- [system-cleanup](https://github.com/Sqxirts/system-cleanup): a guided disk cleanup script for Windows
- [portfolio](https://github.com/Sqxirts/james-portfolio): my personal website

## Tools

- **Languages:** Python, Bash (Linux scripting), TypeScript
- **Systems:** Linux, Docker, Proxmox
- **Other:** Git, Tailscale (private VPN between my devices)

## Contact

[LinkedIn](https://www.linkedin.com/in/james-cherny-iv)
