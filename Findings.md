# HTB Attempt 1
Server IP: http://10.10.11.104/

===============================================================
Gobuster v3.1.0
by OJ Reeves (@TheColonial) & Christian Mehlmauer (@firefart)
===============================================================
[+] Url:                     http://10.10.11.104
[+] Method:                  GET
[+] Threads:                 10
[+] Wordlist:                wordlists/Discovery/Web-Content/raft-medium-files.txt
[+] Negative Status codes:   404
[+] User Agent:              gobuster/3.1.0
[+] Timeout:                 10s
===============================================================
2021/10/23 14:02:36 Starting gobuster in directory enumeration mode
===============================================================
/index.php            (Status: 302) [Size: 2801] [--> login.php]
/login.php            (Status: 200) [Size: 2224]                
/config.php           (Status: 200) [Size: 0]                   
/download.php         (Status: 302) [Size: 0] [--> login.php]   
/header.php           (Status: 200) [Size: 980]                 
/footer.php           (Status: 200) [Size: 217]                 
/favicon.ico          (Status: 200) [Size: 15406]               
/.htaccess            (Status: 403) [Size: 277]                 
/logout.php           (Status: 302) [Size: 0] [--> login.php]   
/.                    (Status: 302) [Size: 2801] [--> login.php]
/.html                (Status: 403) [Size: 277]                 
/.php                 (Status: 403) [Size: 277]                 
/status.php           (Status: 302) [Size: 2972] [--> login.php]
/.htpasswd            (Status: 403) [Size: 277]                 
/.htm                 (Status: 403) [Size: 277]                 
/.htpasswds           (Status: 403) [Size: 277]                 
/nav.php              (Status: 200) [Size: 1248]                
/accounts.php         (Status: 302) [Size: 3994] [--> login.php]
/files.php            (Status: 302) [Size: 947040] [--> login.php]
/.htgroup             (Status: 403) [Size: 277]                   
/wp-forum.phps        (Status: 403) [Size: 277]                   
/.htaccess.bak        (Status: 403) [Size: 277]                   
/.htuser              (Status: 403) [Size: 277]                   
/.ht                  (Status: 403) [Size: 277]                   
/.htc                 (Status: 403) [Size: 277]    ****