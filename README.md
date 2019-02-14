# DarkPanSix
Tools for building a private Perl6 library Ecosystem

## Plans :

- Script for modifying your zef config file to ensure your personal ecosystem is available.
- Script for creating a combined Meta.json file that can be deployed to a webservice or git
- Dockerfiles for each of these
- Documentation on using them.

## How the system works

Building a private Perl6 ecosystem relies on two things.

- The original Perl6 ecosystem which involved collating a list of different `META6.json` files into a list.
- The ability to add custom ecosystem plugins to Zef.

In order to maintain a personal library ecosystem you need a list of `META6.json` file URLs. This is then converted into an `ecosystem.json` file that you can then host somewhere available to people who require it.

On the client side you need to tell Zef the existence of your local ecosystem but updating it's config.

