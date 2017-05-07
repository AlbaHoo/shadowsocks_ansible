# Command line
ansible-playbook -s install_ss.yml -i ./inventory/hosts
ansible-playbook -s insall_ss.yml -i ./inventory/hosts --limit xbox
---

# Example data load from winston json
curl -XPOST http://40.115.79.157:8080 --data-binary @filename

# open port 80 for http input(logstash)

sudo setcap 'cap_net_bind_service=+ep' /usr/lib/jvm/java-8-oracle/jre/bin/java
