# boilr-validate

This is a [boilr template](https://github.com/tmrts/boilr) for creating a validation extension. Use a validation extension to create and enforce custom yaml linting rules. Get started by cloning the project and installing the template:

```console
$ cd boilr-validate
$ boilr template save . drone-validate -f
```

create a project in directory my-validator:

```console
$ boilr template use drone-validate my-validator
```

enter the docker registry name for this project:

```text
[?] Please choose a value for "DockerRepository" [default: "foo/bar"]:
```

enter the go module name:

```text
[?] Please choose a value for "GoModule" [default: "github.com/foo/bar":
```
