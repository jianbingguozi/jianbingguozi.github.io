## 使用说明
在浏览器创建一个书签，书签内容为为
```javascript
    javascript: void((function () {
		var element = document.createElement('script');
		element.id = 'outfox_seed_js';
		element.charset = 'utf-8',
		element.setAttribute('src', 'https://jianbingguozi.github.io/tool/translate/seed.js?' + Date.parse(new Date()));
		document.body.appendChild(element);
	})())
```
