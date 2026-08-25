# Leo — downloads

Leo is a desktop assistant for practising architects. This repository holds **installers and
update metadata only** — no source code.

You do not need a GitHub account to download from here.

## Install

Go to [**Releases**](https://github.com/vtruvian/leo-releases/releases/latest) and download the
`.exe`. Windows 10 or 11, 64-bit.

Leo updates itself after that. You will not need to come back to this page.

## Windows will warn you. Here is how to get past it.

Leo is not yet code-signed — a certificate costs money this alpha does not have — so Windows
SmartScreen shows a blue box saying **"Windows protected your PC"**, with no obvious way
forward. The *Run anyway* button is hidden until you ask for it.

1. Click **More info** — the small link under the message.
2. The dialog expands and shows **Run anyway**. Click it.

That is the whole workaround. If your antivirus also objects: the installer unpacks a Python
interpreter into your user folder, which some scanners treat as suspicious on sight. It is the
engine Leo runs on.

**This warning is about a missing signature, not about what the software does.** If that is not
good enough for you or your IT policy, that is a reasonable position — please say so rather than
clicking through, and wait for a signed build.

## What Leo does with your files

Leo reads project files you point it at and can write into your project folders. During the
alpha, please do not point it at a live job on a deadline until you have seen how it behaves on
a copy.

## Reporting something

Use the in-app **Send feedback**, which attaches your version, OS and recent log lines — that is
the difference between a report that can be fixed and one that cannot. Bugs raised here as
issues are read too.

## Releases you will see here

| Tag | Who it is for |
| --- | --- |
| `v0.1.0` | The alpha cohort |
| `v0.1.0-alpha.N` | Pipeline rehearsals — **ignore these**, they are not builds for you |

---

Leo is unreleased software under active development. © 2026 Vtruvian.
