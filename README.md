# ansible-role-clock

Ansible role to manage the system clock


## Requirements

    None


## Dependencies

    None


## Role Variables

    * clock_timezone

    Timezone to use

    (default: Etc/UTC)


## Example Playbook

    ```yaml
    ---
    - hosts: all

      roles:
          - foolean/clock
    ```


## Supported Operating Systems

    * Debian (11)
    * Raspbian (11)
    * RedHat (8)
    * Rocky (8)


## License

    BSD-3-Clause
