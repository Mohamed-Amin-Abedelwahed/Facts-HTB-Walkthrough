# Facts.htb - Penetration Testing Walkthrough

A professionally formatted writeup documenting the full exploitation lifecycle of the **Facts.htb** machine from HackTheBox.

## Document Links
* 📄 [Download / View Full Walkthrough PDF](./DOC-20260613-WA0003.pdf)
* 🌐 [View Raw HTML Layout](./walkthrough.html)

## Exploit Chain Summary
* **Initial Access:** Authenticated Path Traversal via Camaleon CMS (CVE-2024-46987) to exfiltrate an encrypted SSH private key.
* **Privilege Escalation:** Exploiting Puppet Facter's `--custom-dir` flag to execute a malicious Ruby environment payload as root.
