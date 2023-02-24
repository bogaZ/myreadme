## PR Link
https://refactory.sev-2.com/diffusion/196/history/feat%252FT68307/

## Description

Create user_roles table and move the column or field customRoles on user tables to user_roles table and make edges relationship between user and user_roles table

[T68307](https://refactory.sev-2.com/diffusion/196/repository/feat%252FT68307/): move roles on user table to the new user_roles table and make edges relationship

- Add new .sql file 20230217.add_user_roles.sql
- Create MySQL Query to create new table user_roles and add column user_rolesPHID on table user in 20230217.add_user_roles.sql
- Running MySQL Query on 20230217.add_user_roles.sql with ./storage upgrade --force to add this table to database
- Add class for represent the new user_roles table, file name is PhabricatorUserRoles.php
- Add edgesUserRoles() function on class PhabricatorUser.php to make edges relationship betwen PhabricatorUser and PhabricatorUserRoles
- Add getCustomRoles() function on class PhabricatorUser.php to get roles on user_roles table where this table has relation with user table

## Type of change

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking changes/Refactor (fix or feature that would cause existing functionality to not work as expected)
- [x] Increase Unit Testing Coverage

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

Link video:
- 
Step to reproduce:
- GOTO Sev2 App/ desktop
