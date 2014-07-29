#### Add Class
```javascript
//JQUERY
$(el).addClass(className);

//IE10+
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

#### Before
```javascript
//JQUERY
$(el).before(htmlString);

//IE8+
el.insertAdjacentHTML('beforebegin', htmlString);
```

#### Children
```javascript
//JQUERY
$(el).children();

//IE9+
el.children;
```

#### Clone
```javascript
//JQUERY
$(el).clone();

//IE8+
el.cloneNode(true);
```

#### Contains
```javascript
//JQUERY
$.contains(el, child);

//IE8+
el !== child && el.contains(child);
```

#### Contains Selector
```javascript
//JQUERY
$(el).find(selector).length;

//IE8+
el.querySelector(selector) !== null
```

#### Each
```javascript
//JQUERY
$(selector).each(function(i, el){

});

//IE9+
var elements = document.querySelectorAll(selector);
Array.prototype.forEach.call(elements, function(el, i){

});
```

#### Empty
```javascript
//JQUERY
$(el).empty();

//IE9+
el.innerHTML = '';
```

#### Filter
```javascript
//JQUERY
$(selector).filter(filterFn);

//IE9+
Array.prototype.filter.call(document.querySelectorAll(selector), filterFn);
```

#### Find Children
```javascript
//JQUERY
$(el).find(selector);

//IE8+
el.querySelectorAll(selector);
```



