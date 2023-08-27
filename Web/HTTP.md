### Request structure
```
{method} {path} {version}
{header_name}: {header_value}

{body}
```
Example:
```
GET /path?param=value HTTP/1.1
Content-Type: text/html

<!DOCTYPE html>...
```
### Response structure

```
{version} {status} {status_message}
{header_name}: {header_value}

{body}
```
Example:
```
HTTP/1.1 200 OK
Content-Type: text/html

<!DOCTYPE html>...
```