# Entropia SSO Collection

This repository contains the `entropia.sso` Ansible Collection.

## Using this collection

This collection is shipped with the Ansible package. So if you have it installed, no more action is required.

If you have a minimal installation (only Ansible Core installed) or you want to use the latest version of the collection along with the whole Ansible package, you need to install the collection from [Ansible Galaxy](https://galaxy.ansible.com/ui/repo/published/entropia/sso/) manually with the `ansible-galaxy` command-line tool:

    ansible-galaxy collection install entropia.sso

You can also include it in a `requirements.yml` file and install it via `ansible-galaxy collection install -r requirements.yml` using the format:

```yaml
collections:
- name: entropia.sso
```

Note that if you install the collection manually, it will not be upgraded automatically when you upgrade the Ansible package. To upgrade the collection to the latest available version, run the following command:

```bash
ansible-galaxy collection install entropia.sso --upgrade
```

You can also install a specific version of the collection, for example, if you need to downgrade when something is broken in the latest version (please report an issue in this repository). Use the following syntax where `X.Y.Z` can be any [available version](https://galaxy.ansible.com/ui/repo/published/entropia/sso/):

```bash
ansible-galaxy collection install entropia.sso:==X.Y.Z
```

See [Ansible Using collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html) for more details.
