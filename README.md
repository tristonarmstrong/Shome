# Shome

A dead-simple, single-file landing page for your home server.

Drop `index.html` into `/var/www/html` (or your Nginx root) and you're done.

## Features

- Material 3 design
- Auto light/dark mode
- 1:1 grid buttons
- Dynamic `{{current_domain}}` → works on any IP/domain
- No build, no deps

## Add a Service

```html
<a href="http://{{current_domain}}:9090" class="service-button">
  <span class="icon">dashboard</span>
  <span class="label">Cockpit</span>
</a>
