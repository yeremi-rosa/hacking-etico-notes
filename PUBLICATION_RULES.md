# Public Documentation Standards

This repository is a public portfolio artifact. Documentation should be clear, reproducible, ethical, and safe to share.

---

## Publishable Content

Good public lab documentation includes:

- Completed lab writeups with objective, environment, commands, results, findings, and defensive takeaway.
- Scripts created during labs, with comments and safe defaults.
- Reproducible commands and relevant output.
- Original diagrams or explanations written in my own words.
- Screenshots that clearly support the technical explanation.
- Troubleshooting summaries written in professional cause/effect language.
- Defensive notes: how to detect, monitor, mitigate, or harden against the technique.
- General lessons learned that help another learner reproduce the lab safely.

---

## Safety Review Before Publishing

Before publishing, each file should be reviewed for:

- Credentials, API keys, tokens, passwords, cookies, session IDs, or connection strings.
- Personal account details, emails, notifications, private URLs, or browser session data.
- Sensitive IP addresses, hostnames, or infrastructure details that should not be public.
- Client, employer, or third-party private information.
- Copied course material, slides, transcripts, or non-original wording.
- Screenshots that reveal unrelated tabs, accounts, messages, or private data.

If the material does not directly support the technical writeup, remove it.

---

## Documentation Quality Bar

Every public writeup should answer:

- What was the objective?
- What environment was used?
- What commands or tools were executed?
- What result was observed?
- What was learned?
- How does the offensive technique connect to detection, mitigation, or hardening?

---

## Screenshot Standards

Screenshots should be used only when they improve clarity.

Before publishing screenshots:

- Crop unrelated browser tabs, account menus, and desktop notifications.
- Hide secrets, tokens, cookies, and session data.
- Hide personal account information.
- Keep the screenshot focused on the lab evidence.
- Prefer text output when a screenshot adds no extra value.

---

## Commit Standard

Each commit should represent a clear portfolio improvement:

- A completed lab writeup.
- A useful script or tool note.
- A documentation cleanup.
- A troubleshooting or defensive security improvement.

The repository should read like professional technical documentation, not a scratchpad.
