# wikipedia-android-app-server-setup
Ansible scripts to set up server side services for running a fork of the wikipedia android app.

Run as:

    ansible-playbook -s playbook.yml -u <user> --extra-vars "api_url='<api_url>'" --ask-sudo-pass
