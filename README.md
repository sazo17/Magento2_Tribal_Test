Subir la carpeta Tribal al directorio app/design/frontend/

en el root de Magento ejecutar

php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
php bin/magento index:reindex
php bin/magento cache:clean
php bin/magento cache:flush

Test Tribal
Jorge Sazo

