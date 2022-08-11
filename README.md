
# Install the prerequisite applications

- https://github.com/computate-org/computate_libcaca

# Install the toilet ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_toilet

# Clone the toilet ansible role. 
git clone git@github.com:computate-org/computate_toilet.git ~/.ansible/roles/computate.computate_toilet

# Change into the toilet ansible role directory. 
cd ~/.ansible/roles/computate.computate_toilet
```

# Run the toilet ansible playbook to install toilet locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
