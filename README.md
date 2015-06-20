# common_yum

Ansible simple yum role that supports installation of few packages and/or groups the should be required everywhere, also a yum cache clean handler.

## Requirements

Should never depend on any other role.

## Role Variables

There are 2 variables to be configured under the common_yum namespace:
  * packages
  * groups
Both hold lists of values for either packages or groups that should be installed.

## Dependencies

Should never depend on any other role.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mashimom.common_yum, common_yum: { packages: [yum-presto] } }

## License

MIT

## Author Information

<!-- An optional section for the role authors to include contact information, or a website (HTML is not allowed). -->
