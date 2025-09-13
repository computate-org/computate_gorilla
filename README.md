
# Prerequisites

Install the ITCL application as a prerequisite, see: 
https://github.com/computate-org/computate_itcl
## Install the itcl ansible role

Create a directory for the ansible role. 

```bash
install -d ~/.ansible/roles/computate.computate_itcl
```

Clone the itcl ansible role. 

```bash
git clone git@github.com:computate-org/computate_itcl.git ~/.ansible/roles/computate.computate_itcl
```

# Run the itcl ansible playbook to install itcl locally. 

```bash
ansible-playbook ~/.ansible/roles/computate.computate_itcl/install.yml
```

# Install the gorilla ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_gorilla

# Clone the gorilla ansible role. 
git clone git@github.com:computate-org/computate_gorilla.git ~/.ansible/roles/computate.computate_gorilla
```

# Run the gorilla ansible playbook to install gorilla locally. 

```bash
ansible-playbook ~/.ansible/roles/computate.computate_gorilla/install.yml
```

