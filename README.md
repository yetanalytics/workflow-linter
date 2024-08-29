# workflow-linter

Small reusable GitHub workflow for clj-kondo linting. Takes the following optional inputs:

| Input               | Description                           | Default
| ---                 | ---                                   | ---
| `clj-kondo-version` | Version of clj-kondo to install       | `2024.08.01`
| `lint-directories`  | List of directories to run linting on | `src/main src/test` 

See also: The [setup-clojure action](https://github.com/DeLaGuardo/setup-clojure) and [clj-kondo CI integration](https://github.com/clj-kondo/clj-kondo/blob/master/doc/ci-integration.md). Note that this action currently does not support custom configuration files for clj-kondo.

