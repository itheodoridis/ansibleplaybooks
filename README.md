This is a collection of playbooks to share mostly for linux server administration in the context of OSS Network Management tools

# Bring Servers and services to a desired state
# check_syslog-ng.yml
This playbook is meant for ubuntu (or debian based) servers (there is a reference to apt)
- Make sure syslog-ng is installed
- check for existance of loki configuration file, if it doesn't exist then create an empty one.
- if the config for loki as a destination is not there add it (or modify it)
- if the config for routing the source of local data to loki's destination is there, add it (or modify it)
