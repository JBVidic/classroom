Ansible playbooks for deploying classroom computers. Run with something like:

    ansible-playbook --user <AD admin> --ask-pass \
        --become --become-method=runas --become-user=<local admin>
        --inventory hosts setup.yml
