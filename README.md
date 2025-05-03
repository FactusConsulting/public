# public

Repo for stuff I want to share

``` bash
ansible-playbook ansible/playbooks/update-servers.yaml -i ansible/inventory/hosts.ini --ask-pass --ask-become-pass
```

use --ask-pass if there are no passwordless ssh setup.

use --ask-become-pass if there are no passwordless sudo setup.
