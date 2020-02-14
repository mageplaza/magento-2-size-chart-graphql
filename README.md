# Size Chart GraphQl

## How to install
Run the following command in Magento 2 root folder:

```
composer require mageplaza/module-size-chart-graphql
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

## How to use

To start working with **Size Chart GraphQL** in Magento, you need to:

- Use Magento 2.3.x. Return your site to developer mode
- Install [chrome extension](https://chrome.google.com/webstore/detail/chromeiql/fkkiamalmpiidkljmicmjfbieiclmeij?hl=en) (currently does not support other browsers)
- Set **GraphQL endpoint** as `http://<magento2-3-server>/graphql` in url box, click **Set endpoint**. (e.g. http://develop.mageplaza.com/graphql/ce232/graphql)
- Perform a query in the left cell then click the **Run** button or **Ctrl + Enter** to see the result in the right cell
- To see the supported queries for **Size Chart GraphQL** of Mageplaza, you can look in `Docs > Query > mpSizeChart` in the right corner

![](https://i.imgur.com/br9go6o.png)

- Also, you can add more sizechart info into product query by Mageplaza Size Chart extension. You can see the right corner and go to `Doc > Query > product`.

![](https://i.imgur.com/LUE5YsU.png)
