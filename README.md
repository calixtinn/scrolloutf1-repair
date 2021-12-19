# scrolloutf1-repair

Forked from [scrolloutf1-repair](https://github.com/steelburn/scrolloutf1-repair)

## Adjustements:

- Debian 9 doesn't have the php5-fpm, php5-cgi and php5 packages on your repository. I've added Debian 8 "Jessie" repositories temporarily to download these dependencies, and after install, I removed them.

- SpamAssassin update bug fixed

## Observations:

The server must have the hostname and FQDN configured correctly! Please set the correct hostname before install, and FQDN on /etc/hosts !

## Installation (as root)

```bash
apt update
apt-get install -y sudo ca-certificates git
git clone https://github.com/calixtinn/scrolloutf1-repair.git /tmp/scrolloutf1
chmod 755 /tmp/scrolloutf1/www/bin/*
/tmp/scrolloutf1/www/bin/install.sh
```

## Credits

All the credits for this software must be given to MARIUS GOLOGAN (marius.gologan@gmail.com) !!





