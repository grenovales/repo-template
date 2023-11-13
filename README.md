# Replace Repo Title


## What is this template for?
This template helps to have better experiences doing code reviews, we are using Github Actions to automate and do initial checks, to the submited PR's

---
### Pull Request Template
---
Here's an example of a PR template
#### Description

- What:
- How:
- Link to Ticket:

---

#### Checklist

- [ ] tested
- [ ] documented

---

#### Notes

---
### Github Actions
---

####Pull Request Labeler
GitHub action to assign labels based on pull request change sizes.

For example:
| Changed Lines | T-Shirt Size |
| ----------- | ----------- |
| 0      | XS       |
| 20      | S       |
| 50      | M       |
| 200      | L       |
| 800      | XL       |
| 2000      | XXL      |

#### Release Note Generator
This Gihubb action will automatically create a release notes when a milestone is closed

<p align="center">
  <img src="https://github.com/Decathlon/release-notes-generator-action/raw/master/images/release_notes.png" alt="Result illustration"/>
<p>

### Semantic Check
ENforcing good pull request its importan to have proper title check this guide [Conventional Commits](https://www.conventionalcommits.org)
