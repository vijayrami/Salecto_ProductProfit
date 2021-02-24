# Salecto_ProductProfit
Add Extra column **Estimated Profit** to the products grid in Magento2 Backend.

Estimated profit should be calculated as: **(Sales price - Cost price) X Qty in stock**

### Installation

 - Unzip the zip file in `app/code/Salecto/ProductProfit`
 - Enable the module by running `php bin/magento module:enable Salecto_ProductProfit`
 - Run Below commands:
 
  `php bin/magento setup:upgrade`
  `php bin/magento setup:d:c`
  `php bin/magento setup:s:d -f`
  `php bin/magento c:c`
  `php bin/magento c:f`
 
<p>
  <img src="https://i.ibb.co/QcdvM38/Screenshot-from-2021-02-24-20-00-26.png">
</p>
 <p><img src="https://i.ibb.co/gd2jLCS/Screenshot-from-2021-02-24-20-05-39.png"></p>
