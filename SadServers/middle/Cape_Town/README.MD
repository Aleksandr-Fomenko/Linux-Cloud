<h3>"Tokyo": can't serve web file</h3>

Scenario: "Tokyo": can't serve web file

Level: Medium

Type: Fix

Tags: apache   realistic-interviews  

Description: There's a web server serving a file /var/www/html/index.html with content "hello sadserver" but when we try to check it locally with an HTTP client like curl 127.0.0.1:80, nothing is returned. This scenario is not about the particular web server configuration and you only need to have general knowledge about how web servers work.

Test: curl 127.0.0.1:80 should return: hello sadserver

Time to Solve: 15 minutes.