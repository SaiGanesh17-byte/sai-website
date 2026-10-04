# sAI website

The public page where people request access to sAI. Only the website lives here --
never sAI's source code. Hosted free on GitHub Pages.

- Requests arrive by email via FormSubmit (`./publish.sh you@example.com` sets the address;
  the first request triggers a one-time "activate this form" email from FormSubmit).
- Approve a request from the sAI repo: `venv/bin/python -m guard approve ...`
  (see sAI's docs/PROTECTED_BUILDS.md).
