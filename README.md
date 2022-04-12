# cloudguard-bootstrap
Ansible Playbook to create Checkpoint Cloudguard Bootstrap config

Tasks:

1. Validate data and formatting 

2. Load interfaces and render jinja, save to config file

3. Load system vars and render jinja, save to config file

4. Load bgp vars and render jinja, save to config file
 
5. Load list of lan routes and render jinja, save to config file
 
6. Create Cloud-Init User-Data , create iso file and save

7. Create file with list of all commands(for backup option)


