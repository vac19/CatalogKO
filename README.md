# Catalog/Ko

KnockOut.js practice module. 
Appends a timer with color change every second at Category page
It adds a timer with new 'custom component', captures the time change event and apply random color each second. Time interval per second.
Refered Example is using 3 ways to archive the functionality, the latest and suggest way is `storage model`. which has been used with in this example.

## Composer install

- `composer config repositories.reponame vcs https://github.com/vac19/CatalogKO`
- `composer require salecto1/magento2-catalog-ko`

## Composer uninstall

- `composer remove salecto1/magento2-catalog-ko`

## Preview will be added

![timer-in-categoryPage](/readme-images/Timer-at-categoryPage.png "timer-in-categoryPage")


## Settings

- Option `will be updated ..` - Under Construction

## Known issues

- **Issues will be here .. Hopfuly not**\
  Woirk in Progress

## Developer informations
- vashishtha chauhan / Salecto

### Install module
1. Run `composer require salecto1/magento2-catalog-ko`
2. Run `php bin/magento setup:upgrade`
3. Run `php bin/magento setup:di:compile`
4. Run `php bin/magento s:s:d da_DK en_US`
5. Run `php bin/magento c:c`

### Uninstall module
1. Run `composer remove salecto1/magento2-catalog-ko`
2. Run `php bin/magento setup:di:compile`
3. Run `php bin/magento s:s:d da_DK en_US`
4. Run `php bin/magento c:c`

### Additional developer notes
Reference URL `https://inviqa.com/blog/using-knockout-js-magento-2`
