# Geoadmin IGEB-B Github Reusable Workflows

Github Reusable workflows used by IGEB-B Team of Geoadmin organization. For more information on Reusable Workflow see [Reusing workflows](https://docs.github.com/en/actions/learn-github-actions/reusing-workflows).

These workflows are used by most of the IGEB-B repositories and by the [geoadmin/.github](https://github.com/geoadmin/.github) workflow templates.

## Testing the workflow

Before merging any changes in the reusable worklow, they must be tested with [geoadmin/test-milestone-workflow](https://github.com/geoadmin/test-milestone-workflow) and/or [geoadmin/test-semver-workflow](https://github.com/geoadmin/test-semver-workflow). Those repository are configured to use the reusable workflow based on the `develop` branch, not that the productive repository refer to the `master` branch.
