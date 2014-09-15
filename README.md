persianFullCalendar
===================

Persian Full Calendar for Jquery>=1.8  And Bootstarp 3.0

```html
<div id="cal">
</div>
```

```javascript
$(function () {
    $('#cal').persianDatepicker({
        dates: ['1393/06/16', '1393/06/16', '1393/06/25'],
        onSelect: function (value) {
            alert(value);
        }
    });
});
```