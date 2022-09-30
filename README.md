# The Website

This is a website for our NASA SpaceApps 2022 submittion.
It's a simple static site.

## Deployment

The repo comes with a pretty basic `lighttpd` config file.
all what's required is to set the username file to that of the user that owns the repo's directory (probably yours).
and then run

`sudo lighttpd -f lighttpd.conf`

