# npmtest-phenomic

#### basic test coverage for  [phenomic (v0.21.1)](https://phenomic.io)  [![npm package](https://img.shields.io/npm/v/npmtest-phenomic.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-phenomic) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-phenomic.svg)](https://travis-ci.org/npmtest/node-npmtest-phenomic)

#### Modern website generator based on the React and Webpack ecosystem.

[![NPM](https://nodei.co/npm/phenomic.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/phenomic)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-phenomic/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-phenomic/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-phenomic/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-phenomic/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-phenomic/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-phenomic/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-phenomic/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-phenomic/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-phenomic/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-phenomic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-phenomic/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-phenomic/build/test-report.html](https://npmtest.github.io/node-npmtest-phenomic/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-phenomic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-phenomic/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-phenomic/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-phenomic/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phenomic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phenomic/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-phenomic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-phenomic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "#eslintConfig/rules/import/no-extraneous-dependencies": "phenomic usage in theme is not specified in package.json (and can't be for now)",
    "#eslintConfig/rules/import/no-unresolved": "deps in docs & theme are installed after the lint step",
    "author": {
        "name": "Maxime Thirouin"
    },
    "babel": {
        "presets": [
            "babel-preset-env",
            "babel-preset-stage-1",
            "babel-preset-react"
        ],
        "plugins": [
            "babel-plugin-flow-react-proptypes"
        ]
    },
    "bin": {
        "phenomic": "npm/bin.js"
    },
    "bugs": {
        "url": "https://github.com/MoOx/phenomic/issues"
    },
    "dependencies": {
        "babel-polyfill": "^6.5.0",
        "babel-register": "^6.6.5",
        "chalk": "^1.1.0",
        "classnames": "^2.2.3",
        "connect-history-api-fallback": "^1.2.0",
        "express": "^4.13.3",
        "find-cache-dir": "^0.1.1",
        "fs-extra": "^0.26.4",
        "fs-promise": "^0.3.1",
        "globby": "^6.0.0",
        "gray-matter": "^2.0.0",
        "hard-source-webpack-plugin": "^0.3.8",
        "inquirer": "^1.0.0",
        "loader-utils": "^1.1.0",
        "log-symbols": "^1.0.2",
        "lru-memoize": "^1.0.1",
        "mkdirp": "^0.5.1",
        "multili": "^1.0.1",
        "node-object-hash": "^1.0.2",
        "offline-plugin": "^4.5.5",
        "opn": "^4.0.2",
        "ora": "^0.3.0",
        "pify": "^2.3.0",
        "portfinder": "^1.0.2",
        "react-router-scroll": "^0.3.2",
        "redbox-react": "^1.2.2",
        "remark": "^5.0.0",
        "remark-autolink-headings": "^4.0.0",
        "remark-highlight.js": "^4.0.0",
        "remark-html": "^5.0.0",
        "remark-slug": "^4.1.0",
        "remark-toc": "^3.1.0",
        "rimraf": "^2.4.2",
        "rss": "^1.2.0",
        "semver": "^5.3.0",
        "simple-json-fetch": "^1.0.1",
        "sitemap": "^1.8.2",
        "source-map-support": "^0.4.0",
        "strip-markdown": "^0.3.1",
        "url-join": "^1.1.0",
        "valid-url": "^1.0.9",
        "webpack-dev-middleware": "^1.10.1",
        "webpack-hot-middleware": "^2.17.1",
        "webpack-sources": "^0.2.3",
        "yargs": "^4.3.1"
    },
    "description": "Modern website generator based on the React and Webpack ecosystem.",
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-core": "^6.14.0",
        "babel-eslint": "^7.0.0",
        "babel-jest": "^17.0.0",
        "babel-plugin-flow-react-proptypes": "^0.10.1",
        "babel-preset-env": "^1.3.2",
        "babel-preset-react": "^6.23.0",
        "babel-preset-stage-1": "^6.22.0",
        "cmd-shim": "^2.0.2",
        "coveralls": "^2.11.8",
        "cp-cli": "^1.0.2",
        "cross-env": "^2.0.0",
        "eslint": "^3.7.1",
        "eslint-config-i-am-meticulous": "^5.0.2",
        "eslint-plugin-flow-vars": "^0.5.0",
        "eslint-plugin-import": "^2.0.0",
        "eslint-plugin-react": "^6.4.0",
        "exec-cmd": "^2.0.1",
        "expect": "^1.13.4",
        "expect-jsx": "^2.2.1",
        "flow-bin": "^0.38.0",
        "jest": "^19.0.0",
        "jest-ava-api": "^0.1.0",
        "js-beautify": "^1.5.10",
        "jsdom": "^9.2.0",
        "lnfs": "^3.0.0",
        "npm-run-all": "^3.0.0",
        "npmpub": "^3.0.0",
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "react-helmet": "^3.0.0",
        "react-redux": "^4.0.0",
        "react-router": "^2.3.0",
        "react-test-renderer": "^15.3.2",
        "redux": "^3.0.0",
        "stylelint": "^7.2.0",
        "stylelint-config-standard": "^16.0.0",
        "suppose": "^0.6.1",
        "webpack": "^2.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d9677fe01cf0dbeb6b228986b31c8afa2d3ab48d",
        "tarball": "https://registry.npmjs.org/phenomic/-/phenomic-0.21.1.tgz"
    },
    "engines": {
        "node": ">=4.2.0",
        "npm": ">=3.0.0",
        "yarn": ">=0.16.0"
    },
    "eslintConfig": {
        "root": true,
        "parser": "babel-eslint",
        "extends": [
            "eslint-config-i-am-meticulous/react-flow"
        ],
        "env": {
            "jest": true
        },
        "rules": {
            "import/max-dependencies": [
                2,
                {
                    "max": 20
                }
            ],
            "import/no-extraneous-dependencies": 0,
            "import/no-unresolved": 0
        }
    },
    "files": [
        "npm",
        "lib",
        "src",
        "themes",
        "docs/content",
        "!**/__tests__"
    ],
    "gitHead": "f17b19024a344be171c334d430299347777ffef7",
    "homepage": "https://phenomic.io",
    "jest": {
        "testEnvironment": "node",
        "notify": true,
        "coverageThreshold": {
            "global": {
                "statements": 80,
                "branches": 75,
                "functions": 75,
                "lines": 80
            }
        },
        "transformIgnorePatterns": [
            "node_modules"
        ],
        "testPathIgnorePatterns": [
            "/utils/",
            "/fixtures/",
            "/results/",
            "/stub/",
            "/_output/"
        ]
    },
    "keywords": [
        "webpack",
        "react",
        "ssg",
        "static",
        "file",
        "site",
        "website",
        "blog",
        "generator",
        "markdown",
        "jekyll",
        "wintersmith",
        "blacksmith",
        "metalsmith",
        "gatsby",
        "gatsbyjs"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "moox"
        }
    ],
    "name": "phenomic",
    "optionalDependencies": {},
    "peerDependencies": {
        "babel-cli": "^6.14.0",
        "babel-core": "^6.14.0",
        "extract-text-webpack-plugin": "^2.1.0",
        "history": "^2.0.0",
        "react": "^0.14.0 || ^15.0.0-rc.1",
        "react-dom": "^0.14.0 || ^15.0.0-rc.1",
        "react-helmet": "^3.0.0",
        "react-redux": "^4.0.0",
        "react-router": "^2.3.0",
        "redux": "^3.0.0",
        "webpack": "^2.3.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MoOx/phenomic.git"
    },
    "scripts": {
        "#lint:js:eslint": "https://github.com/eslint/eslint/issues/5679",
        "cleanup": "rimraf yarn.lock docs/yarn.lock themes/phenomic-theme-base/yarn.lock node_modules docs/node_modules themes/phenomic-theme-base/node_modules test-setup",
        "coverage": "cat ./coverage/lcov.info | coveralls",
        "docs-deploy": "cd docs && npm run build && cd .. && npm run themes:prepare",
        "docs-linting": "eslint --ignore-path .gitignore --fix docs/scripts docs/src",
        "docs-start": "cd docs && npm start",
        "e2e:tests": "jest --runInBand --forceExit e2e-tests",
        "lint": "npm-run-all --parallel lint:*",
        "lint:js": "npm-run-all --parallel lint:js:*",
        "lint:js:eslint": "eslint --ignore-path .gitignore --fix src scripts npm __tests__",
        "lint:js:flow": "flow check",
        "phenomic-theme-base-linting": "eslint --config package.json --ignore-path .gitignore --fix themes/phenomic-theme-base/scripts themes/phenomic-theme-base/src",
        "phenomic-theme-base-start": "cd themes/phenomic-theme-base && npm start",
        "postdocs-deploy": "cd docs && ./scripts/deploy.sh",
        "postinstall": "node npm/postinstall.js",
        "postrelease": "npm run docs-deploy",
        "posttest": "npm run test-docs",
        "postthemes:prepare": "cp-cli themes/phenomic-theme-base/dist docs/dist/themes/base/demo",
        "predocs-deploy": "cd docs && npm run showcase-screenshots",
        "prepublish": "rimraf lib && npm run transpile",
        "pretest": "npm run transpile && npm run lint",
        "pretest-docs": "npm run docs-linting",
        "release": "npmpub",
        "test": "npm run tests && npm run phenomic-theme-base-linting && npm run test-setup && npm run e2e:tests",
        "test-docs": "cd docs && npm test",
        "test-setup": "cd test-setup && npm test",
        "tests": "cross-env TESTING=1 jest --runInBand --coverage src",
        "themes:prepare": "cd themes/phenomic-theme-base && npm run build",
        "transpile": "babel --ignore __tests__ --copy-files src --out-dir lib"
    },
    "stylelint": {
        "extends": "stylelint-config-standard",
        "rules": {
            "block-no-empty": null,
            "comment-empty-line-before": null,
            "comment-whitespace-inside": null,
            "selector-pseudo-class-no-unknown": null
        }
    },
    "version": "0.21.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
