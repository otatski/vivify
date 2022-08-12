# Vivify
#### A simple, yet powerful, TUI provisioner powered by Rust and Ansible.

This instructions will be updated as the project evolves.

---
### Required for Development
- Rust
---
### Installation
##### From source
- Clone the repository
- Navigate to project directory
-   $: `cargo build -r`
-   $: `./target/release/vivify`

##### Binary
- As development progresses, this option will become available for the master 
branch of the project.

---

### Development
Currently, the goal is to have a set of Ansible playbooks that are as generic as 
possible, to allow for use on multiple systems. They currently exist in the
**playbooks** directory of the project. The Rust portion will scan that 
directory and give the user the option of applying that playbook to their system.

The flow of interaction the TUI will have has yet to be determined and will 
evolve over time. At the very least, a description of the currently selected
playbook and what it does and/or installs will be provided for each one either 
on the side or bottom of the window.
