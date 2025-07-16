# Playbook: Phishing Attack

## Summary
A user receives a fake email and clicks a link.

## Trigger Conditions
- Email with suspicious domain
- Splunk alert for login from unknown IP

## Identification
- Check email headers
- SIEM query for failed logins

## Containment
- Disable user account
- Block domain

## Eradication
- Remove malicious email
- Clear browser cache

## Recovery
- Reset user credentials
- Educate user

## Post-Incident
- Add sender to blocklist
- Update spam filter rules
