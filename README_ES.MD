# payment.css

## ¿Como se instala?
Para importar el paquete en JS puedes usar el comando de npm:
```
npm install payment.css
```
o tambien puedes usar pnpm
```
pnpm add payment.css
```

Si no estas usando npm y lo quieres usar para tu proyecto vanilla. Puedes usar
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruxwez/payment.css@main/dist/icons.min.css" />
```

## ¿Como se usa?

En NPM tendremos que importarlo en el archivo principal del proyecto:
```jsx
import "payment.css"
```

Un ejemplo de como funciona es asi:

```html
<div class="pay_icons short icon-american-express-light"></div>
```

Las clases de css son:

- Etiquetas principales
  - .pay_icons: Esta sirve para indicar que es un icono y no tiene ningun tamaño
- Etiquetas de dimensiones del icono
  - .short: 40px x 25.2px
  - .medium: 55px x 34.65px
  - .large: 65px x 40.94px
- Etiquetas de tipos de icono
  - .icon-amazon-dark: Ícono oscuro del método de pago Amazon.
  - .icon-amazon-light: Ícono claro del método de pago Amazon.
  - .icon-american-express-dark: Ícono oscuro del método de pago American Express.
  - .icon-american-express-light: Ícono claro del método de pago American Express.
  - .icon-cirrus-dark: Ícono oscuro del método de pago Cirrus.
  - .icon-cirrus-light: Ícono claro del método de pago Cirrus.
  - .icon-diners-dark: Ícono oscuro del método de pago Diners Club.
  - .icon-diners-light: Ícono claro del método de pago Diners Club.
  - .icon-discover-dark: Ícono oscuro del método de pago Discover.
  - .icon-discover-light: Ícono claro del método de pago Discover.
  - .icon-ebay-dark: Ícono oscuro del método de pago eBay.
  - .icon-ebay-light: Ícono claro del método de pago eBay.
  - .icon-elo-dark: Ícono oscuro del método de pago Elo.
  - .icon-elo-light: Ícono claro del método de pago Elo.
  - .icon-maestro-dark: Ícono oscuro del método de pago Maestro.
  - .icon-maestro-light: Ícono claro del método de pago Maestro.
  - .icon-master-card-dark: Ícono oscuro del método de pago MasterCard.
  - .icon-master-card-light: Ícono claro del método de pago MasterCard.
  - .icon-paypal-dark: Ícono oscuro del método de pago PayPal.
  - .icon-paypal-light: Ícono claro del método de pago PayPal.
  - .icon-sage-dark: Ícono oscuro del método de pago Sage.
  - .icon-sage-light: Ícono claro del método de pago Sage.
  - .icon-visa-dark: Ícono oscuro del método de pago Visa.
  - .icon-visa-light: Ícono claro del método de pago Visa.
  - .icon-visa-electron-dark: Ícono oscuro del método de pago Visa Electron.
  - .icon-visa-electron-light: Ícono claro del método de pago Visa Electron.

