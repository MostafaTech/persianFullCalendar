persianFullCalendar
===================

Persian Full Calendar for Jquery>=1.8  And Bootstarp 3.0

[there is an online preview available on rawgit](https://rawgit.com/MostafaTech/persianFullCalendar/master/index.html)

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

notes
-----

- if you are not using Bootstarp just set the **box-sizing** to **border-box** for calendar container

```css
#cal {
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
}
```

