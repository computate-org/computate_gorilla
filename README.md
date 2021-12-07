
# Install the bzflag ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_bzflag

# Clone the bzflag ansible role. 
git clone git@github.com:computate-org/computate_bzflag.git ~/.ansible/roles/computate.computate_bzflag
cd ~/.ansible/roles/computate.computate_bzflag
```

# Run the bzflag ansible playbook to install bzflag locally (requires sudo privileges with -K). 

```bash
ansible-playbook -K install.yml
```

