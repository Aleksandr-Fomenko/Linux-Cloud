<h3>"Tarifa": Between Two Seas</h3>

Scenario: "Tarifa": Between Two Seas

Level: Medium

Type: Fix

Tags: docker   haproxy   realistic-interviews  

Description: There are three Docker containers defined in the docker-compose.yml file: an HAProxy accepting connetions on port :5000 of the host, and two nginx containers, not exposed to the host.

The person who tried to set this up wanted to have HAProxy in front of the (backend or upstream) nginx containers load-balancing them but something is not working.

Test: Running curl localhost:5000 several times returns both hello there from nginx_0 and hello there from nginx_1

Check /home/admin/agent/check.sh for the test that "Check My Solution" runs.

Time to Solve: 20 minutes.