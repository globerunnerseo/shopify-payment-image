# How to copy payment image from footer to product single page in shopify.


### First copy this code from footer.liquid file

`<img src="{{ 'payment.png' | asset_url }}" alt="Payment" />`

### and then go to `snippets` and find the `single-product-layout-type-1.liquid` file

### And go to line #250

### and add the code:

`<img src="{{ 'payment.png' | asset_url }}" alt="Payment" />`

### To add spacing, we can add this: 

<div class="grid__item" style="margin-top:10px;">
   <img src="{{ 'payment.png' | asset_url }}" alt="Payment" />
</div>
