# Webhosting

## VPS/Hosting Providers

* [MediaTemple](http://www.mediatemple.net/#a_aid=4f02a00cb69fc)
* [Digital Ocean](https://www.digitalocean.com/?refcode=d899c87d027c)

## Server Customisations: CentOS

* Install/Setup Base OS
* `yum update`
* Enable SSH on port 443 (optional)
  * `vi /etc/ssh/sshd_config`
  * Add/check the following lines exist
    * `Port 22`
    * `Port 443`
* Future/TODO/Etc
  * Setting up SSH keys, etc
  * Setup [Plesk](http://www.parallels.com/au/products/plesk/pricing-licensing/)/similar
  * Setup Git/[GitLab](http://gitlab.org/)?
  * Setup [Drush](http://drush.ws/)?
  * Server Hardening?
