# HC-ACRULES-LEGACY

ast-grep rules that CodeRabbit runs on Heuristyc pull requests whose destination is an Acumatica release before 2025R2, or an unresolved release.

Heuristyc generates this repository from its internal skills (branch `main`), leaving out rules that only hold from 2025R2 on. Do not edit it here: changes are overwritten on the next publish.

| Folder | Contents |
|---|---|
| `rules/` | One ast-grep rule per file. `metadata.skill` names the skill the rule comes from. |
| `rule-tests/` | Valid and invalid examples for each rule, run with `ast-grep test`. |
| `utils/` | Shared utility rules. |

CodeRabbit loads this repository as an ast-grep package (`reviews.tools.ast-grep.packages`), which must be public and have no dots in its name.
