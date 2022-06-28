# ansible-fedora-ws-setup
Very simple ansible playbook to establish foundation config of Fedora workstation. Nvidia optional.

To apply nvidia steps run a `--tags nvidia` swtich.
Possible executions:

```yaml
ansible-playbook fedora.yml -e dnf_upd_cache=yes
ansible-playbook fedora.yml -t nvidia
ansible-playbook fedora.yml --skip-tags dnf
```
