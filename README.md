# Precise. Rapid. Discreet.

Welcome to the **official SMU website**. This repository hosts our public-facing landing page intended for controlled external visibility. The site is delivered via GitHub Pages and consists solely of static content.

The design prioritizes minimal digital signature, reduced attack surface, and privacy-by-default principles.

---

## Architecture

- Static HTML, CSS, and a small amount of inline JavaScript
- Single file — no build step, no package manager, no dependency tree
- No server-side code
- No databases or persistent storage
- No authentication mechanisms
- No cookies, local storage, or session storage
- No client-side tracking, analytics, or telemetry

The JavaScript is inline and does three things: the mobile navigation menu, the back-to-top button, and runtime assembly of the contact address. It makes no network requests.

This architecture intentionally limits exposure and eliminates common vectors for data compromise.

---

## Privacy & Signature Reduction

- No user data is collected or processed by this site
- No third-party scripts or embedded services are used
- No behavioral analytics or telemetry are present
- All content is intentionally public and non-sensitive

Contact information displayed on the site is provided for legitimate engagement and does not expose credentials, identifiers, or privileged access.

---

## What This Does Not Cover

Stating the limits honestly is part of the discipline this site is about.

- **Host logs.** GitHub Pages records visitor IP addresses, user-agents, and requested paths in its own infrastructure. This is outside the site's control and is the only visitor collection that still occurs. Anyone relying on this page's privacy posture should understand that the hosting provider sees traffic regardless of what the markup does.
- **Repository metadata.** This repository is public, and so is its commit history. Every commit carries an author name, an author email address, and a timestamp. Commit timing across a history also reveals a working-pattern signature. Verify what identity is attached to commits before pushing, and consider a dedicated address or GitHub's no-reply address.
- **Archives.** Prior versions of this site, including any content since removed, are likely captured by the Internet Archive and similar services. Removing content going forward does not retract what was published.
- **Transport.** Email is not a secure channel. The site says so at the point of contact; it should keep saying so.

---

## Force Protection Considerations

- This site functions strictly as an information and contact relay
- No operational, personnel, or sensitive business data is hosted
- Repository contents should be treated as publicly accessible at all times
- Changes should be reviewed with OPSEC and digital footprint considerations in mind

### Pre-commit checklist

1. Does the change add any request to a host other than this one? If yes, stop.
2. Does it introduce a build step, package manager, or external dependency?
3. Does it place the contact address in plain text anywhere in the markup?
4. Does it add a claim about the organization, affiliation, or personnel that cannot be substantiated?
5. Does it add cookies, storage, or any form of visitor state?
6. Is the identity attached to this commit the one intended to be public?

---

## License

**All rights reserved.**

Copyright © Signature Management Unit, LLC. The source code, markup, styling, written content, design, and all other materials in this repository are proprietary. No license is granted, expressly or by implication.

You may not copy, modify, distribute, publish, sublicense, or create derivative works from any part of this repository without prior written permission from SMU. Viewing the source in a browser, as any visitor may, does not constitute a grant of any right to reuse it.

This repository is public for transparency and delivery, not for reuse. Absence of a permissive license file is deliberate; under copyright law, no license means no permission.

### One limit worth knowing

Because this repository is hosted publicly on GitHub, GitHub's Terms of Service grant other GitHub users the ability to view and fork it *within the platform*, regardless of the terms above. "All rights reserved" governs use outside that in-platform mechanism, and it does not disable the fork button.

If preventing forks matters more than public delivery, the repository must be private — which requires GitHub Pro or higher to still publish Pages from it, or moving hosting elsewhere.

---

## Repository Use, Attribution, and Branding

- This repository is the sole authoritative source for the **official SMU website**. All official content, updates, and maintenance are performed exclusively by the SMU team or authorized representatives. This repository and the associated live site are the only sources through which official SMU web content and contact information are published.

- No permission is granted to reuse this codebase or its content. Should any copy or derivative nonetheless be published, it does not carry permission to represent, brand, or imply affiliation with SMU, nor to present itself as an official SMU site. Any such copy must clearly identify itself as unofficial and remove SMU branding and identifying marks in full.

- SMU names, logos, written content, and other identifying materials are proprietary and are not licensed under any terms. No third party is authorized to claim to act on behalf of, speak for, or represent SMU through a copied or derivative version of this site.

---

🇺🇸 **Precise. Rapid. Discreet.**
