# Quick reference

-	**Maintained by**:
	[the <organization-title> Team](https://github.com/<organization>/docker-mkpasswd)

-	**Where to get help**:
	[the <organization-title> online doc](http://doc.<organization>.com/), [the <organization-title> Support Organization](https://support.<organization>.com/)

# Supported tags and respective `Dockerfile` links

-	[`latest` (*Dockerfile*)](https://github.com/<organization>/docker-<product>/blob/master/Dockerfile)

# Quick reference (cont.)

-	**Where to file issues**:
	[https://github.com/<organization>/docker-mkpasswd/issues](https://github.com/<organization>/docker-mkpasswd/issues)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))
	[`amd64`](https://hub.docker.com/r/amd64/<product>/)

-	**Source of this description**:
	[docs repo's `<organization>/` directory](https://github.com/<organization>/docker-<product>/tree/master) ([history](https://github.com/<organization>/docker-<product>/commits/master))

-	**Supported Docker versions**:
	[the latest release](https://github.com/docker/docker-ce/releases/latest) (down to 1.6 on a best-effort basis)

# What is <product>?

**<product>** generates passwords and can apply them automatically to users.

# How to use this image

Command line help is provided:

```bash
docker run --name <product> --rm <organization>/<product>:latest -h
```

---

# How to use this template

When you are done modifying the project boilerplate, remove this section from the documentation.

The template is parameterized so that you can use sed to replace strings globally to produce a fully configured baseline project. Globally replace the following terms with your tailored variants:

| Replacement | Description |
|---|---|
| `<organization>` | The Docker Hub organization name, in lowercase, as shown in Docker Hub  |
| `<organization-title>` | The organization's proper name, as registered. |
| `<product>` | The product name, lower-cased. |
| `<description>` | The product long description. |
| `<short-description>` | The product short description. |
| `<version>` | The product version. |
| `<release>` | The product release. Different than version, it can be used to denote the version of constituent software instead of your product, e.g. for MySQL if you were to extend MySQL. |

The sample Docker is operational, and fully secure, and CLAIRE scanned. It for illustration purposes simply provides CURL.

The sample Docker uses Alpine 3.11, to keep the image lightweight.

# License

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

View [license information](https://raw.githubusercontent.com/tool-dockers/docker-whois/master/LICENSE) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.

# About

[tool-dockers][website] maintains and funds this project.

  [logo]: https://avatars3.githubusercontent.com/u/57697117?s=60&v=4
  [website]: https://continuul.solutions
  [slack]: https://continuul.slack.com
