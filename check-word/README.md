# ansible-check-word
Ansible playbook for check some word in archive and return response.

## To execute
To execute, just type the command

      ansible-playbook -v -u <your-user> --ask-pass -K -i <invetory-path> check-word.yml --limit <limit-vms>

**Pay attention** to the fields that need to be changed.

```yaml
path: <your-path>
regexp: '^.*word.*$'
```
## Diferential
In the task "debug" The code return a message about the word existence.

#### Thank you
By Matheus Fazolli