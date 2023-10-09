# payment.css

## How is it installed?
To import the package into JS you can use the npm command:
```
npm install payment.css
```
or you can also use pnpm
```
pnpm add payment.css
```

If you are not using npm and want to use it for your vanilla project. You can use
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruxwez/payment.css@main/dist/icons.min.css" />
```

## How is it used?

In NPM we will have to import it into the main project file:
```jsx
import "payment.css"
```

An example of how it works is as follows:

```html
<div class="pay_icons short icon-american-express-light"></div>
```

The css classes are:

- Main tags
  - .pay_icons: This is used to indicate that it is an icon and has no size.
- Icon dimensions tags
  - .short: 40px x 25.2px
  - .medium: 55px x 34.65px
  - .large: 65px x 40.94px
- Icon type tags
  - .icon-amazon-dark: Amazon payment method dark icon.
  - .icon-amazon-light: Light Amazon payment method icon.
  - .icon-american-express-dark: Dark icon of the American Express payment method.
  - .icon-american-express-light: Light icon of the American Express payment method.
  - .icon-cirrus-dark: Dark icon of the Cirrus payment method.
  - .icon-cirrus-light: Light icon of the Cirrus payment method.
  - .icon-diners-dark: Dark icon of Diners Club payment method.
  - .icon-diners-light: Light icon of Diners Club payment method.
  - .icon-discover-dark: Dark icon of Discover payment method.
  - .icon-discover-light: Light icon of the Discover payment method.
  - .icon-ebay-dark: Dark icon of the eBay payment method.
  - .icon-ebay-light: Light icon of the eBay payment method.
  - .icon-elo-dark: Dark icon of the Elo payment method.
  - .icon-elo-light: Light icon of the Elo payment method.
  - .icon-maestro-dark: Dark icon of the Maestro payment method.
  - .icon-maestro-light: Light icon of the Maestro payment method.
  - .icon-master-card-dark: Dark icon of the MasterCard payment method.
  - .icon-master-card-light: Light MasterCard payment method icon.
  - .icon-paypal-dark: Dark icon of the PayPal payment method.
  - .icon-paypal-light: Light icon of the PayPal payment method.
  - .icon-sage-dark: Dark icon of the Sage payment method.
  - .icon-sage-light: Light icon of the Sage payment method.
  - .icon-visa-dark: Dark icon of the Visa payment method.
  - .icon-visa-light: Light icon of the Visa payment method.
  - .icon-visa-electron-dark: Dark icon of the Visa Electron payment method.
  - .icon-visa-electron-light: Light icon of the Visa Electron payment method.

