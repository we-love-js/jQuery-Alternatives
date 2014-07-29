#### Add Class
```javascript
//JQUERY
$(el).addClass(className);
IE10+
el.classList.add('className');
```

#### After
```javascript
//JQUERY
$(el).after(htmlString);
//IE8+
el.insertAdjacentHTML('afterend',htmlString);
```

#### Append
```javascript
//JQUERY
$(parent).append(el);
//IE8+
parent.appendChild(el);
```

Before

JQUERY
```javascript
$(el).before(htmlString);
```
IE8+
```javascript
el.insertAdjacentHTML('beforebegin', htmlString);
```

Children

JQUERY
```javascript
$(el).children();
```
IE9+
```javascript
el.children;
```

Clone

JQUERY
```javascript
$(el).clone();
```
IE8+
```javascript
el.cloneNode(true);
```

Contains

JQUERY
```javascript
$.contains(el, child);
```
IE8+
```javascript
el !== child && el.contains(child);
```

Contains Selector

JQUERY
```javascript
$(el).find(selector).length;
```
IE8+
```javascript
el.querySelector(selector) !== null
```

Each

JQUERY
```javascript
$(selector).each(function(i, el){

});
```
IE9+
```
var elements = document.querySelectorAll(selector);
Array.prototype.forEach.call(elements, function(el, i){

});
```

Empty

JQUERY
```javascript
$(el).empty();
```
IE9+
```javascript
el.innerHTML = '';
```

Filter

JQUERY
```javascript
$(selector).filter(filterFn);
```
IE9+
```javascript
Array.prototype.filter.call(document.querySelectorAll(selector), filterFn);
```

Find Children

JQUERY
```javascript
$(el).find(selector);
```
IE8+
```javascript
el.querySelectorAll(selector);
```



