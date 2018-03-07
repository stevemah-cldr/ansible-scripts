scripts uses
     when: ansible_os_family == "Debian"
     when: ansible_os_family == "RedHat"
to determine Linux Variant before updating package.
