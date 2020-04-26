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

## Releases

Releases and tags mark the ratification of an amendment to the Constitution or Bylaws.

Tags should be prefixed with a 'v' and numbers separated with a period with the first number referring to the Constitution version, the second number referring to the Constitution amendment number, and the third number referring to the Bylaws amendment number. (e.g. `v2.1.0`)

Add the same description as the merged PR with a summarized version of the `Text` section.

Upload the PDF versions of the new Constitution and Bylaws to the assets for easy download in the future.
