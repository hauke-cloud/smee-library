<!-- llm-readme-management spec=1 commit=65bb11a04de868548876b2cd4ef1f2d8f01dcbd2 template=default model=qwen3.8-27b-q4 digest=598d66067ca0 generated=2026-10-12T12:23:35Z -->
<a href="https://hauke.cloud" target="_blank"><img src="https://img.shields.io/badge/home-hauke.cloud-brightgreen" alt="hauke.cloud" style="display: block;" /></a>
<a href="https://github.com/hauke-cloud" target="_blank"><img src="https://img.shields.io/badge/github-hauke.cloud-blue" alt="hauke.cloud Github Organisation" style="display: block;" /></a>
<a href="https://github.com/hauke-cloud/llm-readme-management" target="_blank"><img src="https://img.shields.io/badge/template-default-orange" alt="Repository type - default" style="display: block;" /></a>


# Smee Library


<img src="https://raw.githubusercontent.com/hauke-cloud/.github/main/resources/img/organisation-logo-small.png" alt="hauke.cloud logo" width="109" height="123" align="right">


<llm header>

This repository provides prebuilt Docker container images that bundle a development tooling environment for Smee. The images include tools such as OpenTofu, Terraform, and Helm, a pre-configured zsh terminal with the spaceship prompt, and a set of shell aliases and functions. They are intended for developers who want a consistent tooling setup without configuring their own environment.

</llm>


## :book: Description

<llm description>

`smee-library` is a collection of prebuilt container images that provide a ready-to-use development tooling environment for Smee. Rather than installing and configuring individual CLI tools, a shell prompt, and shell aliases separately on each machine or runner, you pull an image that already has them in place.

The images target specific development environments and ship with a pre-configured zsh terminal using the spaceship prompt, along with a set of pre-configured aliases and shell functions.

- OpenTofu/Terraform tooling
- Helm tooling
- Pre-configured zsh shell with spaceship prompt
- Pre-configured aliases and shell functions

The repository is part of the `hauke-cloud` organisation and is used by Smee. At the current commit the tracked tree contains only the README and an empty placeholder file; the image definitions and shell configuration described above are not present in this checkout.

</llm>


## 🚀 Getting started

<llm getting_started hint="Assume nothing about the ecosystem beyond what the analysis names. If the repository has no build step, say what a reader does with it instead.">

1. Clone the repository.

```bash
git clone https://github.com/hauke-cloud/smee-library.git
cd smee-library
```

2. There is nothing to build, install, or run. The repository at its current state contains only a `README.md` and an empty `.keep` placeholder file. No Dockerfiles, build scripts, CI workflows, or source code are present, and no commands are documented.

3. The README describes a collection of prebuilt container images (tooling for OpenTofu/Terraform, Helm, a zsh shell with the spaceship prompt, and pre-configured aliases), but the image definitions are not in this repository. The README also references a `LICENSE` file and a `CONTRIBUTING.md` file that are not present in the tree.

In short: after cloning, you have a descriptive README and a placeholder. There is no further step that produces a working result from this checkout.

</llm>


## :airplane: Usage

<llm usage>

The images in this repository are intended to be pulled and run as your development shell. Each image ships with a pre-configured zsh terminal (spaceship prompt), a set of pre-configured aliases and functions, and tooling for specific environments such as opentofu/terraform and helm. You would typically pull the image for the environment you need and start an interactive session inside it.

At the current state of this repository (commit `65bb11a0`), no Dockerfiles, image definitions, build scripts, or registry references are present in the tracked tree. The repository contains only a `README.md` and an empty `.keep` placeholder. Until the image definitions and build tooling are added, there are no concrete pull or run commands to document here.

</llm>


## 📄 License

This Project is licensed under the GNU General Public License v3.0

- see the [LICENSE](LICENSE) file for details.


## :coffee: Contributing

To become a contributor, please check out the [CONTRIBUTING](CONTRIBUTING.md) file.


## :email: Contact

For any inquiries or support requests, please open an issue in this
repository or contact us at [contact@hauke.cloud](mailto:contact@hauke.cloud).
