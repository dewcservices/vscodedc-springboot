# vscodedc-springboot
VSCode Devcontainer for Springboot (Gradle) with Java17 &amp; a Postgresql database

## How to use

The following are specific commands for this devcontainer

### Add devcontainer to a project for the first time

```shell
git submodule add git@github.com:dewcservices/vscodedc-springboot.git ./.devcontainer
```

#### Expected result

/.gitmodules
```shell
[submodule ".devcontainer"]
    path = .devcontainer
    url = ssh://<submodule-repo>.git
```

### Cloning a project with submodules

```shell
git clone --recurse-submodles ssh://<submodule-repo>.git
```