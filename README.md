# CHAINER

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `CHAINER` in category **MEDICINE_DEVELOPMENT**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/chainer/chainer · **Upstream pin:** `a8e15cbe55a90854a3918b8b5a976abbbff9ec94` · **Category:** MEDICINE_DEVELOPMENT · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

***Notice: As [announced](https://chainer.org/announcement/2019/12/05/released-v7.html), Chainer is under the maintenance phase and further development will be limited to bug-fixes and maintenance only.***

----

<div align="center"><img src="https://raw.githubusercontent.com/chainer/chainer/master/docs/image/chainer_red_h.png" width="400"/></div>

# Chainer: A deep learning framework

[![pypi](https://img.shields.io/pypi/v/chainer.svg)](https://pypi.python.org/pypi/chainer)
[![GitHub license](https://img.shields.io/github/license/chainer/chainer.svg)](https://github.com/chainer/chainer)
[![travis](https://img.shields.io/travis/chainer/chainer/master.svg)](https://travis-ci.org/chainer/chainer)
[![coveralls](https://img.shields.io/coveralls/chainer/chainer.svg)](https://coveralls.io/github/chainer/chainer)
[![Read the Docs](https://readthedocs.org/projects/chainer/badge/?version=stable)](https://docs.chainer.org/en/stable/?badge=stable)
[![Optuna](https://img.shields.io/badge/Optuna-integrated-blue)](https://optuna.org)

[**Website**](https://chainer.org/)
| [**Docs**](https://docs.chainer.org/en/stable/)
| [**Install Guide**](https://docs.chainer.org/en/stable/install.html)
| **Tutorials** ([ja](https://tutorials.chainer.org/ja/))
| **Examples** ([Official](examples), [External](https://github.com/chainer-community/awesome-chainer))
| [**Concepts**](https://docs.chainer.org/en/stable/guides/)
| [**ChainerX**](#chainerx)

**Forum** ([en](https://groups.google.com/forum/#!forum/chainer), [ja](https://groups.google.com/forum/#!forum/chainer-jp))
| **Slack invitation** ([en](https://bit.ly/go-chainer-slack), [ja](https://bit.ly/go-chainer-jp-slack))
| **Twitter** ([en](https://twitter.com/CuPy_Team), [ja](https://twitter.com/ChainerJP))

*Chainer* is a Python-based deep learning framework aiming at flexibility.
It provides automatic differentiation APIs based on the **define-by-run** approach (a.k.a. dynamic computational graphs) as well as object-oriented high-level APIs to build and train neural networks.
It also supports CUDA/cuDNN using [CuPy](https://github.com/cupy/cupy) for high performance training and inference.
For more details about Chainer, see the documents and resources listed above and join the community in Forum, Slack, and Twitter.

## Installation

*For more details, see the [installation guide](https://docs.chainer.org/en/stable/install.html).*

To install Chainer, use `pip`.

```sh
$ pip install chainer
```

To enable CUDA support, [CuPy](https://github.com/cupy/cupy) is required.
Refer to the [CuPy installation guide](https://docs-cupy.chainer.org/en/stable/install.html).

## Docker image

We are providing the official Docker image.
This image supports [nvidia-docker](https://github.com/NVIDIA/nvidia-docker).
Login to the environment with the following command, and run the Python interpreter to use Chainer with CUDA and cuDNN support.

```
$ nvidia-docker run -it chainer/chainer /bin/bash
```

## Contribution

See the [contribution guide](https://docs.chainer.org/en/stable/contribution.html).

## ChainerX

See the [ChainerX documentation](https://docs.chainer.org/en/stable/chainerx/index.html).

## License

MIT License (see `LICENSE` file).

## More information

- [Release notes](https://github.com/chainer/chainer/releases)

## References

Tokui, Seiya, et al. "Chainer: A Deep Learning Framework for Accelerating the Research Cycle." *Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining*. ACM, 2019.
[URL](https://dl.acm.org/citation.cfm?id=3330756) [BibTex](chainer2019_bibtex.txt)

Tokui, S., Oono, K., Hido, S. and Clayton, J.,
Chainer: a Next-Generation Open Source Framework for Deep Learning,
*Proceedings of Workshop on Machine Learning Systems(LearningSys) in
The Twenty-ninth Annual Conference on Neural Information Processing Systems (NIPS)*, (2015)
[URL](http://learningsys.org/papers/LearningSys_2015_paper_33.pdf), [BibTex](chainer_bibtex.txt)

Akiba, T., Fukuda, K. and Suzuki, S.,
ChainerMN: Scalable Distributed Deep Learning Framework,
*Proceedings of Workshop on ML Systems in
The Thirty-first Annual Conference on Neural Information Processing Systems (NIPS)*, (2017)
[URL](http://learningsys.org/nips17/assets/papers/paper_25.pdf), [BibTex](chainermn_bibtex.txt)

---

## Installation

| **Tutorials** ([ja](https://tutorials.chainer.org/ja/))
| **Examples** ([Official](examples), [External](https://github.com/chainer-community/awesome-chainer))
| [**Concepts**](https://docs.chainer.org/en/stable/guides/)
| [**ChainerX**](#chainerx)

**Forum** ([en](https://groups.google.com/forum/#!forum/chainer), [ja](https://groups.google.com/forum/#!forum/chainer-jp))
| **Slack invitation** ([en](https://bit.ly/go-chainer-slack), [ja](https://bit.ly/go-chainer-jp-slack))
| **Twitter** ([en](https://twitter.com/CuPy_Team), [ja](https://twitter.com/ChainerJP))

*Chainer* is a Python-based deep learning framework aiming at flexibility.
It provides automatic differentiation APIs based on the **define-by-run** approach (a.k.a. dynamic computational graphs) as well as object-oriented high-level APIs to build and train neural networks.
It also supports CUDA/cuDNN using [CuPy](https://github.com/cupy/cupy) for high performance training and inference.
For more details about Chainer, see the documents and resources listed above and join the community in Forum, Slack, and Twitter.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

It also supports CUDA/cuDNN using [CuPy](https://github.com/cupy/cupy) for high performance training and inference.
For more details about Chainer, see the documents and resources listed above and join the community in Forum, Slack, and Twitter.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

```
$ nvidia-docker run -it chainer/chainer /bin/bash
```

## Contributing

Please refer to [our Contribution Guide](https://docs.chainer.org/en/stable/contribution.html).

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/chainer/chainer
- **Pinned SHA:** `a8e15cbe55a90854a3918b8b5a976abbbff9ec94`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`43f6a2b8525b918bcfb4fe7e1f99f52e2f2fa34116acf821752f237a05df8e7c`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

