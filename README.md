# Size Chart GraphQl

## How to install
Run the following command in Magento 2 root folder:

```
composer require mageplaza/module-size-chart-graphql
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

## How to use

To start working with Size Chart GraphQl in Magento, you need the following:
- Use Magento 2.3.x. Returns site to developer mode
- Install [chrome extension](https://chrome.google.com/webstore/detail/chromeiql/fkkiamalmpiidkljmicmjfbieiclmeij?hl=en) (currently does not support other browsers)
- Set **GraphQL endpoint** as `http://<magento2-3-server>/graphql` in url box, click **Set endpoint**. (e.g. http://develop.mageplaza.com/graphql/ce232/graphql)