While you can rename your repository's existing default branch, {% data variables.product.company_short %} plans to provide tools to simplify the process of renaming the default branch. For more information on these plans, see [`github/renaming`](https://github.com/github/renaming).

If you have already renamed the default branch, {% data variables.product.prodname_dotcom %} will automatically redirect links on {% if currentVersion ver_gt "enterprise-server@2.22" %} {% data variables.product.product_location_enterprise %}{% else %}{% data variables.product.prodname_dotcom_the_website %}{% endif %} that contain a deleted `master` branch name to the equivalent link on the repository's default branch.