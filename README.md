

# Keyboard-interactive ArubaOS-Switch Collection for Ansible
[![CI](https://github.com/evajust/kbd_interactive.aosswitch/actions/workflows/ansible-test.yml/badge.svg?branch=main&event=schedule)](https://github.com/evajust/kbd_interactive.aosswitch/actions/workflows/ansible-test.yml)
<!--[![Codecov](https://codecov.io/gh/evajust/kbd_interactive.aosswitch/branch/main/graph/badge.svg)](https://codecov.io/gh/evajust/kbd_interactive.aosswitch) -->

The Keyboard-interactive ArubaOS-Switch collection includes Ansbile content to help automate the management of ArubaOS-Switch devices that must have **password configuration-control** enabled. This configuration line disables the use of 'password' as an authentication method and doesn't allow ssh remote command execution. This prevents the Ansible's built-in network_cli connection method from being able to manage the device.

## Communication

<!--
If your collection is not present on the Ansible forum yet, please check out the existing [tags](https://forum.ansible.com/tags) and [groups](https://forum.ansible.com/g) - use what suits your collection. If there is no appropriate tag and group yet, please [request one](https://forum.ansible.com/t/requesting-a-forum-group/503/17).
-->

* Join the Ansible forum:
  * [Get Help](https://forum.ansible.com/c/help/6): get help or help others. Please add appropriate tags if you start new discussions, for example the `YOUR TAG` tag.
  * [Posts tagged with 'your tag'](https://forum.ansible.com/tag/YOUR_TAG): subscribe to participate in collection/technology-related conversations.
  * [Refer to your forum group here if exists](https://forum.ansible.com/g/): by joining the team you will automatically get subscribed to the posts tagged with [your group forum tag here](https://forum.ansible.com/tags).
  * [Social Spaces](https://forum.ansible.com/c/chat/4): gather and interact with fellow enthusiasts.
  * [News & Announcements](https://forum.ansible.com/c/news/5): track project-wide announcements including social events. The [Bullhorn newsletter](https://docs.ansible.com/ansible/devel/community/communication.html#the-bullhorn), which is used to announce releases and important changes, can also be found here.

For more information about communication, see the [Ansible communication guide](https://docs.ansible.com/ansible/devel/community/communication.html).

## Collection maintenance

The current maintainers are listed in the [MAINTAINERS](MAINTAINERS) file. If you have questions or need help, feel free to mention them in the proposals.

To learn how to maintain/become a maintainer of this collection, refer to the [Maintainer guidelines](https://docs.ansible.com/ansible/devel/community/maintainers.html).

It is necessary for maintainers of this collection to be subscribed to:

* The collection itself (the `Watch` button -> `All Activity` in the upper right corner of the repository's homepage).
* The [news-for-maintainers repository](https://github.com/ansible-collections/news-for-maintainers).

They also should be subscribed to Ansible's [The Bullhorn newsletter](https://docs.ansible.com/ansible/devel/community/communication.html#the-bullhorn).

## Governance

<!--Describe how the collection is governed. Here can be the following text:-->

The process of decision making in this collection is based on discussing and finding consensus among participants.

Every voice is important. If you have something on your mind, create an issue or dedicated discussion and let's discuss it!

## Tested with Ansible

<!-- List the versions of Ansible the collection has been tested with. Must match what is in galaxy.yml. -->

## External requirements

<!-- List any external resources the collection depends on, for example minimum versions of an OS, libraries, or utilities. Do not list other Ansible collections here. -->

### Supported connections
<!-- Optional. If your collection supports only specific connection types (such as HTTPAPI, netconf, or others), list them here. -->

## Included content

<!-- Galaxy now usually displays full module and plugin docs within the UI. If you don't use Galaxy for your collection, you may need to either describe your plugins etc here, or point to an external docsite to cover that information. -->

## Using this collection

<!--Include some quick examples that cover the most common use cases for your collection content. It can include the following examples of installation and upgrade (change NAMESPACE.COLLECTION_NAME correspondingly):-->

### Installing the Collection from Ansible Galaxy

Before using this collection, you need to install it with the Ansible Galaxy command-line tool:
```bash
ansible-galaxy collection install kbd_interactive.aosswitch
```

You can also include it in a `requirements.yml` file and install it with `ansible-galaxy collection install -r requirements.yml`, using the format:
```yaml
---
collections:
  - name: kbd_interactive.aosswitch
```

Note that if you install the collection from Ansible Galaxy, it will not be upgraded automatically when you upgrade the `ansible` package. To upgrade the collection to the latest available version, run the following command:
```bash
ansible-galaxy collection install kbd_interactive.aosswitch --upgrade
```

You can also install a specific version of the collection, for example, if you need to downgrade when something is broken in the latest version (please report an issue in this repository). Use the following syntax to install version `0.1.0`:

```bash
ansible-galaxy collection install kbd_interactive.aosswitch:==0.1.0
```

See [using Ansible collections](https://docs.ansible.com/ansible/devel/user_guide/collections_using.html) for more details.

## Contributing to this collection

We welcome contributions to this collection. If you find problems, please open an issue or create a PR against the [Keyboard-interactive ArubaOS-Switch repository](https://github.com/evajust/kbd_interactive.aosswitch).

You can also join us on:

- [Discord](https://discord.gg/U7u9qYpNph)

### Code of Conduct

This collection follows the Ansible project's
[Code of Conduct](https://docs.ansible.com/ansible/devel/community/code_of_conduct.html).
Please read and familiarize yourself with this document.

## Release notes

<!--Add a link to a changelog.md file or an external docsite to cover this information. -->

Release notes are available [here](https://github.com/evajust/kbd_interactive.aosswitch/blob/main/CHANGELOG.rst).

## More information

- [Ansible network resources](https://docs.ansible.com/ansible/latest/network/getting_started/network_resources.html)
- [Ansible Collection Overview](https://github.com/ansible-collections/overview)
- [Ansible User guide](https://docs.ansible.com/ansible/latest/user_guide/index.html)
- [Ansible Developer Guide](https://docs.ansible.com/ansible/latest/dev_guide/index.html)
- [Ansible Community Code of Conduct](https://docs.ansible.com/ansible/latest/community/code_of_conduct.html)

## Licensing

GNU General Public License v3.0 or later.

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.
