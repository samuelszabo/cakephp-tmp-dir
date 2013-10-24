Simple GIT to lazy copy tmp CakePHP app directory structure:
- change directory to working directory
  cd newSuperCakePHP
- clone this repository into app/tmp directory
  git clone --depth 1 --branch master https://github.com/samuelszabo/cakephp-tmp-dir.git app/tmp
- remove .git and readme from app/tmp
  rm -rf app/tmp/.git app/tmp/README.md
- chmod app/tmp dir
  chmod -R 777 app/tmp
- voila.. finish.

Or, try this:
https://gist.github.com/tijmenb/956993
