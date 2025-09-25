#Local Network Port Scan - Jitta Sharanya

Scanned range:192.168.1.16/24
Commands Used:
-nmap -sn 192.168.1.16/24 -oN discovery.txt
-nmap -sn 192.168.1.16/24 -oN syn_scan.txt
-nmap -sn 192.168.1.12 -oN service_192-168-1-12.txt


Top findings:
-192.168.1.1 : ports 80 (http)open
-192.168.1.2 : ports 554(rtsp)open



Actions Taken:
-Blocked 80/tcp in windows firewall