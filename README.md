# merge-tests

## Recreating this repo

- create main branch
- create develop branch (with apple and with typo)
- create release branch for 1.0
- bump version in develop to 1.1.0-SNAPSHOT
- release version 1.0.0-rc.1 from release branch (update changelog and version in pom.xml)
- merge release into develop (resolve conflict manually)
- create feature branches from develop (banana, cranberry, dragon fruit)
- fix bug in release branch
- release version 1.0.0-rc.2 from release branch
