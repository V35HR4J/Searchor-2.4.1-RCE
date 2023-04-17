# Searchor <= 2.4.1 RCE
searchor is a ⚡️ Quick and easy search engine queries. Affected versions of this package are vulnerable to Arbitrary Code Execution due to unsafe implementation of eval method.

Exploit Usage:

`python3 exploit.py <url> <command>`

Example:

`python3 exploit.py http://localhost:5000/search ls`

References:
- https://security.snyk.io/vuln/SNYK-PYTHON-SEARCHOR-3166303
- https://github.com/ArjunSharda/Searchor/commit/29d5b1f28d29d6a282a5e860d456fab2df24a16b
- https://github.com/ArjunSharda/Searchor/pull/130
