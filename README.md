## PR Link
https://refactory.sev-2.com/diffusion/196/history/feat%252FT68213/

## Description

Revamp the position of dark mode toggle to the bottom left to make the toggle is not floating when the resolution on minimize mode

[T68213](https://refactory.sev-2.com/diffusion/196/browse/feat%252FT68213/): make the toggle is not floating when the resolution on minimize mode  

- Changing offset properties from bottom to top in class .dark-mode-toggle-container on dark-mode-toggle.css 
- Add value offset bottom 455 px in class .dark-mode-toggle-container on dark-mode-toggle.css

## Type of change

- [x] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
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

Link video:
- 
Step to reproduce:
- Open Home of Sev2 app on minimize mode
- Check the dark mode toggle when you change resolution
