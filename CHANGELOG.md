## 1.4.0 (Unreleased)

BUG FIXES:

* The module installer will now record in its manifest a correct module source URL after normalization when the URL given as input contains both a query string portion and a subdirectory portion. Terraform itself doesn't currently make use of this information and so this is just a cosmetic fix to make the recorded metadata more correct. [GH-31636]

ENHANCEMENTS:

* The "Failed to install provider" error message now includes the reason a provider could not be installed. [GH-31898]

## Previous Releases

For information on prior major and minor releases, see their changelogs:

* [v1.3](https://github.com/hashicorp/terraform/blob/v1.3/CHANGELOG.md)
* [v1.2](https://github.com/hashicorp/terraform/blob/v1.2/CHANGELOG.md)
* [v1.1](https://github.com/hashicorp/terraform/blob/v1.1/CHANGELOG.md)
* [v1.0](https://github.com/hashicorp/terraform/blob/v1.0/CHANGELOG.md)
* [v0.15](https://github.com/hashicorp/terraform/blob/v0.15/CHANGELOG.md)
* [v0.14](https://github.com/hashicorp/terraform/blob/v0.14/CHANGELOG.md)
* [v0.13](https://github.com/hashicorp/terraform/blob/v0.13/CHANGELOG.md)
* [v0.12](https://github.com/hashicorp/terraform/blob/v0.12/CHANGELOG.md)
* [v0.11 and earlier](https://github.com/hashicorp/terraform/blob/v0.11/CHANGELOG.md)
