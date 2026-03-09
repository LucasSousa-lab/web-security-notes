# Web Security Notes

Basic security vulnerabilities explained.

## SQL Injection

Example:

' OR '1'='1

This can bypass authentication if the system is vulnerable.

## XSS

Example:

<script>alert('XSS')</script>
