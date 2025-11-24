# Omasa Landing Page

This directory contains the landing page for the Omasa massage routines app.

## Live Site
- Current URL: https://benju.fr/omasa/ or https://www.benju.fr/omasa/
- Planned subdomain: https://omasa.benju.fr (requires DNS configuration)

## Setting up the Subdomain (omasa.benju.fr)

To make the landing page accessible at `omasa.benju.fr`, you need to configure DNS records at your domain registrar (OVH):

### Option 1: CNAME Record (Recommended)
1. Log in to your OVH domain management panel
2. Go to DNS Zone configuration for `benju.fr`
3. Add a CNAME record:
   - **Subdomain**: `omasa`
   - **Type**: `CNAME`
   - **Target**: `benju69.github.io.` (note the trailing dot)
   - **TTL**: 3600 (or default)

### Option 2: A Records
Alternatively, you can use A records pointing to GitHub Pages IPs:
1. Add A records for subdomain `omasa`:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`

### GitHub Pages Configuration
After DNS is configured:
1. Go to repository settings on GitHub
2. Navigate to Pages section
3. Add `omasa.benju.fr` as a custom domain
4. Enable HTTPS (recommended)

**Note**: DNS propagation can take up to 48 hours, but usually completes within a few hours.

## Files
- `index.html` - Main landing page
- `privacy-policy.html` - Privacy policy
- `terms-of-use.html` - Terms of use
- `README.md` - This file

## Contact
For questions about the Omasa app: omasa.contact@gmail.com
