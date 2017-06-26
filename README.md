# \<isw-jwt-ajax\>

An iron-ajax extension for JSON Web Token.

iron-ajax with an added jwt property that accepts an JSON Web Token and adds an "authorization: Bearer" header to the request.

```html
<isw-jwt-ajax
  jwt="eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiYWRtaW4iOnRydWV9.TJVA95OrM7E2cBab30RMHrHDcEfxjoYZgeFONFh7HgQ"
  url="..."></isw-jwt-ajax>
```