# IDOR-Vulnerable-code-snippet

 IDOR, or Insecure Direct Object Reference, is a type of security vulnerability that occurs when an application provides direct access to objects based on user-supplied input, without proper authorization checks. This allows attackers to bypass authorization and access resources they should not be able to reach.  How IDOR Works Direct Access to Resources: Applications often access internal objects like files, database entries, or other resources using user-provided input as part of the URL or request parameters. 
 
Lack of Authorization Checks: If the application does not properly verify that the requesting user is authorized to access the specific resource, an attacker can manipulate the input to access resources they are not supposed to.
