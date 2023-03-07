## PR Link

[feat/T70052](https://refactory.sev-2.com/source/kurirmoo-be-pre-ip-batch-17/history/feat%252FT70052/)

## Description

Create Table for Data Pengalian Dalam Kota

USECASE

This table will be use to relate with table data pengali.

[T70052](https://refactory.sev-2.com/source/kurirmoo-be-pre-ip-batch-17/history/feat%252FT70052/): Create Table for Data Pengalian Dalam Kota

- Add definition for model MultiplierInCity on swagger.yml
- Generate model using comand line : make all
- Add model on file runtime.go on function autoMigration
- Migrate table using comand line : make run-local

## Type of change

- [ ] Bug fix (non-breaking change which fixes an issue)
- [x] New feature (non-breaking change which adds functionality)
- [ ] Breaking changes/Refactor (fix or feature that would cause existing functionality to not work as expected)
- [ ] Increase Unit Testing Coverage

## Completion Requirement:

- [x] I don't put any sensitive information or credentials information(password, token, secret, etc.) in the commit and pull request
- [x] My code or changes follows the style guidelines of this project
- [x] I have performed a self-review of my own code or changes
- [x] I have commented/documented my code or changes
- [x] I have checked my code and corrected any misspellings
- [x] I have performed integration test with current branch/configuration/design and have verify everything works without conflict
- [x] I have notify my lead or manager that i will merge my changes 

*If this project managed by Refactory after completing all above list you must proceed with merging or apply your changes*
Kurirmoo, Biofarma, Sev2, Recre.

## Evidence that show my changes works properly 

Link foto:
- [Screenshoot Table and Migrate Process](https://drive.google.com/drive/folders/1Q4K9h5A7x8op-0CsrubDleQH-omLy_6-?usp=share_link)

Step to reproduce:
- Setup BE Kurirmoo project
use comand line:
- make all
- make run-local
- check table on database
