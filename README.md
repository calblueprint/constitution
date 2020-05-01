# The Constitution of Blueprint, Technology for Non-Profits

The documents [`Current_Constitution.md`](Current_Constitution.md) and [`Current_Bylaws.md`](Current_Bylaws.md) shall be the source of truth for Blueprint's Constitution and Bylaws. Should there be any discrepancies between the markdown and PDF versions, the markdown version should be referenced.

## Pull Requests

There are three versions of pull requests that can be created.

1. Amendment

    An amendment that can be proposed by 2/3 of the Executive Committee or 2/3 of the total membership. It must be ratified by 3/4 of the total membership.

2. Bylaw

    A two-thirds majority of the Executive Committee is necessary to enact a bylaw.

3. Feature

    This is any changes that does not modify the contents of the Constitution or Bylaws.

Only the **markdown files** should be changed when making changes to the Constitution or Bylaws. A Github Action will convert the markdown file into PDFs once a pull request has been created.

### Adding a Bylaw

1. Make sure the pull request is properly formatted
   1. Title is prefixed with `Bylaw:`
   2. Header text is filled in
   3. Description text is added with proper link to decision log
   4. Request review from e-team members
   5. Draft author(s) added as assignees
   6. Pull request properly labeled with `bylaw`
2. Update voting record after e-team votes through GitHub review (green check should appear)
3. Squash and merge with the follow as the commit message:
   1. Title of pull request
   2. `Drafted:` the author of the proposal
   3. `Proposed:` when it was proposed
   4. `Proposed by:` who proposed it (can only be `Executive Team`)
   5. `Ratified:` when it was voted on
   6. Voting record

### Adding an Amendment

1. Make sure the pull request is properly formatted
   1. Title is prefixed with `Amendment:`
   2. Header text is filled in
   3. Description text is added with proper link to decision log
   4. Changes section with diffs showing what has changed
   5. Request review from calblueprint/e-team (won't be used for voting)
   6. Draft author(s) added as assignees
   7. Pull request properly labeled with `amendment`
2. Add an Amendment file under `Amendments/Constitution_B` with the same contents as pull request
3. Update voting record after club votes with picture of result
   - Picture/results should indicate date voted
   - Picture/results should go in `Amendments/Constitution_B/assets`
4. Squash and merge with the follow as the commit message:
   1. Title of pull request
   2. `Drafted:` the author of the proposal
   3. `Proposed:` when it was proposed
   4. `Proposed by:` who proposed it (can be `Executive Team` or `Club Convention`)
   5. `Ratified:` when it was voted on
   6. Voting record

## Releases

Releases and tags mark the ratification of an amendment to the Constitution or Bylaws.

Tags should be prefixed with a 'v' and numbers separated with a period with the first number referring to the Constitution version, the second number referring to the Constitution amendment number, and the third number referring to the Bylaws amendment number. (e.g. `v2.1.0`)

Add the same description as the merged PR with a summarized version of the `Text` section but no `Changes` section.

Upload the PDF versions of the new Constitution and Bylaws to the assets for easy download in the future.
