# was-it-a-webpack-issue

## it was a webpack issue!

- minification and uglification as part of production error caused certain code to become unreachable: https://gist.github.com/samelliottdlt/2b123385bdcbd83d1fa7b344e8a89fb8
- script ordering resulted in objects being undefined when object was expected to exist

## it was not a webpack issue!

- if a file is not being imported it will not be a part of the resultant bundle. queue shock and surprise from everyone involved in debugging.
