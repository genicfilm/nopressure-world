# nopressure.world

The NO PRESSURE waitlist site. Static, served by GitHub Pages at https://nopressure.world (DNS at GoDaddy).

- `index.html` is the whole site: the scroll film from the first waitlist build, then the launch-kit story, then the form.
- Signups post straight to Klaviyo (account XVVLZu, list `VtUvii` "NO PRESSURE — Waitlist (nopressure.world)") through the public client subscriptions endpoint, with `custom_source` `nopressure.world · hero|final` and `np_*` UTM properties. No server, no secrets.
- Film: `film/*-scrub-v2.mp4`, buffered to a blob and scrubbed by scroll.
- Images come from `output/no-pressure-ig-launch-20261022` (AI renders; product and placement are provisional).
