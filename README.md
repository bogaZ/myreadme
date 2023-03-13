## PR Link

[FEAT/T70007](https://refactory.sev-2.com/source/kurirmoo-be-pre-ip-batch-17/history/feat%252FT70007/)

## Description

Create endpoint to Create Route in Admin CMS with field

- Origin city (Validation data must same with data in table city)
- Destination city (Validation data must same with data in table city)
- Route (Option only 2 Utara or Selatan)
- City Passed (Validation must same with data in table city_passed and can be more than 1)
- Distance (In Kilometer)

Tanpa validasi role melalui token

[T70007](https://refactory.sev-2.com/source/kurirmoo-be-pre-ip-batch-17/history/feat%252FT70007/): Create endpoint to Create Route in Admin CMS with field

- Definition endpoint and models on swagger.yml
- Generate endpoint and models file using make all
- Create file for handling endpoint create route
- Implement endpoint on route.go
- Create validation for proccess store data on table route and city_passed
- Testing endpoint unsing Postman

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
- [Link Video Test Endpoint Create Route](https://drive.google.com/file/d/1rwvHxGjnnocB6zrTCtRZxwEoiqb9wbMi/view?usp=share_link)

Step to reproduce:
- Setup BE Kurirmoo
- [Endpoint URL](http://127.0.0.1:8080/create/route)
