# Exemple d'utilisation de GitHub Super Linter

[![GitHub Super-Linter](https://github.com/jenovateurs/github_superlinter_demo/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/marketplace/actions/super-linter)

## Debug en local

docker run -e RUN_LOCAL=true -e VALIDATE_PHP=true -e VALIDATE_PHP_BUILTIN=true  -e FILTER_REGEX_INCLUDE='.*app/.*php' -e LOG_LEVEL=DEBUG -v /<chemin>:/tmp/lint github/super-linter:slim-v4
