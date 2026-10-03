# -NAAN-MUDHALVAN-PROJECT
Script-Controlled ACL – Restrict Records Based on Field Value This project implements a Script-Controlled Access Control List (ACL) in ServiceNow to restrict users from accessing records based on a specific field value. 

Project Summary

The Script-Controlled ACL: Restrict Records Based on Field Value project is designed to improve data security and access control in the ServiceNow platform. An Access Control List (ACL) is used to determine whether a user is allowed to view, create, update, or delete a particular record. In this project, a server-side JavaScript script is added to the ACL to check the value of a specific field before granting access.

When a user attempts to access a record, the ACL is triggered and the script evaluates the required field value. Based on the defined condition, the system either allows or denies access to the record. For example, records containing sensitive or critical information can be restricted to authorized users, while normal records can remain accessible to other users.

This approach provides dynamic and condition-based security rather than relying only on user roles. It helps organizations protect sensitive information, prevent unauthorized modifications, and maintain better control over records. The project demonstrates how ServiceNow ACLs and server-side scripting can be combined to implement flexible, secure, and reliable record-level access control.
