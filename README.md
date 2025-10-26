# Shome

Dead-simple dark-mode landing page for your home server.

Drop `index.html` into `/var/www/html` — Nginx serves it on `:80`.

## Features

- **Dark only** (`#00b3ff` primary)
- Gradient background
- System sans-serif font (no Google Fonts)
- 1:1 service grid
- `{{current_domain}}` → auto IP/domain
- Favicon: `favicon.svg` (Lucide *server*)

## Add Service

```html
<a href="http://{{current_domain}}:1234" class="service-button">
  <span class="icon">apps</span>
  <span class="label">App</span>
</a>
