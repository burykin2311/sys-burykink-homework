# Домашнее задание к занятию "`Уязвимости и атаки на информационные системы`" - `Бурыкин Кирилл`

### Задание 1

nmap -Pn -sV <ip-адресс машины Metasploitable>

<img width="994" height="477" alt="image" src="https://github.com/user-attachments/assets/cbc58461-d194-4e00-8f2e-88985fc4a1c8" />

Уязвимости с ссылками: 

1. vsftpd 2.3.4 — Backdoor Command Execution
   https://www.exploit-db.com/exploits/17491
   
2. Apache 2.2.8 — PHP-CGI Remote Code Execution
   https://www.exploit-db.com/exploits/29290
   
3. Samba 3.X — usermap_script Command Execution
   https://www.exploit-db.com/exploits/16320

### Задание 2

nmap -sS <ip-адресс> (SYN)

<img width="1297" height="547" alt="image" src="https://github.com/user-attachments/assets/e6e1a227-566d-4de6-ac36-85a1ac45286c" />

nmap -sF <ip-адресс> (FIN)

<img width="1301" height="548" alt="image" src="https://github.com/user-attachments/assets/8d8c1553-99c6-4eb4-a58b-c02adca76c18" />

nmap -sX <ip-адресс> (Xmas)

<img width="1317" height="526" alt="image" src="https://github.com/user-attachments/assets/5cb1b451-a41c-4ea2-98fb-0b22d209da15" />

nmap -sU <ip-адресс> (UDP)

<img width="1314" height="545" alt="image" src="https://github.com/user-attachments/assets/9b7098dc-92b4-4660-b1e0-3eb4cf0d1053" />


1.Главное отличие: SYN получает ответ всегда, FIN/Xmas – только от закрытых портов (открытые молчат), UDP – работает с другим протоколом

2.· SYN: открытый порт>SYN-ACK, закрытый>RST
· FIN/Xmas: закрытый порт>RST, открытый>нет ответа
· UDP: закрытый порт>ICMP ошибка, открытый>нет ответа

