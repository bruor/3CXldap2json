# 3CXjson2ldap
Allows 3CX to query LDAP for CID lookup via CRM/JSON interface, adapted from https://github.com/larsks/ldap2json

I'm running this on linux for now, may move it to windows at some point. 
4 parts needed.
 - systemd service file
 - ldap2json.py
 - ldap2json.conf
 - xml transform for 3cx 
