# wholehartedwellness.com

The company website for Wholeharted Wellness, LLC. One static HTML page, no
framework and no build step, hosted on GitHub Pages.

## Editing it

`index.html` is the whole site. Change it, commit, push — GitHub Pages redeploys
within a minute or two.

## Hosting and DNS

- **Host:** GitHub Pages, from the `main` branch of this repository.
- **Domain:** registered at GoDaddy, DNS there too. The apex points at GitHub Pages'
  four A records; `www` is a CNAME to the `github.io` address.
- **Email:** forwarding only, no mailbox — mail to the domain is forwarded to the
  company's inbox. Sending from the address would need an SMTP relay, which is not
  set up.

## Not related to the app

Schedule Maxxing (schedulemaxxing.com) is a separate codebase, repository and host.
Nothing here shares code with it, and nothing here should be moved into it.
