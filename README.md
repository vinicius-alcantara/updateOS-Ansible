# Update OS: Gestão de vulnerabilidades

Playbook desenvolvido com o objetivo de automatizar o processo de atualização dos SO's do cliente, a fim de eliminar vulnerabilidades, de acordo com o descritivo abaixo:

* Atualiza distros Centos/Ubuntu para a versão mais atual.
* Atualiza todos os pacotes do repositório Base, já instalados.
* Atualiza o kernel e remove a versão antiga.
* Realiza o start da aplicação do cliente após o reboot.

## Requirements

```bash
ansible 2.9.7 ou superior
ansible-galaxy
ansible-vault
```

## Examplo de execução do playbook
 
```bash

cd ~/updateOS-SRM 

ansible-playbook -i hosts playbook.yml --ask-vault-pass

```

# updateOS-Ansible
