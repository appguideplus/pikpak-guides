---
name: pikpak-onboarding
description: Help a person start using PikPak with an existing account or optional referral registration, account verification, and their first authorized file save and download. Use for PikPak onboarding and setup problems, not bulk registration or unattended account management.
---

# PikPak onboarding by AppGuide+

Independent guidance, not official PikPak support. Reply in the user's language. Loading this skill does not install software, sign in, or authorize account access.

## Choose the starting point

Use information already supplied; find out whether the person has an account and wants the app/web drive or an AI tool with the official CLI. Existing users sign in rather than create another account. App/web users can follow the illustrated guide without installing the CLI.

Choose the corresponding locale: Korean `ko`, English `en`, Japanese `ja`, Simplified Chinese `zh-hans`, Taiwan Traditional Chinese `zh-hant`, or Hong Kong Traditional Chinese `zh-hk`. Substitute a real locale before presenting links:
- CLI and signup choices: https://appguideplus.com/{locale}/pikpak/cli-ai/#signup
- First cloud save: https://appguideplus.com/{locale}/pikpak-guide/#save
- Device download: https://appguideplus.com/{locale}/pikpak-guide/#download
- App invitation conditions: https://appguideplus.com/{locale}/pikpak-free-premium/

## Prepare only the requested connection

Read https://mypikpak.com/en-US/cli for the current official installer. Let the person review it and their AI tool's installation scope. Do not install dependencies or change global agent settings just because this skill was loaded.

When command execution is authorized, use `pikpak --help` and the installed subcommand's help before file operations. Follow the actual installed version rather than inventing flags. Existing users can use `pikpak auth login` and complete the official browser authorization themselves. Do not request, print, store or place passwords, verification codes, tokens or payment details in commands or generated files. A failed login is not evidence that an account does not exist.

## Disclose and offer the signup choice

Before referral registration, explain in the user's language: AppGuide+ may earn commission from qualifying purchases when you register with its code; you can register without a referral. Do not choose for the person.

For a new user choosing the referral:
```text
pikpak auth register --affiliate 79099748
```
For a new user choosing no referral:
```text
pikpak auth register
```

The `PIKPAK_AFFILIATE` environment variable can also supply a referral; an explicit `--affiliate` flag takes precedence. Do not silently set persistent environment variables. In the no-referral path, explain that an existing environment setting may still supply a code; have the person check and remove any referrer on the official registration page without dumping their environment. They can remove or restore the referrer before completing registration.

The person completes registration, terms, CAPTCHA and authentication in the official browser flow. Never register accounts in the background. Existing users do not become new referrals by installing this skill. A copied command is not verified registration or attribution. Do not promise app trial benefits for CLI registration, cash rewards to visitors, or guaranteed commissions.

## Verify and complete one useful task

After CLI registration, sign in through PikPak Web or the app within 72 hours to verify the account. Public sharing is restricted before verification; missing the deadline can temporarily lock the account. Resolve verification through the existing account rather than registering again.

Ask for one file/link the person is entitled to store and the intended folder. Confirm account/target when ambiguous, without listing unrelated private files. App/web users follow the illustrated save guide. For an authorized CLI task, consult installed help for the actual upload/save and task-status commands. Do not guess commands.

Distinguish a local upload from fetching a supported link into the cloud. Check the actual service task status; submission alone is not completion. After completion, verify the intended file exists. Cloud storage is not a copy on the device.

For a local copy, follow the device-download guide or the installed CLI's documented download command. Confirm the local destination; resolve existing-file conflicts before overwriting. Deletion, moving existing files, public sharing and permission changes need the person's explicit requested scope; onboarding does not authorize them.

## Resolve problems and report honestly

- Authentication/verification: use the official browser flow, without collecting credentials or bypassing challenges.
- Failed/pending saves: report actual status; do not resubmit a possibly running task blindly.
- Quota or Premium restrictions: explain the displayed limit without automatically buying or upgrading.
- No authorized account/device access: provide instructions and mark execution unverified.

Report completed steps, cloud versus device location, and the remaining action if blocked. Never infer referral attribution or revenue from file operations or clipboard success.

## Official references

- CLI and operation skill: https://mypikpak.com/en-US/cli
- Registration/verification: https://mypikpak.com/en-US/help-center/connected_apps/pikpak_cli/register_account
- Referral command: https://mypikpak.com/referral/help-center/ko/8-cli-and-developer-distribution/how-to-use-invitation-code-in-pikpak-cli
- Referral disclosure: https://mypikpak.com/referral/help-center/ko/8-cli-and-developer-distribution/what-to-do-after-enabling-affiliate-distribution

Checked 2026-10-21. Consult current official help if commands or conditions differ.
