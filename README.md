# Catatan-belajar-CEH-Practical
Repository ini dibuat sebagai catatan belajar dan dokumentasi perjalanan saya dalam memahami materi Certified Ethical Hacker (CEH) Practical.

1. Contoh penggunaan nmap: nmap -Pn -p445 -A [IP]
2. Cara mencari versi IMAP dengan nmap: nmap -Pn -p143 -A [IP]
3. cara menggunakan hydra untuk bruteforce: hydra -L user.txt -P pass.txt rdp://IP
4. mencari device mobile yang ada di subnet tertentu: search for IP that open port 5555
5. Cara menggunakan OpenVAS: login to OpenVAS and do the following
   -  The OpenVAS Dashboards appears. Navigate to Scans --> Tasks from the Menu bar.
   -  Hover over wand icon and click the Task Wizard option.
   -  The Task Wizard window appears; enter the target IP address in the IP address or hostname field (here, the target system is Windows Server 2022 [10.10.1.22]) and click the Start Scan button.
   - Wait for the Status to change from Requested to Done. Once it is completed, click the Done button under the Status column to view the vulnerabilities found in the target system.
