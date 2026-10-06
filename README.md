# James Cherny IV

Cyber defense student at the University of Arizona. I run a Proxmox home lab on a Dell PowerEdge R630 and treat it like production: a separate access key for every system, default-deny firewalls, and backups I have actually restored.

Looking for cybersecurity and security operations internships in Tucson, remote, or hybrid.

## Start here

**[homelab-hardening](https://github.com/Sqxirts/homelab-hardening)** is my lab's security baseline as code: SSH, fail2ban, firewall and VPN policy, plus `verify-baseline.sh`, which reads each host's live settings and fails when they drift from the standard. Applying a baseline is easy. Knowing it still applies three months later is the part I built this for.

Two incident write-ups from that work:

- [The VPN exit node that ate 40% of my download speed](https://github.com/Sqxirts/homelab-hardening/blob/main/writeups/exit-node-bandwidth.md): 491 Mbps on an 800 Mbps line, and the cause was two layers above the network card I spent two hours tuning.
- [Access review: my VPN was allow-all](https://github.com/Sqxirts/homelab-hardening/blob/main/writeups/vpn-access-review.md): a guest laptop could reach every server, so I rewrote the policy to grant only what each person needs.

## Other projects

- **[palworld-docker-server](https://github.com/Sqxirts/palworld-docker-server)**: containerized Palworld dedicated server with Docker Compose, secrets kept out of the repo
- **[minecraft-docker-server](https://github.com/Sqxirts/minecraft-docker-server)**: Paper Minecraft server with Docker Compose, secrets kept out of the repo
- **[video-transcriber](https://github.com/Sqxirts/video-transcriber)**: local video and audio transcription (yt-dlp and faster-whisper) in a hardened LXC container
- **[pihole-tui](https://github.com/Sqxirts/pihole-tui)**: terminal UI for Pi-hole stats
- **[system-cleanup](https://github.com/Sqxirts/system-cleanup)**: interactive Windows disk cleanup script
- **[james-portfolio](https://github.com/Sqxirts/james-portfolio)**: source for my personal site, static HTML and CSS

## What I work with

Proxmox VE, LXC, Linux, Tailscale, Pi-hole, fail2ban, ufw, Docker, Python, Bash, C

## Contact

[LinkedIn](https://www.linkedin.com/in/james-cherny-iv)
