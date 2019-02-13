# Magento 1 Contact Form Captcha
## By [Edmonds Commerce](https://www.edmondscommerce.co.uk)

Magento's default captcha isn't available on the contact form by default. Install this to add it as an option.

### Installation

1. Drop this module in
2. Navigate to System > Conmfiguration > Customers > Customer Configuration > CAPTCHA > Forms and select Contact Page
3. Add `<?php echo $this->getChildHtml('form.additional.info'); ?>` to your `contacts/form.phtml` template
4. Clear caches
