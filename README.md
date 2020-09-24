# 3CXjson2ldap
Allows 3CX to query LDAP for CID lookup via CRM/JSON interface, adapted from https://github.com/larsks/ldap2json

I'm running this on linux for now, may move it to windows at some point. 
4 parts needed.
 - systemd service file
 - ldap2json.py  (modfy line 51 and 198 to set your user/pass and LDAP (AD) server, I couldn't get these to work via config file)
 - ldap2json.conf
 - xml transform for 3cx 
