# Pre-Commit StyLua

A [pre-commit](https://pre-commit.com) hook for running [StyLua](https://github.com/JohnnyMorganz/StyLua).

## Usage

```yaml
-   repo: "git://github.com/LebJe/PreCommitStyLua"
    rev: "main"
    hooks:
    -   id: "stylua"
```