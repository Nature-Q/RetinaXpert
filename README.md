# RetinaXpert

Reproducibility materials for multi-label retinal disease classification from fundus images.

## Release status

**Repository structure initialized; research files pending upload.**

The current repository contains directory guides only. The actual image resources, harmonized annotations, dataset split manifests, model implementation, training and evaluation scripts, experimental configurations, and results have not yet been uploaded. No trained model or runnable implementation is included in this initial commit.

## Repository organization

| Path | Intended contents |
| --- | --- |
| `NoSplit/` | Unsplit data resources, associated annotation files, or links to the corresponding image archive. |
| `Split/` | The fixed training, validation, test, and external-evaluation resources used in the reported experiments, or links to those resources. |
| `metadata/` | Harmonized annotations, original-source mappings, split manifests, and a data dictionary. |
| `code/` | The actual model implementation, preprocessing, training, and evaluation scripts. |
| `configs/` | The experimental settings and software environment used to produce the reported results. |
| `results/` | Released evaluation outputs and links to model weights, when available. |

Each directory currently contains a README describing the files to add. These guides are not research data or executable code.

## Data access

The original fundus-image sources are listed in Tables 1 and 2 of the accompanying manuscript. Original images remain subject to their respective licenses and terms of use. See [DATA_ACCESS.md](DATA_ACCESS.md) for the data-release organization.

Large image collections may be hosted in a suitable data repository, with their download links recorded here. The presence of `NoSplit/` and `Split/` does not indicate that the complete image collections have been uploaded.

## Completing the release

1. Add the existing NoSplit and Split materials without changing the sample assignments used for the reported results.
2. Add the harmonized annotations, source mapping, split manifests, and label definitions to `metadata/`.
3. Add the actual final implementation and training/evaluation scripts to `code/`, with their configuration and environment records in `configs/`.
4. Record the exact commit or release corresponding to the manuscript, update this release-status section, and verify that every advertised file or download link is accessible.

For large archives, add a download location instead of duplicate image copies. GitHub's current browser-upload limits are documented in [Adding a file to a repository](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository).

## Licenses

Third-party images remain governed by the original dataset licenses and access conditions. This repository does not grant additional rights to those images. A license for the authors' own implementation can be added when that implementation is released.
