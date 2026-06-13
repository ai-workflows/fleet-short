# fleet-short

A small, self-hostable URL shortener and share-link generator for Fleet.

Turn a long URL into a short, shareable link; track basic click analytics;
optionally use a custom slug. Intended as a lightweight internal tool.

## Status

Early build — see the issues for the current plan and progress.

## Planned scope

- Shorten a URL → short code, with redirect
- Custom slugs (optional, collision-checked)
- Click analytics (count + recent referrers/timestamps)
- Minimal web UI to create and list links
- Tests + a simple deploy path

## Tech

Kept intentionally simple and dependency-light; the implementing team will
choose a small, conventional stack (a single web service + lightweight
persistence) and document it here as it lands.
