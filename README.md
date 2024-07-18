# server-install-basic-tools
To install basic tools, git, vim, etc. on a fresh server like Rocky

Clone into your new server you want to set up basic tools on (you will need to sudo yum install git!): 

```
git clone https://github.com/ucla-data-science-center/server-install-basic-tools.git)

```

Run by: 

```
ansible-playbook -i inventory server-install-basic-tools.yml
```
