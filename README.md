install ansible
```
sudo apt install git ansible
```

use the playbook to setup localhost
```
cd ansible
ansible-playbook setup_playbook.yml -K
```

add containers
```
cd docker
docker-compose up
```

this will start a simple webservice `whoami` on port `80` mapped on host `8080`
test it with `curl localhost:8080` 