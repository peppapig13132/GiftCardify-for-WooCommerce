# GiftCardify for WooCommerce

💡 The plugin is in development stage.

<div align="center">
<img src="https://raw.githubusercontent.com/peppapig13132/GiftCardify-for-WooCommerce/main/assets/images/others/Gift-card.png"  alt="giftcard">
</div>

## Key Features

Gift card form includes:
```
Amount:
  Preset prices(For example, 100, 250, 500) and custom price
Receiver:
  First name
  Last name
  Email(and Email confirm)
Sender:
  Sender name
Gift message
Shipping date
```

- [x] Purchase a gift card - cart page, checkout page
- [x] Send custom email to the customer and the gift card receiver
- [x] Buy product with a gift card

## How to use GiftCardify?
### Create a product - Gift Card
- Name: Gift Card
- Product Type: Gift Card (GiftCaridfy plugin adds this product type)
- Preset prices with comma
<div align="center">
<img src="https://raw.githubusercontent.com/peppapig13132/GiftCardify-for-WooCommerce/main/assets/images/others/edit-product.png"  alt="edit-product">
</div>

### Modify template - single product gift card
Modify single product gift card template here: `templates/single-product/gift-card.php`.

### Modify custom email templates
- Check HTML email templates and then move then to PHP templates in `templates/emails`.

## Screenshots
- Single Product Gift Card page: [Click here](https://github.com/peppapig13132/GiftCardify-for-WooCommerce/blob/main/assets/images/others/single-product-gift-card.png)
- Custom order complete notification email: [Click here](https://github.com/peppapig13132/GiftCardify-for-WooCommerce/blob/main/assets/images/others/custom-order-completed-email-html.png)
- Gift card received notification email: [Click here](https://github.com/peppapig13132/GiftCardify-for-WooCommerce/blob/main/assets/images/others/gift-card-received-email-html.png)