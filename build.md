RvX: 18.31.40  
ReX: 18.33.40  
Music-X: 6.19.51  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-3.1.2-all.jar  
Integrations: inotia00/revanced-integrations-0.117.4.apk  
Patches: inotia00/revanced-patches-2.190.4.jar  

YouTube
==
- fix(youtube/bypass-ambient-mode-restrictions): update fingerprint
- fix(youtube/default-video-quality): default video quality is not applied at cold start
- fix(youtube/hide-suggestions-shelf): not working on tablets https://github.com/inotia00/ReVanced_Extended/issues/1337
- fix(youtube/sponsorblock): change invalid patch name
- fix(youtube/sponsorblock): fetch to latest source
- fix(youtube/spoof-player-parameters): spoofing also applies to shorts videos
- fix(youtube/settings): remove unused string resources
- feat(youtube/translations): update translation
`Korean`, `Vietnamese`


YouTube Music
==
- feat(music): add `replace-dismiss-queue` patch
- feat(music): add `sponsorblock` patch https://github.com/inotia00/ReVanced_Extended/issues/97
- feat(music): add support version `v6.19.51`
- feat(music/hide-flyout-panel): code refactoring
- fix(music/enable-new-layout): change patch description
- fix(music/hook-download-button): change the default external downloader package name https://github.com/inotia00/ReVanced_Extended/issues/1340
- fix(music/hook-download-button): download button not hooked in certain situations
- fix(music/spoof-app-version): add missing dependencies
- refactor(music/settings): integrate the preferences of the `return-youtube-dislike` setting into the existing settings
- feat(music/translations): update translation
`Brazilian`, `Dutch`, `French`, `Japanese`, `Korean`, `Polish`, `Russia`, `Spanish`, `Turkish`, `Vietnamese`


Etc
==
- build: update dependency


※ Compatible ReVanced Manager: [RVX Manager v1.9.7 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.9.7)
---
CLI: YT-Advanced/revanced-cli-3.1.0-all.jar  
Integrations: YT-Advanced/revanced-integrations-0.120.0.apk  
Patches: YT-Advanced/revanced-patches-2.191.0.jar  

### [2.191.0](https://github.com/YT-Advanced/ReX-patches/compare/v2.190.2...v2.191.0) (2023-09-19)
### Bug Fixes
* **music/return-youtube-dislike:** add translation exception ([6f56d78](https://github.com/YT-Advanced/ReX-patches/commit/6f56d78e3edb8f34643168c6cbe513cf71124f6a))
* **music/spoof-app-version:** add missing dependencies ([acd7d05](https://github.com/YT-Advanced/ReX-patches/commit/acd7d057b9918a6a539dfd1ea748fcc143efee52))
* **youtube/bypass-ambient-mode-restrictions:** update fingerprint ([6087d7b](https://github.com/YT-Advanced/ReX-patches/commit/6087d7be8340e48488a054c715ebd0b9b4a80bd0))
* **youtube/default-video-quality:** default video quality is not applied at cold start ([517e86f](https://github.com/YT-Advanced/ReX-patches/commit/517e86f75ceb18b1fbeac7a01a39bc065e6deb67))
* **youtube/settings:** remove unused string resources ([a09e2e5](https://github.com/YT-Advanced/ReX-patches/commit/a09e2e5b137c71a65377feb55aa3d0aee26dc6d3))
* **youtube/sponsorblock:** change invalid patch name ([ae06785](https://github.com/YT-Advanced/ReX-patches/commit/ae06785f7741c73d046658a5eecf97ebfa4f1217))
### Features
* **music/hide-flyout-panel:** code refactoring ([33ad9af](https://github.com/YT-Advanced/ReX-patches/commit/33ad9afe89a556014a1aa083bf9dd18781642fa1))
* **music:** add `replace-dismiss-queue` patch ([0a06b69](https://github.com/YT-Advanced/ReX-patches/commit/0a06b69b6bd842df34aac55a9117e63d0b81c49a))
* **music:** add `sponsorblock` patch https://github.com/inotia00/ReVanced_Extended/issues/97 ([88d6389](https://github.com/YT-Advanced/ReX-patches/commit/88d63898bce47d78e535114a40beb3be5c41d695))
* **music:** add support version `v6.19.51` ([69cb800](https://github.com/YT-Advanced/ReX-patches/commit/69cb800603356e98f74888342634eca305b80054))
* Readd Ads Whitelist ([c83c3b8](https://github.com/YT-Advanced/ReX-patches/commit/c83c3b823ee574e8f06814ec79a2943934ad8956))

---  
