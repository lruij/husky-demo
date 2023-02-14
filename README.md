### husky demo

#### Guide

commitlint https://commitlint.js.org/#/
husky https://typicode.github.io/husky/#/
conventional https://www.conventionalcommits.org/zh-hans/v1.0.0/

#### Note
* git config set core.hooksPath = .husky
* npx husky add .husky/commit-msg 'npx --no -- commitlint --edit ${1}'
* commitlint
* conventional config
