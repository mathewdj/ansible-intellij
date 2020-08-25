# Ansible Intellij
This playbook is to install or upgrade intellij. For the Intellij playbook, see https://github.com/Homebrew/homebrew-cask/blob/master/Casks/intellij-idea-ce.rb.

The manual way to upgrade intellij is to run:
```
brew cask upgrade intellij-idea-ce
brew cask upgrade intellij-idea
```

## Quickstart
1. To test playbook locally:
  ```
  ansible-playbook test-role.yml -vvvv
  ```

## License
[GPLv3](LICENSE)
