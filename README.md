# basic-dns-setup
# Basic DNS Setup — Practice Version

## Goal
Practice static website hosting and basic DNS configuration
using free alternatives.

## Tools Used
- GitHub and GitHub Pages
- FreeDNS
- VMware
- Ubuntu
- Nginx

## Task 1: GitHub Pages
1. Published my Super Cars website using GitHub Pages.
2. Created the FreeDNS hostname:
   supercars-spanishflu.strangled.net
3. Attempted to connect it to GitHub Pages.
4. FreeDNS restricted CNAME records on the selected shared domain.
5. Tried an A record, but GitHub reported InvalidARecordError.

Result: The GitHub Pages website works, but its custom DNS
configuration is incomplete.

## Task 2: Local Static Site Server
1. Installed Ubuntu in VMware.
2. Installed Nginx:
   sudo apt update
   sudo apt install nginx
3. Downloaded my website project into ~/basic-dns-setup.
4. Copied the HTML and CSS files to /var/www/html:
   sudo cp ~/basic-dns-setup/*.html ~/basic-dns-setup/*.css /var/www/html/
5. Opened http://localhost inside Ubuntu.
6. Confirmed that my Super Cars website loads.

Result: Local hosting works inside the VM. Access from the
main computer was attempted but not completed.

## Limitations
- Used a free shared subdomain instead of purchasing a domain.
- Used a local Ubuntu VM instead of a DigitalOcean Droplet.
- Did not complete a working custom-domain DNS connection.
- Did not configure DNS for the local server.
