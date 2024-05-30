# Port-25-smtp-Postfix-smtpd
1.nmap -sV (target)
![image](https://github.com/thanawut2903/Port-25-smtp-Postfix-smtpd/assets/159118913/20aed725-18e2-4d5c-9ed2-6f46eb740cca)
2.msfconsole
3.msf 6 > search smtp
![image](https://github.com/thanawut2903/Port-25-smtp-Postfix-smtpd/assets/159118913/60255675-e22f-40cc-a2b9-5a0c75bb1906)
4.msf 6 > use auiliary/scanner/smtp/smtp_enum
5.msf 6 > show options 
6.msf 6 > set RHOST <target>
![image](https://github.com/thanawut2903/Port-25-smtp-Postfix-smtpd/assets/159118913/8eb17b7a-76aa-4be6-b64a-8b2ae0df9738)
7. msf 6 > run
![image](https://github.com/thanawut2903/Port-25-smtp-Postfix-smtpd/assets/159118913/08026c8b-7621-45b6-a20c-58fd63e3a5d6)
8.nc (target)
![image](https://github.com/thanawut2903/Port-25-smtp-Postfix-smtpd/assets/159118913/5c9dc34d-3615-45ae-afc2-a35d82e1c521)
