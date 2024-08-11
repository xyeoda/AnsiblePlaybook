# AnsiblePlaybook
Playbook for Yeoda HomeLab

Steps to commit this from Ansible Server:

1) git status
2) git diff <FileName>
3) git add README.md
4) git status
5) git commit -m "updated readme file to have instructions"
6) git push origin master


Some Commands to Remember:

1) ansible all --list-hosts
2) ansible all -m ping
3) ansible all -m gather_facts
4) ansible all -m gather_facts --limit unifi.local.yeoda.space
