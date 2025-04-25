<p align="center">
  <img src="https://github.com/Project-Elixir/docs/blob/bkl/res/elixir-a16banner.png" />
</p

<br>   

### Project Elixir Jenkins Device Configs シ
Repo which contains the Jenkins Build Parameters of all the devices which are used by Elixir Robot (bot) to trigger builds in Project Elixir Jenkins

[![Download Project Elixir [Custom ROM]](https://img.shields.io/sourceforge/dm/project-elixir.svg)](https://projectelixiros.com/download) <img src="https://komarev.com/ghpvc/?username=Project-Elixir&style=flat-square" alt="Project-Elixir" />  [![Download Project Elixir [Custom ROM]](https://img.shields.io/sourceforge/dt/project-elixir.svg)](https://projectelixiros.com/download) 

### Instructions to the maintainers
Please follow the below steps to create your device config and make a PR to this repo:

1. Create a JSON file having your device codename as its file name.
```text
codename.json
```

2. Use the below template and edit it according to your needs and add it in the JSON file.
```json
{
    "DEVICE": "",
    "REPO": "",
    "DIR": "",
    "BUILD_TYPE": "userdebug",
    "UPLOAD_RECOVERY": true,
    "IS_PIXEL": false,
    "SHOW_STATUS": true
}
```
> [!Note]
> - `DEVICE`: Device codename.
> - `REPO`: Github repo link of the device tree.
> - `DIR`: Directory where the device tree repo needs to be cloned.
> - `BUILD_TYPE`: Self explanatory.
> - `UPLOAD_RECOVERY`: Self explanatory.
> - `IS_PIXEL`: Self explanatory.
> - `SHOW_STATUS`: Show/Hide jenkins console and post on cli channel

3. Finally make a PR to this repo and tag any core member in maintainers group to merge it.

### Example: [Ref Here](https://github.com/ProjectElixir-Devices/jenkins_config/blob/main/lynx.json)

<br>

> [!Tip]
> **Donate**: [Do consider donating or buying us a coffee](https://projectelixiros.com/donate)

<p align="center">
  <img src="https://github.com/Project-Elixir/docs/blob/bkl/res/elixir-copyright.png" />
</p
