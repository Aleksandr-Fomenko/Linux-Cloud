<h3>"Cape Town": Borked Nginx</h3>

Scenario: "Cape Town": Borked Nginx

Level: Medium

Type: Fix

Tags: nginx   realistic-interviews  

Description: There's an Nginx web server installed and managed by systemd. Running curl -I 127.0.0.1:80 returns curl: (7) Failed to connect to localhost port 80: Connection refused , fix it so when you curl you get the default Nginx page.

Test: curl -Is 127.0.0.1:80|head -1 returns HTTP/1.1 200 OK

Time to Solve: 15 minutes.