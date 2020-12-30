# GitHub Action: `babbel/publish-gem`

Publishes RubyGem to GitHub Packages.

## Usage

```
    steps:
      - uses: babbel/publish-gem
```

You can also specify a `gemspec-file` input if you have multiple gemspec files:

```
    steps:
      - uses: babbel/publish-gem
        with:
          gemspec-file: example.gemspec
```
