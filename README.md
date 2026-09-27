# Human3.6M

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FHuman3.6M-181717?logo=github)](https://github.com/biometric-community/Human3.6M)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://vision.imar.ro/human3.6m/)

**Human3.6M** — tbiom catalog packaging for `human36m` (pose3d; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/Human3.6M
- **Upstream source**: http://vision.imar.ro/human3.6m/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `human36m` |
| Category | `pose3d` |
| Access | `register` |
| Upstream homepage | http://vision.imar.ro/human3.6m/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Human3.6M; academic license agreement.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/Human3.6M.git
cd Human3.6M
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_human36m.sh
```

Place licensed archives under `projects/datasets/human36m/` (gitignored).

## Dataset structure

```text
Human3.6M/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://vision.imar.ro/human3.6m/
- Packaging: https://github.com/biometric-community/Human3.6M/issues
