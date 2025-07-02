# Catatan-belajar-CEH
Repository ini dibuat sebagai catatan belajar dan dokumentasi perjalanan saya dalam memahami materi Certified Ethical Hacker (CEH) Practical.

1. Cracking password dengan john: https://www.youtube.com/watch?v=6KC5R8I3bKQ, soal ctf.hackverse.com --> Round 2 warm-up question
2. Contoh penggunaan nmap: nmap -Pn -p445 -A [IP]
3. Cara mencari versi IMAP dengan nmap: nmap -Pn -p143 -A [IP]
4. cara menggunakan hydra untuk bruteforce: hydra -L user.txt -P pass.txt rdp://IP
5. mencari device mobile yang ada di subnet tertentu: search for IP that open port 5555; ADB --> ADB shell to connect to device and ADB pull to download the file (https://docs.ubports.com/en/latest/userguide/advanceduse/adb.html)
6. Cara menggunakan OpenVAS: login to OpenVAS and do the following
   -  The OpenVAS Dashboards appears. Navigate to Scans --> Tasks from the Menu bar.
      ![OpenVAS interface 1](https://github.com/user-attachments/assets/20a88f49-9d00-48e9-b0f1-0d7d6140bd19)

   -  Hover over wand icon and click the Task Wizard option.
      ![OpenVAS interface 2](https://github.com/user-attachments/assets/d88d8fbd-1a86-45cd-88c2-8ef5c7949be1)

   -  The Task Wizard window appears; enter the target IP address in the IP address or hostname field (here, the target system is Windows Server 2022 [10.10.1.22]) and click the Start Scan button.
      ![OpenVAS interface 3](https://github.com/user-attachments/assets/52060a7a-2a4f-400c-a9ac-5bfba4d78efc)

   - Wait for the Status to change from Requested to Done. Once it is completed, click the Done button under the Status column to view the vulnerabilities found in the target system.
     ![OpenVAS interface 4](https://github.com/user-attachments/assets/28cbf9e0-f4c1-4cf1-ae97-4eb3d4ec0f6c)

   - Click on any vulnerability under the Vulnerability column to view its detailed information.
 7. Mencari mesin dgn OS linux yang memungkinkan untuk remote login dengan menggunakan angry ip scanner atau nmap
 8. steganography: https://i-3.co.id/cara-mendeteksi-dan-membuka-steganografi-menggunakan-stegspy-dan-openstego/
 9. scanning SMB services: https://nullprofile.com/scanning-smb-services-with-nmap --> bruteforce SMB with hydra: hydra -L user.txt -P pass.txt smb://IP. kemudian koneksi ke SMB menggunakan file explorer atau smb client.
 10. Belajar menggunakan PEinfo atau tools yang lain untuk melakukan malware analysis & mencare image version dari suatu malware
 11. study module 7 malware threats --> static & dynamic malware analysis
 12. Mencari Entri Point dari malware yang harus di analisis...? Pelajari cara menggunakan PEinfo: (https://www.majorgeeks.com/files/details/peinfo.html#google_vignette)
 13. Pelajari cara menggunakan wireshark untuk mencari IP sumber serangan DDOS --> Module 10: Denial of service
 14. Pelajari kembali Module 15 SQL injection attacks
 15. Menganalisis sebuah web dengan memanfaatkan fitur view page source
 16. Melakukan exploitasi terhadap sebuah web yg memiliki vulnerability --> use Nikto/zapproxy to scan the web.  How to use metasploit to exploit (https://www.oreilly.com/library/view/hands-on-web-penetration/9781789953527/7a4d442c-493b-4cae-9962-28eae680bf47.xhtml)
 17. Belajar DVWA: (https://medium.com/@alexandrangeline/command-injection-sederhana-menggunakan-damn-vulnerable-web-application-dvwa-e50713c54b6f)
 18. Pelajari kembali wireshark untuk analisa iot devices --> MQTT protocol
 19. Pelajari cara decrypt file menggunakan veracrypt
 20. Pelajari cara cracking wifi password: https://predatech.co.uk/capturing-and-cracking-wpa-wpa2-wifi-passwords/
