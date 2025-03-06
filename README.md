<p align="center">
  <img src="https://i.imgur.com/irnHU8d.png" />
</p>

### Project Elixir Jenkins Device Configs シ
Repo which contains the Jenkins Build Parameters of all the devices which are used by Elixir Robot (bot) to trigger builds in Project Elixir Jenkins

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
  <img src="https://i.imgur.com/bETSPlo.png" />
</p>
