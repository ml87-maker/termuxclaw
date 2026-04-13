# TermuxClaw

TermuxClaw is the public-facing showcase for my mobile product.

This repository is not the private source code of the app. It exists to expose the experience, the interface, the download path, and the product direction without publishing the backend, runtime, or internal implementation.

TermuxClaw is positioned as a serious mobile-native coding agent surface and a direct mobile rival to OpenClaw.

![TermuxClaw showcase](./images/src_light_mode_agent_working.png)

## What this repo contains

- a public landing page
- screenshots and demo assets
- a release link for APK distribution
- a concise product description for GitHub visitors

## What stays private

- Android app source code
- backend orchestration
- runtime and service internals
- build pipeline internals
- private credentials and provider configuration

## Screens

![TermuxClaw agent working](./images/src_agent_worked.png)

![TermuxClaw terminal tracking](./images/src_terminal_tracking_from_chat.png)

![TermuxClaw live terminal](./images/src_terminal_live.png)

![TermuxClaw workspace manager](./images/src_worpsapce_folder_manager.png)

![TermuxClaw provider settings](./images/src_setting_provider.png)

## Demo

The repo contains the current product recording here:

- [`videos/Screencast from 2026-04-13 02-43-55.webm`](/media/light/Data/_Projects/Android_prime/ivyAppExposed/videos/Screencast%20from%202026-04-13%2002-43-55.webm)

## Before publishing

Update the two download links inside [index.html](/media/light/Data/_Projects/Android_prime/ivyAppExposed/index.html). Right now they still point to a placeholder GitHub Releases URL.

## Suggested release flow

1. Push this repository to GitHub.
2. Upload the APK to GitHub Releases.
3. Replace the placeholder release link in [index.html](/media/light/Data/_Projects/Android_prime/ivyAppExposed/index.html).
4. Keep adding stronger screenshots as the product evolves.
5. Enable GitHub Pages if you want the landing page hosted directly from the repo.

## Positioning

This repository is a product shell, not an open-source drop.

If one day I decide to open more, this repo can still remain the public landing layer while the private implementation stays separate.
