<h3>"Monaco": Disappearing Trick</h3>

Scenario: "Monaco": Disappearing Trick

Level: Hard

Type: Hack

Tags: unusual-tricky  

Description: There is a web server on :5000 with a form. POSTing the correct form password into this web service will return a secret.

Save this secret provided by the web page (not the password you sent to it) to /home/admin/mysolution, for example: echo "SecretFromWebSite" > ~/mysolution

TIP: a developer worked on the web server code in this VM, using the same 'admin' account.

Scenario credit: PuppiestDoggo

Test: md5sum /home/admin/mysolution returns a250aa19f16dda6f9fcef286f035ec4b

Time to Solve: 30 minutes.