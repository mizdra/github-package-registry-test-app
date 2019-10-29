# github-package-registry-test-app

GitHub Package Registry を package registry として利用するテストアプリケーション.

## Usage

```
$ git clone https://github.com/mizdra/github-package-registry-test-app.git
$ cd github-package-registry-test-app
$ npm install
$ cat package-lock.json| grep resolved
      "resolved": "https://npm.pkg.github.com/download/@mizdra/github-package-registry-test/0.0.0/3f54a07c7d69f4f220c09d674143bdf9f0e7cb8d313c36fc7a2b7b44e579a327",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-3.2.1.tgz",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-2.4.2.tgz",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-1.9.3.tgz",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.3.tgz",
      "resolved": "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-3.0.0.tgz",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-5.5.0.tgz",
```
