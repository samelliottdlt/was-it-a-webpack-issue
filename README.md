# was-it-a-webpack-issue

## it was a webpack issue!

- minification and uglification as part of production error caused certain code to become unreachable: https://gist.github.com/samelliottdlt/2b123385bdcbd83d1fa7b344e8a89fb8
- script ordering resulted in objects being undefined when object was expected to exist

## it was not a webpack issue!

- if i file is not being imported it will not be a part of the resultant bundle. queue shock and surprise from everyone involved in debugging.

## why did you create this repo?

I introduced webpack into a large jQuery SPA and I have a feeling that the team is using it as scapegoat for issues not webpack related. I understand why this is worrying for others because now there is a scary blackbox in the middle of things where there used to be none. My intention is to document issues that are thought of potential webpack issues and document them as they happen. I plan to use my findings to determine whether there are legitimate issues with the introduction of webpack to the project or the team is using webpack as a scapegoat.
