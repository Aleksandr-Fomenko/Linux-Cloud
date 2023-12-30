<h3>"Oaxaca": Close an Open File</h3>

Scenario: "Oaxaca": Close an Open File

Level: Medium

Type: Fix

Tags: bash   unusual-tricky  

Description: The file /home/admin/somefile is open for writing by some process. Close this file without killing the process.

Test: lsof /home/admin/somefile returns nothing.

Time to Solve: 15 minutes