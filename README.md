ansible-tls-klusters

## Usage

### Dependencies

Depencies are listed in each inventory folder

Install dependencies :
```bash
pip install -r <my_inventory>/requirements/python_requirements.txt

ansible-galaxy install -f -r <my_inventory>/requirements/ansible_requirements.yml
```

### Execute playbook

Run keystores.yml :
```bash
ansible-playbook -i inventories/test/docker playbooks/tls/keystores.yml
```
