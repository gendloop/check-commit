# check-commit

Check if the commit message meets the following format:

- `<type>[optional scope]: <description>`
  * type
    * fix      -- Fixing a bug
    * feat     -- Adding a new feature
    * chore    -- Miscellaneous tasks
    * ci       -- Updating the workflow
    * docs     -- Updating documentation
    * style    -- Updating styles
    * refactor -- Refactoring code
    * test     -- Updating tests
- `<type>[optional scope]!: <description>` 
  * Adding `!` indicates a major update
  * Note that there is a space between `!:` and `<description>`
- The colon is the symbol used in the English input method, not the symbol used in the Chinese input method.

## Usage

Place the [Check_Commit.yml](.github/workflows/Check_Commit.yml) file in the *.github/workflows* directory.

