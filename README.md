# FUTURE_CS_01-
Web application security testing report 
The assessment focused on identifying and 
mitigating common web appication vulnerabilities.

Vunerabilities Tested
  1. SQL Injection (SQLi)
       Payload: ' OR 1=1--
       Impact:Logged in without valid
       credentials;hidden data was exposed
  2. Cross-Site Scripting (XSS)
       Payload: <script>alert('XSS')
       </script>
       Impact: Script executed in victim's
       browser,confirming vulnerability.
  3. Authentication Flaw
       Observation: Application revealed
       different responses for valid/invalid
       usernames,allowing enumeration.
     
Tool Used
  OWASP ZAP
  Brup Suite
  SQLMap

Key Takeaways
  Hands-on experience in identifying and
  documenting vulnerailities.
  Understanding of secure coding practices 
  and mitigation strategies.

 
