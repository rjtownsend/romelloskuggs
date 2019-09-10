## ROMELLO SKUGGS

# A starter website for Drupal Developers

Usage:

```
composer create-project drupal-composer/drupal-project:8.x-dev some-dir --no-interaction

cd some-dir

composer require rjtownsend/romelloskuggs

mkdir -p web/themes/custom && mv themes/custom/bs_subtheme web/themes/custom/bs_subtheme # see https://github.com/drupal-composer/drupal-project/pull/517

```
Navigate to website.local/core/install.php and install as usual. 