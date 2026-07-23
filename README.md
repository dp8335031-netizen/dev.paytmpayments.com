# Subdomain Takeover Proof of Concept

## Vulnerability: Subdomain Takeover

**Domain:** paytmpayments.com  
**Subdomain:** dev.paytmpayments.com  
**Status:** Confirmed & Demonstrated  
**Date:** 23rd July 2026  

## Proof

This repository demonstrates that the subdomain `dev.paytmpayments.com` is vulnerable to takeover.

### DNS Status

```bash
C:\Windows\System32>nslookup dev.paytmpayments.com
Server:  dns.google
Address:  8.8.8.8
*** dns.google can't find dev.paytmpayments.com: Non-existent domain
