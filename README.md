# SE502-conf-ansible

## executer le playbook

- installer sshpass et ansible
- se procurer le mot de passe vault
- créer un fichier password.txt dans le dossier contenant:

```python
#!/usr/bin/env python

import os
print "le mot de passe vault"
```

puis dans un terminal dans le dossier
```bash
ansible-playbook site.yml
```