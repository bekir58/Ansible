

# tags

###  tag eins wird durchgeführt
ansible-playbook tags/playbook-tags.yaml --tags eins

###  tag zwei wird durchgeführt
ansible-playbook tags/playbook-tags.yaml --tags zwei

###  tag eins wird ignoriert
ansible-playbook tags/playbook-tags.yaml --skip-tags eins



