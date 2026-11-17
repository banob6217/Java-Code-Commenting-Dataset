# Java Code Commenting Dataset — Two Repositories

## Overview
A curated set of 25 original Java source files selected from two public GitHub repositories:
- 15 files from `TheAlgorithms/Java`
- 10 files from `otuemre/dsa-Java`

The sample spans algorithms, data structures, graph traversal, searching, sorting, strings, compression, cryptography, mathematics, geometry, dynamic programming, and trees.

## Structure
- `codes/`: selected source files, labeled C01-C25. Source file contents are copied without modification.
- `dataset.csv`: index including repository and original source-file URL for each record.
- `dataset.json`: same metadata in JSON format.
- `LICENSE_TheAlgorithms_Java`: license file from the first repository archive.
- `LICENSE_otuemre_dsa-Java.md`: license file from the second repository archive.

## Source repositories
1. TheAlgorithms. (n.d.). *Java*. GitHub. https://github.com/TheAlgorithms/Java
2. otuemre. (n.d.). *dsa-Java*. GitHub. https://github.com/otuemre/dsa-Java

## Selection and provenance
The selected source files were extracted from the ZIP archives provided by the user. Each record has a repository path and a GitHub source URL in `dataset.csv` and `dataset.json`. The C01-C25 identifiers are assigned for this study; they are not original upstream identifiers. The Java source files have not been edited.

## Important notes for research use
- The dataset contains source files from two repositories, not 25 independent projects.
- Some selected files may depend on other classes or project structure in their original repository. A source file being complete as a file does not guarantee that it compiles alone.
- Preserve the original license notices and check each repository's license terms before redistributing the files publicly.
- Before evaluating comment generation, define whether the unit of analysis is each selected Java file or a larger group of related source files. Keep that rule consistent for all 25 records.
