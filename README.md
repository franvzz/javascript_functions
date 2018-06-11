# javascript "solutions"

```javascript
//-- only numbers
$('.number').keyup(function(e) {
  var n = parseInt(e.target.value);
  if(isNaN(n)) { n = 0; }
  $(this).val(n);
});
```
