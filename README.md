# Jenkins Device Configs

> Repo which contains the Jenkins Build Parameters of all the devices which are used by [ElixirRobot](https://telegram.me/projectelixir_bot) to trigger builds in [ProjectElixir Jenkins](https://jenkins.projectelixiros.com).

## Instructions to the maintainers

### Please follow the below steps to create your device config and make a PR to this repo:

#### 1. Create a JSON file having your device codename as its file name.

```text
codename.json
```

#### 2. Use the below template and edit it according to your needs and add it in the JSON file.

```json
{
    "DEVICE": "",
    "REPO": "",
    "DIR": "",
    "BUILD_TYPE": "",
    "UPLOAD_RECOVERY": true
}
```

- `DEVICE`: Device codename.
- `REPO`: Github repo link of the device tree.
- `DIR`: Directory where the device tree repo needs to be cloned.
- `BUILD_TYPE`: Self explanatory.

#### 3. Finally make a PR to this repo and tag any core member in maintainers group to merge it.

### Example: [Here](https://github.com/ProjectElixir-Devices/jenkins_config/blob/main/guacamoleb.json)

