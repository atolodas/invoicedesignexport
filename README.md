# Invoice design import and export module for Invoice Ninja

This module adds the ability to import and export the invoice design.

## Installation
Install the module like any other Invoice Ninja module:

```
php artisan module:install feyst/invoicedesignexport --type=github-https
```

After the installation is complete, you must run the Artisan command to inject the view into the relevant Invoice Ninja views:
```
php artisan invoicedesignexport:insert-buttons
```

To remove the scanner from the page(s), run the following command:
```
php artisan invoicedesignexport:remove-buttons
```

## Issues / Feedback
All feedback or issues are welcome!  Feel free to open an issue for any bugs or feature requests.
