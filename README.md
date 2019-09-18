## ROMELLO SKUGGS

# A starter website for Drupal 8 Developers

Usage:

```
composer create-project drupal-composer/drupal-project:8.x-dev some-dir --no-interaction

cd some-dir

composer require rjtownsend/romelloskuggs

mkdir -p web/themes/custom && mv themes/custom/bs_subtheme web/themes/custom/bs_subtheme # see https://github.com/drupal-composer/drupal-project/pull/517

# Enabling settings.local.php is recommended during developemnt
# Uncomment on web/sites/default/settings.php to enable

cp web/sites/example.settings.local.php web/sites/default/settings.local.php

```
Navigate to website.local/core/install.php and install as usual. 
