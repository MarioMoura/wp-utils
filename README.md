# WordPress Utilities
This is a set of shell scripts that help managing WordPress installations. Keep in mind that all of the scripts were made for a Debian 10 "Buster".

## wp-full-install
Downloads and configures a WordPress instance in a LAMP architecture.
Uses [certbot](https://certbot.eff.org/) to fetch certificates and configure apache.

### Notes:
- All the dependencies are installed at the beginning.
- This is intended to be user on a fresh install.

## wp-install
Configures a WordPress instance.
### Notes:

- Depends on a mariadb, apache2 and php installation.
- Does not configure any packages.
- Uses certbot if required.

## wp-dl
Downloads an WordPress bundle to the current directory.

### Notes
- Has no dependencies.

## wp-cli-dl
Install the [wp-cli](https://wp-cli.org/) tool.

### Notes
- Can be installed by the package manager in some distributions.
