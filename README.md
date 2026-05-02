# My Website

Website for Jason Ngo

## Deployment

Automatic thanks to Codeberg

### Note

Deployment is done via Codeberg's legacy method.

The new method is to use Forgejo Actions to deploy to git-pages (within Codeberge).

However, the new method does not support custom domain names yet.

### Deployment Set-up

- Set domain(s) in `.domains` in root folder
- Add Codeberg DNS records
  - name jason.ngo, type A, data 217.197.84.141
  - name jason.ngo, type AAAA, data 2a0a:4580:103f:c0de::2
  - name jason.ngo, type TXT, data jasonngo.codeberg.page

### References

- https://docs.codeberg.org/codeberg-pages
- https://docs.codeberg.org/codeberg-pages/using-custom-domain
- https://docs.codeberg.org/codeberg-pages/using-custom-domain/#option-3%3A-a%2Faaaa-record
- https://docs.codeberg.org/codeberg-pages/using-custom-domain/#personal%2Forganization-site%2C-apex-domain
