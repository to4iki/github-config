# github-config

Manage GitHub repository settings and shared files using [gh-infra](https://github.com/babarot/gh-infra).

## Usage

Install:

```sh
gh extension install babarot/gh-infra
```

Manage repository settings:

```sh
gh infra plan repos/
gh infra apply repos/
```

Applying common files to multiple repositories:

```sh
gh infra plan files/
gh infra appy files/
```
