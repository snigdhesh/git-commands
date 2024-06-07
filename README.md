# git-commands

Test-case: Untrack a modified file.
Explanation:
  - I want to make changes to application.yml file with passwords for local testing.
  - But I don't want to commit it.

Example: src/main/resources/application.yml

    git update-index --assume-unchanged <file>

If you want to do the opposite

    git update-index --no-assume-unchanged <file>
