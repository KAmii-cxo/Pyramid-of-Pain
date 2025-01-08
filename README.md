
# Pyramid of Pain 🛡️

The Pyramid of Pain is a cybersecurity framework that highlights how different types of Indicators of Compromise (IOCs) impact attackers and defenders.

## Levels of the Pyramid
![Pyramidofpain](https://www.attackiq.com/wp-content/uploads/2019/06/blog-pyramid-pain-01-768x432.jpg)

1. **Hash Values**
   - Unique IDs for files (e.g., MD5, SHA256).
   - Easy to detect and block.
   - Attackers can quickly change these.

2. **IP Addresses**
   - Identifies the source of malicious activity.
   - Blocking helps, but attackers often use dynamic IPs or proxies.

3. **Domain Names**
   - Malicious domains used by attackers.
   - Blocking domains disrupts attackers but they can register new ones.

4. **Network/Host Artifacts**
   - Patterns like HTTP headers or filenames.
   - Requires more analysis to detect.
   - Harder for attackers to change.

5. **Tools**
   - Malware or scripts used by attackers.
   - Detecting their tools forces them to find new ones.

6. **Tactics, Techniques, and Procedures (TTPs)**
   - How attackers operate (e.g., lateral movement methods).
   - Detecting TTPs causes major disruption to attackers.

## Key Takeaway

The higher up the pyramid you go:
- Detection becomes harder.
- The impact on attackers becomes greater.

Focusing on **TTPs** gives long-term benefits and forces attackers to rethink their strategies.

## How I Use It

- Understanding this concept helps in threat hunting and creating stronger defenses.
- Tools like Splunk and Wireshark are useful for analyzing activity at higher levels of the pyramid.
- It’s a mindset shift: not just reacting to threats but anticipating and disrupting attackers.

## Let’s Connect!

I’m on a journey to becoming a SOC Analyst, focusing on threat hunting and malware analysis. If this resonates with you, let’s collaborate!
