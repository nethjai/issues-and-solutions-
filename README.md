# issues-and-solutions-


Problem : ERROR! Unexpected Exception, this is probably a bug: (cryptography 1.2.3 (/usr/lib/python3/dist-packages), Requirement.parse('cryptography>=1.5'), {'paramiko'})

Solution:

sudo pip3 uninstall cryptography
removed cryptography-1.2.3

sudo pip3 install cryptography
install cryptography-2.2.2
