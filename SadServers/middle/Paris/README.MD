<h3>"Paris": Where is my webserver?</h3>

Scenario: "Paris": Where is my webserver?

Level: Medium

Type: Hack

Tags: unusual-tricky  

Description: A developer put an important password on his webserver localhost:5000 . However, he can't find a way to recover it. This scenario is easy to to once you realize the one "trick".

Find the password and save it in /home/admin/mysolution , for example: echo "somepassword" > ~/mysolution

Scenario credit: PuppiestDoggo

Test: md5sum ~/mysolution returns d8bee9d7f830d5fb59b89e1e120cce8e

Time to Solve: 15 minutes.