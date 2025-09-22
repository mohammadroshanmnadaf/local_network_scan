# local_network_scan

## 📌 Objective
Discover open ports on devices in a local network to understand potential network exposure.

## 🛠 Tools Used
- **Nmap**– For scanning the local network and discovering open ports.
- **VS Code/Notepad** – To organize files and document results.

## 📋 Steps Performed
1. Identified the local network range ('192.168.X.0/24') for scanning.  
2. Ran Nmap scans using:
   - '-sS' (SYN scan – stealthy and fast).
   - '-sT' (TCP connect scan – full TCP handshake).
3. Saved scan results as 'nmap_scan_results.txt' (masked IP addresses for privacy).  
4. Found common services running on detected open ports.  
5. Identified **potential security risks** associated with the discovered open ports.  
6. Organized all related files for submission.

## 📂 Files Included 
- 'nmap_scan_results.txt' – Masked scan results from Nmap. 
- 'scan_commands.txt' – Nmap commands used and their explanations.  
- 'services_info.txt' – Common services found on the scanned ports.  
- 'security_risks.txt' – Security risks identified from the open ports.  

## 🔒 Notes on Privacy
- Device IP addresses have been masked for privacy (eg:'192.168.1.X').  

## 🧠 Key Takeaways
- Nmap is a powerful tool to discover network exposure.  
- Even common ports (eg: 80, 443, 445) can introduce risks if not properly secured.  
- Always mask private IP addresses and sensitive details when sharing results publicly.


