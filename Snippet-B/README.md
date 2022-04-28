### Snippet B

Copy and paste the code snippet below to your sale confirmation page. The 
placeholders in the curly brackets should be replaced with your own macros. 

```js
<script>
  var stylightParameters = {
    'propertyId': '{{ property_ID }}',  // Your Stylight property id. Example: 'test12345'
    'oi': '{{ order_id }}',             // Order ID in your system. Example: 'abcde'
    'ta': '{{ total_amount }}',         // Total amount of the basket. Example: 10.5
    'ic': '{{ item_count }}',           // Number of items in the basket. Example: 2
    'c': '{{ currency }}'               // Currency of the sale: Example: 'USD'
  };
  stylightSales.sendPixel(stylightParameters);
</script>
```