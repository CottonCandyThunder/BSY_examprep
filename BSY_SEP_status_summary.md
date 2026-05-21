# Status summary: BSY SEP task/exercise extraction

_As of 2026-05-21 18:44 UTC (from active agent session)._

## Main branch status (`origin/main`)
- Current `main` commit: `0d1584c` (`Past_Exam`).
- File inventory on `main`: only `BSY SEP.pdf`.
- There is **no merged LaTeX worksheet artifact** yet on `main`.

## Tasks / issue tracker status
- Open issues related to extraction/formatting: **none** (`0` repository issues).
- Work is currently tracked through Copilot PR branches and workflow runs.

## Pull requests related to extraction from `BSY SEP.pdf`
1. **PR #1** (open, draft): `Create complete LaTeX worksheet from BSY SEP.pdf with all exam tasks (no solutions)`
   - Branch: `copilot/extract-latex-worksheet`
   - Scope: adds `bsy_sep_worksheet.tex`
   - Change size: `1` file, `+284` lines, `2` commits
   - Stage: extraction draft prepared, not merged
2. **PR #2** (open, draft, current branch): `[WIP] Update task and exercise extraction from BSY SEP.pdf`
   - Branch: `copilot/extract-format-bsy-sep-pdf`
   - Stage: orchestration/status update PR; currently no worksheet file changes were present before this summary update

## Agent and automation activity
- Workflow present: `Copilot cloud agent`.
- Recent runs:
  - Run `#1` (branch `copilot/extract-latex-worksheet`): **completed/success**.
  - Run `#2` (branch `copilot/extract-format-bsy-sep-pdf`): **in progress** with `Processing Request (Linux)` active at capture time.

## Current processing stage
- **Extraction/formatting output exists in an open draft PR (#1), but not integrated into `main`.**
- **Current agent run is producing a status-oriented update in PR #2.**

## Next steps for user
1. Review `bsy_sep_worksheet.tex` in PR #1 for completeness and formatting quality.
2. Decide merge strategy:
   - merge PR #1 directly, or
   - port/cherry-pick `bsy_sep_worksheet.tex` into the active PR and merge one consolidated PR.
3. After merge, verify that `main` contains both `BSY SEP.pdf` and the finalized worksheet `.tex` file.
4. Optionally add a lightweight README note documenting worksheet generation source and update process.
