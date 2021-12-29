* Utilização de vault para proteger arquivo "confidential"
* Executar tarefas assíncronas utilizando "async" sem polling de status

```bash
ansible-vault encrypt confidential
```

Para executar o playbook:
```bash
ansible-playbook --ask-vault-pass /home/ansible/webserver.yml
```