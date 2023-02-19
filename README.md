# Octodroid Build Service
## Description (June 9th, 2022)
This project may be considered like an alternative to a CI setup for [official Octodroid repository](https://github.com/slapperwan/gh4a) (an unofficial open-source GitHub client for Android devices) and was born because there is no release since [4.6.7](https://github.com/slapperwan/gh4a/releases/tag/4.6.7) which doesn't include a lot of merged PRs. Every time a new PR will be merged in official repository, a new apk will be released in this repository.

## Updates (July 15th, 2022)
Official [4.6.8](https://github.com/slapperwan/gh4a/releases/tag/4.6.8) release has finally arrived. However, this repo will remain active to host future Octodroid debug builds (which will be available every time a new PR, or group of PRs, is merged). Stay tuned to get future updates!

## Usage
Go to [releases page](https://github.com/pokemaniac05/OctodroidBuildService/releases/latest) and download latest apk. It is an unofficial debug build and corresponding PRs will be shown in that page. You may install this debug build alongside official app because a different package name is used (``com.gh4a.debug``).

## Notes
This project isn't affiliated in any way with official Octodroid developers or with GitHub. The rights of Octodroid belong to [Azwan Adli](https://github.com/slapperwan) and those of Github belong to Microsoft. This is an unofficial way to get a rolling-release approach for Octodroid.

In order to make this project work, secret files are used to manage Github login system and allowing login using an unofficial app. Only @pokemaniac05 - in quality of project maintainer - has access to those files and no one is authorized to fork this repo or reverse engineer the apks in releases page in order to access secret codes necessary to build app. If you want to get access to these files and contribute to the project, please contact me.
