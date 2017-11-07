frosted pre-commit
==================

wrapped of frosted for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For frosed: see https://github.com/timothycrosley/frosted


### Using frosted with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/pre-commit/frosed-pre-commit
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: forsted
