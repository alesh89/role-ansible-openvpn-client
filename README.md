# role-ansible-openvpn-client
Роль для установки клиента OpenVPN на Ubuntu 16.04

## Установка

- Установить роль командой ansible-galaxy install -r requirements.yml --force
- Запустить команду установки ansible-playbook -i inventory -l clients test.yml --ask-pass --ask-sudo-pass