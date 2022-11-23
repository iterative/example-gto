# Example GTO Model Registry

This [model registry] is an auto-generated repository for use in
[Get Started with GTO], a step-by-step introduction to the most valuable GTO
concepts and operations.

> 🐛 Please report any issues found in this project in [example-repos-dev].

Branch [`mlem`] contains a version that also uses [MLEM] to deploy a model upon
deployment stage [assignment].

[get started with gto]: https://mlem.ai/doc/gto/get-started
[model registry]: https://mlem.ai/doc/use-cases/model-registry
[example-repos-dev]: https://github.com/iterative/example-repos-dev
[`mlem`]: https://github.com/iterative/example-gto/tree/mlem
[MLEM]: https://mlem.ai/
[assignment]: https://github.com/iterative/gto#assigning-a-stage-to-version

## Installation

Python 3.7+ is required to run code from this repo.

After cloning this repo, `cd` into it and install the requirements, which
include [gto]. We strongly recommend creating a virtual environment first,
for example with [virtualenv]:

```console
$ virtualenv -p python3 .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

[gto]: https://github.com/iterative/gto
[virtualenv]: https://virtualenv.pypa.io/en/stable/

## To see GTO in action

Start by [showing] the current registry stage:

```console
$ gto show
╒══════════╤══════════╤════════╤═════════╤════════════╕
│ name     │ latest   │ #dev   │ #prod   │ #staging   │
╞══════════╪══════════╪════════╪═════════╪════════════╡
│ churn    │ v3.1.1   │ v3.1.1 │ v3.0.0  │ v3.1.0     │
│ segment  │ v0.4.1   │ v0.4.1 │ -       │ -          │
│ cv-class │ v0.1.13  │ -      │ -       │ -          │
╘══════════╧══════════╧════════╧═════════╧════════════╛
```

> Compare this to the [repository tags] and [`artifacts.yaml`].

🧑‍💻 To continue leargnin, head to [Get Started with GTO].

[showing]: https://github.com/iterative/gto#show-the-current-state
[repository tags]: https://github.com/iterative/example-gto/tags
[`artifacts.yaml`]: https://github.com/iterative/example-gto/blob/main/artifacts.yaml
