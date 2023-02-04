# ToDo

1. CREATE SELINUX POLICY

# Set SELINUX to enforcing

# - name: Set SELINUX to enforcing
#   shell: semodule -i dnscache.pp
#   register: selinux_output

# - name: PiHole Output
#   debug: msg={{ selinux_output.stdout_lines }}

# - name: Reboot
#   reboot:
#     reboot_timeout: 300
#     test_command: whoami

# - name: PiHole Output
#   debug: msg={{ pihole_interface }}
