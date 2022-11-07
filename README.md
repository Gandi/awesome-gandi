<!--lint disable awesome-badge awesome-git-repo-age awesome-github-->

# <a href="https://www.gandi.net/"><img align="right" src="https://upload.wikimedia.org/wikipedia/en/c/c7/GandiSAS.svg" alt="awesome-gandi" title="awesome-gandi" style="width: 250px; height: 54px;" width="250" height="54"/></a> Awesome Gandi

> A curated list of awesome Gandi tools, tutorials, and other resources.

## Contents

- [Libraries](#libraries)
- [Deployment](#deployment)
- [Clients](#clients)
- [APIs](#apis)
- [Docs & tutorials](#docs--tutorials)

#### Contributing

Contributions are welcome! To add a resource to the list, please [create an Issue](https://github.com/nlewo/awesome-gandi/issues) or fork this repository and submit a pull request ([click here to edit this file from GitHub](https://github.com/nlewo/awesome-gandi/edit/main/README.md)).

For more details, see [contribution guidelines](CONTRIBUTING.md).

## Libraries

- [go-gandi](https://github.com/go-gandi/go-gandi) - A Go library for Gandi V5 APIs.
- [Lego](https://github.com/go-acme/lego) - A ACME client and library that supports Gandi V5 API and built in Go.
- [LibDNS](https://github.com/libdns/libdns) - A Universal DNS provider APIs for Go with a [Gandi V5 provider](https://github.com/libdns/gandi) available.
- [libcloud](https://github.com/apache/libcloud) - A Python library to manage cloud resources (compute and DNS for Gandi driver).
- [Lexicon](https://github.com/AnalogJ/lexicon) - A Python library to manipulate DNS records in a standardized way, supporting Gandi LiveDNS.

## Deployment

- [Ansible Gandi LiveDNS](https://docs.ansible.com/ansible/latest/collections/community/general/gandi_livedns_module.html) - A Ansible module for managing Gandi LiveDNS records.
- [Gandi Pulumi Provider](https://github.com/pulumiverse/pulumi-gandi) - A Pulumi provider to manage Gandi resources.
- [Gandi Terraform Provider](https://github.com/go-gandi/terraform-provider-gandi) - A Terraform provider to manages Gandi resources (domains, mailboxes, etc.).
- [gandi-2-terraform](https://github.com/marcaurele/gandi-2-terraform) - A Python tool to export DNS records of a Gandi organization to a compatible Terraform file using the [Gandi Terraform Provider](https://registry.terraform.io/providers/go-gandi/gandi).

## Clients

- [Certbot](https://certbot.eff.org/) - A ACME client that supports Gandi V5 API with [certbot-plugin-gandi](https://github.com/obynio/certbot-plugin-gandi).
- [DDClient](https://github.com/ddclient/ddclient) - The most popular open-source DDNS client that supports Gandi LiveDNS.
- [Lego](https://go-acme.github.io/lego/usage/cli/) - A ACME client and library that supports Gandi V5 API and built in Go.

## APIs

- [Gandi API](https://api.gandi.net) - The Gandi v5 API.
- [Gandi Sandbox API](https://api.sandbox.gandi.net) - The Gandi v5 Sandbox API allowing you to use the API without creating any resources.

## Docs & tutorials

- [Gandi documentation](https://docs.gandi.net) - Official documentation.
- [GandiCloud VPS tutorials](https://docs.gandi.net/en/cloud/vps/tutorials/index.html) - Tutorials made by Gandi with examples of what can be done with a GandiCloud VPS.
- [Custom Linux distribution on GandiCloud VPS](https://mdk.fr/blog/how-to-install-any-distrib-on-a-gandi-vps.html) - Article about how to install any distribution on a GandiCloud VPS.
- [Install OpenBSD 7.0 on a Gandicloud VPS](https://mvieira.fr/posts/install-openbsd-on-gandicloud-vps/) - Article about how to install OpenBSD 7.0 on a GandiCloud VPS ([also available in french](https://themimitoof.fr/installer-openbsd-7-0-sur-gandicloud-vps/)).
