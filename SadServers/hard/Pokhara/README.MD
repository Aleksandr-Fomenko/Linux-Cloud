<h3>"Pokhara": SSH and other sshenanigans</h3>

Scenario: "Pokhara": SSH and other sshenanigans

Level: Hard

Type: Fix

Tags: ssh   realistic-interviews  

Description: A user client was added to the server, as well as their SSH public key.
The objective is to be able to SSH locally (there's only one server) as this user client using their ssh keys. This is, if as root you change to this user sudo su; su client, you should be able to login with ssh: ssh localhost.


Test: As user admin: sudo -u client ssh client@localhost 'pwd' returns /home/client

Time to Solve: 30 minutes.