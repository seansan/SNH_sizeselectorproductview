# SNH_sizeselectorproductview
Simple Magento extension to store attribute selected on configurable products (and set it on load)

Possible improvement
* Not tested on all types of product combinations (grouped, more complex configurable, /w extensions)
* Maybe revert to Mage.Cookies instead of native JS with model functions (could not get Mage.Cookies working fast enough)
* Maybe it is possible to update the XML so this *only* gets loaded on product_type_configurable
* Create system config option to tell magento which attribute contains size
* Bsed on config option detected layered navigation size selection and also trigger cookie creation
* Anything else?
