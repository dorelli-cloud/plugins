---
description: Put the site in this folder online on Dorelli Cloud, or update the existing site.
argument-hint: (optional) email address for the management link
---

Put the site in the current folder online on Dorelli Cloud with the skill
`dorelli-deploy`. If there is already a `.dorelli.json`, update that same
site. If no email address is known and "$ARGUMENTS" has none, ask the user
for it; never make one up.

Then give the user the URL of the site (the last line of the output) and say
that the management link arrives by email.
