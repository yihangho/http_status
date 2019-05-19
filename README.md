# HTTP Status

Provides semantic aliases to HTTP status codes.

## Example

```javascript
import * as HTTP_STATUS from '@yihangho/http_status';

const handler = async (event) => {
  return {
    status: HTTP_STATUS.OK,
    body: 'Everything is a-ok!'
  };
};
```

## Source

The relevant HTTP status codes are taken from the [IANA HTTP Status Code Registry][iana-registry].

[iana-registry]: https://www.iana.org/assignments/http-status-codes/http-status-codes.xhtml
