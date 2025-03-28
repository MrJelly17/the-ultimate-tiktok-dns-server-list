# The Ultimate TikTok DNS Server List

"The Ultimate TikTok DNS Server List" is a public repository containing a comprehensive and up-to-date list of TikTok's DNS servers and main domains. This list is intended for use with tools like Pi-hole, AdGuard Home, NextDNS, and others that allow blocking website and application access through DNS query filtering.  The list is now categorized for improved clarity.

## How to Use

1. **Download the DNS List**
   The list of TikTok DNS servers and domains is available in the `tiktok-dns.txt` file in this repository. You can download it directly or clone the repository using the following command:

   ```
   git clone https://github.com/MrJelly17/The-Ultimate-Tiktok-DNS-Server-List.git
   ```

2. **Import into Your Filtering Tool**
- **Pi-hole**: Add the DNS entries from `tiktok-dns.txt` to your Pi-hole's blacklist.  Remember to separate the main domains and subdomains appropriately within your Pi-hole configuration.
- **AdGuard Home**: Import the DNS entries into the blocklist section of AdGuard Home.  Similarly, consider separating the entries for better organization.
- **NextDNS**: Copy the DNS entries into your NextDNS denylist.

3. **Apply Changes**
After importing the list, ensure you apply the changes and restart your DNS filtering tool if necessary.

## Purpose

This list is designed to block access to TikTok by preventing DNS queries to TikTok's servers and main domains. It is particularly useful for parents, network administrators, or anyone looking to restrict access to TikTok on their network.

## Updates

The DNS list will be regularly updated to ensure it remains effective. Check back frequently or subscribe to updates to stay informed about changes.

## Repository Link

[GitHub Repository](https://github.com/MrJelly17/The-Ultimate-Tiktok-DNS-Server-List.git)
