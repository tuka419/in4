# in4
{
  "name": "etherspot",
  "version": "1.43.9",
  "lockfileVersion": 2,
  "requires": true,
  "packages": {
    "": {
      "name": "etherspot",
      "version": "1.43.9",
      "license": "MIT",
      "dependencies": {
        "@apollo/client": "3.4.0",
        "@etherspot/contracts": "1.9.9",
        "@lifi/sdk": "1.6.4",
        "@nerdwallet/apollo-cache-policies": "1.2.1",
        "class-transformer": "0.4.0",
        "class-validator": "0.14.0",
        "cross-fetch": "3.1.5",
        "graphql": "15.5.3",
        "subscriptions-transport-ws": "0.9.18",
        "validator": "13.7.0"
      },
      "devDependencies": {
        "@cucumber/cucumber": "7.0.0-rc.0",
        "@types/graphql": "14.5.0",
        "@types/jest": "25.2.3",
        "@types/node": "13.13.9",
        "@types/ws": "7.2.4",
        "@typescript-eslint/eslint-plugin": "2.34.0",
        "@typescript-eslint/parser": "2.34.0",
        "eslint": "6.8.0",
        "eslint-config-prettier": "6.11.0",
        "eslint-plugin-import": "2.20.2",
        "ethers": "5.6.8",
        "expect": "25.5.0",
        "gh-pages": "3.2.3",
        "husky": "^8.0.0",
        "jest": "25.5.4",
        "prettier": "2.0.5",
        "reflect-metadata": "0.1.13",
        "rimraf": "3.0.2",
        "rxjs": "6.6.7",
        "serve": "14.1.2",
        "ts-jest": "25.5.1",
        "ts-node": "8.10.2",
        "typedoc": "0.17.8",
        "typescript": "3.9.3",
        "ws": "7.4.6"
      },
      "peerDependencies": {
        "ethers": "^5.6.8",
        "reflect-metadata": "^0.1.13",
        "rxjs": "^6.6.2"
      }
    },
    "node_modules/@apollo/client": {
      "version": "3.4.0",
      "resolved": "https://registry.npmjs.org/@apollo/client/-/client-3.4.0.tgz",
      "integrity": "sha512-ASGw+L1KYLm3Syl5lJKFB6nLEuthBUcvSYhI6p4g4hi+kMli6+UarMONuIYmTBUec2KcQCfs4uwi3bd0xWQ8zg==",
      "dependencies": {
        "@graphql-typed-document-node/core": "^3.0.0",
        "@wry/context": "^0.6.0",
        "@wry/equality": "^0.5.0",
        "@wry/trie": "^0.3.0",
        "graphql-tag": "^2.12.3",
        "hoist-non-react-statics": "^3.3.2",
        "optimism": "^0.16.1",
        "prop-types": "^15.7.2",
        "symbol-observable": "^4.0.0",
        "ts-invariant": "^0.9.0",
        "tslib": "^2.3.0",
        "zen-observable-ts": "^1.1.0"
      },
      "peerDependencies": {
        "graphql": "^14.0.0 || ^15.0.0",
        "react": "^16.8.0 || ^17.0.0",
        "subscriptions-transport-ws": "^0.9.0"
      },
      "peerDependenciesMeta": {
        "react": {
          "optional": true
        },
        "subscriptions-transport-ws": {
          "optional": true
        }
      }
    },
    "node_modules/@apollo/client/node_modules/tslib": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
      "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
    },
    "node_modules/@babel/code-frame": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.14.5.tgz",
      "integrity": "sha512-9pzDqyc6OLDaqe+zbACgFkb6fKMNG6CObKpnYXChRsvYGyEdc7CA2BaqeOM+vOtCS5ndmJicPJhKAwYRI6UfFw==",
      "dev": true,
      "dependencies": {
        "@babel/highlight": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/compat-data": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/compat-data/-/compat-data-7.14.5.tgz",
      "integrity": "sha512-kixrYn4JwfAVPa0f2yfzc2AWti6WRRyO3XjWW5PJAvtE11qhSayrrcrEnee05KAtNaPC+EwehE8Qt1UedEVB8w==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/core": {
      "version": "7.14.6",
      "resolved": "https://registry.npmjs.org/@babel/core/-/core-7.14.6.tgz",
      "integrity": "sha512-gJnOEWSqTk96qG5BoIrl5bVtc23DCycmIePPYnamY9RboYdI4nFy5vAQMSl81O5K/W0sLDWfGysnOECC+KUUCA==",
      "dev": true,
      "dependencies": {
        "@babel/code-frame": "^7.14.5",
        "@babel/generator": "^7.14.5",
        "@babel/helper-compilation-targets": "^7.14.5",
        "@babel/helper-module-transforms": "^7.14.5",
        "@babel/helpers": "^7.14.6",
        "@babel/parser": "^7.14.6",
        "@babel/template": "^7.14.5",
        "@babel/traverse": "^7.14.5",
        "@babel/types": "^7.14.5",
        "convert-source-map": "^1.7.0",
        "debug": "^4.1.0",
        "gensync": "^1.0.0-beta.2",
        "json5": "^2.1.2",
        "semver": "^6.3.0",
        "source-map": "^0.5.0"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/babel"
      }
    },
    "node_modules/@babel/core/node_modules/semver": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
      "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/@babel/core/node_modules/source-map": {
      "version": "0.5.7",
      "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.5.7.tgz",
      "integrity": "sha1-igOdLRAh0i0eoUyA2OpGi6LvP8w=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/@babel/generator": {
      "version": "7.14.8",
      "resolved": "https://registry.npmjs.org/@babel/generator/-/generator-7.14.8.tgz",
      "integrity": "sha512-cYDUpvIzhBVnMzRoY1fkSEhK/HmwEVwlyULYgn/tMQYd6Obag3ylCjONle3gdErfXBW61SVTlR9QR7uWlgeIkg==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.14.8",
        "jsesc": "^2.5.1",
        "source-map": "^0.5.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/generator/node_modules/source-map": {
      "version": "0.5.7",
      "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.5.7.tgz",
      "integrity": "sha1-igOdLRAh0i0eoUyA2OpGi6LvP8w=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/@babel/helper-compilation-targets": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-compilation-targets/-/helper-compilation-targets-7.14.5.tgz",
      "integrity": "sha512-v+QtZqXEiOnpO6EYvlImB6zCD2Lel06RzOPzmkz/D/XgQiUu3C/Jb1LOqSt/AIA34TYi/Q+KlT8vTQrgdxkbLw==",
      "dev": true,
      "dependencies": {
        "@babel/compat-data": "^7.14.5",
        "@babel/helper-validator-option": "^7.14.5",
        "browserslist": "^4.16.6",
        "semver": "^6.3.0"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0"
      }
    },
    "node_modules/@babel/helper-compilation-targets/node_modules/semver": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
      "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/@babel/helper-function-name": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-function-name/-/helper-function-name-7.14.5.tgz",
      "integrity": "sha512-Gjna0AsXWfFvrAuX+VKcN/aNNWonizBj39yGwUzVDVTlMYJMK2Wp6xdpy72mfArFq5uK+NOuexfzZlzI1z9+AQ==",
      "dev": true,
      "dependencies": {
        "@babel/helper-get-function-arity": "^7.14.5",
        "@babel/template": "^7.14.5",
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-get-function-arity": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-get-function-arity/-/helper-get-function-arity-7.14.5.tgz",
      "integrity": "sha512-I1Db4Shst5lewOM4V+ZKJzQ0JGGaZ6VY1jYvMghRjqs6DWgxLCIyFt30GlnKkfUeFLpJt2vzbMVEXVSXlIFYUg==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-hoist-variables": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-hoist-variables/-/helper-hoist-variables-7.14.5.tgz",
      "integrity": "sha512-R1PXiz31Uc0Vxy4OEOm07x0oSjKAdPPCh3tPivn/Eo8cvz6gveAeuyUUPB21Hoiif0uoPQSSdhIPS3352nvdyQ==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-member-expression-to-functions": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-member-expression-to-functions/-/helper-member-expression-to-functions-7.14.5.tgz",
      "integrity": "sha512-UxUeEYPrqH1Q/k0yRku1JE7dyfyehNwT6SVkMHvYvPDv4+uu627VXBckVj891BO8ruKBkiDoGnZf4qPDD8abDQ==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-module-imports": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-imports/-/helper-module-imports-7.14.5.tgz",
      "integrity": "sha512-SwrNHu5QWS84XlHwGYPDtCxcA0hrSlL2yhWYLgeOc0w7ccOl2qv4s/nARI0aYZW+bSwAL5CukeXA47B/1NKcnQ==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-module-transforms": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-transforms/-/helper-module-transforms-7.14.5.tgz",
      "integrity": "sha512-iXpX4KW8LVODuAieD7MzhNjmM6dzYY5tfRqT+R9HDXWl0jPn/djKmA+G9s/2C2T9zggw5tK1QNqZ70USfedOwA==",
      "dev": true,
      "dependencies": {
        "@babel/helper-module-imports": "^7.14.5",
        "@babel/helper-replace-supers": "^7.14.5",
        "@babel/helper-simple-access": "^7.14.5",
        "@babel/helper-split-export-declaration": "^7.14.5",
        "@babel/helper-validator-identifier": "^7.14.5",
        "@babel/template": "^7.14.5",
        "@babel/traverse": "^7.14.5",
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-optimise-call-expression": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-optimise-call-expression/-/helper-optimise-call-expression-7.14.5.tgz",
      "integrity": "sha512-IqiLIrODUOdnPU9/F8ib1Fx2ohlgDhxnIDU7OEVi+kAbEZcyiF7BLU8W6PfvPi9LzztjS7kcbzbmL7oG8kD6VA==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-plugin-utils": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-plugin-utils/-/helper-plugin-utils-7.14.5.tgz",
      "integrity": "sha512-/37qQCE3K0vvZKwoK4XU/irIJQdIfCJuhU5eKnNxpFDsOkgFaUAwbv+RYw6eYgsC0E4hS7r5KqGULUogqui0fQ==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-replace-supers": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-replace-supers/-/helper-replace-supers-7.14.5.tgz",
      "integrity": "sha512-3i1Qe9/8x/hCHINujn+iuHy+mMRLoc77b2nI9TB0zjH1hvn9qGlXjWlggdwUcju36PkPCy/lpM7LLUdcTyH4Ow==",
      "dev": true,
      "dependencies": {
        "@babel/helper-member-expression-to-functions": "^7.14.5",
        "@babel/helper-optimise-call-expression": "^7.14.5",
        "@babel/traverse": "^7.14.5",
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-simple-access": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-simple-access/-/helper-simple-access-7.14.5.tgz",
      "integrity": "sha512-nfBN9xvmCt6nrMZjfhkl7i0oTV3yxR4/FztsbOASyTvVcoYd0TRHh7eMLdlEcCqobydC0LAF3LtC92Iwxo0wyw==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-split-export-declaration": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-split-export-declaration/-/helper-split-export-declaration-7.14.5.tgz",
      "integrity": "sha512-hprxVPu6e5Kdp2puZUmvOGjaLv9TCe58E/Fl6hRq4YiVQxIcNvuq6uTM2r1mT/oPskuS9CgR+I94sqAYv0NGKA==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-validator-identifier": {
      "version": "7.15.7",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-identifier/-/helper-validator-identifier-7.15.7.tgz",
      "integrity": "sha512-K4JvCtQqad9OY2+yTU8w+E82ywk/fe+ELNlt1G8z3bVGlZfn/hOcQQsUhGhW/N+tb3fxK800wLtKOE/aM0m72w==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-validator-option": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-option/-/helper-validator-option-7.14.5.tgz",
      "integrity": "sha512-OX8D5eeX4XwcroVW45NMvoYaIuFI+GQpA2a8Gi+X/U/cDUIRsV37qQfF905F0htTRCREQIB4KqPeaveRJUl3Ow==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helpers": {
      "version": "7.14.6",
      "resolved": "https://registry.npmjs.org/@babel/helpers/-/helpers-7.14.6.tgz",
      "integrity": "sha512-yesp1ENQBiLI+iYHSJdoZKUtRpfTlL1grDIX9NRlAVppljLw/4tTyYupIB7uIYmC3stW/imAv8EqaKaS/ibmeA==",
      "dev": true,
      "dependencies": {
        "@babel/template": "^7.14.5",
        "@babel/traverse": "^7.14.5",
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/highlight": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/highlight/-/highlight-7.14.5.tgz",
      "integrity": "sha512-qf9u2WFWVV0MppaL877j2dBtQIDgmidgjGk5VIMw3OadXvYaXn66U1BFlH2t4+t3i+8PhedppRv+i40ABzd+gg==",
      "dev": true,
      "dependencies": {
        "@babel/helper-validator-identifier": "^7.14.5",
        "chalk": "^2.0.0",
        "js-tokens": "^4.0.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/parser": {
      "version": "7.14.6",
      "resolved": "https://registry.npmjs.org/@babel/parser/-/parser-7.14.6.tgz",
      "integrity": "sha512-oG0ej7efjEXxb4UgE+klVx+3j4MVo+A2vCzm7OUN4CLo6WhQ+vSOD2yJ8m7B+DghObxtLxt3EfgMWpq+AsWehQ==",
      "dev": true,
      "bin": {
        "parser": "bin/babel-parser.js"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@babel/plugin-syntax-async-generators": {
      "version": "7.8.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-async-generators/-/plugin-syntax-async-generators-7.8.4.tgz",
      "integrity": "sha512-tycmZxkGfZaxhMRbXlPXuVFpdWlXpir2W4AMhSJgRKzk/eDlIXOhb2LHWoLpDF7TEHylV5zNhykX6KAgHJmTNw==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.8.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-bigint": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-bigint/-/plugin-syntax-bigint-7.8.3.tgz",
      "integrity": "sha512-wnTnFlG+YxQm3vDxpGE57Pj0srRU4sHE/mDkt1qv2YJJSeUAec2ma4WLUnUPeKjyrfntVwe/N6dCXpU+zL3Npg==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.8.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-class-properties": {
      "version": "7.12.13",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-class-properties/-/plugin-syntax-class-properties-7.12.13.tgz",
      "integrity": "sha512-fm4idjKla0YahUNgFNLCB0qySdsoPiZP3iQE3rky0mBUtMZ23yDJ9SJdg6dXTSDnulOVqiF3Hgr9nbXvXTQZYA==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.12.13"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-import-meta": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-import-meta/-/plugin-syntax-import-meta-7.10.4.tgz",
      "integrity": "sha512-Yqfm+XDx0+Prh3VSeEQCPU81yC+JWZ2pDPFSS4ZdpfZhp4MkFMaDC1UqseovEKwSUpnIL7+vK+Clp7bfh0iD7g==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.10.4"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-json-strings": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-json-strings/-/plugin-syntax-json-strings-7.8.3.tgz",
      "integrity": "sha512-lY6kdGpWHvjoe2vk4WrAapEuBR69EMxZl+RoGRhrFGNYVK8mOPAW8VfbT/ZgrFbXlDNiiaxQnAtgVCZ6jv30EA==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.8.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-logical-assignment-operators": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-logical-assignment-operators/-/plugin-syntax-logical-assignment-operators-7.10.4.tgz",
      "integrity": "sha512-d8waShlpFDinQ5MtvGU9xDAOzKH47+FFoney2baFIoMr952hKOLp1HR7VszoZvOsV/4+RRszNY7D17ba0te0ig==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.10.4"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-nullish-coalescing-operator": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-nullish-coalescing-operator/-/plugin-syntax-nullish-coalescing-operator-7.8.3.tgz",
      "integrity": "sha512-aSff4zPII1u2QD7y+F8oDsz19ew4IGEJg9SVW+bqwpwtfFleiQDMdzA/R+UlWDzfnHFCxxleFT0PMIrR36XLNQ==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.8.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-numeric-separator": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-numeric-separator/-/plugin-syntax-numeric-separator-7.10.4.tgz",
      "integrity": "sha512-9H6YdfkcK/uOnY/K7/aA2xpzaAgkQn37yzWUMRK7OaPOqOpGS1+n0H5hxT9AUw9EsSjPW8SVyMJwYRtWs3X3ug==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.10.4"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-object-rest-spread": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-object-rest-spread/-/plugin-syntax-object-rest-spread-7.8.3.tgz",
      "integrity": "sha512-XoqMijGZb9y3y2XskN+P1wUGiVwWZ5JmoDRwx5+3GmEplNyVM2s2Dg8ILFQm8rWM48orGy5YpI5Bl8U1y7ydlA==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.8.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-optional-catch-binding": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-optional-catch-binding/-/plugin-syntax-optional-catch-binding-7.8.3.tgz",
      "integrity": "sha512-6VPD0Pc1lpTqw0aKoeRTMiB+kWhAoT24PA+ksWSBrFtl5SIRVpZlwN3NNPQjehA2E/91FV3RjLWoVTglWcSV3Q==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.8.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-syntax-optional-chaining": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-optional-chaining/-/plugin-syntax-optional-chaining-7.8.3.tgz",
      "integrity": "sha512-KoK9ErH1MBlCPxV0VANkXW2/dw4vlbGDrFgz8bmUsBGYkFRcbRwMh6cIJubdPrkxRwuGdtCk0v/wPTKbQgBjkg==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.8.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/template": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/template/-/template-7.14.5.tgz",
      "integrity": "sha512-6Z3Po85sfxRGachLULUhOmvAaOo7xCvqGQtxINai2mEGPFm6pQ4z5QInFnUrRpfoSV60BnjyF5F3c+15fxFV1g==",
      "dev": true,
      "dependencies": {
        "@babel/code-frame": "^7.14.5",
        "@babel/parser": "^7.14.5",
        "@babel/types": "^7.14.5"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/traverse": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/traverse/-/traverse-7.14.5.tgz",
      "integrity": "sha512-G3BiS15vevepdmFqmUc9X+64y0viZYygubAMO8SvBmKARuF6CPSZtH4Ng9vi/lrWlZFGe3FWdXNy835akH8Glg==",
      "dev": true,
      "dependencies": {
        "@babel/code-frame": "^7.14.5",
        "@babel/generator": "^7.14.5",
        "@babel/helper-function-name": "^7.14.5",
        "@babel/helper-hoist-variables": "^7.14.5",
        "@babel/helper-split-export-declaration": "^7.14.5",
        "@babel/parser": "^7.14.5",
        "@babel/types": "^7.14.5",
        "debug": "^4.1.0",
        "globals": "^11.1.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/traverse/node_modules/globals": {
      "version": "11.12.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-11.12.0.tgz",
      "integrity": "sha512-WOBp/EEGUiIsJSp7wcv/y6MO+lV9UoncWqxuFfm8eBwzWNgyfBd6Gz+IeKQ9jCmyhoH99g15M3T+QaVHFjizVA==",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/@babel/types": {
      "version": "7.14.8",
      "resolved": "https://registry.npmjs.org/@babel/types/-/types-7.14.8.tgz",
      "integrity": "sha512-iob4soQa7dZw8nodR/KlOQkPh9S4I8RwCxwRIFuiMRYjOzH/KJzdUfDgz6cGi5dDaclXF4P2PAhCdrBJNIg68Q==",
      "dev": true,
      "dependencies": {
        "@babel/helper-validator-identifier": "^7.14.8",
        "to-fast-properties": "^2.0.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@bcoe/v8-coverage": {
      "version": "0.2.3",
      "resolved": "https://registry.npmjs.org/@bcoe/v8-coverage/-/v8-coverage-0.2.3.tgz",
      "integrity": "sha512-0hYQ8SB4Db5zvZB4axdMHGwEaQjkZzFjQiN9LVYvIFB2nSUHW9tYpxWriPrWDASIxiaXax83REcLxuSdnGPZtw==",
      "dev": true
    },
    "node_modules/@cnakazawa/watch": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/@cnakazawa/watch/-/watch-1.0.4.tgz",
      "integrity": "sha512-v9kIhKwjeZThiWrLmj0y17CWoyddASLj9O2yvbZkbvw/N3rWOYy9zkV66ursAoVr0mV15bL8g0c4QZUE6cdDoQ==",
      "dev": true,
      "dependencies": {
        "exec-sh": "^0.3.2",
        "minimist": "^1.2.0"
      },
      "bin": {
        "watch": "cli.js"
      },
      "engines": {
        "node": ">=0.1.95"
      }
    },
    "node_modules/@cucumber/create-meta": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/@cucumber/create-meta/-/create-meta-2.0.4.tgz",
      "integrity": "sha512-upbfuih3NVm1efWSbPGH7HI6O2O037QRAPLMgTDIGaf2lfcrMCgB/qkqPHk8DOUuz7Vjpg5tFFoJODSDcxtNOA==",
      "dev": true,
      "dependencies": {
        "@cucumber/messages": "^13.1.0",
        "ts-node": "^9.0.0",
        "typescript": "^4.0.5"
      }
    },
    "node_modules/@cucumber/create-meta/node_modules/arg": {
      "version": "4.1.3",
      "resolved": "https://registry.npmjs.org/arg/-/arg-4.1.3.tgz",
      "integrity": "sha512-58S9QDqG0Xx27YwPSt9fJxivjYl432YCwfDMfZ+71RAqUrZef7LrKQZ3LHLOwCS4FLNBplP533Zx895SeOCHvA==",
      "dev": true
    },
    "node_modules/@cucumber/create-meta/node_modules/ts-node": {
      "version": "9.1.1",
      "resolved": "https://registry.npmjs.org/ts-node/-/ts-node-9.1.1.tgz",
      "integrity": "sha512-hPlt7ZACERQGf03M253ytLY3dHbGNGrAq9qIHWUY9XHYl1z7wYngSr3OQ5xmui8o2AaxsONxIzjafLUiWBo1Fg==",
      "dev": true,
      "dependencies": {
        "arg": "^4.1.0",
        "create-require": "^1.1.0",
        "diff": "^4.0.1",
        "make-error": "^1.1.1",
        "source-map-support": "^0.5.17",
        "yn": "3.1.1"
      },
      "bin": {
        "ts-node": "dist/bin.js",
        "ts-node-script": "dist/bin-script.js",
        "ts-node-transpile-only": "dist/bin-transpile.js",
        "ts-script": "dist/bin-script-deprecated.js"
      },
      "engines": {
        "node": ">=10.0.0"
      },
      "peerDependencies": {
        "typescript": ">=2.7"
      }
    },
    "node_modules/@cucumber/create-meta/node_modules/typescript": {
      "version": "4.3.3",
      "resolved": "https://registry.npmjs.org/typescript/-/typescript-4.3.3.tgz",
      "integrity": "sha512-rUvLW0WtF7PF2b9yenwWUi9Da9euvDRhmH7BLyBG4DCFfOJ850LGNknmRpp8Z8kXNUPObdZQEfKOiHtXuQHHKA==",
      "dev": true,
      "bin": {
        "tsc": "bin/tsc",
        "tsserver": "bin/tsserver"
      },
      "engines": {
        "node": ">=4.2.0"
      }
    },
    "node_modules/@cucumber/cucumber": {
      "version": "7.0.0-rc.0",
      "resolved": "https://registry.npmjs.org/@cucumber/cucumber/-/cucumber-7.0.0-rc.0.tgz",
      "integrity": "sha512-OUuFR78NB0hSuwA3tuVeshfHCVbd5yn6i8/NkftVP3QxyKD3wM01ngV4Fo/WckLffTIj0RCHEPaIV80icv2jgQ==",
      "dev": true,
      "dependencies": {
        "@cucumber/create-meta": "^2.0.2",
        "@cucumber/cucumber-expressions": "^10.3.0",
        "@cucumber/gherkin": "^15.0.2",
        "@cucumber/messages": "^13.0.1",
        "@cucumber/query": "^7.0.0",
        "@cucumber/tag-expressions": "^2.0.4",
        "assertion-error-formatter": "^3.0.0",
        "bluebird": "^3.7.2",
        "capital-case": "^1.0.3",
        "cli-table3": "^0.6.0",
        "colors": "^1.4.0",
        "commander": "^5.0.0",
        "duration": "^0.2.2",
        "durations": "^3.4.2",
        "figures": "^3.2.0",
        "glob": "^7.1.6",
        "indent-string": "^4.0.0",
        "is-generator": "^1.0.3",
        "is-stream": "^2.0.0",
        "knuth-shuffle-seeded": "^1.0.6",
        "lodash": "^4.17.20",
        "mz": "^2.7.0",
        "progress": "^2.0.3",
        "read-pkg-up": "^7.0.1",
        "resolve": "^1.17.0",
        "stack-chain": "^2.0.0",
        "stacktrace-js": "^2.0.2",
        "string-argv": "^0.3.1",
        "tmp": "^0.2.1",
        "util-arity": "^1.1.0",
        "verror": "^1.10.0"
      },
      "bin": {
        "cucumber-js": "bin/cucumber-js"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/@cucumber/cucumber-expressions": {
      "version": "10.3.0",
      "resolved": "https://registry.npmjs.org/@cucumber/cucumber-expressions/-/cucumber-expressions-10.3.0.tgz",
      "integrity": "sha512-ZoDb6UPXPmYnRpAye2AoSO7T2j345MDH+D64ikLlXU4WT+83fvma7ULrx3B9IfNlIQOKuE2dodi4uPu95uPjbA==",
      "dev": true,
      "dependencies": {
        "becke-ch--regex--s0-0-v1--base--pl--lib": "^1.4.0"
      }
    },
    "node_modules/@cucumber/gherkin": {
      "version": "15.0.2",
      "resolved": "https://registry.npmjs.org/@cucumber/gherkin/-/gherkin-15.0.2.tgz",
      "integrity": "sha512-E8GIulakxjXPlGatW6DxYQ1jJSHvT9mDLginqe7AkjyIjBuddQvXFShI/4fdYa6XaF3gO4ybhQvHtcza/1ob/Q==",
      "dev": true,
      "dependencies": {
        "@cucumber/messages": "^13.0.1",
        "@teppeis/multimaps": "^1.1.0",
        "commander": "^6.0.0",
        "source-map-support": "^0.5.19"
      },
      "bin": {
        "gherkin-javascript": "bin/gherkin"
      }
    },
    "node_modules/@cucumber/gherkin/node_modules/commander": {
      "version": "6.2.1",
      "resolved": "https://registry.npmjs.org/commander/-/commander-6.2.1.tgz",
      "integrity": "sha512-U7VdrJFnJgo4xjrHpTzu0yrHPGImdsmD95ZlgYSEajAn2JKzDhDTPG9kBTefmObL2w/ngeZnilk+OV9CG3d7UA==",
      "dev": true,
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/@cucumber/messages": {
      "version": "13.2.1",
      "resolved": "https://registry.npmjs.org/@cucumber/messages/-/messages-13.2.1.tgz",
      "integrity": "sha512-2cu6P1JsEcH0/RlMx302KOK9rkKDHYS1H+6/VhQ6L+yrVW458wOU3CiVgurLn3heCDdJH8r4L87pkSwt0rxiGQ==",
      "dev": true,
      "dependencies": {
        "@types/uuid": "^8.3.0",
        "protobufjs": "^6.10.2",
        "uuid": "^8.3.1"
      }
    },
    "node_modules/@cucumber/query": {
      "version": "7.0.1",
      "resolved": "https://registry.npmjs.org/@cucumber/query/-/query-7.0.1.tgz",
      "integrity": "sha512-Ocxtm0LLLbYa3TwZZFzHG4/uHnb7GkYNUsRzf+bLyKOYymkffMkgLcITkx+X4Kw/tq+xzzHh3z/YivEAXxBJdQ==",
      "dev": true,
      "dependencies": {
        "@cucumber/messages": "^13.2.1",
        "@teppeis/multimaps": "^1.1.0"
      }
    },
    "node_modules/@cucumber/tag-expressions": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/@cucumber/tag-expressions/-/tag-expressions-2.0.4.tgz",
      "integrity": "sha512-HiNncmg/gS34yNpMFAeoIyUHqLFFN92MXIj3rs+BKo7vn16SxvYsigDvd2PAHyjSIThsp9TO1XDtl0SLKVB58g==",
      "dev": true
    },
    "node_modules/@etherspot/contracts": {
      "version": "1.9.9",
      "resolved": "https://registry.npmjs.org/@etherspot/contracts/-/contracts-1.9.9.tgz",
      "integrity": "sha512-n53Z39VNmRxPR7XWZ8gkj+gmeMrJka6RfJLRWCDUbVGyKd1sLixd+8e2qqobrpcBYn4uazqAvzWokfqLp5wxRw=="
    },
    "node_modules/@ethersproject/abi": {
      "version": "5.6.3",
      "resolved": "https://registry.npmjs.org/@ethersproject/abi/-/abi-5.6.3.tgz",
      "integrity": "sha512-CxKTdoZY4zDJLWXG6HzNH6znWK0M79WzzxHegDoecE3+K32pzfHOzuXg2/oGSTecZynFgpkjYXNPOqXVJlqClw==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/hash": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/abstract-provider": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/abstract-provider/-/abstract-provider-5.6.1.tgz",
      "integrity": "sha512-BxlIgogYJtp1FS8Muvj8YfdClk3unZH0vRMVX791Z9INBNT/kuACZ9GzaY1Y4yFq+YSy6/w4gzj3HCRKrK9hsQ==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/networks": "^5.6.3",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/transactions": "^5.6.2",
        "@ethersproject/web": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/abstract-signer": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/abstract-signer/-/abstract-signer-5.6.2.tgz",
      "integrity": "sha512-n1r6lttFBG0t2vNiI3HoWaS/KdOt8xyDjzlP2cuevlWLG6EX0OwcKLyG/Kp/cuwNxdy/ous+R/DEMdTUwWQIjQ==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-provider": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0"
      }
    },
    "node_modules/@ethersproject/address": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/address/-/address-5.6.1.tgz",
      "integrity": "sha512-uOgF0kS5MJv9ZvCz7x6T2EXJSzotiybApn4XlOgoTX0xdtyVIJ7pF+6cGPxiEq/dpBiTfMiw7Yc81JcwhSYA0Q==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/rlp": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/base64": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/base64/-/base64-5.6.1.tgz",
      "integrity": "sha512-qB76rjop6a0RIYYMiB4Eh/8n+Hxu2NIZm8S/Q7kNo5pmZfXhHGHmS4MinUainiBC54SCyRnwzL+KZjj8zbsSsw==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/basex": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/basex/-/basex-5.6.1.tgz",
      "integrity": "sha512-a52MkVz4vuBXR06nvflPMotld1FJWSj2QT0985v7P/emPZO00PucFAkbcmq2vpVU7Ts7umKiSI6SppiLykVWsA==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/properties": "^5.6.0"
      }
    },
    "node_modules/@ethersproject/bignumber": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/bignumber/-/bignumber-5.6.2.tgz",
      "integrity": "sha512-v7+EEUbhGqT3XJ9LMPsKvXYHFc8eHxTowFCG/HgJErmq4XHJ2WR7aeyICg3uTOAQ7Icn0GFHAohXEhxQHq4Ubw==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "bn.js": "^5.2.1"
      }
    },
    "node_modules/@ethersproject/bytes": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/bytes/-/bytes-5.6.1.tgz",
      "integrity": "sha512-NwQt7cKn5+ZE4uDn+X5RAXLp46E1chXoaMmrxAyA0rblpxz8t58lVkrHXoRIn0lz1joQElQ8410GqhTqMOwc6g==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "node_modules/@ethersproject/constants": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/constants/-/constants-5.6.1.tgz",
      "integrity": "sha512-QSq9WVnZbxXYFftrjSjZDUshp6/eKp6qrtdBtUCm0QxCV5z1fG/w3kdlcsjMCQuQHUnAclKoK7XpXMezhRDOLg==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.6.2"
      }
    },
    "node_modules/@ethersproject/contracts": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/contracts/-/contracts-5.6.2.tgz",
      "integrity": "sha512-hguUA57BIKi6WY0kHvZp6PwPlWF87MCeB4B7Z7AbUpTxfFXFdn/3b0GmjZPagIHS+3yhcBJDnuEfU4Xz+Ks/8g==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abi": "^5.6.3",
        "@ethersproject/abstract-provider": "^5.6.1",
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/transactions": "^5.6.2"
      }
    },
    "node_modules/@ethersproject/hash": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/hash/-/hash-5.6.1.tgz",
      "integrity": "sha512-L1xAHurbaxG8VVul4ankNX5HgQ8PNCTrnVXEiFnE9xoRnaUcgfD12tZINtDinSllxPLCtGwguQxJ5E6keE84pA==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/hdnode": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/hdnode/-/hdnode-5.6.2.tgz",
      "integrity": "sha512-tERxW8Ccf9CxW2db3WsN01Qao3wFeRsfYY9TCuhmG0xNpl2IO8wgXU3HtWIZ49gUWPggRy4Yg5axU0ACaEKf1Q==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/basex": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/pbkdf2": "^5.6.1",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/sha2": "^5.6.1",
        "@ethersproject/signing-key": "^5.6.2",
        "@ethersproject/strings": "^5.6.1",
        "@ethersproject/transactions": "^5.6.2",
        "@ethersproject/wordlists": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/json-wallets": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/json-wallets/-/json-wallets-5.6.1.tgz",
      "integrity": "sha512-KfyJ6Zwz3kGeX25nLihPwZYlDqamO6pfGKNnVMWWfEVVp42lTfCZVXXy5Ie8IZTN0HKwAngpIPi7gk4IJzgmqQ==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/hdnode": "^5.6.2",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/pbkdf2": "^5.6.1",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/random": "^5.6.1",
        "@ethersproject/strings": "^5.6.1",
        "@ethersproject/transactions": "^5.6.2",
        "aes-js": "3.0.0",
        "scrypt-js": "3.0.1"
      }
    },
    "node_modules/@ethersproject/keccak256": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/keccak256/-/keccak256-5.6.1.tgz",
      "integrity": "sha512-bB7DQHCTRDooZZdL3lk9wpL0+XuG3XLGHLh3cePnybsO3V0rdCAOQGpn/0R3aODmnTOOkCATJiD2hnL+5bwthA==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "js-sha3": "0.8.0"
      }
    },
    "node_modules/@ethersproject/logger": {
      "version": "5.6.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/logger/-/logger-5.6.0.tgz",
      "integrity": "sha512-BiBWllUROH9w+P21RzoxJKzqoqpkyM1pRnEKG69bulE9TSQD8SAIvTQqIMZmmCO8pUNkgLP1wndX1gKghSpBmg==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ]
    },
    "node_modules/@ethersproject/networks": {
      "version": "5.6.3",
      "resolved": "https://registry.npmjs.org/@ethersproject/networks/-/networks-5.6.3.tgz",
      "integrity": "sha512-QZxRH7cA5Ut9TbXwZFiCyuPchdWi87ZtVNHWZd0R6YFgYtes2jQ3+bsslJ0WdyDe0i6QumqtoYqvY3rrQFRZOQ==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "node_modules/@ethersproject/pbkdf2": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/pbkdf2/-/pbkdf2-5.6.1.tgz",
      "integrity": "sha512-k4gRQ+D93zDRPNUfmduNKq065uadC2YjMP/CqwwX5qG6R05f47boq6pLZtV/RnC4NZAYOPH1Cyo54q0c9sshRQ==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/sha2": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/properties": {
      "version": "5.6.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/properties/-/properties-5.6.0.tgz",
      "integrity": "sha512-szoOkHskajKePTJSZ46uHUWWkbv7TzP2ypdEK6jGMqJaEt2sb0jCgfBo0gH0m2HBpRixMuJ6TBRaQCF7a9DoCg==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "node_modules/@ethersproject/providers": {
      "version": "5.6.8",
      "resolved": "https://registry.npmjs.org/@ethersproject/providers/-/providers-5.6.8.tgz",
      "integrity": "sha512-Wf+CseT/iOJjrGtAOf3ck9zS7AgPmr2fZ3N97r4+YXN3mBePTG2/bJ8DApl9mVwYL+RpYbNxMEkEp4mPGdwG/w==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-provider": "^5.6.1",
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/base64": "^5.6.1",
        "@ethersproject/basex": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/hash": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/networks": "^5.6.3",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/random": "^5.6.1",
        "@ethersproject/rlp": "^5.6.1",
        "@ethersproject/sha2": "^5.6.1",
        "@ethersproject/strings": "^5.6.1",
        "@ethersproject/transactions": "^5.6.2",
        "@ethersproject/web": "^5.6.1",
        "bech32": "1.1.4",
        "ws": "7.4.6"
      }
    },
    "node_modules/@ethersproject/random": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/random/-/random-5.6.1.tgz",
      "integrity": "sha512-/wtPNHwbmng+5yi3fkipA8YBT59DdkGRoC2vWk09Dci/q5DlgnMkhIycjHlavrvrjJBkFjO/ueLyT+aUDfc4lA==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "node_modules/@ethersproject/rlp": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/rlp/-/rlp-5.6.1.tgz",
      "integrity": "sha512-uYjmcZx+DKlFUk7a5/W9aQVaoEC7+1MOBgNtvNg13+RnuUwT4F0zTovC0tmay5SmRslb29V1B7Y5KCri46WhuQ==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "node_modules/@ethersproject/sha2": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/sha2/-/sha2-5.6.1.tgz",
      "integrity": "sha512-5K2GyqcW7G4Yo3uenHegbXRPDgARpWUiXc6RiF7b6i/HXUoWlb7uCARh7BAHg7/qT/Q5ydofNwiZcim9qpjB6g==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "hash.js": "1.1.7"
      }
    },
    "node_modules/@ethersproject/signing-key": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/signing-key/-/signing-key-5.6.2.tgz",
      "integrity": "sha512-jVbu0RuP7EFpw82vHcL+GP35+KaNruVAZM90GxgQnGqB6crhBqW/ozBfFvdeImtmb4qPko0uxXjn8l9jpn0cwQ==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "bn.js": "^5.2.1",
        "elliptic": "6.5.4",
        "hash.js": "1.1.7"
      }
    },
    "node_modules/@ethersproject/solidity": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/solidity/-/solidity-5.6.1.tgz",
      "integrity": "sha512-KWqVLkUUoLBfL1iwdzUVlkNqAUIFMpbbeH0rgCfKmJp0vFtY4AsaN91gHKo9ZZLkC4UOm3cI3BmMV4N53BOq4g==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/sha2": "^5.6.1",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/strings": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/strings/-/strings-5.6.1.tgz",
      "integrity": "sha512-2X1Lgk6Jyfg26MUnsHiT456U9ijxKUybz8IM1Vih+NJxYtXhmvKBcHOmvGqpFSVJ0nQ4ZCoIViR8XlRw1v/+Cw==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "node_modules/@ethersproject/transactions": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/transactions/-/transactions-5.6.2.tgz",
      "integrity": "sha512-BuV63IRPHmJvthNkkt9G70Ullx6AcM+SDc+a8Aw/8Yew6YwT51TcBKEp1P4oOQ/bP25I18JJr7rcFRgFtU9B2Q==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/rlp": "^5.6.1",
        "@ethersproject/signing-key": "^5.6.2"
      }
    },
    "node_modules/@ethersproject/units": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/units/-/units-5.6.1.tgz",
      "integrity": "sha512-rEfSEvMQ7obcx3KWD5EWWx77gqv54K6BKiZzKxkQJqtpriVsICrktIQmKl8ReNToPeIYPnFHpXvKpi068YFZXw==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "node_modules/@ethersproject/wallet": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/wallet/-/wallet-5.6.2.tgz",
      "integrity": "sha512-lrgh0FDQPuOnHcF80Q3gHYsSUODp6aJLAdDmDV0xKCN/T7D99ta1jGVhulg3PY8wiXEngD0DfM0I2XKXlrqJfg==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-provider": "^5.6.1",
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/hash": "^5.6.1",
        "@ethersproject/hdnode": "^5.6.2",
        "@ethersproject/json-wallets": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/random": "^5.6.1",
        "@ethersproject/signing-key": "^5.6.2",
        "@ethersproject/transactions": "^5.6.2",
        "@ethersproject/wordlists": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/web": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/web/-/web-5.6.1.tgz",
      "integrity": "sha512-/vSyzaQlNXkO1WV+RneYKqCJwualcUdx/Z3gseVovZP0wIlOFcCE1hkRhKBH8ImKbGQbMl9EAAyJFrJu7V0aqA==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/base64": "^5.6.1",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "node_modules/@ethersproject/wordlists": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/wordlists/-/wordlists-5.6.1.tgz",
      "integrity": "sha512-wiPRgBpNbNwCQFoCr8bcWO8o5I810cqO6mkdtKfLKFlLxeCWcnzDi4Alu8iyNzlhYuS9npCwivMbRWF19dyblw==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/hash": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "node_modules/@graphql-typed-document-node/core": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/@graphql-typed-document-node/core/-/core-3.1.0.tgz",
      "integrity": "sha512-wYn6r8zVZyQJ6rQaALBEln5B1pzxb9shV5Ef97kTvn6yVGrqyXVnDqnU24MXnFubR+rZjBY9NWuxX3FB2sTsjg==",
      "peerDependencies": {
        "graphql": "^0.8.0 || ^0.9.0 || ^0.10.0 || ^0.11.0 || ^0.12.0 || ^0.13.0 || ^14.0.0 || ^15.0.0"
      }
    },
    "node_modules/@istanbuljs/load-nyc-config": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@istanbuljs/load-nyc-config/-/load-nyc-config-1.1.0.tgz",
      "integrity": "sha512-VjeHSlIzpv/NyD3N0YuHfXOPDIixcA1q2ZV98wsMqcYlPmv2n3Yb2lYP9XMElnaFVXg5A7YLTeLu6V84uQDjmQ==",
      "dev": true,
      "dependencies": {
        "camelcase": "^5.3.1",
        "find-up": "^4.1.0",
        "get-package-type": "^0.1.0",
        "js-yaml": "^3.13.1",
        "resolve-from": "^5.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@istanbuljs/load-nyc-config/node_modules/resolve-from": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/resolve-from/-/resolve-from-5.0.0.tgz",
      "integrity": "sha512-qYg9KP24dD5qka9J47d0aVky0N+b4fTU89LN9iDnjB5waksiC49rvMB0PrUJQGoTmH50XPiqOvAjDfaijGxYZw==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@istanbuljs/schema": {
      "version": "0.1.3",
      "resolved": "https://registry.npmjs.org/@istanbuljs/schema/-/schema-0.1.3.tgz",
      "integrity": "sha512-ZXRY4jNvVgSVQ8DL3LTcakaAtXwTVUxE81hslsyD2AtoXW/wVob10HkOJ1X/pAlcI7D+2YoZKg5do8G/w6RYgA==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/console": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/console/-/console-25.5.0.tgz",
      "integrity": "sha512-T48kZa6MK1Y6k4b89sexwmSF4YLeZS/Udqg3Jj3jG/cHH+N/sLFCEoXEDMOKugJQ9FxPN1osxIknvKkxt6MKyw==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "jest-message-util": "^25.5.0",
        "jest-util": "^25.5.0",
        "slash": "^3.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/console/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/@jest/console/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/console/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/@jest/console/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/@jest/console/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/console/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/core": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/@jest/core/-/core-25.5.4.tgz",
      "integrity": "sha512-3uSo7laYxF00Dg/DMgbn4xMJKmDdWvZnf89n8Xj/5/AeQ2dOQmn6b6Hkj/MleyzZWXpwv+WSdYWl4cLsy2JsoA==",
      "dev": true,
      "dependencies": {
        "@jest/console": "^25.5.0",
        "@jest/reporters": "^25.5.1",
        "@jest/test-result": "^25.5.0",
        "@jest/transform": "^25.5.1",
        "@jest/types": "^25.5.0",
        "ansi-escapes": "^4.2.1",
        "chalk": "^3.0.0",
        "exit": "^0.1.2",
        "graceful-fs": "^4.2.4",
        "jest-changed-files": "^25.5.0",
        "jest-config": "^25.5.4",
        "jest-haste-map": "^25.5.1",
        "jest-message-util": "^25.5.0",
        "jest-regex-util": "^25.2.6",
        "jest-resolve": "^25.5.1",
        "jest-resolve-dependencies": "^25.5.4",
        "jest-runner": "^25.5.4",
        "jest-runtime": "^25.5.4",
        "jest-snapshot": "^25.5.1",
        "jest-util": "^25.5.0",
        "jest-validate": "^25.5.0",
        "jest-watcher": "^25.5.0",
        "micromatch": "^4.0.2",
        "p-each-series": "^2.1.0",
        "realpath-native": "^2.0.0",
        "rimraf": "^3.0.0",
        "slash": "^3.0.0",
        "strip-ansi": "^6.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/core/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/@jest/core/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/core/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/@jest/core/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/@jest/core/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/core/node_modules/strip-ansi": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
      "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^5.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/core/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/environment": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/environment/-/environment-25.5.0.tgz",
      "integrity": "sha512-U2VXPEqL07E/V7pSZMSQCvV5Ea4lqOlT+0ZFijl/i316cRMHvZ4qC+jBdryd+lmRetjQo0YIQr6cVPNxxK87mA==",
      "dev": true,
      "dependencies": {
        "@jest/fake-timers": "^25.5.0",
        "@jest/types": "^25.5.0",
        "jest-mock": "^25.5.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/fake-timers": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/fake-timers/-/fake-timers-25.5.0.tgz",
      "integrity": "sha512-9y2+uGnESw/oyOI3eww9yaxdZyHq7XvprfP/eeoCsjqKYts2yRlsHS/SgjPDV8FyMfn2nbMy8YzUk6nyvdLOpQ==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-mock": "^25.5.0",
        "jest-util": "^25.5.0",
        "lolex": "^5.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/globals": {
      "version": "25.5.2",
      "resolved": "https://registry.npmjs.org/@jest/globals/-/globals-25.5.2.tgz",
      "integrity": "sha512-AgAS/Ny7Q2RCIj5kZ+0MuKM1wbF0WMLxbCVl/GOMoCNbODRdJ541IxJ98xnZdVSZXivKpJlNPIWa3QmY0l4CXA==",
      "dev": true,
      "dependencies": {
        "@jest/environment": "^25.5.0",
        "@jest/types": "^25.5.0",
        "expect": "^25.5.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/reporters": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/@jest/reporters/-/reporters-25.5.1.tgz",
      "integrity": "sha512-3jbd8pPDTuhYJ7vqiHXbSwTJQNavczPs+f1kRprRDxETeE3u6srJ+f0NPuwvOmk+lmunZzPkYWIFZDLHQPkviw==",
      "dev": true,
      "dependencies": {
        "@bcoe/v8-coverage": "^0.2.3",
        "@jest/console": "^25.5.0",
        "@jest/test-result": "^25.5.0",
        "@jest/transform": "^25.5.1",
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "collect-v8-coverage": "^1.0.0",
        "exit": "^0.1.2",
        "glob": "^7.1.2",
        "graceful-fs": "^4.2.4",
        "istanbul-lib-coverage": "^3.0.0",
        "istanbul-lib-instrument": "^4.0.0",
        "istanbul-lib-report": "^3.0.0",
        "istanbul-lib-source-maps": "^4.0.0",
        "istanbul-reports": "^3.0.2",
        "jest-haste-map": "^25.5.1",
        "jest-resolve": "^25.5.1",
        "jest-util": "^25.5.0",
        "jest-worker": "^25.5.0",
        "slash": "^3.0.0",
        "source-map": "^0.6.0",
        "string-length": "^3.1.0",
        "terminal-link": "^2.0.0",
        "v8-to-istanbul": "^4.1.3"
      },
      "engines": {
        "node": ">= 8.3"
      },
      "optionalDependencies": {
        "node-notifier": "^6.0.0"
      }
    },
    "node_modules/@jest/reporters/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/@jest/reporters/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/reporters/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/@jest/reporters/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/@jest/reporters/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/reporters/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/source-map": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/source-map/-/source-map-25.5.0.tgz",
      "integrity": "sha512-eIGx0xN12yVpMcPaVpjXPnn3N30QGJCJQSkEDUt9x1fI1Gdvb07Ml6K5iN2hG7NmMP6FDmtPEssE3z6doOYUwQ==",
      "dev": true,
      "dependencies": {
        "callsites": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "source-map": "^0.6.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/test-result": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/test-result/-/test-result-25.5.0.tgz",
      "integrity": "sha512-oV+hPJgXN7IQf/fHWkcS99y0smKLU2czLBJ9WA0jHITLst58HpQMtzSYxzaBvYc6U5U6jfoMthqsUlUlbRXs0A==",
      "dev": true,
      "dependencies": {
        "@jest/console": "^25.5.0",
        "@jest/types": "^25.5.0",
        "@types/istanbul-lib-coverage": "^2.0.0",
        "collect-v8-coverage": "^1.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/test-sequencer": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/@jest/test-sequencer/-/test-sequencer-25.5.4.tgz",
      "integrity": "sha512-pTJGEkSeg1EkCO2YWq6hbFvKNXk8ejqlxiOg1jBNLnWrgXOkdY6UmqZpwGFXNnRt9B8nO1uWMzLLZ4eCmhkPNA==",
      "dev": true,
      "dependencies": {
        "@jest/test-result": "^25.5.0",
        "graceful-fs": "^4.2.4",
        "jest-haste-map": "^25.5.1",
        "jest-runner": "^25.5.4",
        "jest-runtime": "^25.5.4"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/transform": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/@jest/transform/-/transform-25.5.1.tgz",
      "integrity": "sha512-Y8CEoVwXb4QwA6Y/9uDkn0Xfz0finGkieuV0xkdF9UtZGJeLukD5nLkaVrVsODB1ojRWlaoD0AJZpVHCSnJEvg==",
      "dev": true,
      "dependencies": {
        "@babel/core": "^7.1.0",
        "@jest/types": "^25.5.0",
        "babel-plugin-istanbul": "^6.0.0",
        "chalk": "^3.0.0",
        "convert-source-map": "^1.4.0",
        "fast-json-stable-stringify": "^2.0.0",
        "graceful-fs": "^4.2.4",
        "jest-haste-map": "^25.5.1",
        "jest-regex-util": "^25.2.6",
        "jest-util": "^25.5.0",
        "micromatch": "^4.0.2",
        "pirates": "^4.0.1",
        "realpath-native": "^2.0.0",
        "slash": "^3.0.0",
        "source-map": "^0.6.1",
        "write-file-atomic": "^3.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/transform/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/@jest/transform/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/transform/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/@jest/transform/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/@jest/transform/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/transform/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/types": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/types/-/types-25.5.0.tgz",
      "integrity": "sha512-OXD0RgQ86Tu3MazKo8bnrkDRaDXXMGUqd+kTtLtK1Zb7CRzQcaSRPPPV37SvYTdevXEBVxe0HXylEjs8ibkmCw==",
      "dev": true,
      "dependencies": {
        "@types/istanbul-lib-coverage": "^2.0.0",
        "@types/istanbul-reports": "^1.1.1",
        "@types/yargs": "^15.0.0",
        "chalk": "^3.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/@jest/types/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/@jest/types/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/types/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/@jest/types/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/@jest/types/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@jest/types/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@lifi/sdk": {
      "version": "1.6.4",
      "resolved": "https://registry.npmjs.org/@lifi/sdk/-/sdk-1.6.4.tgz",
      "integrity": "sha512-g2wjHoXjM9QmTNAezMeHuFcUrfzn/6MSTSTRiWVgFOXcQt7e8guzn9tqLj+4Q24xwPlLB6nj0Coz2JX8dh1spA==",
      "dependencies": {
        "@ethersproject/abi": "^5.7.0",
        "@ethersproject/contracts": "^5.7.0",
        "@lifi/types": "^1.16.0",
        "axios": "^1.1.3",
        "bignumber.js": "^9.1.0",
        "eth-rpc-errors": "^4.0.3",
        "ethers": "^5.7.2"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/abi": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/abi/-/abi-5.7.0.tgz",
      "integrity": "sha512-351ktp42TiRcYB3H1OP8yajPeAQstMW/yCFokj/AthP9bLHzQFPlOrxOcwYEDkUAICmOHljvN4K39OMTMUa9RA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/hash": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/abstract-provider": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/abstract-provider/-/abstract-provider-5.7.0.tgz",
      "integrity": "sha512-R41c9UkchKCpAqStMYUpdunjo3pkEvZC3FAwZn5S5MGbXoMQOHIdHItezTETxAO5bevtMApSyEhn9+CHcDsWBw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/networks": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "@ethersproject/web": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/abstract-signer": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/abstract-signer/-/abstract-signer-5.7.0.tgz",
      "integrity": "sha512-a16V8bq1/Cz+TGCkE2OPMTOUDLS3grCpdjoJCYNnVBbdYEMSgKrU0+B90s8b6H+ByYTBZN7a3g76jdIJi7UfKQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-provider": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/address": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/address/-/address-5.7.0.tgz",
      "integrity": "sha512-9wYhYt7aghVGo758POM5nqcOMaE168Q6aRLJZwUmiqSrAungkG74gSSeKEIR7ukixesdRZGPgVqme6vmxs1fkA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/rlp": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/base64": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/base64/-/base64-5.7.0.tgz",
      "integrity": "sha512-Dr8tcHt2mEbsZr/mwTPIQAf3Ai0Bks/7gTw9dSqk1mQvhW3XvRlmDJr/4n+wg1JmCl16NZue17CDh8xb/vZ0sQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/basex": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/basex/-/basex-5.7.0.tgz",
      "integrity": "sha512-ywlh43GwZLv2Voc2gQVTKBoVQ1mti3d8HK5aMxsfu/nRDnMmNqaSJ3r3n85HBByT8OpoY96SXM1FogC533T4zw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/properties": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/bignumber": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/bignumber/-/bignumber-5.7.0.tgz",
      "integrity": "sha512-n1CAdIHRWjSucQO3MC1zPSVgV/6dy/fjL9pMrPP9peL+QxEg9wOsVqwD4+818B6LUEtaXzVHQiuivzRoxPxUGw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "bn.js": "^5.2.1"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/bytes": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/bytes/-/bytes-5.7.0.tgz",
      "integrity": "sha512-nsbxwgFXWh9NyYWo+U8atvmMsSdKJprTcICAkvbBffT75qDocbuggBU0SJiVK2MuTrp0q+xvLkTnGMPK1+uA9A==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/constants": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/constants/-/constants-5.7.0.tgz",
      "integrity": "sha512-DHI+y5dBNvkpYUMiRQyxRBYBefZkJfo70VUkUAsRjcPs47muV9evftfZ0PJVCXYbAiCgght0DtcF9srFQmIgWA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/contracts": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/contracts/-/contracts-5.7.0.tgz",
      "integrity": "sha512-5GJbzEU3X+d33CdfPhcyS+z8MzsTrBGk/sc+G+59+tPa9yFkl6HQ9D6L0QMgNTA9q8dT0XKxxkyp883XsQvbbg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abi": "^5.7.0",
        "@ethersproject/abstract-provider": "^5.7.0",
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/hash": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/hash/-/hash-5.7.0.tgz",
      "integrity": "sha512-qX5WrQfnah1EFnO5zJv1v46a8HW0+E5xuBBDTwMFZLuVTx0tbU2kkx15NqdjxecrLGatQN9FGQKpb1FKdHCt+g==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/base64": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/hdnode": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/hdnode/-/hdnode-5.7.0.tgz",
      "integrity": "sha512-OmyYo9EENBPPf4ERhR7oj6uAtUAhYGqOnIS+jE5pTXvdKBS99ikzq1E7Iv0ZQZ5V36Lqx1qZLeak0Ra16qpeOg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/basex": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/pbkdf2": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/sha2": "^5.7.0",
        "@ethersproject/signing-key": "^5.7.0",
        "@ethersproject/strings": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "@ethersproject/wordlists": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/json-wallets": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/json-wallets/-/json-wallets-5.7.0.tgz",
      "integrity": "sha512-8oee5Xgu6+RKgJTkvEMl2wDgSPSAQ9MB/3JYjFV9jlKvcYHUXZC+cQp0njgmxdHkYWn8s6/IqIZYm0YWCjO/0g==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/hdnode": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/pbkdf2": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/random": "^5.7.0",
        "@ethersproject/strings": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "aes-js": "3.0.0",
        "scrypt-js": "3.0.1"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/keccak256": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/keccak256/-/keccak256-5.7.0.tgz",
      "integrity": "sha512-2UcPboeL/iW+pSg6vZ6ydF8tCnv3Iu/8tUmLLzWWGzxWKFFqOBQFLo6uLUv6BDrLgCDfN28RJ/wtByx+jZ4KBg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "js-sha3": "0.8.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/logger": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/logger/-/logger-5.7.0.tgz",
      "integrity": "sha512-0odtFdXu/XHtjQXJYA3u9G0G8btm0ND5Cu8M7i5vhEcE8/HmF4Lbdqanwyv4uQTr2tx6b7fQRmgLrsnpQlmnig==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ]
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/networks": {
      "version": "5.7.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/networks/-/networks-5.7.1.tgz",
      "integrity": "sha512-n/MufjFYv3yFcUyfhnXotyDlNdFb7onmkSy8aQERi2PjNcnWQ66xXxa3XlS8nCcA8aJKJjIIMNJTC7tu80GwpQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/pbkdf2": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/pbkdf2/-/pbkdf2-5.7.0.tgz",
      "integrity": "sha512-oR/dBRZR6GTyaofd86DehG72hY6NpAjhabkhxgr3X2FpJtJuodEl2auADWBZfhDHgVCbu3/H/Ocq2uC6dpNjjw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/sha2": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/properties": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/properties/-/properties-5.7.0.tgz",
      "integrity": "sha512-J87jy8suntrAkIZtecpxEPxY//szqr1mlBaYlQ0r4RCaiD2hjheqF9s1LVE8vVuJCXisjIP+JgtK/Do54ej4Sw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/providers": {
      "version": "5.7.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/providers/-/providers-5.7.2.tgz",
      "integrity": "sha512-g34EWZ1WWAVgr4aptGlVBF8mhl3VWjv+8hoAnzStu8Ah22VHBsuGzP17eb6xDVRzw895G4W7vvx60lFFur/1Rg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-provider": "^5.7.0",
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/base64": "^5.7.0",
        "@ethersproject/basex": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/hash": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/networks": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/random": "^5.7.0",
        "@ethersproject/rlp": "^5.7.0",
        "@ethersproject/sha2": "^5.7.0",
        "@ethersproject/strings": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "@ethersproject/web": "^5.7.0",
        "bech32": "1.1.4",
        "ws": "7.4.6"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/random": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/random/-/random-5.7.0.tgz",
      "integrity": "sha512-19WjScqRA8IIeWclFme75VMXSBvi4e6InrUNuaR4s5pTF2qNhcGdCUwdxUVGtDDqC00sDLCO93jPQoDUH4HVmQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/rlp": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/rlp/-/rlp-5.7.0.tgz",
      "integrity": "sha512-rBxzX2vK8mVF7b0Tol44t5Tb8gomOHkj5guL+HhzQ1yBh/ydjGnpw6at+X6Iw0Kp3OzzzkcKp8N9r0W4kYSs9w==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/sha2": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/sha2/-/sha2-5.7.0.tgz",
      "integrity": "sha512-gKlH42riwb3KYp0reLsFTokByAKoJdgFCwI+CCiX/k+Jm2mbNs6oOaCjYQSlI1+XBVejwH2KrmCbMAT/GnRDQw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "hash.js": "1.1.7"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/signing-key": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/signing-key/-/signing-key-5.7.0.tgz",
      "integrity": "sha512-MZdy2nL3wO0u7gkB4nA/pEf8lu1TlFswPNmy8AiYkfKTdO6eXBJyUdmHO/ehm/htHw9K/qF8ujnTyUAD+Ry54Q==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "bn.js": "^5.2.1",
        "elliptic": "6.5.4",
        "hash.js": "1.1.7"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/solidity": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/solidity/-/solidity-5.7.0.tgz",
      "integrity": "sha512-HmabMd2Dt/raavyaGukF4XxizWKhKQ24DoLtdNbBmNKUOPqwjsKQSdV9GQtj9CBEea9DlzETlVER1gYeXXBGaA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/sha2": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/strings": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/strings/-/strings-5.7.0.tgz",
      "integrity": "sha512-/9nu+lj0YswRNSH0NXYqrh8775XNyEdUQAuf3f+SmOrnVewcJ5SBNAjF7lpgehKi4abvNNXyf+HX86czCdJ8Mg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/transactions": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/transactions/-/transactions-5.7.0.tgz",
      "integrity": "sha512-kmcNicCp1lp8qanMTC3RIikGgoJ80ztTyvtsFvCYpSCfkjhD0jZ2LOrnbcuxuToLIUYYf+4XwD1rP+B/erDIhQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/rlp": "^5.7.0",
        "@ethersproject/signing-key": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/units": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/units/-/units-5.7.0.tgz",
      "integrity": "sha512-pD3xLMy3SJu9kG5xDGI7+xhTEmGXlEqXU4OfNapmfnxLVY4EMSSRp7j1k7eezutBPH7RBN/7QPnwR7hzNlEFeg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/wallet": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/wallet/-/wallet-5.7.0.tgz",
      "integrity": "sha512-MhmXlJXEJFBFVKrDLB4ZdDzxcBxQ3rLyCkhNqVu3CDYvR97E+8r01UgrI+TI99Le+aYm/in/0vp86guJuM7FCA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-provider": "^5.7.0",
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/hash": "^5.7.0",
        "@ethersproject/hdnode": "^5.7.0",
        "@ethersproject/json-wallets": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/random": "^5.7.0",
        "@ethersproject/signing-key": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "@ethersproject/wordlists": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/web": {
      "version": "5.7.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/web/-/web-5.7.1.tgz",
      "integrity": "sha512-Gueu8lSvyjBWL4cYsWsjh6MtMwM0+H4HvqFPZfB6dV8ctbP9zFAO73VG1cMWae0FLPCtz0peKPpZY8/ugJJX2w==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/base64": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/@ethersproject/wordlists": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/wordlists/-/wordlists-5.7.0.tgz",
      "integrity": "sha512-S2TFNJNfHWVHNE6cNDjbVlZ6MgE17MIxMbMg2zv3wn+3XSJGosL1m9ZVv3GXCf/2ymSsQ+hRI5IzoMJTG6aoVA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/hash": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/sdk/node_modules/ethers": {
      "version": "5.7.2",
      "resolved": "https://registry.npmjs.org/ethers/-/ethers-5.7.2.tgz",
      "integrity": "sha512-wswUsmWo1aOK8rR7DIKiWSw9DbLWe6x98Jrn8wcTflTVvaXhAMaB5zGAXy0GYQEQp9iO1iSHWVyARQm11zUtyg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abi": "5.7.0",
        "@ethersproject/abstract-provider": "5.7.0",
        "@ethersproject/abstract-signer": "5.7.0",
        "@ethersproject/address": "5.7.0",
        "@ethersproject/base64": "5.7.0",
        "@ethersproject/basex": "5.7.0",
        "@ethersproject/bignumber": "5.7.0",
        "@ethersproject/bytes": "5.7.0",
        "@ethersproject/constants": "5.7.0",
        "@ethersproject/contracts": "5.7.0",
        "@ethersproject/hash": "5.7.0",
        "@ethersproject/hdnode": "5.7.0",
        "@ethersproject/json-wallets": "5.7.0",
        "@ethersproject/keccak256": "5.7.0",
        "@ethersproject/logger": "5.7.0",
        "@ethersproject/networks": "5.7.1",
        "@ethersproject/pbkdf2": "5.7.0",
        "@ethersproject/properties": "5.7.0",
        "@ethersproject/providers": "5.7.2",
        "@ethersproject/random": "5.7.0",
        "@ethersproject/rlp": "5.7.0",
        "@ethersproject/sha2": "5.7.0",
        "@ethersproject/signing-key": "5.7.0",
        "@ethersproject/solidity": "5.7.0",
        "@ethersproject/strings": "5.7.0",
        "@ethersproject/transactions": "5.7.0",
        "@ethersproject/units": "5.7.0",
        "@ethersproject/wallet": "5.7.0",
        "@ethersproject/web": "5.7.1",
        "@ethersproject/wordlists": "5.7.0"
      }
    },
    "node_modules/@lifi/types": {
      "version": "1.17.0",
      "resolved": "https://registry.npmjs.org/@lifi/types/-/types-1.17.0.tgz",
      "integrity": "sha512-TpDbBlFfQ09kWyuwqhQ51AfFLgyslYLB9p7Swa2PPL8r40i2SpYTmaEmHyTmenZAGRVm8XLNfGBJR3Bygn4h9A==",
      "hasInstallScript": true,
      "dependencies": {
        "ethers": "^5.7.2"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/abi": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/abi/-/abi-5.7.0.tgz",
      "integrity": "sha512-351ktp42TiRcYB3H1OP8yajPeAQstMW/yCFokj/AthP9bLHzQFPlOrxOcwYEDkUAICmOHljvN4K39OMTMUa9RA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/hash": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/abstract-provider": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/abstract-provider/-/abstract-provider-5.7.0.tgz",
      "integrity": "sha512-R41c9UkchKCpAqStMYUpdunjo3pkEvZC3FAwZn5S5MGbXoMQOHIdHItezTETxAO5bevtMApSyEhn9+CHcDsWBw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/networks": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "@ethersproject/web": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/abstract-signer": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/abstract-signer/-/abstract-signer-5.7.0.tgz",
      "integrity": "sha512-a16V8bq1/Cz+TGCkE2OPMTOUDLS3grCpdjoJCYNnVBbdYEMSgKrU0+B90s8b6H+ByYTBZN7a3g76jdIJi7UfKQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-provider": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/address": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/address/-/address-5.7.0.tgz",
      "integrity": "sha512-9wYhYt7aghVGo758POM5nqcOMaE168Q6aRLJZwUmiqSrAungkG74gSSeKEIR7ukixesdRZGPgVqme6vmxs1fkA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/rlp": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/base64": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/base64/-/base64-5.7.0.tgz",
      "integrity": "sha512-Dr8tcHt2mEbsZr/mwTPIQAf3Ai0Bks/7gTw9dSqk1mQvhW3XvRlmDJr/4n+wg1JmCl16NZue17CDh8xb/vZ0sQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/basex": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/basex/-/basex-5.7.0.tgz",
      "integrity": "sha512-ywlh43GwZLv2Voc2gQVTKBoVQ1mti3d8HK5aMxsfu/nRDnMmNqaSJ3r3n85HBByT8OpoY96SXM1FogC533T4zw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/properties": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/bignumber": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/bignumber/-/bignumber-5.7.0.tgz",
      "integrity": "sha512-n1CAdIHRWjSucQO3MC1zPSVgV/6dy/fjL9pMrPP9peL+QxEg9wOsVqwD4+818B6LUEtaXzVHQiuivzRoxPxUGw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "bn.js": "^5.2.1"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/bytes": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/bytes/-/bytes-5.7.0.tgz",
      "integrity": "sha512-nsbxwgFXWh9NyYWo+U8atvmMsSdKJprTcICAkvbBffT75qDocbuggBU0SJiVK2MuTrp0q+xvLkTnGMPK1+uA9A==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/constants": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/constants/-/constants-5.7.0.tgz",
      "integrity": "sha512-DHI+y5dBNvkpYUMiRQyxRBYBefZkJfo70VUkUAsRjcPs47muV9evftfZ0PJVCXYbAiCgght0DtcF9srFQmIgWA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/contracts": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/contracts/-/contracts-5.7.0.tgz",
      "integrity": "sha512-5GJbzEU3X+d33CdfPhcyS+z8MzsTrBGk/sc+G+59+tPa9yFkl6HQ9D6L0QMgNTA9q8dT0XKxxkyp883XsQvbbg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abi": "^5.7.0",
        "@ethersproject/abstract-provider": "^5.7.0",
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/hash": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/hash/-/hash-5.7.0.tgz",
      "integrity": "sha512-qX5WrQfnah1EFnO5zJv1v46a8HW0+E5xuBBDTwMFZLuVTx0tbU2kkx15NqdjxecrLGatQN9FGQKpb1FKdHCt+g==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/base64": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/hdnode": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/hdnode/-/hdnode-5.7.0.tgz",
      "integrity": "sha512-OmyYo9EENBPPf4ERhR7oj6uAtUAhYGqOnIS+jE5pTXvdKBS99ikzq1E7Iv0ZQZ5V36Lqx1qZLeak0Ra16qpeOg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/basex": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/pbkdf2": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/sha2": "^5.7.0",
        "@ethersproject/signing-key": "^5.7.0",
        "@ethersproject/strings": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "@ethersproject/wordlists": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/json-wallets": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/json-wallets/-/json-wallets-5.7.0.tgz",
      "integrity": "sha512-8oee5Xgu6+RKgJTkvEMl2wDgSPSAQ9MB/3JYjFV9jlKvcYHUXZC+cQp0njgmxdHkYWn8s6/IqIZYm0YWCjO/0g==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/hdnode": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/pbkdf2": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/random": "^5.7.0",
        "@ethersproject/strings": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "aes-js": "3.0.0",
        "scrypt-js": "3.0.1"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/keccak256": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/keccak256/-/keccak256-5.7.0.tgz",
      "integrity": "sha512-2UcPboeL/iW+pSg6vZ6ydF8tCnv3Iu/8tUmLLzWWGzxWKFFqOBQFLo6uLUv6BDrLgCDfN28RJ/wtByx+jZ4KBg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "js-sha3": "0.8.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/logger": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/logger/-/logger-5.7.0.tgz",
      "integrity": "sha512-0odtFdXu/XHtjQXJYA3u9G0G8btm0ND5Cu8M7i5vhEcE8/HmF4Lbdqanwyv4uQTr2tx6b7fQRmgLrsnpQlmnig==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ]
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/networks": {
      "version": "5.7.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/networks/-/networks-5.7.1.tgz",
      "integrity": "sha512-n/MufjFYv3yFcUyfhnXotyDlNdFb7onmkSy8aQERi2PjNcnWQ66xXxa3XlS8nCcA8aJKJjIIMNJTC7tu80GwpQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/pbkdf2": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/pbkdf2/-/pbkdf2-5.7.0.tgz",
      "integrity": "sha512-oR/dBRZR6GTyaofd86DehG72hY6NpAjhabkhxgr3X2FpJtJuodEl2auADWBZfhDHgVCbu3/H/Ocq2uC6dpNjjw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/sha2": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/properties": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/properties/-/properties-5.7.0.tgz",
      "integrity": "sha512-J87jy8suntrAkIZtecpxEPxY//szqr1mlBaYlQ0r4RCaiD2hjheqF9s1LVE8vVuJCXisjIP+JgtK/Do54ej4Sw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/providers": {
      "version": "5.7.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/providers/-/providers-5.7.2.tgz",
      "integrity": "sha512-g34EWZ1WWAVgr4aptGlVBF8mhl3VWjv+8hoAnzStu8Ah22VHBsuGzP17eb6xDVRzw895G4W7vvx60lFFur/1Rg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-provider": "^5.7.0",
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/base64": "^5.7.0",
        "@ethersproject/basex": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/hash": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/networks": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/random": "^5.7.0",
        "@ethersproject/rlp": "^5.7.0",
        "@ethersproject/sha2": "^5.7.0",
        "@ethersproject/strings": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "@ethersproject/web": "^5.7.0",
        "bech32": "1.1.4",
        "ws": "7.4.6"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/random": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/random/-/random-5.7.0.tgz",
      "integrity": "sha512-19WjScqRA8IIeWclFme75VMXSBvi4e6InrUNuaR4s5pTF2qNhcGdCUwdxUVGtDDqC00sDLCO93jPQoDUH4HVmQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/rlp": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/rlp/-/rlp-5.7.0.tgz",
      "integrity": "sha512-rBxzX2vK8mVF7b0Tol44t5Tb8gomOHkj5guL+HhzQ1yBh/ydjGnpw6at+X6Iw0Kp3OzzzkcKp8N9r0W4kYSs9w==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/sha2": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/sha2/-/sha2-5.7.0.tgz",
      "integrity": "sha512-gKlH42riwb3KYp0reLsFTokByAKoJdgFCwI+CCiX/k+Jm2mbNs6oOaCjYQSlI1+XBVejwH2KrmCbMAT/GnRDQw==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "hash.js": "1.1.7"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/signing-key": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/signing-key/-/signing-key-5.7.0.tgz",
      "integrity": "sha512-MZdy2nL3wO0u7gkB4nA/pEf8lu1TlFswPNmy8AiYkfKTdO6eXBJyUdmHO/ehm/htHw9K/qF8ujnTyUAD+Ry54Q==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "bn.js": "^5.2.1",
        "elliptic": "6.5.4",
        "hash.js": "1.1.7"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/solidity": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/solidity/-/solidity-5.7.0.tgz",
      "integrity": "sha512-HmabMd2Dt/raavyaGukF4XxizWKhKQ24DoLtdNbBmNKUOPqwjsKQSdV9GQtj9CBEea9DlzETlVER1gYeXXBGaA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/sha2": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/strings": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/strings/-/strings-5.7.0.tgz",
      "integrity": "sha512-/9nu+lj0YswRNSH0NXYqrh8775XNyEdUQAuf3f+SmOrnVewcJ5SBNAjF7lpgehKi4abvNNXyf+HX86czCdJ8Mg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/transactions": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/transactions/-/transactions-5.7.0.tgz",
      "integrity": "sha512-kmcNicCp1lp8qanMTC3RIikGgoJ80ztTyvtsFvCYpSCfkjhD0jZ2LOrnbcuxuToLIUYYf+4XwD1rP+B/erDIhQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/rlp": "^5.7.0",
        "@ethersproject/signing-key": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/units": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/units/-/units-5.7.0.tgz",
      "integrity": "sha512-pD3xLMy3SJu9kG5xDGI7+xhTEmGXlEqXU4OfNapmfnxLVY4EMSSRp7j1k7eezutBPH7RBN/7QPnwR7hzNlEFeg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/constants": "^5.7.0",
        "@ethersproject/logger": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/wallet": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/wallet/-/wallet-5.7.0.tgz",
      "integrity": "sha512-MhmXlJXEJFBFVKrDLB4ZdDzxcBxQ3rLyCkhNqVu3CDYvR97E+8r01UgrI+TI99Le+aYm/in/0vp86guJuM7FCA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abstract-provider": "^5.7.0",
        "@ethersproject/abstract-signer": "^5.7.0",
        "@ethersproject/address": "^5.7.0",
        "@ethersproject/bignumber": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/hash": "^5.7.0",
        "@ethersproject/hdnode": "^5.7.0",
        "@ethersproject/json-wallets": "^5.7.0",
        "@ethersproject/keccak256": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/random": "^5.7.0",
        "@ethersproject/signing-key": "^5.7.0",
        "@ethersproject/transactions": "^5.7.0",
        "@ethersproject/wordlists": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/web": {
      "version": "5.7.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/web/-/web-5.7.1.tgz",
      "integrity": "sha512-Gueu8lSvyjBWL4cYsWsjh6MtMwM0+H4HvqFPZfB6dV8ctbP9zFAO73VG1cMWae0FLPCtz0peKPpZY8/ugJJX2w==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/base64": "^5.7.0",
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/@ethersproject/wordlists": {
      "version": "5.7.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/wordlists/-/wordlists-5.7.0.tgz",
      "integrity": "sha512-S2TFNJNfHWVHNE6cNDjbVlZ6MgE17MIxMbMg2zv3wn+3XSJGosL1m9ZVv3GXCf/2ymSsQ+hRI5IzoMJTG6aoVA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/bytes": "^5.7.0",
        "@ethersproject/hash": "^5.7.0",
        "@ethersproject/logger": "^5.7.0",
        "@ethersproject/properties": "^5.7.0",
        "@ethersproject/strings": "^5.7.0"
      }
    },
    "node_modules/@lifi/types/node_modules/ethers": {
      "version": "5.7.2",
      "resolved": "https://registry.npmjs.org/ethers/-/ethers-5.7.2.tgz",
      "integrity": "sha512-wswUsmWo1aOK8rR7DIKiWSw9DbLWe6x98Jrn8wcTflTVvaXhAMaB5zGAXy0GYQEQp9iO1iSHWVyARQm11zUtyg==",
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abi": "5.7.0",
        "@ethersproject/abstract-provider": "5.7.0",
        "@ethersproject/abstract-signer": "5.7.0",
        "@ethersproject/address": "5.7.0",
        "@ethersproject/base64": "5.7.0",
        "@ethersproject/basex": "5.7.0",
        "@ethersproject/bignumber": "5.7.0",
        "@ethersproject/bytes": "5.7.0",
        "@ethersproject/constants": "5.7.0",
        "@ethersproject/contracts": "5.7.0",
        "@ethersproject/hash": "5.7.0",
        "@ethersproject/hdnode": "5.7.0",
        "@ethersproject/json-wallets": "5.7.0",
        "@ethersproject/keccak256": "5.7.0",
        "@ethersproject/logger": "5.7.0",
        "@ethersproject/networks": "5.7.1",
        "@ethersproject/pbkdf2": "5.7.0",
        "@ethersproject/properties": "5.7.0",
        "@ethersproject/providers": "5.7.2",
        "@ethersproject/random": "5.7.0",
        "@ethersproject/rlp": "5.7.0",
        "@ethersproject/sha2": "5.7.0",
        "@ethersproject/signing-key": "5.7.0",
        "@ethersproject/solidity": "5.7.0",
        "@ethersproject/strings": "5.7.0",
        "@ethersproject/transactions": "5.7.0",
        "@ethersproject/units": "5.7.0",
        "@ethersproject/wallet": "5.7.0",
        "@ethersproject/web": "5.7.1",
        "@ethersproject/wordlists": "5.7.0"
      }
    },
    "node_modules/@nerdwallet/apollo-cache-policies": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/@nerdwallet/apollo-cache-policies/-/apollo-cache-policies-1.2.1.tgz",
      "integrity": "sha512-B9ffnsNadLJ4Ge6l92lwVDLgzSmen8MqZhZenK4ocQQ7x1vctOdVSffXtmJUCYb98/KYHNQRskj0xgnS1+dlmw==",
      "dependencies": {
        "@types/graphql": "^14.5.0",
        "@types/lodash": "^4.14.168",
        "@types/uuid": "^7.0.4",
        "graphql": "^15.5.0",
        "lodash": "^4.17.20",
        "typescript": "^4.3.2",
        "uuid": "^7.0.3"
      },
      "peerDependencies": {
        "@apollo/client": "^3.3.0"
      }
    },
    "node_modules/@nerdwallet/apollo-cache-policies/node_modules/@types/uuid": {
      "version": "7.0.4",
      "resolved": "https://registry.npmjs.org/@types/uuid/-/uuid-7.0.4.tgz",
      "integrity": "sha512-WGZCqBZZ0mXN2RxvLHL6/7RCu+OWs28jgQMP04LWfpyJlQUMTR6YU9CNJAKDgbw+EV/u687INXuLUc7FuML/4g=="
    },
    "node_modules/@nerdwallet/apollo-cache-policies/node_modules/typescript": {
      "version": "4.3.4",
      "resolved": "https://registry.npmjs.org/typescript/-/typescript-4.3.4.tgz",
      "integrity": "sha512-uauPG7XZn9F/mo+7MrsRjyvbxFpzemRjKEZXS4AK83oP2KKOJPvb+9cO/gmnv8arWZvhnjVOXz7B49m1l0e9Ew==",
      "bin": {
        "tsc": "bin/tsc",
        "tsserver": "bin/tsserver"
      },
      "engines": {
        "node": ">=4.2.0"
      }
    },
    "node_modules/@nerdwallet/apollo-cache-policies/node_modules/uuid": {
      "version": "7.0.3",
      "resolved": "https://registry.npmjs.org/uuid/-/uuid-7.0.3.tgz",
      "integrity": "sha512-DPSke0pXhTZgoF/d+WSt2QaKMCFSfx7QegxEWT+JOuHF5aWrKEn0G+ztjuJg/gG8/ItK+rbPCD/yNv8yyih6Cg==",
      "bin": {
        "uuid": "dist/bin/uuid"
      }
    },
    "node_modules/@protobufjs/aspromise": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/@protobufjs/aspromise/-/aspromise-1.1.2.tgz",
      "integrity": "sha1-m4sMxmPWaafY9vXQiToU00jzD78=",
      "dev": true
    },
    "node_modules/@protobufjs/base64": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/@protobufjs/base64/-/base64-1.1.2.tgz",
      "integrity": "sha512-AZkcAA5vnN/v4PDqKyMR5lx7hZttPDgClv83E//FMNhR2TMcLUhfRUBHCmSl0oi9zMgDDqRUJkSxO3wm85+XLg==",
      "dev": true
    },
    "node_modules/@protobufjs/codegen": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/@protobufjs/codegen/-/codegen-2.0.4.tgz",
      "integrity": "sha512-YyFaikqM5sH0ziFZCN3xDC7zeGaB/d0IUb9CATugHWbd1FRFwWwt4ld4OYMPWu5a3Xe01mGAULCdqhMlPl29Jg==",
      "dev": true
    },
    "node_modules/@protobufjs/eventemitter": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/eventemitter/-/eventemitter-1.1.0.tgz",
      "integrity": "sha1-NVy8mLr61ZePntCV85diHx0Ga3A=",
      "dev": true
    },
    "node_modules/@protobufjs/fetch": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/fetch/-/fetch-1.1.0.tgz",
      "integrity": "sha1-upn7WYYUr2VwDBYZ/wbUVLDYTEU=",
      "dev": true,
      "dependencies": {
        "@protobufjs/aspromise": "^1.1.1",
        "@protobufjs/inquire": "^1.1.0"
      }
    },
    "node_modules/@protobufjs/float": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/@protobufjs/float/-/float-1.0.2.tgz",
      "integrity": "sha1-Xp4avctz/Ap8uLKR33jIy9l7h9E=",
      "dev": true
    },
    "node_modules/@protobufjs/inquire": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/inquire/-/inquire-1.1.0.tgz",
      "integrity": "sha1-/yAOPnzyQp4tyvwRQIKOjMY48Ik=",
      "dev": true
    },
    "node_modules/@protobufjs/path": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/@protobufjs/path/-/path-1.1.2.tgz",
      "integrity": "sha1-bMKyDFya1q0NzP0hynZz2Nf79o0=",
      "dev": true
    },
    "node_modules/@protobufjs/pool": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/pool/-/pool-1.1.0.tgz",
      "integrity": "sha1-Cf0V8tbTq/qbZbw2ZQbWrXhG/1Q=",
      "dev": true
    },
    "node_modules/@protobufjs/utf8": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/utf8/-/utf8-1.1.0.tgz",
      "integrity": "sha1-p3c2C1s5oaLlEG+OhY8v0tBgxXA=",
      "dev": true
    },
    "node_modules/@sinonjs/commons": {
      "version": "1.8.3",
      "resolved": "https://registry.npmjs.org/@sinonjs/commons/-/commons-1.8.3.tgz",
      "integrity": "sha512-xkNcLAn/wZaX14RPlwizcKicDk9G3F8m2nU3L7Ukm5zBgTwiT0wsoFAHx9Jq56fJA1z/7uKGtCRu16sOUCLIHQ==",
      "dev": true,
      "dependencies": {
        "type-detect": "4.0.8"
      }
    },
    "node_modules/@teppeis/multimaps": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@teppeis/multimaps/-/multimaps-1.1.0.tgz",
      "integrity": "sha512-YgANgfYU7LqgaLkGPWSTiwu2qcuhj0IOvj+kRwDFjAVbiEXT7ZQLPaFfmrAAN/Fa+tvwy1aYFd0RdT7lMO1Msw==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/@types/babel__core": {
      "version": "7.1.14",
      "resolved": "https://registry.npmjs.org/@types/babel__core/-/babel__core-7.1.14.tgz",
      "integrity": "sha512-zGZJzzBUVDo/eV6KgbE0f0ZI7dInEYvo12Rb70uNQDshC3SkRMb67ja0GgRHZgAX3Za6rhaWlvbDO8rrGyAb1g==",
      "dev": true,
      "dependencies": {
        "@babel/parser": "^7.1.0",
        "@babel/types": "^7.0.0",
        "@types/babel__generator": "*",
        "@types/babel__template": "*",
        "@types/babel__traverse": "*"
      }
    },
    "node_modules/@types/babel__generator": {
      "version": "7.6.2",
      "resolved": "https://registry.npmjs.org/@types/babel__generator/-/babel__generator-7.6.2.tgz",
      "integrity": "sha512-MdSJnBjl+bdwkLskZ3NGFp9YcXGx5ggLpQQPqtgakVhsWK0hTtNYhjpZLlWQTviGTvF8at+Bvli3jV7faPdgeQ==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.0.0"
      }
    },
    "node_modules/@types/babel__template": {
      "version": "7.4.0",
      "resolved": "https://registry.npmjs.org/@types/babel__template/-/babel__template-7.4.0.tgz",
      "integrity": "sha512-NTPErx4/FiPCGScH7foPyr+/1Dkzkni+rHiYHHoTjvwou7AQzJkNeD60A9CXRy+ZEN2B1bggmkTMCDb+Mv5k+A==",
      "dev": true,
      "dependencies": {
        "@babel/parser": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "node_modules/@types/babel__traverse": {
      "version": "7.11.1",
      "resolved": "https://registry.npmjs.org/@types/babel__traverse/-/babel__traverse-7.11.1.tgz",
      "integrity": "sha512-Vs0hm0vPahPMYi9tDjtP66llufgO3ST16WXaSTtDGEl9cewAl3AibmxWw6TINOqHPT9z0uABKAYjT9jNSg4npw==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.3.0"
      }
    },
    "node_modules/@types/eslint-visitor-keys": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/@types/eslint-visitor-keys/-/eslint-visitor-keys-1.0.0.tgz",
      "integrity": "sha512-OCutwjDZ4aFS6PB1UZ988C4YgwlBHJd6wCeQqaLdmadZ/7e+w79+hbMUFC1QXDNCmdyoRfAFdm0RypzwR+Qpag==",
      "dev": true
    },
    "node_modules/@types/graceful-fs": {
      "version": "4.1.5",
      "resolved": "https://registry.npmjs.org/@types/graceful-fs/-/graceful-fs-4.1.5.tgz",
      "integrity": "sha512-anKkLmZZ+xm4p8JWBf4hElkM4XR+EZeA2M9BAkkTldmcyDY4mbdIJnRghDJH3Ov5ooY7/UAoENtmdMSkaAd7Cw==",
      "dev": true,
      "dependencies": {
        "@types/node": "*"
      }
    },
    "node_modules/@types/graphql": {
      "version": "14.5.0",
      "resolved": "https://registry.npmjs.org/@types/graphql/-/graphql-14.5.0.tgz",
      "integrity": "sha512-MOkzsEp1Jk5bXuAsHsUi6BVv0zCO+7/2PTiZMXWDSsMXvNU6w/PLMQT2vHn8hy2i0JqojPz1Sz6rsFjHtsU0lA==",
      "deprecated": "This is a stub types definition. graphql provides its own type definitions, so you do not need this installed.",
      "dependencies": {
        "graphql": "*"
      }
    },
    "node_modules/@types/istanbul-lib-coverage": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/@types/istanbul-lib-coverage/-/istanbul-lib-coverage-2.0.3.tgz",
      "integrity": "sha512-sz7iLqvVUg1gIedBOvlkxPlc8/uVzyS5OwGz1cKjXzkl3FpL3al0crU8YGU1WoHkxn0Wxbw5tyi6hvzJKNzFsw==",
      "dev": true
    },
    "node_modules/@types/istanbul-lib-report": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/@types/istanbul-lib-report/-/istanbul-lib-report-3.0.0.tgz",
      "integrity": "sha512-plGgXAPfVKFoYfa9NpYDAkseG+g6Jr294RqeqcqDixSbU34MZVJRi/P+7Y8GDpzkEwLaGZZOpKIEmeVZNtKsrg==",
      "dev": true,
      "dependencies": {
        "@types/istanbul-lib-coverage": "*"
      }
    },
    "node_modules/@types/istanbul-reports": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/@types/istanbul-reports/-/istanbul-reports-1.1.2.tgz",
      "integrity": "sha512-P/W9yOX/3oPZSpaYOCQzGqgCQRXn0FFO/V8bWrCQs+wLmvVVxk6CRBXALEvNs9OHIatlnlFokfhuDo2ug01ciw==",
      "dev": true,
      "dependencies": {
        "@types/istanbul-lib-coverage": "*",
        "@types/istanbul-lib-report": "*"
      }
    },
    "node_modules/@types/jest": {
      "version": "25.2.3",
      "resolved": "https://registry.npmjs.org/@types/jest/-/jest-25.2.3.tgz",
      "integrity": "sha512-JXc1nK/tXHiDhV55dvfzqtmP4S3sy3T3ouV2tkViZgxY/zeUkcpQcQPGRlgF4KmWzWW5oiWYSZwtCB+2RsE4Fw==",
      "dev": true,
      "dependencies": {
        "jest-diff": "^25.2.1",
        "pretty-format": "^25.2.1"
      }
    },
    "node_modules/@types/json-schema": {
      "version": "7.0.7",
      "resolved": "https://registry.npmjs.org/@types/json-schema/-/json-schema-7.0.7.tgz",
      "integrity": "sha512-cxWFQVseBm6O9Gbw1IWb8r6OS4OhSt3hPZLkFApLjM8TEXROBuQGLAH2i2gZpcXdLBIrpXuTDhH7Vbm1iXmNGA==",
      "dev": true
    },
    "node_modules/@types/lodash": {
      "version": "4.14.170",
      "resolved": "https://registry.npmjs.org/@types/lodash/-/lodash-4.14.170.tgz",
      "integrity": "sha512-bpcvu/MKHHeYX+qeEN8GE7DIravODWdACVA1ctevD8CN24RhPZIKMn9ntfAsrvLfSX3cR5RrBKAbYm9bGs0A+Q=="
    },
    "node_modules/@types/long": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/@types/long/-/long-4.0.1.tgz",
      "integrity": "sha512-5tXH6Bx/kNGd3MgffdmP4dy2Z+G4eaXw0SE81Tq3BNadtnMR5/ySMzX4SLEzHJzSmPNn4HIdpQsBvXMUykr58w==",
      "dev": true
    },
    "node_modules/@types/node": {
      "version": "13.13.9",
      "resolved": "https://registry.npmjs.org/@types/node/-/node-13.13.9.tgz",
      "integrity": "sha512-EPZBIGed5gNnfWCiwEIwTE2Jdg4813odnG8iNPMQGrqVxrI+wL68SPtPeCX+ZxGBaA6pKAVc6jaKgP/Q0QzfdQ==",
      "dev": true
    },
    "node_modules/@types/normalize-package-data": {
      "version": "2.4.0",
      "resolved": "https://registry.npmjs.org/@types/normalize-package-data/-/normalize-package-data-2.4.0.tgz",
      "integrity": "sha512-f5j5b/Gf71L+dbqxIpQ4Z2WlmI/mPJ0fOkGGmFgtb6sAu97EPczzbS3/tJKxmcYDj55OX6ssqwDAWOHIYDRDGA==",
      "dev": true
    },
    "node_modules/@types/prettier": {
      "version": "1.19.1",
      "resolved": "https://registry.npmjs.org/@types/prettier/-/prettier-1.19.1.tgz",
      "integrity": "sha512-5qOlnZscTn4xxM5MeGXAMOsIOIKIbh9e85zJWfBRVPlRMEVawzoPhINYbRGkBZCI8LxvBe7tJCdWiarA99OZfQ==",
      "dev": true
    },
    "node_modules/@types/stack-utils": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/@types/stack-utils/-/stack-utils-1.0.1.tgz",
      "integrity": "sha512-l42BggppR6zLmpfU6fq9HEa2oGPEI8yrSPL3GITjfRInppYFahObbIQOQK3UGxEnyQpltZLaPe75046NOZQikw==",
      "dev": true
    },
    "node_modules/@types/uuid": {
      "version": "8.3.0",
      "resolved": "https://registry.npmjs.org/@types/uuid/-/uuid-8.3.0.tgz",
      "integrity": "sha512-eQ9qFW/fhfGJF8WKHGEHZEyVWfZxrT+6CLIJGBcZPfxUh/+BnEj+UCGYMlr9qZuX/2AltsvwrGqp0LhEW8D0zQ==",
      "dev": true
    },
    "node_modules/@types/validator": {
      "version": "13.7.10",
      "resolved": "https://registry.npmjs.org/@types/validator/-/validator-13.7.10.tgz",
      "integrity": "sha512-t1yxFAR2n0+VO6hd/FJ9F2uezAZVWHLmpmlJzm1eX03+H7+HsuTAp7L8QJs+2pQCfWkP1+EXsGK9Z9v7o/qPVQ=="
    },
    "node_modules/@types/ws": {
      "version": "7.2.4",
      "resolved": "https://registry.npmjs.org/@types/ws/-/ws-7.2.4.tgz",
      "integrity": "sha512-9S6Ask71vujkVyeEXKxjBSUV8ZUB0mjL5la4IncBoheu04bDaYyUKErh1BQcY9+WzOUOiKqz/OnpJHYckbMfNg==",
      "dev": true,
      "dependencies": {
        "@types/node": "*"
      }
    },
    "node_modules/@types/yargs": {
      "version": "15.0.13",
      "resolved": "https://registry.npmjs.org/@types/yargs/-/yargs-15.0.13.tgz",
      "integrity": "sha512-kQ5JNTrbDv3Rp5X2n/iUu37IJBDU2gsZ5R/g1/KHOOEc5IKfUFjXT6DENPGduh08I/pamwtEq4oul7gUqKTQDQ==",
      "dev": true,
      "dependencies": {
        "@types/yargs-parser": "*"
      }
    },
    "node_modules/@types/yargs-parser": {
      "version": "20.2.0",
      "resolved": "https://registry.npmjs.org/@types/yargs-parser/-/yargs-parser-20.2.0.tgz",
      "integrity": "sha512-37RSHht+gzzgYeobbG+KWryeAW8J33Nhr69cjTqSYymXVZEN9NbRYWoYlRtDhHKPVT1FyNKwaTPC1NynKZpzRA==",
      "dev": true
    },
    "node_modules/@types/zen-observable": {
      "version": "0.8.3",
      "resolved": "https://registry.npmjs.org/@types/zen-observable/-/zen-observable-0.8.3.tgz",
      "integrity": "sha512-fbF6oTd4sGGy0xjHPKAt+eS2CrxJ3+6gQ3FGcBoIJR2TLAyCkCyI8JqZNy+FeON0AhVgNJoUumVoZQjBFUqHkw=="
    },
    "node_modules/@typescript-eslint/eslint-plugin": {
      "version": "2.34.0",
      "resolved": "https://registry.npmjs.org/@typescript-eslint/eslint-plugin/-/eslint-plugin-2.34.0.tgz",
      "integrity": "sha512-4zY3Z88rEE99+CNvTbXSyovv2z9PNOVffTWD2W8QF5s2prBQtwN2zadqERcrHpcR7O/+KMI3fcTAmUUhK/iQcQ==",
      "dev": true,
      "dependencies": {
        "@typescript-eslint/experimental-utils": "2.34.0",
        "functional-red-black-tree": "^1.0.1",
        "regexpp": "^3.0.0",
        "tsutils": "^3.17.1"
      },
      "engines": {
        "node": "^8.10.0 || ^10.13.0 || >=11.10.1"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/typescript-eslint"
      },
      "peerDependencies": {
        "@typescript-eslint/parser": "^2.0.0",
        "eslint": "^5.0.0 || ^6.0.0"
      },
      "peerDependenciesMeta": {
        "typescript": {
          "optional": true
        }
      }
    },
    "node_modules/@typescript-eslint/experimental-utils": {
      "version": "2.34.0",
      "resolved": "https://registry.npmjs.org/@typescript-eslint/experimental-utils/-/experimental-utils-2.34.0.tgz",
      "integrity": "sha512-eS6FTkq+wuMJ+sgtuNTtcqavWXqsflWcfBnlYhg/nS4aZ1leewkXGbvBhaapn1q6qf4M71bsR1tez5JTRMuqwA==",
      "dev": true,
      "dependencies": {
        "@types/json-schema": "^7.0.3",
        "@typescript-eslint/typescript-estree": "2.34.0",
        "eslint-scope": "^5.0.0",
        "eslint-utils": "^2.0.0"
      },
      "engines": {
        "node": "^8.10.0 || ^10.13.0 || >=11.10.1"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/typescript-eslint"
      },
      "peerDependencies": {
        "eslint": "*"
      }
    },
    "node_modules/@typescript-eslint/parser": {
      "version": "2.34.0",
      "resolved": "https://registry.npmjs.org/@typescript-eslint/parser/-/parser-2.34.0.tgz",
      "integrity": "sha512-03ilO0ucSD0EPTw2X4PntSIRFtDPWjrVq7C3/Z3VQHRC7+13YB55rcJI3Jt+YgeHbjUdJPcPa7b23rXCBokuyA==",
      "dev": true,
      "dependencies": {
        "@types/eslint-visitor-keys": "^1.0.0",
        "@typescript-eslint/experimental-utils": "2.34.0",
        "@typescript-eslint/typescript-estree": "2.34.0",
        "eslint-visitor-keys": "^1.1.0"
      },
      "engines": {
        "node": "^8.10.0 || ^10.13.0 || >=11.10.1"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/typescript-eslint"
      },
      "peerDependencies": {
        "eslint": "^5.0.0 || ^6.0.0"
      },
      "peerDependenciesMeta": {
        "typescript": {
          "optional": true
        }
      }
    },
    "node_modules/@typescript-eslint/typescript-estree": {
      "version": "2.34.0",
      "resolved": "https://registry.npmjs.org/@typescript-eslint/typescript-estree/-/typescript-estree-2.34.0.tgz",
      "integrity": "sha512-OMAr+nJWKdlVM9LOqCqh3pQQPwxHAN7Du8DR6dmwCrAmxtiXQnhHJ6tBNtf+cggqfo51SG/FCwnKhXCIM7hnVg==",
      "dev": true,
      "dependencies": {
        "debug": "^4.1.1",
        "eslint-visitor-keys": "^1.1.0",
        "glob": "^7.1.6",
        "is-glob": "^4.0.1",
        "lodash": "^4.17.15",
        "semver": "^7.3.2",
        "tsutils": "^3.17.1"
      },
      "engines": {
        "node": "^8.10.0 || ^10.13.0 || >=11.10.1"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/typescript-eslint"
      },
      "peerDependenciesMeta": {
        "typescript": {
          "optional": true
        }
      }
    },
    "node_modules/@wry/context": {
      "version": "0.6.1",
      "resolved": "https://registry.npmjs.org/@wry/context/-/context-0.6.1.tgz",
      "integrity": "sha512-LOmVnY1iTU2D8tv4Xf6MVMZZ+juIJ87Kt/plMijjN20NMAXGmH4u8bS1t0uT74cZ5gwpocYueV58YwyI8y+GKw==",
      "dependencies": {
        "tslib": "^2.3.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@wry/context/node_modules/tslib": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
      "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
    },
    "node_modules/@wry/equality": {
      "version": "0.5.2",
      "resolved": "https://registry.npmjs.org/@wry/equality/-/equality-0.5.2.tgz",
      "integrity": "sha512-oVMxbUXL48EV/C0/M7gLVsoK6qRHPS85x8zECofEZOVvxGmIPLA9o5Z27cc2PoAyZz1S2VoM2A7FLAnpfGlneA==",
      "dependencies": {
        "tslib": "^2.3.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@wry/equality/node_modules/tslib": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
      "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
    },
    "node_modules/@wry/trie": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/@wry/trie/-/trie-0.3.1.tgz",
      "integrity": "sha512-WwB53ikYudh9pIorgxrkHKrQZcCqNM/Q/bDzZBffEaGUKGuHrRb3zZUT9Sh2qw9yogC7SsdRmQ1ER0pqvd3bfw==",
      "dependencies": {
        "tslib": "^2.3.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/@wry/trie/node_modules/tslib": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
      "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
    },
    "node_modules/@zeit/schemas": {
      "version": "2.21.0",
      "resolved": "https://registry.npmjs.org/@zeit/schemas/-/schemas-2.21.0.tgz",
      "integrity": "sha512-/J4WBTpWtQ4itN1rb3ao8LfClmVcmz2pO6oYb7Qd4h7VSqUhIbJIvrykz9Ew1WMg6eFWsKdsMHc5uPbFxqlCpg==",
      "dev": true
    },
    "node_modules/abab": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/abab/-/abab-2.0.5.tgz",
      "integrity": "sha512-9IK9EadsbHo6jLWIpxpR6pL0sazTXV6+SQv25ZB+F7Bj9mJNaOc4nCRabwd5M/JwmUa8idz6Eci6eKfJryPs6Q==",
      "dev": true
    },
    "node_modules/accepts": {
      "version": "1.3.8",
      "resolved": "https://registry.npmjs.org/accepts/-/accepts-1.3.8.tgz",
      "integrity": "sha512-PYAthTa2m2VKxuvSD3DPC/Gy+U+sOA1LAuT8mkmRuvw+NACSaeXEQ+NHcVF7rONl6qcaxV3Uuemwawk+7+SJLw==",
      "dev": true,
      "dependencies": {
        "mime-types": "~2.1.34",
        "negotiator": "0.6.3"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/accepts/node_modules/mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
      "dev": true,
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/accepts/node_modules/mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "dev": true,
      "dependencies": {
        "mime-db": "1.52.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/acorn": {
      "version": "7.4.1",
      "resolved": "https://registry.npmjs.org/acorn/-/acorn-7.4.1.tgz",
      "integrity": "sha512-nQyp0o1/mNdbTO1PO6kHkwSrmgZ0MT/jCCpNiwbUjGoRN4dlBhqJtoQuCnEOKzgTVwg0ZWiCoQy6SxMebQVh8A==",
      "dev": true,
      "bin": {
        "acorn": "bin/acorn"
      },
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/acorn-globals": {
      "version": "4.3.4",
      "resolved": "https://registry.npmjs.org/acorn-globals/-/acorn-globals-4.3.4.tgz",
      "integrity": "sha512-clfQEh21R+D0leSbUdWf3OcfqyaCSAQ8Ryq00bofSekfr9W8u1jyYZo6ir0xu9Gtcf7BjcHJpnbZH7JOCpP60A==",
      "dev": true,
      "dependencies": {
        "acorn": "^6.0.1",
        "acorn-walk": "^6.0.1"
      }
    },
    "node_modules/acorn-globals/node_modules/acorn": {
      "version": "6.4.2",
      "resolved": "https://registry.npmjs.org/acorn/-/acorn-6.4.2.tgz",
      "integrity": "sha512-XtGIhXwF8YM8bJhGxG5kXgjkEuNGLTkoYqVE+KMR+aspr4KGYmKYg7yUe3KghyQ9yheNwLnjmzh/7+gfDBmHCQ==",
      "dev": true,
      "bin": {
        "acorn": "bin/acorn"
      },
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/acorn-jsx": {
      "version": "5.3.1",
      "resolved": "https://registry.npmjs.org/acorn-jsx/-/acorn-jsx-5.3.1.tgz",
      "integrity": "sha512-K0Ptm/47OKfQRpNQ2J/oIN/3QYiK6FwW+eJbILhsdxh2WTLdl+30o8aGdTbm5JbffpFFAg/g+zi1E+jvJha5ng==",
      "dev": true,
      "peerDependencies": {
        "acorn": "^6.0.0 || ^7.0.0 || ^8.0.0"
      }
    },
    "node_modules/acorn-walk": {
      "version": "6.2.0",
      "resolved": "https://registry.npmjs.org/acorn-walk/-/acorn-walk-6.2.0.tgz",
      "integrity": "sha512-7evsyfH1cLOCdAzZAd43Cic04yKydNx0cF+7tiA19p1XnLLPU4dpCQOqpjqwokFe//vS0QqfqqjCS2JkiIs0cA==",
      "dev": true,
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/aes-js": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/aes-js/-/aes-js-3.0.0.tgz",
      "integrity": "sha1-4h3xCtbCBTKVvLuNq0Cwnb6ofk0="
    },
    "node_modules/ajv": {
      "version": "6.12.6",
      "resolved": "https://registry.npmjs.org/ajv/-/ajv-6.12.6.tgz",
      "integrity": "sha512-j3fVLgvTo527anyYyJOGTYJbG+vnnQYvE0m5mmkc1TK+nxAppkCLMIL0aZ4dblVCNoGShhm+kzE4ZUykBoMg4g==",
      "dev": true,
      "dependencies": {
        "fast-deep-equal": "^3.1.1",
        "fast-json-stable-stringify": "^2.0.0",
        "json-schema-traverse": "^0.4.1",
        "uri-js": "^4.2.2"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/epoberezkin"
      }
    },
    "node_modules/ansi-align": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/ansi-align/-/ansi-align-3.0.1.tgz",
      "integrity": "sha512-IOfwwBF5iczOjp/WeY4YxyjqAFMQoZufdQWDd19SEExbVLNXqvpzSJ/M7Za4/sCPmQ0+GRquoA7bGcINcxew6w==",
      "dev": true,
      "dependencies": {
        "string-width": "^4.1.0"
      }
    },
    "node_modules/ansi-escapes": {
      "version": "4.3.2",
      "resolved": "https://registry.npmjs.org/ansi-escapes/-/ansi-escapes-4.3.2.tgz",
      "integrity": "sha512-gKXj5ALrKWQLsYG9jlTRmR/xKluxHV+Z9QEwNIgCfM1/uwPMCuzVVnh5mwTd+OuBZcwSIMbqssNWRm1lE51QaQ==",
      "dev": true,
      "dependencies": {
        "type-fest": "^0.21.3"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/ansi-escapes/node_modules/type-fest": {
      "version": "0.21.3",
      "resolved": "https://registry.npmjs.org/type-fest/-/type-fest-0.21.3.tgz",
      "integrity": "sha512-t0rzBq87m3fVcduHDUFhKmyyX+9eo6WQjZvf51Ea/M0Q7+T374Jp1aUiyUl0GKxp8M/OETVHSDvmkyPgvX+X2w==",
      "dev": true,
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/ansi-styles": {
      "version": "3.2.1",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-3.2.1.tgz",
      "integrity": "sha512-VT0ZI6kZRdTh8YyJw3SMbYm/u+NqfsAxEpWO0Pf9sq8/e94WxxOpPKx9FR1FlyCtOVDNOQ+8ntlqFxiRc+r5qA==",
      "dev": true,
      "dependencies": {
        "color-convert": "^1.9.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/any-promise": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/any-promise/-/any-promise-1.3.0.tgz",
      "integrity": "sha1-q8av7tzqUugJzcA3au0845Y10X8=",
      "dev": true
    },
    "node_modules/anymatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/anymatch/-/anymatch-3.1.2.tgz",
      "integrity": "sha512-P43ePfOAIupkguHUycrc4qJ9kz8ZiuOUijaETwX7THt0Y/GNK7v0aa8rY816xWjZ7rJdA5XdMcpVFTKMq+RvWg==",
      "dev": true,
      "dependencies": {
        "normalize-path": "^3.0.0",
        "picomatch": "^2.0.4"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/arch": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/arch/-/arch-2.2.0.tgz",
      "integrity": "sha512-Of/R0wqp83cgHozfIYLbBMnej79U/SVGOOyuB3VVFv1NRM/PSFMK12x9KVtiYzJqmnU5WR2qp0Z5rHb7sWGnFQ==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ]
    },
    "node_modules/arg": {
      "version": "5.0.2",
      "resolved": "https://registry.npmjs.org/arg/-/arg-5.0.2.tgz",
      "integrity": "sha512-PYjyFOLKQ9y57JvQ6QLo8dAgNqswh8M1RMJYdQduT6xbWSgK36P/Z/v+p888pM69jMMfS8Xd8F6I1kQ/I9HUGg==",
      "dev": true
    },
    "node_modules/argparse": {
      "version": "1.0.10",
      "resolved": "https://registry.npmjs.org/argparse/-/argparse-1.0.10.tgz",
      "integrity": "sha512-o5Roy6tNG4SL/FOkCAN6RzjiakZS25RLYFrcMttJqbdd8BWrnA+fGz57iN5Pb06pvBGvl5gQ0B48dJlslXvoTg==",
      "dev": true,
      "dependencies": {
        "sprintf-js": "~1.0.2"
      }
    },
    "node_modules/arr-diff": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/arr-diff/-/arr-diff-4.0.0.tgz",
      "integrity": "sha1-1kYQdP6/7HHn4VI1dhoyml3HxSA=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/arr-flatten": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/arr-flatten/-/arr-flatten-1.1.0.tgz",
      "integrity": "sha512-L3hKV5R/p5o81R7O02IGnwpDmkp6E982XhtbuwSe3O4qOtMMMtodicASA1Cny2U+aCXcNpml+m4dPsvsJ3jatg==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/arr-union": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/arr-union/-/arr-union-3.1.0.tgz",
      "integrity": "sha1-45sJrqne+Gao8gbiiK9jkZuuOcQ=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/array-equal": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/array-equal/-/array-equal-1.0.0.tgz",
      "integrity": "sha1-jCpe8kcv2ep0KwTHenUJO6J1fJM=",
      "dev": true
    },
    "node_modules/array-includes": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/array-includes/-/array-includes-3.1.3.tgz",
      "integrity": "sha512-gcem1KlBU7c9rB+Rq8/3PPKsK2kjqeEBa3bD5kkQo4nYlOHQCJqIJFqBXDEfwaRuYTT4E+FxA9xez7Gf/e3Q7A==",
      "dev": true,
      "dependencies": {
        "call-bind": "^1.0.2",
        "define-properties": "^1.1.3",
        "es-abstract": "^1.18.0-next.2",
        "get-intrinsic": "^1.1.1",
        "is-string": "^1.0.5"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/array-union": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/array-union/-/array-union-1.0.2.tgz",
      "integrity": "sha1-mjRBDk9OPaI96jdb5b5w8kd47Dk=",
      "dev": true,
      "dependencies": {
        "array-uniq": "^1.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/array-uniq": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/array-uniq/-/array-uniq-1.0.3.tgz",
      "integrity": "sha1-r2rId6Jcx/dOBYiUdThY39sk/bY=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/array-unique": {
      "version": "0.3.2",
      "resolved": "https://registry.npmjs.org/array-unique/-/array-unique-0.3.2.tgz",
      "integrity": "sha1-qJS3XUvE9s1nnvMkSp/Y9Gri1Cg=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/array.prototype.flat": {
      "version": "1.2.4",
      "resolved": "https://registry.npmjs.org/array.prototype.flat/-/array.prototype.flat-1.2.4.tgz",
      "integrity": "sha512-4470Xi3GAPAjZqFcljX2xzckv1qeKPizoNkiS0+O4IoPR2ZNpcjE0pkhdihlDouK+x6QOast26B4Q/O9DJnwSg==",
      "dev": true,
      "dependencies": {
        "call-bind": "^1.0.0",
        "define-properties": "^1.1.3",
        "es-abstract": "^1.18.0-next.1"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/asn1": {
      "version": "0.2.4",
      "resolved": "https://registry.npmjs.org/asn1/-/asn1-0.2.4.tgz",
      "integrity": "sha512-jxwzQpLQjSmWXgwaCZE9Nz+glAG01yF1QnWgbhGwHI5A6FRIEY6IVqtHhIepHqI7/kyEyQEagBC5mBEFlIYvdg==",
      "dev": true,
      "dependencies": {
        "safer-buffer": "~2.1.0"
      }
    },
    "node_modules/assert-plus": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/assert-plus/-/assert-plus-1.0.0.tgz",
      "integrity": "sha1-8S4PPF13sLHN2RRpQuTpbB5N1SU=",
      "dev": true,
      "engines": {
        "node": ">=0.8"
      }
    },
    "node_modules/assertion-error-formatter": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/assertion-error-formatter/-/assertion-error-formatter-3.0.0.tgz",
      "integrity": "sha512-6YyAVLrEze0kQ7CmJfUgrLHb+Y7XghmL2Ie7ijVa2Y9ynP3LV+VDiwFk62Dn0qtqbmY0BT0ss6p1xxpiF2PYbQ==",
      "dev": true,
      "dependencies": {
        "diff": "^4.0.1",
        "pad-right": "^0.2.2",
        "repeat-string": "^1.6.1"
      }
    },
    "node_modules/assign-symbols": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/assign-symbols/-/assign-symbols-1.0.0.tgz",
      "integrity": "sha1-WWZ/QfrdTyDMvCu5a41Pf3jsA2c=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/astral-regex": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/astral-regex/-/astral-regex-1.0.0.tgz",
      "integrity": "sha512-+Ryf6g3BKoRc7jfp7ad8tM4TtMiaWvbF/1/sQcZPkkS7ag3D5nMBCe2UfOTONtAkaG0tO0ij3C5Lwmf1EiyjHg==",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/async": {
      "version": "2.6.4",
      "resolved": "https://registry.npmjs.org/async/-/async-2.6.4.tgz",
      "integrity": "sha512-mzo5dfJYwAn29PeiJ0zvwTo04zj8HDJj0Mn8TD7sno7q12prdbnasKJHhkm2c1LgrhlJ0teaea8860oxi51mGA==",
      "dev": true,
      "dependencies": {
        "lodash": "^4.17.14"
      }
    },
    "node_modules/async-limiter": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/async-limiter/-/async-limiter-1.0.1.tgz",
      "integrity": "sha512-csOlWGAcRFJaI6m+F2WKdnMKr4HhdhFVBk0H/QbJFMCr+uO2kwohwXQPxw/9OCxp05r5ghVBFSyioixx3gfkNQ=="
    },
    "node_modules/asynckit": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/asynckit/-/asynckit-0.4.0.tgz",
      "integrity": "sha1-x57Zf380y48robyXkLzDZkdLS3k="
    },
    "node_modules/atob": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/atob/-/atob-2.1.2.tgz",
      "integrity": "sha512-Wm6ukoaOGJi/73p/cl2GvLjTI5JM1k/O14isD73YML8StrH/7/lRFgmg8nICZgD3bZZvjwCGxtMOD3wWNAu8cg==",
      "dev": true,
      "bin": {
        "atob": "bin/atob.js"
      },
      "engines": {
        "node": ">= 4.5.0"
      }
    },
    "node_modules/aws-sign2": {
      "version": "0.7.0",
      "resolved": "https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.7.0.tgz",
      "integrity": "sha1-tG6JCTSpWR8tL2+G1+ap8bP+dqg=",
      "dev": true,
      "engines": {
        "node": "*"
      }
    },
    "node_modules/aws4": {
      "version": "1.11.0",
      "resolved": "https://registry.npmjs.org/aws4/-/aws4-1.11.0.tgz",
      "integrity": "sha512-xh1Rl34h6Fi1DC2WWKfxUTVqRsNnr6LsKz2+hfwDxQJWmrx8+c7ylaqBMcHfl1U1r2dsifOvKX3LQuLNZ+XSvA==",
      "dev": true
    },
    "node_modules/axios": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/axios/-/axios-1.1.3.tgz",
      "integrity": "sha512-00tXVRwKx/FZr/IDVFt4C+f9FYairX517WoGCL6dpOntqLkZofjhu43F/Xl44UOpqa+9sLFDrG/XAnFsUYgkDA==",
      "dependencies": {
        "follow-redirects": "^1.15.0",
        "form-data": "^4.0.0",
        "proxy-from-env": "^1.1.0"
      }
    },
    "node_modules/axios/node_modules/form-data": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-4.0.0.tgz",
      "integrity": "sha512-ETEklSGi5t0QMZuiXoA/Q6vcnxcLQP5vdugSpuAyi6SVGi2clPPp+xgEhuMaHC+zGgn31Kd235W35f7Hykkaww==",
      "dependencies": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.8",
        "mime-types": "^2.1.12"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/babel-jest": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/babel-jest/-/babel-jest-25.5.1.tgz",
      "integrity": "sha512-9dA9+GmMjIzgPnYtkhBg73gOo/RHqPmLruP3BaGL4KEX3Dwz6pI8auSN8G8+iuEG90+GSswyKvslN+JYSaacaQ==",
      "dev": true,
      "dependencies": {
        "@jest/transform": "^25.5.1",
        "@jest/types": "^25.5.0",
        "@types/babel__core": "^7.1.7",
        "babel-plugin-istanbul": "^6.0.0",
        "babel-preset-jest": "^25.5.0",
        "chalk": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "slash": "^3.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0"
      }
    },
    "node_modules/babel-jest/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/babel-jest/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/babel-jest/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/babel-jest/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/babel-jest/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/babel-jest/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/babel-plugin-istanbul": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-istanbul/-/babel-plugin-istanbul-6.0.0.tgz",
      "integrity": "sha512-AF55rZXpe7trmEylbaE1Gv54wn6rwU03aptvRoVIGP8YykoSxqdVLV1TfwflBCE/QtHmqtP8SWlTENqbK8GCSQ==",
      "dev": true,
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@istanbuljs/load-nyc-config": "^1.0.0",
        "@istanbuljs/schema": "^0.1.2",
        "istanbul-lib-instrument": "^4.0.0",
        "test-exclude": "^6.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/babel-plugin-jest-hoist": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-jest-hoist/-/babel-plugin-jest-hoist-25.5.0.tgz",
      "integrity": "sha512-u+/W+WAjMlvoocYGTwthAiQSxDcJAyHpQ6oWlHdFZaaN+Rlk8Q7iiwDPg2lN/FyJtAYnKjFxbn7xus4HCFkg5g==",
      "dev": true,
      "dependencies": {
        "@babel/template": "^7.3.3",
        "@babel/types": "^7.3.3",
        "@types/babel__traverse": "^7.0.6"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/babel-preset-current-node-syntax": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/babel-preset-current-node-syntax/-/babel-preset-current-node-syntax-0.1.4.tgz",
      "integrity": "sha512-5/INNCYhUGqw7VbVjT/hb3ucjgkVHKXY7lX3ZjlN4gm565VyFmJUrJ/h+h16ECVB38R/9SF6aACydpKMLZ/c9w==",
      "dev": true,
      "dependencies": {
        "@babel/plugin-syntax-async-generators": "^7.8.4",
        "@babel/plugin-syntax-bigint": "^7.8.3",
        "@babel/plugin-syntax-class-properties": "^7.8.3",
        "@babel/plugin-syntax-import-meta": "^7.8.3",
        "@babel/plugin-syntax-json-strings": "^7.8.3",
        "@babel/plugin-syntax-logical-assignment-operators": "^7.8.3",
        "@babel/plugin-syntax-nullish-coalescing-operator": "^7.8.3",
        "@babel/plugin-syntax-numeric-separator": "^7.8.3",
        "@babel/plugin-syntax-object-rest-spread": "^7.8.3",
        "@babel/plugin-syntax-optional-catch-binding": "^7.8.3",
        "@babel/plugin-syntax-optional-chaining": "^7.8.3"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0"
      }
    },
    "node_modules/babel-preset-jest": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/babel-preset-jest/-/babel-preset-jest-25.5.0.tgz",
      "integrity": "sha512-8ZczygctQkBU+63DtSOKGh7tFL0CeCuz+1ieud9lJ1WPQ9O6A1a/r+LGn6Y705PA6whHQ3T1XuB/PmpfNYf8Fw==",
      "dev": true,
      "dependencies": {
        "babel-plugin-jest-hoist": "^25.5.0",
        "babel-preset-current-node-syntax": "^0.1.2"
      },
      "engines": {
        "node": ">= 8.3"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0"
      }
    },
    "node_modules/backo2": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz",
      "integrity": "sha1-MasayLEpNjRj41s+u2n038+6eUc="
    },
    "node_modules/balanced-match": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/balanced-match/-/balanced-match-1.0.2.tgz",
      "integrity": "sha512-3oSeUO0TMV67hN1AmbXsK4yaqU7tjiHlbxRDZOpH0KW9+CeX4bRAaX0Anxt0tx2MrpRpWwQaPwIlISEJhYU5Pw==",
      "dev": true
    },
    "node_modules/base": {
      "version": "0.11.2",
      "resolved": "https://registry.npmjs.org/base/-/base-0.11.2.tgz",
      "integrity": "sha512-5T6P4xPgpp0YDFvSWwEZ4NoE3aM4QBQXDzmVbraCkFj8zHM+mba8SyqB5DbZWyR7mYHo6Y7BdQo3MoA4m0TeQg==",
      "dev": true,
      "dependencies": {
        "cache-base": "^1.0.1",
        "class-utils": "^0.3.5",
        "component-emitter": "^1.2.1",
        "define-property": "^1.0.0",
        "isobject": "^3.0.1",
        "mixin-deep": "^1.2.0",
        "pascalcase": "^0.1.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/base/node_modules/define-property": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
      "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
      "dev": true,
      "dependencies": {
        "is-descriptor": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/bcrypt-pbkdf": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/bcrypt-pbkdf/-/bcrypt-pbkdf-1.0.2.tgz",
      "integrity": "sha1-pDAdOJtqQ/m2f/PKEaP2Y342Dp4=",
      "dev": true,
      "dependencies": {
        "tweetnacl": "^0.14.3"
      }
    },
    "node_modules/bech32": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/bech32/-/bech32-1.1.4.tgz",
      "integrity": "sha512-s0IrSOzLlbvX7yp4WBfPITzpAU8sqQcpsmwXDiKwrG4r491vwCO/XpejasRNl0piBMe/DvP4Tz0mIS/X1DPJBQ=="
    },
    "node_modules/becke-ch--regex--s0-0-v1--base--pl--lib": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/becke-ch--regex--s0-0-v1--base--pl--lib/-/becke-ch--regex--s0-0-v1--base--pl--lib-1.4.0.tgz",
      "integrity": "sha1-Qpzuu/pffpNueNc/vcfacWKyDiA=",
      "dev": true
    },
    "node_modules/bignumber.js": {
      "version": "9.1.0",
      "resolved": "https://registry.npmjs.org/bignumber.js/-/bignumber.js-9.1.0.tgz",
      "integrity": "sha512-4LwHK4nfDOraBCtst+wOWIHbu1vhvAPJK8g8nROd4iuc3PSEjWif/qwbkh8jwCJz6yDBvtU4KPynETgrfh7y3A==",
      "engines": {
        "node": "*"
      }
    },
    "node_modules/bluebird": {
      "version": "3.7.2",
      "resolved": "https://registry.npmjs.org/bluebird/-/bluebird-3.7.2.tgz",
      "integrity": "sha512-XpNj6GDQzdfW+r2Wnn7xiSAd7TM3jzkxGXBGTtWKuSXv1xUV+azxAm8jdWZN06QTQk+2N2XB9jRDkvbmQmcRtg==",
      "dev": true
    },
    "node_modules/bn.js": {
      "version": "5.2.1",
      "resolved": "https://registry.npmjs.org/bn.js/-/bn.js-5.2.1.tgz",
      "integrity": "sha512-eXRvHzWyYPBuB4NBy0cmYQjGitUrtqwbvlzP3G6VFnNRbsZQIxQ10PbKKHt8gZ/HW/D/747aDl+QkDqg3KQLMQ=="
    },
    "node_modules/boxen": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/boxen/-/boxen-7.0.0.tgz",
      "integrity": "sha512-j//dBVuyacJbvW+tvZ9HuH03fZ46QcaKvvhZickZqtB271DxJ7SNRSNxrV/dZX0085m7hISRZWbzWlJvx/rHSg==",
      "dev": true,
      "dependencies": {
        "ansi-align": "^3.0.1",
        "camelcase": "^7.0.0",
        "chalk": "^5.0.1",
        "cli-boxes": "^3.0.0",
        "string-width": "^5.1.2",
        "type-fest": "^2.13.0",
        "widest-line": "^4.0.1",
        "wrap-ansi": "^8.0.1"
      },
      "engines": {
        "node": ">=14.16"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/boxen/node_modules/ansi-regex": {
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-6.0.1.tgz",
      "integrity": "sha512-n5M855fKb2SsfMIiFFoVrABHJC8QtHwVx+mHWP3QcEqBHYienj5dHSgjbxtC0WEZXYt4wcD6zrQElDPhFuZgfA==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-regex?sponsor=1"
      }
    },
    "node_modules/boxen/node_modules/ansi-styles": {
      "version": "6.2.1",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-6.2.1.tgz",
      "integrity": "sha512-bN798gFfQX+viw3R7yrGWRqnrN2oRkEkUjjl4JNn4E8GxxbjtG3FbrEIIY3l8/hrwUwIeCZvi4QuOTP4MErVug==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/boxen/node_modules/camelcase": {
      "version": "7.0.1",
      "resolved": "https://registry.npmjs.org/camelcase/-/camelcase-7.0.1.tgz",
      "integrity": "sha512-xlx1yCK2Oc1APsPXDL2LdlNP6+uu8OCDdhOBSVT279M/S+y75O30C2VuD8T2ogdePBBl7PfPF4504tnLgX3zfw==",
      "dev": true,
      "engines": {
        "node": ">=14.16"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/boxen/node_modules/chalk": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-5.2.0.tgz",
      "integrity": "sha512-ree3Gqw/nazQAPuJJEy+avdl7QfZMcUvmHIKgEZkGL+xOBzRvup5Hxo6LHuMceSxOabuJLJm5Yp/92R9eMmMvA==",
      "dev": true,
      "engines": {
        "node": "^12.17.0 || ^14.13 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/chalk/chalk?sponsor=1"
      }
    },
    "node_modules/boxen/node_modules/emoji-regex": {
      "version": "9.2.2",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-9.2.2.tgz",
      "integrity": "sha512-L18DaJsXSUk2+42pv8mLs5jJT2hqFkFE4j21wOmgbUqsZ2hL72NsUU785g9RXgo3s0ZNgVl42TiHp3ZtOv/Vyg==",
      "dev": true
    },
    "node_modules/boxen/node_modules/string-width": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-5.1.2.tgz",
      "integrity": "sha512-HnLOCR3vjcY8beoNLtcjZ5/nxn2afmME6lhrDrebokqMap+XbeW8n9TXpPDOqdGK5qcI3oT0GKTW6wC7EMiVqA==",
      "dev": true,
      "dependencies": {
        "eastasianwidth": "^0.2.0",
        "emoji-regex": "^9.2.2",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/boxen/node_modules/strip-ansi": {
      "version": "7.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-7.0.1.tgz",
      "integrity": "sha512-cXNxvT8dFNRVfhVME3JAe98mkXDYN2O1l7jmcwMnOslDeESg1rF/OZMtK0nRAhiari1unG5cD4jG3rapUAkLbw==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^6.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/strip-ansi?sponsor=1"
      }
    },
    "node_modules/boxen/node_modules/type-fest": {
      "version": "2.19.0",
      "resolved": "https://registry.npmjs.org/type-fest/-/type-fest-2.19.0.tgz",
      "integrity": "sha512-RAH822pAdBgcNMAfWnCBU3CFZcfZ/i1eZjwFU/dsLKumyuuP3niueg2UAukXYF0E2AAoc82ZSSf9J0WQBinzHA==",
      "dev": true,
      "engines": {
        "node": ">=12.20"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/boxen/node_modules/wrap-ansi": {
      "version": "8.0.1",
      "resolved": "https://registry.npmjs.org/wrap-ansi/-/wrap-ansi-8.0.1.tgz",
      "integrity": "sha512-QFF+ufAqhoYHvoHdajT/Po7KoXVBPXS2bgjIam5isfWJPfIOnQZ50JtUiVvCv/sjgacf3yRrt2ZKUZ/V4itN4g==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^6.1.0",
        "string-width": "^5.0.1",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/wrap-ansi?sponsor=1"
      }
    },
    "node_modules/brace-expansion": {
      "version": "1.1.11",
      "resolved": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.11.tgz",
      "integrity": "sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==",
      "dev": true,
      "dependencies": {
        "balanced-match": "^1.0.0",
        "concat-map": "0.0.1"
      }
    },
    "node_modules/braces": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/braces/-/braces-3.0.2.tgz",
      "integrity": "sha512-b8um+L1RzM3WDSzvhm6gIz1yfTbBt6YTlcEKAvsmqCZZFw46z626lVj9j1yEPW33H5H+lBQpZMP1k8l+78Ha0A==",
      "dev": true,
      "dependencies": {
        "fill-range": "^7.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/brorand": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/brorand/-/brorand-1.1.0.tgz",
      "integrity": "sha1-EsJe/kCkXjwyPrhnWgoM5XsiNx8="
    },
    "node_modules/browser-process-hrtime": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/browser-process-hrtime/-/browser-process-hrtime-1.0.0.tgz",
      "integrity": "sha512-9o5UecI3GhkpM6DrXr69PblIuWxPKk9Y0jHBRhdocZ2y7YECBFCsHm79Pr3OyR2AvjhDkabFJaDJMYRazHgsow==",
      "dev": true
    },
    "node_modules/browser-resolve": {
      "version": "1.11.3",
      "resolved": "https://registry.npmjs.org/browser-resolve/-/browser-resolve-1.11.3.tgz",
      "integrity": "sha512-exDi1BYWB/6raKHmDTCicQfTkqwN5fioMFV4j8BsfMU4R2DK/QfZfK7kOVkmWCNANf0snkBzqGqAJBao9gZMdQ==",
      "dev": true,
      "dependencies": {
        "resolve": "1.1.7"
      }
    },
    "node_modules/browser-resolve/node_modules/resolve": {
      "version": "1.1.7",
      "resolved": "https://registry.npmjs.org/resolve/-/resolve-1.1.7.tgz",
      "integrity": "sha1-IDEU2CrSxe2ejgQRs5ModeiJ6Xs=",
      "dev": true
    },
    "node_modules/browserslist": {
      "version": "4.16.6",
      "resolved": "https://registry.npmjs.org/browserslist/-/browserslist-4.16.6.tgz",
      "integrity": "sha512-Wspk/PqO+4W9qp5iUTJsa1B/QrYn1keNCcEP5OvP7WBwT4KaDly0uONYmC6Xa3Z5IqnUgS0KcgLYu1l74x0ZXQ==",
      "dev": true,
      "dependencies": {
        "caniuse-lite": "^1.0.30001219",
        "colorette": "^1.2.2",
        "electron-to-chromium": "^1.3.723",
        "escalade": "^3.1.1",
        "node-releases": "^1.1.71"
      },
      "bin": {
        "browserslist": "cli.js"
      },
      "engines": {
        "node": "^6 || ^7 || ^8 || ^9 || ^10 || ^11 || ^12 || >=13.7"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/browserslist"
      }
    },
    "node_modules/bs-logger": {
      "version": "0.2.6",
      "resolved": "https://registry.npmjs.org/bs-logger/-/bs-logger-0.2.6.tgz",
      "integrity": "sha512-pd8DCoxmbgc7hyPKOvxtqNcjYoOsABPQdcCUjGp3d42VR2CX1ORhk2A87oqqu5R1kk+76nsxZupkmyd+MVtCog==",
      "dev": true,
      "dependencies": {
        "fast-json-stable-stringify": "2.x"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/bser": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/bser/-/bser-2.1.1.tgz",
      "integrity": "sha512-gQxTNE/GAfIIrmHLUE3oJyp5FO6HRBfhjnw4/wMmA63ZGDJnWBmgY/lyQBpnDUkGmAhbSe39tx2d/iTOAfglwQ==",
      "dev": true,
      "dependencies": {
        "node-int64": "^0.4.0"
      }
    },
    "node_modules/buffer-from": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/buffer-from/-/buffer-from-1.1.1.tgz",
      "integrity": "sha512-MQcXEUbCKtEo7bhqEs6560Hyd4XaovZlO/k9V3hjVUF/zwW7KBVdSK4gIt/bzwS9MbR5qob+F5jusZsb0YQK2A==",
      "dev": true
    },
    "node_modules/bytes": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/bytes/-/bytes-3.0.0.tgz",
      "integrity": "sha512-pMhOfFDPiv9t5jjIXkHosWmkSyQbvsgEVNkz0ERHbuLh2T/7j4Mqqpz523Fe8MVY89KC6Sh/QfS2sM+SjgFDcw==",
      "dev": true,
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/cache-base": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/cache-base/-/cache-base-1.0.1.tgz",
      "integrity": "sha512-AKcdTnFSWATd5/GCPRxr2ChwIJ85CeyrEyjRHlKxQ56d4XJMGym0uAiKn0xbLOGOl3+yRpOTi484dVCEc5AUzQ==",
      "dev": true,
      "dependencies": {
        "collection-visit": "^1.0.0",
        "component-emitter": "^1.2.1",
        "get-value": "^2.0.6",
        "has-value": "^1.0.0",
        "isobject": "^3.0.1",
        "set-value": "^2.0.0",
        "to-object-path": "^0.3.0",
        "union-value": "^1.0.0",
        "unset-value": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/call-bind": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/call-bind/-/call-bind-1.0.2.tgz",
      "integrity": "sha512-7O+FbCihrB5WGbFYesctwmTKae6rOiIzmz1icreWJ+0aA7LJfuqhEso2T9ncpcFtzMQtzXf2QGGueWJGTYsqrA==",
      "dev": true,
      "dependencies": {
        "function-bind": "^1.1.1",
        "get-intrinsic": "^1.0.2"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/callsites": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/callsites/-/callsites-3.1.0.tgz",
      "integrity": "sha512-P8BjAsXvZS+VIDUI11hHCQEv74YT67YUi5JJFNWIqL235sBmjX4+qx9Muvls5ivyNENctx46xQLQ3aTuE7ssaQ==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/camelcase": {
      "version": "5.3.1",
      "resolved": "https://registry.npmjs.org/camelcase/-/camelcase-5.3.1.tgz",
      "integrity": "sha512-L28STB170nwWS63UjtlEOE3dldQApaJXZkOI1uMFfzf3rRuPegHaHesyee+YxQ+W6SvRDQV6UrdOdRiR153wJg==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/caniuse-lite": {
      "version": "1.0.30001237",
      "resolved": "https://registry.npmjs.org/caniuse-lite/-/caniuse-lite-1.0.30001237.tgz",
      "integrity": "sha512-pDHgRndit6p1NR2GhzMbQ6CkRrp4VKuSsqbcLeOQppYPKOYkKT/6ZvZDvKJUqcmtyWIAHuZq3SVS2vc1egCZzw==",
      "dev": true,
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/browserslist"
      }
    },
    "node_modules/capital-case": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/capital-case/-/capital-case-1.0.4.tgz",
      "integrity": "sha512-ds37W8CytHgwnhGGTi88pcPyR15qoNkOpYwmMMfnWqqWgESapLqvDx6huFjQ5vqWSn2Z06173XNA7LtMOeUh1A==",
      "dev": true,
      "dependencies": {
        "no-case": "^3.0.4",
        "tslib": "^2.0.3",
        "upper-case-first": "^2.0.2"
      }
    },
    "node_modules/capital-case/node_modules/tslib": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
      "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg==",
      "dev": true
    },
    "node_modules/capture-exit": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/capture-exit/-/capture-exit-2.0.0.tgz",
      "integrity": "sha512-PiT/hQmTonHhl/HFGN+Lx3JJUznrVYJ3+AQsnthneZbvW7x+f08Tk7yLJTLEOUvBTbduLeeBkxEaYXUOUrRq6g==",
      "dev": true,
      "dependencies": {
        "rsvp": "^4.8.4"
      },
      "engines": {
        "node": "6.* || 8.* || >= 10.*"
      }
    },
    "node_modules/caseless": {
      "version": "0.12.0",
      "resolved": "https://registry.npmjs.org/caseless/-/caseless-0.12.0.tgz",
      "integrity": "sha1-G2gcIf+EAzyCZUMJBolCDRhxUdw=",
      "dev": true
    },
    "node_modules/chalk": {
      "version": "2.4.2",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-2.4.2.tgz",
      "integrity": "sha512-Mti+f9lpJNcwF4tWV8/OrTTtF1gZi+f8FqlyAdouralcFWFQWF2+NgCHShjkCb+IFBLq9buZwE1xckQU4peSuQ==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^3.2.1",
        "escape-string-regexp": "^1.0.5",
        "supports-color": "^5.3.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/chalk-template": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/chalk-template/-/chalk-template-0.4.0.tgz",
      "integrity": "sha512-/ghrgmhfY8RaSdeo43hNXxpoHAtxdbskUHjPpfqUWGttFgycUhYPGx3YZBCnUCvOa7Doivn1IZec3DEGFoMgLg==",
      "dev": true,
      "dependencies": {
        "chalk": "^4.1.2"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/chalk-template?sponsor=1"
      }
    },
    "node_modules/chalk-template/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/chalk-template/node_modules/chalk": {
      "version": "4.1.2",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-4.1.2.tgz",
      "integrity": "sha512-oKnbhFyRIXpUuez8iBMmyEa4nbj4IOQyuhc/wy9kY7/WVPcwIO9VA668Pu8RkO7+0G76SLROeyw9CpQ061i4mA==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/chalk/chalk?sponsor=1"
      }
    },
    "node_modules/chalk-template/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/chalk-template/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/chalk-template/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/chalk-template/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/chardet": {
      "version": "0.7.0",
      "resolved": "https://registry.npmjs.org/chardet/-/chardet-0.7.0.tgz",
      "integrity": "sha512-mT8iDcrh03qDGRRmoA2hmBJnxpllMR+0/0qlzjqZES6NdiWDcZkCNAk4rPFZ9Q85r27unkiNNg8ZOiwZXBHwcA==",
      "dev": true
    },
    "node_modules/ci-info": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ci-info/-/ci-info-2.0.0.tgz",
      "integrity": "sha512-5tK7EtrZ0N+OLFMthtqOj4fI2Jeb88C4CAZPu25LDVUgXJ0A3Js4PMGqrn0JU1W0Mh1/Z8wZzYPxqUrXeBboCQ==",
      "dev": true
    },
    "node_modules/class-transformer": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/class-transformer/-/class-transformer-0.4.0.tgz",
      "integrity": "sha512-ETWD/H2TbWbKEi7m9N4Km5+cw1hNcqJSxlSYhsLsNjQzWWiZIYA1zafxpK9PwVfaZ6AqR5rrjPVUBGESm5tQUA=="
    },
    "node_modules/class-utils": {
      "version": "0.3.6",
      "resolved": "https://registry.npmjs.org/class-utils/-/class-utils-0.3.6.tgz",
      "integrity": "sha512-qOhPa/Fj7s6TY8H8esGu5QNpMMQxz79h+urzrNYN6mn+9BnxlDGf5QZ+XeCDsxSjPqsSR56XOZOJmpeurnLMeg==",
      "dev": true,
      "dependencies": {
        "arr-union": "^3.1.0",
        "define-property": "^0.2.5",
        "isobject": "^3.0.0",
        "static-extend": "^0.1.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/class-utils/node_modules/define-property": {
      "version": "0.2.5",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
      "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
      "dev": true,
      "dependencies": {
        "is-descriptor": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/class-utils/node_modules/is-accessor-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
      "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/class-utils/node_modules/is-accessor-descriptor/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/class-utils/node_modules/is-data-descriptor": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
      "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/class-utils/node_modules/is-data-descriptor/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/class-utils/node_modules/is-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
      "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
      "dev": true,
      "dependencies": {
        "is-accessor-descriptor": "^0.1.6",
        "is-data-descriptor": "^0.1.4",
        "kind-of": "^5.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/class-utils/node_modules/kind-of": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
      "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/class-validator": {
      "version": "0.14.0",
      "resolved": "https://registry.npmjs.org/class-validator/-/class-validator-0.14.0.tgz",
      "integrity": "sha512-ct3ltplN8I9fOwUd8GrP8UQixwff129BkEtuWDKL5W45cQuLd19xqmTLu5ge78YDm/fdje6FMt0hGOhl0lii3A==",
      "dependencies": {
        "@types/validator": "^13.7.10",
        "libphonenumber-js": "^1.10.14",
        "validator": "^13.7.0"
      }
    },
    "node_modules/cli-boxes": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/cli-boxes/-/cli-boxes-3.0.0.tgz",
      "integrity": "sha512-/lzGpEWL/8PfI0BmBOPRwp0c/wFNX1RdUML3jK/RcSBA9T8mZDdQpqYBKtCFTOfQbwPqWEOpjqW+Fnayc0969g==",
      "dev": true,
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/cli-cursor": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/cli-cursor/-/cli-cursor-3.1.0.tgz",
      "integrity": "sha512-I/zHAwsKf9FqGoXM4WWRACob9+SNukZTd94DWF57E4toouRulbCxcUh6RKUEOQlYTHJnzkPMySvPNaaSLNfLZw==",
      "dev": true,
      "dependencies": {
        "restore-cursor": "^3.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/cli-table3": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/cli-table3/-/cli-table3-0.6.0.tgz",
      "integrity": "sha512-gnB85c3MGC7Nm9I/FkiasNBOKjOiO1RNuXXarQms37q4QMpWdlbBgD/VnOStA2faG1dpXMv31RFApjX1/QdgWQ==",
      "dev": true,
      "dependencies": {
        "object-assign": "^4.1.0",
        "string-width": "^4.2.0"
      },
      "engines": {
        "node": "10.* || >= 12.*"
      },
      "optionalDependencies": {
        "colors": "^1.1.2"
      }
    },
    "node_modules/cli-width": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/cli-width/-/cli-width-3.0.0.tgz",
      "integrity": "sha512-FxqpkPPwu1HjuN93Omfm4h8uIanXofW0RxVEW3k5RKx+mJJYSthzNhp32Kzxxy3YAEZ/Dc/EWN1vZRY0+kOhbw==",
      "dev": true,
      "engines": {
        "node": ">= 10"
      }
    },
    "node_modules/clipboardy": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/clipboardy/-/clipboardy-3.0.0.tgz",
      "integrity": "sha512-Su+uU5sr1jkUy1sGRpLKjKrvEOVXgSgiSInwa/qeID6aJ07yh+5NWc3h2QfjHjBnfX4LhtFcuAWKUsJ3r+fjbg==",
      "dev": true,
      "dependencies": {
        "arch": "^2.2.0",
        "execa": "^5.1.1",
        "is-wsl": "^2.2.0"
      },
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/clipboardy/node_modules/cross-spawn": {
      "version": "7.0.3",
      "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-7.0.3.tgz",
      "integrity": "sha512-iRDPJKUPVEND7dHPO8rkbOnPpyDygcDFtWjpeWNCgy8WP2rXcxXL8TskReQl6OrB2G7+UJrags1q15Fudc7G6w==",
      "dev": true,
      "dependencies": {
        "path-key": "^3.1.0",
        "shebang-command": "^2.0.0",
        "which": "^2.0.1"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/clipboardy/node_modules/execa": {
      "version": "5.1.1",
      "resolved": "https://registry.npmjs.org/execa/-/execa-5.1.1.tgz",
      "integrity": "sha512-8uSpZZocAZRBAPIEINJj3Lo9HyGitllczc27Eh5YYojjMFMn8yHMDMaUHE2Jqfq05D/wucwI4JGURyXt1vchyg==",
      "dev": true,
      "dependencies": {
        "cross-spawn": "^7.0.3",
        "get-stream": "^6.0.0",
        "human-signals": "^2.1.0",
        "is-stream": "^2.0.0",
        "merge-stream": "^2.0.0",
        "npm-run-path": "^4.0.1",
        "onetime": "^5.1.2",
        "signal-exit": "^3.0.3",
        "strip-final-newline": "^2.0.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sindresorhus/execa?sponsor=1"
      }
    },
    "node_modules/clipboardy/node_modules/get-stream": {
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/get-stream/-/get-stream-6.0.1.tgz",
      "integrity": "sha512-ts6Wi+2j3jQjqi70w5AlN8DFnkSwC+MqmxEzdEALB2qXZYV3X/b1CTfgPLGJNMeAWxdPfU8FO1ms3NUfaHCPYg==",
      "dev": true,
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/clipboardy/node_modules/human-signals": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/human-signals/-/human-signals-2.1.0.tgz",
      "integrity": "sha512-B4FFZ6q/T2jhhksgkbEW3HBvWIfDW85snkQgawt07S7J5QXTk6BkNV+0yAeZrM5QpMAdYlocGoljn0sJ/WQkFw==",
      "dev": true,
      "engines": {
        "node": ">=10.17.0"
      }
    },
    "node_modules/clipboardy/node_modules/path-key": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz",
      "integrity": "sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/clipboardy/node_modules/shebang-command": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/shebang-command/-/shebang-command-2.0.0.tgz",
      "integrity": "sha512-kHxr2zZpYtdmrN1qDjrrX/Z1rR1kG8Dx+gkpK1G4eXmvXswmcE1hTWBWYUzlraYw1/yZp6YuDY77YtvbN0dmDA==",
      "dev": true,
      "dependencies": {
        "shebang-regex": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/clipboardy/node_modules/shebang-regex": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/shebang-regex/-/shebang-regex-3.0.0.tgz",
      "integrity": "sha512-7++dFhtcx3353uBaq8DDR4NuxBetBzC7ZQOhmTQInHEd6bSrXdiEyzCvG07Z44UYdLShWUyXt5M/yhz8ekcb1A==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/clipboardy/node_modules/which": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/which/-/which-2.0.2.tgz",
      "integrity": "sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==",
      "dev": true,
      "dependencies": {
        "isexe": "^2.0.0"
      },
      "bin": {
        "node-which": "bin/node-which"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/cliui": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/cliui/-/cliui-6.0.0.tgz",
      "integrity": "sha512-t6wbgtoCXvAzst7QgXxJYqPt0usEfbgQdftEPbLL/cvv6HPE5VgvqCuAIDR0NgU52ds6rFwqrgakNLrHEjCbrQ==",
      "dev": true,
      "dependencies": {
        "string-width": "^4.2.0",
        "strip-ansi": "^6.0.0",
        "wrap-ansi": "^6.2.0"
      }
    },
    "node_modules/cliui/node_modules/strip-ansi": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
      "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^5.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/co": {
      "version": "4.6.0",
      "resolved": "https://registry.npmjs.org/co/-/co-4.6.0.tgz",
      "integrity": "sha1-bqa989hTrlTMuOR7+gvz+QMfsYQ=",
      "dev": true,
      "engines": {
        "iojs": ">= 1.0.0",
        "node": ">= 0.12.0"
      }
    },
    "node_modules/collect-v8-coverage": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/collect-v8-coverage/-/collect-v8-coverage-1.0.1.tgz",
      "integrity": "sha512-iBPtljfCNcTKNAto0KEtDfZ3qzjJvqE3aTGZsbhjSBlorqpXJlaWWtPO35D+ZImoC3KWejX64o+yPGxhWSTzfg==",
      "dev": true
    },
    "node_modules/collection-visit": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/collection-visit/-/collection-visit-1.0.0.tgz",
      "integrity": "sha1-S8A3PBZLwykbTTaMgpzxqApZ3KA=",
      "dev": true,
      "dependencies": {
        "map-visit": "^1.0.0",
        "object-visit": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/color-convert": {
      "version": "1.9.3",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-1.9.3.tgz",
      "integrity": "sha512-QfAUtd+vFdAtFQcC8CCyYt1fYWxSqAiK2cSD6zDB8N3cpsEBAvRxp9zOGg6G/SHHJYAT88/az/IuDGALsNVbGg==",
      "dev": true,
      "dependencies": {
        "color-name": "1.1.3"
      }
    },
    "node_modules/color-name": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.3.tgz",
      "integrity": "sha1-p9BVi9icQveV3UIyj3QIMcpTvCU=",
      "dev": true
    },
    "node_modules/colorette": {
      "version": "1.2.2",
      "resolved": "https://registry.npmjs.org/colorette/-/colorette-1.2.2.tgz",
      "integrity": "sha512-MKGMzyfeuutC/ZJ1cba9NqcNpfeqMUcYmyF1ZFY6/Cn7CNSAKx6a+s48sqLqyAiZuaP2TcqMhoo+dlwFnVxT9w==",
      "dev": true
    },
    "node_modules/colors": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/colors/-/colors-1.4.0.tgz",
      "integrity": "sha512-a+UqTh4kgZg/SlGvfbzDHpgRu7AAQOmmqRHJnxhRZICKFUT91brVhNNt58CMWU9PsBbv3PDCZUHbVxuDiH2mtA==",
      "dev": true,
      "engines": {
        "node": ">=0.1.90"
      }
    },
    "node_modules/combined-stream": {
      "version": "1.0.8",
      "resolved": "https://registry.npmjs.org/combined-stream/-/combined-stream-1.0.8.tgz",
      "integrity": "sha512-FQN4MRfuJeHf7cBbBMJFXhKSDq+2kAArBlmRBvcvFE5BB1HZKXtSFASDhdlz9zOYwxh8lDdnvmMOe/+5cdoEdg==",
      "dependencies": {
        "delayed-stream": "~1.0.0"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/commander": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/commander/-/commander-5.1.0.tgz",
      "integrity": "sha512-P0CysNDQ7rtVw4QIQtm+MRxV66vKFSvlsQvGYXZWR3qFU0jlMKHZZZgw8e+8DSah4UDKMqnknRDQz+xuQXQ/Zg==",
      "dev": true,
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/commondir": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/commondir/-/commondir-1.0.1.tgz",
      "integrity": "sha1-3dgA2gxmEnOTzKWVDqloo6rxJTs=",
      "dev": true
    },
    "node_modules/component-emitter": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/component-emitter/-/component-emitter-1.3.0.tgz",
      "integrity": "sha512-Rd3se6QB+sO1TwqZjscQrurpEPIfO0/yYnSin6Q/rD3mOutHvUrCAhJub3r90uNb+SESBuE0QYoB90YdfatsRg==",
      "dev": true
    },
    "node_modules/compressible": {
      "version": "2.0.18",
      "resolved": "https://registry.npmjs.org/compressible/-/compressible-2.0.18.tgz",
      "integrity": "sha512-AF3r7P5dWxL8MxyITRMlORQNaOA2IkAFaTr4k7BUumjPtRpGDTZpl0Pb1XCO6JeDCBdp126Cgs9sMxqSjgYyRg==",
      "dev": true,
      "dependencies": {
        "mime-db": ">= 1.43.0 < 2"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/compression": {
      "version": "1.7.4",
      "resolved": "https://registry.npmjs.org/compression/-/compression-1.7.4.tgz",
      "integrity": "sha512-jaSIDzP9pZVS4ZfQ+TzvtiWhdpFhE2RDHz8QJkpX9SIpLq88VueF5jJw6t+6CUQcAoA6t+x89MLrWAqpfDE8iQ==",
      "dev": true,
      "dependencies": {
        "accepts": "~1.3.5",
        "bytes": "3.0.0",
        "compressible": "~2.0.16",
        "debug": "2.6.9",
        "on-headers": "~1.0.2",
        "safe-buffer": "5.1.2",
        "vary": "~1.1.2"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/compression/node_modules/debug": {
      "version": "2.6.9",
      "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
      "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
      "dev": true,
      "dependencies": {
        "ms": "2.0.0"
      }
    },
    "node_modules/compression/node_modules/ms": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
      "integrity": "sha512-Tpp60P6IUJDTuOq/5Z8cdskzJujfwqfOTkrwIwj7IRISpnkJnT6SyJ4PCPnGMoFjC9ddhal5KVIYtAt97ix05A==",
      "dev": true
    },
    "node_modules/concat-map": {
      "version": "0.0.1",
      "resolved": "https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz",
      "integrity": "sha1-2Klr13/Wjfd5OnMDajug1UBdR3s=",
      "dev": true
    },
    "node_modules/contains-path": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/contains-path/-/contains-path-0.1.0.tgz",
      "integrity": "sha1-/ozxhP9mcLa67wGp1IYaXL7EEgo=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/content-disposition": {
      "version": "0.5.2",
      "resolved": "https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.2.tgz",
      "integrity": "sha512-kRGRZw3bLlFISDBgwTSA1TMBFN6J6GWDeubmDE3AF+3+yXL8hTWv8r5rkLbqYXY4RjPk/EzHnClI3zQf1cFmHA==",
      "dev": true,
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/convert-source-map": {
      "version": "1.7.0",
      "resolved": "https://registry.npmjs.org/convert-source-map/-/convert-source-map-1.7.0.tgz",
      "integrity": "sha512-4FJkXzKXEDB1snCFZlLP4gpC3JILicCpGbzG9f9G7tGqGCzETQ2hWPrcinA9oU4wtf2biUaEH5065UnMeR33oA==",
      "dev": true,
      "dependencies": {
        "safe-buffer": "~5.1.1"
      }
    },
    "node_modules/copy-descriptor": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/copy-descriptor/-/copy-descriptor-0.1.1.tgz",
      "integrity": "sha1-Z29us8OZl8LuGsOpJP1hJHSPV40=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/core-util-is": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz",
      "integrity": "sha1-tf1UIgqivFq1eqtxQMlAdUUDwac=",
      "dev": true
    },
    "node_modules/create-require": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/create-require/-/create-require-1.1.1.tgz",
      "integrity": "sha512-dcKFX3jn0MpIaXjisoRvexIJVEKzaq7z2rZKxf+MSr9TkdmHmsU4m2lcLojrj/FHl8mk5VxMmYA+ftRkP/3oKQ==",
      "dev": true
    },
    "node_modules/cross-fetch": {
      "version": "3.1.5",
      "resolved": "https://registry.npmjs.org/cross-fetch/-/cross-fetch-3.1.5.tgz",
      "integrity": "sha512-lvb1SBsI0Z7GDwmuid+mU3kWVBwTVUbe7S0H52yaaAdQOXq2YktTCZdlAcNKFzE6QtRz0snpw9bNiPeOIkkQvw==",
      "dependencies": {
        "node-fetch": "2.6.7"
      }
    },
    "node_modules/cross-spawn": {
      "version": "6.0.5",
      "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-6.0.5.tgz",
      "integrity": "sha512-eTVLrBSt7fjbDygz805pMnstIs2VTBNkRm0qxZd+M7A5XDdxVRWO5MxGBXZhjY4cqLYLdtrGqRf8mBPmzwSpWQ==",
      "dev": true,
      "dependencies": {
        "nice-try": "^1.0.4",
        "path-key": "^2.0.1",
        "semver": "^5.5.0",
        "shebang-command": "^1.2.0",
        "which": "^1.2.9"
      },
      "engines": {
        "node": ">=4.8"
      }
    },
    "node_modules/cross-spawn/node_modules/semver": {
      "version": "5.7.1",
      "resolved": "https://registry.npmjs.org/semver/-/semver-5.7.1.tgz",
      "integrity": "sha512-sauaDf/PZdVgrLTNYHRtpXa1iRiKcaebiKQ1BJdpQlWH2lCvexQdX55snPFyK7QzpudqbCI0qXFfOasHdyNDGQ==",
      "dev": true,
      "bin": {
        "semver": "bin/semver"
      }
    },
    "node_modules/cssom": {
      "version": "0.4.4",
      "resolved": "https://registry.npmjs.org/cssom/-/cssom-0.4.4.tgz",
      "integrity": "sha512-p3pvU7r1MyyqbTk+WbNJIgJjG2VmTIaB10rI93LzVPrmDJKkzKYMtxxyAvQXR/NS6otuzveI7+7BBq3SjBS2mw==",
      "dev": true
    },
    "node_modules/cssstyle": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/cssstyle/-/cssstyle-2.3.0.tgz",
      "integrity": "sha512-AZL67abkUzIuvcHqk7c09cezpGNcxUxU4Ioi/05xHk4DQeTkWmGYftIE6ctU6AEt+Gn4n1lDStOtj7FKycP71A==",
      "dev": true,
      "dependencies": {
        "cssom": "~0.3.6"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/cssstyle/node_modules/cssom": {
      "version": "0.3.8",
      "resolved": "https://registry.npmjs.org/cssom/-/cssom-0.3.8.tgz",
      "integrity": "sha512-b0tGHbfegbhPJpxpiBPU2sCkigAqtM9O121le6bbOlgyV+NyGyCmVfJ6QW9eRjz8CpNfWEOYBIMIGRYkLwsIYg==",
      "dev": true
    },
    "node_modules/d": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/d/-/d-1.0.1.tgz",
      "integrity": "sha512-m62ShEObQ39CfralilEQRjH6oAMtNCV1xJyEx5LpRYUVN+EviphDgUc/F3hnYbADmkiNs67Y+3ylmlG7Lnu+FA==",
      "dev": true,
      "dependencies": {
        "es5-ext": "^0.10.50",
        "type": "^1.0.1"
      }
    },
    "node_modules/dashdash": {
      "version": "1.14.1",
      "resolved": "https://registry.npmjs.org/dashdash/-/dashdash-1.14.1.tgz",
      "integrity": "sha1-hTz6D3y+L+1d4gMmuN1YEDX24vA=",
      "dev": true,
      "dependencies": {
        "assert-plus": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10"
      }
    },
    "node_modules/data-urls": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/data-urls/-/data-urls-1.1.0.tgz",
      "integrity": "sha512-YTWYI9se1P55u58gL5GkQHW4P6VJBJ5iBT+B5a7i2Tjadhv52paJG0qHX4A0OR6/t52odI64KP2YvFpkDOi3eQ==",
      "dev": true,
      "dependencies": {
        "abab": "^2.0.0",
        "whatwg-mimetype": "^2.2.0",
        "whatwg-url": "^7.0.0"
      }
    },
    "node_modules/debug": {
      "version": "4.3.1",
      "resolved": "https://registry.npmjs.org/debug/-/debug-4.3.1.tgz",
      "integrity": "sha512-doEwdvm4PCeK4K3RQN2ZC2BYUBaxwLARCqZmMjtF8a51J2Rb0xpVloFRnCODwqjpwnAoao4pelN8l3RJdv3gRQ==",
      "dev": true,
      "dependencies": {
        "ms": "2.1.2"
      },
      "engines": {
        "node": ">=6.0"
      },
      "peerDependenciesMeta": {
        "supports-color": {
          "optional": true
        }
      }
    },
    "node_modules/decamelize": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/decamelize/-/decamelize-1.2.0.tgz",
      "integrity": "sha1-9lNNFRSCabIDUue+4m9QH5oZEpA=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/decode-uri-component": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/decode-uri-component/-/decode-uri-component-0.2.0.tgz",
      "integrity": "sha1-6zkTMzRYd1y4TNGh+uBiEGu4dUU=",
      "dev": true,
      "engines": {
        "node": ">=0.10"
      }
    },
    "node_modules/deep-extend": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/deep-extend/-/deep-extend-0.6.0.tgz",
      "integrity": "sha512-LOHxIOaPYdHlJRtCQfDIVZtfw/ufM8+rVj649RIHzcm/vGwQRXFt6OPqIFWsm2XEMrNIEtWR64sY1LEKD2vAOA==",
      "dev": true,
      "engines": {
        "node": ">=4.0.0"
      }
    },
    "node_modules/deep-is": {
      "version": "0.1.3",
      "resolved": "https://registry.npmjs.org/deep-is/-/deep-is-0.1.3.tgz",
      "integrity": "sha1-s2nW+128E+7PUk+RsHD+7cNXzzQ=",
      "dev": true
    },
    "node_modules/deepmerge": {
      "version": "4.2.2",
      "resolved": "https://registry.npmjs.org/deepmerge/-/deepmerge-4.2.2.tgz",
      "integrity": "sha512-FJ3UgI4gIl+PHZm53knsuSFpE+nESMr7M4v9QcgB7S63Kj/6WqMiFQJpBBYz1Pt+66bZpP3Q7Lye0Oo9MPKEdg==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/define-properties": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/define-properties/-/define-properties-1.1.3.tgz",
      "integrity": "sha512-3MqfYKj2lLzdMSf8ZIZE/V+Zuy+BgD6f164e8K2w7dgnpKArBDerGYpM46IYYcjnkdPNMjPk9A6VFB8+3SKlXQ==",
      "dev": true,
      "dependencies": {
        "object-keys": "^1.0.12"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/define-property": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-2.0.2.tgz",
      "integrity": "sha512-jwK2UV4cnPpbcG7+VRARKTZPUWowwXA8bzH5NP6ud0oeAxyYPuGZUAC7hMugpCdz4BeSZl2Dl9k66CHJ/46ZYQ==",
      "dev": true,
      "dependencies": {
        "is-descriptor": "^1.0.2",
        "isobject": "^3.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/delayed-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delayed-stream/-/delayed-stream-1.0.0.tgz",
      "integrity": "sha1-3zrhmayt+31ECqrgsp4icrJOxhk=",
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/detect-newline": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/detect-newline/-/detect-newline-3.1.0.tgz",
      "integrity": "sha512-TLz+x/vEXm/Y7P7wn1EJFNLxYpUD4TgMosxY6fAVJUnJMbupHBOncxyWUG9OpTaH9EBD7uFI5LfEgmMOc54DsA==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/diff": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/diff/-/diff-4.0.2.tgz",
      "integrity": "sha512-58lmxKSA4BNyLz+HHMUzlOEpg09FV+ev6ZMe3vJihgdxzgcwZ8VoEEPmALCZG9LmqfVoNMMKpttIYTVG6uDY7A==",
      "dev": true,
      "engines": {
        "node": ">=0.3.1"
      }
    },
    "node_modules/diff-sequences": {
      "version": "25.2.6",
      "resolved": "https://registry.npmjs.org/diff-sequences/-/diff-sequences-25.2.6.tgz",
      "integrity": "sha512-Hq8o7+6GaZeoFjtpgvRBUknSXNeJiCx7V9Fr94ZMljNiCr9n9L8H8aJqgWOQiDDGdyn29fRNcDdRVJ5fdyihfg==",
      "dev": true,
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/doctrine": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/doctrine/-/doctrine-3.0.0.tgz",
      "integrity": "sha512-yS+Q5i3hBf7GBkd4KG8a7eBNNWNGLTaEwwYWUijIYM7zrlYDM0BFXHjjPWlWZ1Rg7UaddZeIDmi9jF3HmqiQ2w==",
      "dev": true,
      "dependencies": {
        "esutils": "^2.0.2"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/domexception": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/domexception/-/domexception-1.0.1.tgz",
      "integrity": "sha512-raigMkn7CJNNo6Ihro1fzG7wr3fHuYVytzquZKX5n0yizGsTcYgzdIUwj1X9pK0VvjeihV+XiclP+DjwbsSKug==",
      "dev": true,
      "dependencies": {
        "webidl-conversions": "^4.0.2"
      }
    },
    "node_modules/duration": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/duration/-/duration-0.2.2.tgz",
      "integrity": "sha512-06kgtea+bGreF5eKYgI/36A6pLXggY7oR4p1pq4SmdFBn1ReOL5D8RhG64VrqfTTKNucqqtBAwEj8aB88mcqrg==",
      "dev": true,
      "dependencies": {
        "d": "1",
        "es5-ext": "~0.10.46"
      }
    },
    "node_modules/durations": {
      "version": "3.4.2",
      "resolved": "https://registry.npmjs.org/durations/-/durations-3.4.2.tgz",
      "integrity": "sha512-V/lf7y33dGaypZZetVI1eu7BmvkbC4dItq12OElLRpKuaU5JxQstV2zHwLv8P7cNbQ+KL1WD80zMCTx5dNC4dg==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/eastasianwidth": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/eastasianwidth/-/eastasianwidth-0.2.0.tgz",
      "integrity": "sha512-I88TYZWc9XiYHRQ4/3c5rjjfgkjhLyW2luGIheGERbNQ6OY7yTybanSpDXZa8y7VUP9YmDcYa+eyq4ca7iLqWA==",
      "dev": true
    },
    "node_modules/ecc-jsbn": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.2.tgz",
      "integrity": "sha1-OoOpBOVDUyh4dMVkt1SThoSamMk=",
      "dev": true,
      "dependencies": {
        "jsbn": "~0.1.0",
        "safer-buffer": "^2.1.0"
      }
    },
    "node_modules/electron-to-chromium": {
      "version": "1.3.752",
      "resolved": "https://registry.npmjs.org/electron-to-chromium/-/electron-to-chromium-1.3.752.tgz",
      "integrity": "sha512-2Tg+7jSl3oPxgsBsWKh5H83QazTkmWG/cnNwJplmyZc7KcN61+I10oUgaXSVk/NwfvN3BdkKDR4FYuRBQQ2v0A==",
      "dev": true
    },
    "node_modules/elliptic": {
      "version": "6.5.4",
      "resolved": "https://registry.npmjs.org/elliptic/-/elliptic-6.5.4.tgz",
      "integrity": "sha512-iLhC6ULemrljPZb+QutR5TQGB+pdW6KGD5RSegS+8sorOZT+rdQFbsQFJgvN3eRqNALqJer4oQ16YvJHlU8hzQ==",
      "dependencies": {
        "bn.js": "^4.11.9",
        "brorand": "^1.1.0",
        "hash.js": "^1.0.0",
        "hmac-drbg": "^1.0.1",
        "inherits": "^2.0.4",
        "minimalistic-assert": "^1.0.1",
        "minimalistic-crypto-utils": "^1.0.1"
      }
    },
    "node_modules/elliptic/node_modules/bn.js": {
      "version": "4.12.0",
      "resolved": "https://registry.npmjs.org/bn.js/-/bn.js-4.12.0.tgz",
      "integrity": "sha512-c98Bf3tPniI+scsdk237ku1Dc3ujXQTSgyiPUDEOe7tRkhrqridvh8klBv0HCEso1OLOYcHuCv/cS6DNxKH+ZA=="
    },
    "node_modules/email-addresses": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/email-addresses/-/email-addresses-3.1.0.tgz",
      "integrity": "sha512-k0/r7GrWVL32kZlGwfPNgB2Y/mMXVTq/decgLczm/j34whdaspNrZO8CnXPf1laaHxI6ptUlsnAxN+UAPw+fzg==",
      "dev": true
    },
    "node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "dev": true
    },
    "node_modules/end-of-stream": {
      "version": "1.4.4",
      "resolved": "https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.4.4.tgz",
      "integrity": "sha512-+uw1inIHVPQoaVuHzRyXd21icM+cnt4CzD5rW+NC1wjOUSTOs+Te7FOv7AhN7vS9x/oIyhLP5PR1H+phQAHu5Q==",
      "dev": true,
      "dependencies": {
        "once": "^1.4.0"
      }
    },
    "node_modules/error-ex": {
      "version": "1.3.2",
      "resolved": "https://registry.npmjs.org/error-ex/-/error-ex-1.3.2.tgz",
      "integrity": "sha512-7dFHNmqeFSEt2ZBsCriorKnn3Z2pj+fd9kmI6QoWw4//DL+icEBfc0U7qJCisqrTsKTjw4fNFy2pW9OqStD84g==",
      "dev": true,
      "dependencies": {
        "is-arrayish": "^0.2.1"
      }
    },
    "node_modules/error-stack-parser": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/error-stack-parser/-/error-stack-parser-2.0.6.tgz",
      "integrity": "sha512-d51brTeqC+BHlwF0BhPtcYgF5nlzf9ZZ0ZIUQNZpc9ZB9qw5IJ2diTrBY9jlCJkTLITYPjmiX6OWCwH+fuyNgQ==",
      "dev": true,
      "dependencies": {
        "stackframe": "^1.1.1"
      }
    },
    "node_modules/es-abstract": {
      "version": "1.18.3",
      "resolved": "https://registry.npmjs.org/es-abstract/-/es-abstract-1.18.3.tgz",
      "integrity": "sha512-nQIr12dxV7SSxE6r6f1l3DtAeEYdsGpps13dR0TwJg1S8gyp4ZPgy3FZcHBgbiQqnoqSTb+oC+kO4UQ0C/J8vw==",
      "dev": true,
      "dependencies": {
        "call-bind": "^1.0.2",
        "es-to-primitive": "^1.2.1",
        "function-bind": "^1.1.1",
        "get-intrinsic": "^1.1.1",
        "has": "^1.0.3",
        "has-symbols": "^1.0.2",
        "is-callable": "^1.2.3",
        "is-negative-zero": "^2.0.1",
        "is-regex": "^1.1.3",
        "is-string": "^1.0.6",
        "object-inspect": "^1.10.3",
        "object-keys": "^1.1.1",
        "object.assign": "^4.1.2",
        "string.prototype.trimend": "^1.0.4",
        "string.prototype.trimstart": "^1.0.4",
        "unbox-primitive": "^1.0.1"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/es-to-primitive": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/es-to-primitive/-/es-to-primitive-1.2.1.tgz",
      "integrity": "sha512-QCOllgZJtaUo9miYBcLChTUaHNjJF3PYs1VidD7AwiEj1kYxKeQTctLAezAOH5ZKRH0g2IgPn6KwB4IT8iRpvA==",
      "dev": true,
      "dependencies": {
        "is-callable": "^1.1.4",
        "is-date-object": "^1.0.1",
        "is-symbol": "^1.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/es5-ext": {
      "version": "0.10.53",
      "resolved": "https://registry.npmjs.org/es5-ext/-/es5-ext-0.10.53.tgz",
      "integrity": "sha512-Xs2Stw6NiNHWypzRTY1MtaG/uJlwCk8kH81920ma8mvN8Xq1gsfhZvpkImLQArw8AHnv8MT2I45J3c0R8slE+Q==",
      "dev": true,
      "dependencies": {
        "es6-iterator": "~2.0.3",
        "es6-symbol": "~3.1.3",
        "next-tick": "~1.0.0"
      }
    },
    "node_modules/es6-iterator": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/es6-iterator/-/es6-iterator-2.0.3.tgz",
      "integrity": "sha1-p96IkUGgWpSwhUQDstCg+/qY87c=",
      "dev": true,
      "dependencies": {
        "d": "1",
        "es5-ext": "^0.10.35",
        "es6-symbol": "^3.1.1"
      }
    },
    "node_modules/es6-symbol": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.1.3.tgz",
      "integrity": "sha512-NJ6Yn3FuDinBaBRWl/q5X/s4koRHBrgKAu+yGI6JCBeiu3qrcbJhwT2GeR/EXVfylRk8dpQVJoLEFhK+Mu31NA==",
      "dev": true,
      "dependencies": {
        "d": "^1.0.1",
        "ext": "^1.1.2"
      }
    },
    "node_modules/escalade": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/escalade/-/escalade-3.1.1.tgz",
      "integrity": "sha512-k0er2gUkLf8O0zKJiAhmkTnJlTvINGv7ygDNPbeIsX/TJjGJZHuh9B2UxbsaEkmlEo9MfhrSzmhIlhRlI2GXnw==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/escape-string-regexp": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz",
      "integrity": "sha1-G2HAViGQqN/2rjuyzwIAyhMLhtQ=",
      "dev": true,
      "engines": {
        "node": ">=0.8.0"
      }
    },
    "node_modules/escodegen": {
      "version": "1.14.3",
      "resolved": "https://registry.npmjs.org/escodegen/-/escodegen-1.14.3.tgz",
      "integrity": "sha512-qFcX0XJkdg+PB3xjZZG/wKSuT1PnQWx57+TVSjIMmILd2yC/6ByYElPwJnslDsuWuSAp4AwJGumarAAmJch5Kw==",
      "dev": true,
      "dependencies": {
        "esprima": "^4.0.1",
        "estraverse": "^4.2.0",
        "esutils": "^2.0.2",
        "optionator": "^0.8.1"
      },
      "bin": {
        "escodegen": "bin/escodegen.js",
        "esgenerate": "bin/esgenerate.js"
      },
      "engines": {
        "node": ">=4.0"
      },
      "optionalDependencies": {
        "source-map": "~0.6.1"
      }
    },
    "node_modules/eslint": {
      "version": "6.8.0",
      "resolved": "https://registry.npmjs.org/eslint/-/eslint-6.8.0.tgz",
      "integrity": "sha512-K+Iayyo2LtyYhDSYwz5D5QdWw0hCacNzyq1Y821Xna2xSJj7cijoLLYmLxTQgcgZ9mC61nryMy9S7GRbYpI5Ig==",
      "dev": true,
      "dependencies": {
        "@babel/code-frame": "^7.0.0",
        "ajv": "^6.10.0",
        "chalk": "^2.1.0",
        "cross-spawn": "^6.0.5",
        "debug": "^4.0.1",
        "doctrine": "^3.0.0",
        "eslint-scope": "^5.0.0",
        "eslint-utils": "^1.4.3",
        "eslint-visitor-keys": "^1.1.0",
        "espree": "^6.1.2",
        "esquery": "^1.0.1",
        "esutils": "^2.0.2",
        "file-entry-cache": "^5.0.1",
        "functional-red-black-tree": "^1.0.1",
        "glob-parent": "^5.0.0",
        "globals": "^12.1.0",
        "ignore": "^4.0.6",
        "import-fresh": "^3.0.0",
        "imurmurhash": "^0.1.4",
        "inquirer": "^7.0.0",
        "is-glob": "^4.0.0",
        "js-yaml": "^3.13.1",
        "json-stable-stringify-without-jsonify": "^1.0.1",
        "levn": "^0.3.0",
        "lodash": "^4.17.14",
        "minimatch": "^3.0.4",
        "mkdirp": "^0.5.1",
        "natural-compare": "^1.4.0",
        "optionator": "^0.8.3",
        "progress": "^2.0.0",
        "regexpp": "^2.0.1",
        "semver": "^6.1.2",
        "strip-ansi": "^5.2.0",
        "strip-json-comments": "^3.0.1",
        "table": "^5.2.3",
        "text-table": "^0.2.0",
        "v8-compile-cache": "^2.0.3"
      },
      "bin": {
        "eslint": "bin/eslint.js"
      },
      "engines": {
        "node": "^8.10.0 || ^10.13.0 || >=11.10.1"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/eslint-config-prettier": {
      "version": "6.11.0",
      "resolved": "https://registry.npmjs.org/eslint-config-prettier/-/eslint-config-prettier-6.11.0.tgz",
      "integrity": "sha512-oB8cpLWSAjOVFEJhhyMZh6NOEOtBVziaqdDQ86+qhDHFbZXoRTM7pNSvFRfW/W/L/LrQ38C99J5CGuRBBzBsdA==",
      "dev": true,
      "dependencies": {
        "get-stdin": "^6.0.0"
      },
      "bin": {
        "eslint-config-prettier-check": "bin/cli.js"
      },
      "peerDependencies": {
        "eslint": ">=3.14.1"
      }
    },
    "node_modules/eslint-import-resolver-node": {
      "version": "0.3.4",
      "resolved": "https://registry.npmjs.org/eslint-import-resolver-node/-/eslint-import-resolver-node-0.3.4.tgz",
      "integrity": "sha512-ogtf+5AB/O+nM6DIeBUNr2fuT7ot9Qg/1harBfBtaP13ekEWFQEEMP94BCB7zaNW3gyY+8SHYF00rnqYwXKWOA==",
      "dev": true,
      "dependencies": {
        "debug": "^2.6.9",
        "resolve": "^1.13.1"
      }
    },
    "node_modules/eslint-import-resolver-node/node_modules/debug": {
      "version": "2.6.9",
      "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
      "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
      "dev": true,
      "dependencies": {
        "ms": "2.0.0"
      }
    },
    "node_modules/eslint-import-resolver-node/node_modules/ms": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
      "integrity": "sha1-VgiurfwAvmwpAd9fmGF4jeDVl8g=",
      "dev": true
    },
    "node_modules/eslint-module-utils": {
      "version": "2.6.1",
      "resolved": "https://registry.npmjs.org/eslint-module-utils/-/eslint-module-utils-2.6.1.tgz",
      "integrity": "sha512-ZXI9B8cxAJIH4nfkhTwcRTEAnrVfobYqwjWy/QMCZ8rHkZHFjf9yO4BzpiF9kCSfNlMG54eKigISHpX0+AaT4A==",
      "dev": true,
      "dependencies": {
        "debug": "^3.2.7",
        "pkg-dir": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint-module-utils/node_modules/debug": {
      "version": "3.2.7",
      "resolved": "https://registry.npmjs.org/debug/-/debug-3.2.7.tgz",
      "integrity": "sha512-CFjzYYAi4ThfiQvizrFQevTTXHtnCqWfe7x1AhgEscTz6ZbLbfoLRLPugTQyBth6f8ZERVUSyWHFD/7Wu4t1XQ==",
      "dev": true,
      "dependencies": {
        "ms": "^2.1.1"
      }
    },
    "node_modules/eslint-plugin-import": {
      "version": "2.20.2",
      "resolved": "https://registry.npmjs.org/eslint-plugin-import/-/eslint-plugin-import-2.20.2.tgz",
      "integrity": "sha512-FObidqpXrR8OnCh4iNsxy+WACztJLXAHBO5hK79T1Hc77PgQZkyDGA5Ag9xAvRpglvLNxhH/zSmZ70/pZ31dHg==",
      "dev": true,
      "dependencies": {
        "array-includes": "^3.0.3",
        "array.prototype.flat": "^1.2.1",
        "contains-path": "^0.1.0",
        "debug": "^2.6.9",
        "doctrine": "1.5.0",
        "eslint-import-resolver-node": "^0.3.2",
        "eslint-module-utils": "^2.4.1",
        "has": "^1.0.3",
        "minimatch": "^3.0.4",
        "object.values": "^1.1.0",
        "read-pkg-up": "^2.0.0",
        "resolve": "^1.12.0"
      },
      "engines": {
        "node": ">=4"
      },
      "peerDependencies": {
        "eslint": "2.x - 6.x"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/debug": {
      "version": "2.6.9",
      "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
      "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
      "dev": true,
      "dependencies": {
        "ms": "2.0.0"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/doctrine": {
      "version": "1.5.0",
      "resolved": "https://registry.npmjs.org/doctrine/-/doctrine-1.5.0.tgz",
      "integrity": "sha1-N53Ocw9hZvds76TmcHoVmwLFpvo=",
      "dev": true,
      "dependencies": {
        "esutils": "^2.0.2",
        "isarray": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/find-up": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/find-up/-/find-up-2.1.0.tgz",
      "integrity": "sha1-RdG35QbHF93UgndaK3eSCjwMV6c=",
      "dev": true,
      "dependencies": {
        "locate-path": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/locate-path": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/locate-path/-/locate-path-2.0.0.tgz",
      "integrity": "sha1-K1aLJl7slExtnA3pw9u7ygNUzY4=",
      "dev": true,
      "dependencies": {
        "p-locate": "^2.0.0",
        "path-exists": "^3.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/ms": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
      "integrity": "sha1-VgiurfwAvmwpAd9fmGF4jeDVl8g=",
      "dev": true
    },
    "node_modules/eslint-plugin-import/node_modules/p-limit": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/p-limit/-/p-limit-1.3.0.tgz",
      "integrity": "sha512-vvcXsLAJ9Dr5rQOPk7toZQZJApBl2K4J6dANSsEuh6QI41JYcsS/qhTGa9ErIUUgK3WNQoJYvylxvjqmiqEA9Q==",
      "dev": true,
      "dependencies": {
        "p-try": "^1.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/p-locate": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/p-locate/-/p-locate-2.0.0.tgz",
      "integrity": "sha1-IKAQOyIqcMj9OcwuWAaA893l7EM=",
      "dev": true,
      "dependencies": {
        "p-limit": "^1.1.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/p-try": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/p-try/-/p-try-1.0.0.tgz",
      "integrity": "sha1-y8ec26+P1CKOE/Yh8rGiN8GyB7M=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/path-exists": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/path-exists/-/path-exists-3.0.0.tgz",
      "integrity": "sha1-zg6+ql94yxiSXqfYENe1mwEP1RU=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/read-pkg": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/read-pkg/-/read-pkg-2.0.0.tgz",
      "integrity": "sha1-jvHAYjxqbbDcZxPEv6xGMysjaPg=",
      "dev": true,
      "dependencies": {
        "load-json-file": "^2.0.0",
        "normalize-package-data": "^2.3.2",
        "path-type": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint-plugin-import/node_modules/read-pkg-up": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/read-pkg-up/-/read-pkg-up-2.0.0.tgz",
      "integrity": "sha1-a3KoBImE4MQeeVEP1en6mbO1Sb4=",
      "dev": true,
      "dependencies": {
        "find-up": "^2.0.0",
        "read-pkg": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint-scope": {
      "version": "5.1.1",
      "resolved": "https://registry.npmjs.org/eslint-scope/-/eslint-scope-5.1.1.tgz",
      "integrity": "sha512-2NxwbF/hZ0KpepYN0cNbo+FN6XoK7GaHlQhgx/hIZl6Va0bF45RQOOwhLIy8lQDbuCiadSLCBnH2CFYquit5bw==",
      "dev": true,
      "dependencies": {
        "esrecurse": "^4.3.0",
        "estraverse": "^4.1.1"
      },
      "engines": {
        "node": ">=8.0.0"
      }
    },
    "node_modules/eslint-utils": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/eslint-utils/-/eslint-utils-2.1.0.tgz",
      "integrity": "sha512-w94dQYoauyvlDc43XnGB8lU3Zt713vNChgt4EWwhXAP2XkBvndfxF0AgIqKOOasjPIPzj9JqgwkwbCYD0/V3Zg==",
      "dev": true,
      "dependencies": {
        "eslint-visitor-keys": "^1.1.0"
      },
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/mysticatea"
      }
    },
    "node_modules/eslint-visitor-keys": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/eslint-visitor-keys/-/eslint-visitor-keys-1.3.0.tgz",
      "integrity": "sha512-6J72N8UNa462wa/KFODt/PJ3IU60SDpC3QXC1Hjc1BXXpfL2C9R5+AU7jhe0F6GREqVMh4Juu+NY7xn+6dipUQ==",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/eslint/node_modules/eslint-utils": {
      "version": "1.4.3",
      "resolved": "https://registry.npmjs.org/eslint-utils/-/eslint-utils-1.4.3.tgz",
      "integrity": "sha512-fbBN5W2xdY45KulGXmLHZ3c3FHfVYmKg0IrAKGOkT/464PQsx2UeIzfz1RmEci+KLm1bBaAzZAh8+/E+XAeZ8Q==",
      "dev": true,
      "dependencies": {
        "eslint-visitor-keys": "^1.1.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/eslint/node_modules/regexpp": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/regexpp/-/regexpp-2.0.1.tgz",
      "integrity": "sha512-lv0M6+TkDVniA3aD1Eg0DVpfU/booSu7Eev3TDO/mZKHBfVjgCGTV4t4buppESEYDtkArYFOxTJWv6S5C+iaNw==",
      "dev": true,
      "engines": {
        "node": ">=6.5.0"
      }
    },
    "node_modules/eslint/node_modules/semver": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
      "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/espree": {
      "version": "6.2.1",
      "resolved": "https://registry.npmjs.org/espree/-/espree-6.2.1.tgz",
      "integrity": "sha512-ysCxRQY3WaXJz9tdbWOwuWr5Y/XrPTGX9Kiz3yoUXwW0VZ4w30HTkQLaGx/+ttFjF8i+ACbArnB4ce68a9m5hw==",
      "dev": true,
      "dependencies": {
        "acorn": "^7.1.1",
        "acorn-jsx": "^5.2.0",
        "eslint-visitor-keys": "^1.1.0"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/esprima": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/esprima/-/esprima-4.0.1.tgz",
      "integrity": "sha512-eGuFFw7Upda+g4p+QHvnW0RyTX/SVeJBDM/gCtMARO0cLuT2HcEKnTPvhjV6aGeqrCB/sbNop0Kszm0jsaWU4A==",
      "dev": true,
      "bin": {
        "esparse": "bin/esparse.js",
        "esvalidate": "bin/esvalidate.js"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/esquery": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/esquery/-/esquery-1.4.0.tgz",
      "integrity": "sha512-cCDispWt5vHHtwMY2YrAQ4ibFkAL8RbH5YGBnZBc90MolvvfkkQcJro/aZiAQUlQ3qgrYS6D6v8Gc5G5CQsc9w==",
      "dev": true,
      "dependencies": {
        "estraverse": "^5.1.0"
      },
      "engines": {
        "node": ">=0.10"
      }
    },
    "node_modules/esquery/node_modules/estraverse": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/estraverse/-/estraverse-5.2.0.tgz",
      "integrity": "sha512-BxbNGGNm0RyRYvUdHpIwv9IWzeM9XClbOxwoATuFdOE7ZE6wHL+HQ5T8hoPM+zHvmKzzsEqhgy0GrQ5X13afiQ==",
      "dev": true,
      "engines": {
        "node": ">=4.0"
      }
    },
    "node_modules/esrecurse": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/esrecurse/-/esrecurse-4.3.0.tgz",
      "integrity": "sha512-KmfKL3b6G+RXvP8N1vr3Tq1kL/oCFgn2NYXEtqP8/L3pKapUA4G8cFVaoF3SU323CD4XypR/ffioHmkti6/Tag==",
      "dev": true,
      "dependencies": {
        "estraverse": "^5.2.0"
      },
      "engines": {
        "node": ">=4.0"
      }
    },
    "node_modules/esrecurse/node_modules/estraverse": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/estraverse/-/estraverse-5.2.0.tgz",
      "integrity": "sha512-BxbNGGNm0RyRYvUdHpIwv9IWzeM9XClbOxwoATuFdOE7ZE6wHL+HQ5T8hoPM+zHvmKzzsEqhgy0GrQ5X13afiQ==",
      "dev": true,
      "engines": {
        "node": ">=4.0"
      }
    },
    "node_modules/estraverse": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/estraverse/-/estraverse-4.3.0.tgz",
      "integrity": "sha512-39nnKffWz8xN1BU/2c79n9nB9HDzo0niYUqx6xyqUnyoAnQyyWpOTdZEeiCch8BBu515t4wp9ZmgVfVhn9EBpw==",
      "dev": true,
      "engines": {
        "node": ">=4.0"
      }
    },
    "node_modules/esutils": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/esutils/-/esutils-2.0.3.tgz",
      "integrity": "sha512-kVscqXk4OCp68SZ0dkgEKVi6/8ij300KBWTJq32P/dYeWTSwK41WyTxalN1eRmA5Z9UU/LX9D7FWSmV9SAYx6g==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/eth-rpc-errors": {
      "version": "4.0.3",
      "resolved": "https://registry.npmjs.org/eth-rpc-errors/-/eth-rpc-errors-4.0.3.tgz",
      "integrity": "sha512-Z3ymjopaoft7JDoxZcEb3pwdGh7yiYMhOwm2doUt6ASXlMavpNlK6Cre0+IMl2VSGyEU9rkiperQhp5iRxn5Pg==",
      "dependencies": {
        "fast-safe-stringify": "^2.0.6"
      }
    },
    "node_modules/ethers": {
      "version": "5.6.8",
      "resolved": "https://registry.npmjs.org/ethers/-/ethers-5.6.8.tgz",
      "integrity": "sha512-YxIGaltAOdvBFPZwIkyHnXbW40f1r8mHUgapW6dxkO+6t7H6wY8POUn0Kbxrd/N7I4hHxyi7YCddMAH/wmho2w==",
      "dev": true,
      "funding": [
        {
          "type": "individual",
          "url": "https://gitcoin.co/grants/13/ethersjs-complete-simple-and-tiny-2"
        },
        {
          "type": "individual",
          "url": "https://www.buymeacoffee.com/ricmoo"
        }
      ],
      "dependencies": {
        "@ethersproject/abi": "5.6.3",
        "@ethersproject/abstract-provider": "5.6.1",
        "@ethersproject/abstract-signer": "5.6.2",
        "@ethersproject/address": "5.6.1",
        "@ethersproject/base64": "5.6.1",
        "@ethersproject/basex": "5.6.1",
        "@ethersproject/bignumber": "5.6.2",
        "@ethersproject/bytes": "5.6.1",
        "@ethersproject/constants": "5.6.1",
        "@ethersproject/contracts": "5.6.2",
        "@ethersproject/hash": "5.6.1",
        "@ethersproject/hdnode": "5.6.2",
        "@ethersproject/json-wallets": "5.6.1",
        "@ethersproject/keccak256": "5.6.1",
        "@ethersproject/logger": "5.6.0",
        "@ethersproject/networks": "5.6.3",
        "@ethersproject/pbkdf2": "5.6.1",
        "@ethersproject/properties": "5.6.0",
        "@ethersproject/providers": "5.6.8",
        "@ethersproject/random": "5.6.1",
        "@ethersproject/rlp": "5.6.1",
        "@ethersproject/sha2": "5.6.1",
        "@ethersproject/signing-key": "5.6.2",
        "@ethersproject/solidity": "5.6.1",
        "@ethersproject/strings": "5.6.1",
        "@ethersproject/transactions": "5.6.2",
        "@ethersproject/units": "5.6.1",
        "@ethersproject/wallet": "5.6.2",
        "@ethersproject/web": "5.6.1",
        "@ethersproject/wordlists": "5.6.1"
      }
    },
    "node_modules/eventemitter3": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/eventemitter3/-/eventemitter3-3.1.2.tgz",
      "integrity": "sha512-tvtQIeLVHjDkJYnzf2dgVMxfuSGJeM/7UCG17TT4EumTfNtF+0nebF/4zWOIkCreAbtNqhGEboB6BWrwqNaw4Q=="
    },
    "node_modules/exec-sh": {
      "version": "0.3.6",
      "resolved": "https://registry.npmjs.org/exec-sh/-/exec-sh-0.3.6.tgz",
      "integrity": "sha512-nQn+hI3yp+oD0huYhKwvYI32+JFeq+XkNcD1GAo3Y/MjxsfVGmrrzrnzjWiNY6f+pUCP440fThsFh5gZrRAU/w==",
      "dev": true
    },
    "node_modules/execa": {
      "version": "3.4.0",
      "resolved": "https://registry.npmjs.org/execa/-/execa-3.4.0.tgz",
      "integrity": "sha512-r9vdGQk4bmCuK1yKQu1KTwcT2zwfWdbdaXfCtAh+5nU/4fSX+JAb7vZGvI5naJrQlvONrEB20jeruESI69530g==",
      "dev": true,
      "dependencies": {
        "cross-spawn": "^7.0.0",
        "get-stream": "^5.0.0",
        "human-signals": "^1.1.1",
        "is-stream": "^2.0.0",
        "merge-stream": "^2.0.0",
        "npm-run-path": "^4.0.0",
        "onetime": "^5.1.0",
        "p-finally": "^2.0.0",
        "signal-exit": "^3.0.2",
        "strip-final-newline": "^2.0.0"
      },
      "engines": {
        "node": "^8.12.0 || >=9.7.0"
      }
    },
    "node_modules/execa/node_modules/cross-spawn": {
      "version": "7.0.3",
      "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-7.0.3.tgz",
      "integrity": "sha512-iRDPJKUPVEND7dHPO8rkbOnPpyDygcDFtWjpeWNCgy8WP2rXcxXL8TskReQl6OrB2G7+UJrags1q15Fudc7G6w==",
      "dev": true,
      "dependencies": {
        "path-key": "^3.1.0",
        "shebang-command": "^2.0.0",
        "which": "^2.0.1"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/execa/node_modules/path-key": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz",
      "integrity": "sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/execa/node_modules/shebang-command": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/shebang-command/-/shebang-command-2.0.0.tgz",
      "integrity": "sha512-kHxr2zZpYtdmrN1qDjrrX/Z1rR1kG8Dx+gkpK1G4eXmvXswmcE1hTWBWYUzlraYw1/yZp6YuDY77YtvbN0dmDA==",
      "dev": true,
      "dependencies": {
        "shebang-regex": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/execa/node_modules/shebang-regex": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/shebang-regex/-/shebang-regex-3.0.0.tgz",
      "integrity": "sha512-7++dFhtcx3353uBaq8DDR4NuxBetBzC7ZQOhmTQInHEd6bSrXdiEyzCvG07Z44UYdLShWUyXt5M/yhz8ekcb1A==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/execa/node_modules/which": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/which/-/which-2.0.2.tgz",
      "integrity": "sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==",
      "dev": true,
      "dependencies": {
        "isexe": "^2.0.0"
      },
      "bin": {
        "node-which": "bin/node-which"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/exit": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/exit/-/exit-0.1.2.tgz",
      "integrity": "sha1-BjJjj42HfMghB9MKD/8aF8uhzQw=",
      "dev": true,
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/expand-brackets": {
      "version": "2.1.4",
      "resolved": "https://registry.npmjs.org/expand-brackets/-/expand-brackets-2.1.4.tgz",
      "integrity": "sha1-t3c14xXOMPa27/D4OwQVGiJEliI=",
      "dev": true,
      "dependencies": {
        "debug": "^2.3.3",
        "define-property": "^0.2.5",
        "extend-shallow": "^2.0.1",
        "posix-character-classes": "^0.1.0",
        "regex-not": "^1.0.0",
        "snapdragon": "^0.8.1",
        "to-regex": "^3.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/debug": {
      "version": "2.6.9",
      "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
      "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
      "dev": true,
      "dependencies": {
        "ms": "2.0.0"
      }
    },
    "node_modules/expand-brackets/node_modules/define-property": {
      "version": "0.2.5",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
      "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
      "dev": true,
      "dependencies": {
        "is-descriptor": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/extend-shallow": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
      "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
      "dev": true,
      "dependencies": {
        "is-extendable": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/is-accessor-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
      "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/is-accessor-descriptor/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/is-data-descriptor": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
      "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/is-data-descriptor/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/is-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
      "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
      "dev": true,
      "dependencies": {
        "is-accessor-descriptor": "^0.1.6",
        "is-data-descriptor": "^0.1.4",
        "kind-of": "^5.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/is-extendable": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
      "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/kind-of": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
      "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/expand-brackets/node_modules/ms": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
      "integrity": "sha1-VgiurfwAvmwpAd9fmGF4jeDVl8g=",
      "dev": true
    },
    "node_modules/expect": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/expect/-/expect-25.5.0.tgz",
      "integrity": "sha512-w7KAXo0+6qqZZhovCaBVPSIqQp7/UTcx4M9uKt2m6pd2VB1voyC8JizLRqeEqud3AAVP02g+hbErDu5gu64tlA==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "ansi-styles": "^4.0.0",
        "jest-get-type": "^25.2.6",
        "jest-matcher-utils": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-regex-util": "^25.2.6"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/expect/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/expect/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/expect/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/ext": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/ext/-/ext-1.4.0.tgz",
      "integrity": "sha512-Key5NIsUxdqKg3vIsdw9dSuXpPCQ297y6wBjL30edxwPgt2E44WcWBZey/ZvUc6sERLTxKdyCu4gZFmUbk1Q7A==",
      "dev": true,
      "dependencies": {
        "type": "^2.0.0"
      }
    },
    "node_modules/ext/node_modules/type": {
      "version": "2.5.0",
      "resolved": "https://registry.npmjs.org/type/-/type-2.5.0.tgz",
      "integrity": "sha512-180WMDQaIMm3+7hGXWf12GtdniDEy7nYcyFMKJn/eZz/6tSLXrUN9V0wKSbMjej0I1WHWbpREDEKHtqPQa9NNw==",
      "dev": true
    },
    "node_modules/extend": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/extend/-/extend-3.0.2.tgz",
      "integrity": "sha512-fjquC59cD7CyW6urNXK0FBufkZcoiGG80wTuPujX590cB5Ttln20E2UB4S/WARVqhXffZl2LNgS+gQdPIIim/g==",
      "dev": true
    },
    "node_modules/extend-shallow": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-3.0.2.tgz",
      "integrity": "sha1-Jqcarwc7OfshJxcnRhMcJwQCjbg=",
      "dev": true,
      "dependencies": {
        "assign-symbols": "^1.0.0",
        "is-extendable": "^1.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/external-editor": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/external-editor/-/external-editor-3.1.0.tgz",
      "integrity": "sha512-hMQ4CX1p1izmuLYyZqLMO/qGNw10wSv9QDCPfzXfyFrOaCSSoRfqE1Kf1s5an66J5JZC62NewG+mK49jOCtQew==",
      "dev": true,
      "dependencies": {
        "chardet": "^0.7.0",
        "iconv-lite": "^0.4.24",
        "tmp": "^0.0.33"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/external-editor/node_modules/tmp": {
      "version": "0.0.33",
      "resolved": "https://registry.npmjs.org/tmp/-/tmp-0.0.33.tgz",
      "integrity": "sha512-jRCJlojKnZ3addtTOjdIqoRuPEKBvNXcGYqzO6zWZX8KfKEpnGY5jfggJQ3EjKuu8D4bJRr0y+cYJFmYbImXGw==",
      "dev": true,
      "dependencies": {
        "os-tmpdir": "~1.0.2"
      },
      "engines": {
        "node": ">=0.6.0"
      }
    },
    "node_modules/extglob": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/extglob/-/extglob-2.0.4.tgz",
      "integrity": "sha512-Nmb6QXkELsuBr24CJSkilo6UHHgbekK5UiZgfE6UHD3Eb27YC6oD+bhcT+tJ6cl8dmsgdQxnWlcry8ksBIBLpw==",
      "dev": true,
      "dependencies": {
        "array-unique": "^0.3.2",
        "define-property": "^1.0.0",
        "expand-brackets": "^2.1.4",
        "extend-shallow": "^2.0.1",
        "fragment-cache": "^0.2.1",
        "regex-not": "^1.0.0",
        "snapdragon": "^0.8.1",
        "to-regex": "^3.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/extglob/node_modules/define-property": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
      "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
      "dev": true,
      "dependencies": {
        "is-descriptor": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/extglob/node_modules/extend-shallow": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
      "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
      "dev": true,
      "dependencies": {
        "is-extendable": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/extglob/node_modules/is-extendable": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
      "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/extsprintf": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/extsprintf/-/extsprintf-1.3.0.tgz",
      "integrity": "sha1-lpGEQOMEGnpBT4xS48V06zw+HgU=",
      "dev": true,
      "engines": [
        "node >=0.6.0"
      ]
    },
    "node_modules/fast-deep-equal": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/fast-deep-equal/-/fast-deep-equal-3.1.3.tgz",
      "integrity": "sha512-f3qQ9oQy9j2AhBe/H9VC91wLmKBCCU/gDOnKNAYG5hswO7BLKj09Hc5HYNz9cGI++xlpDCIgDaitVs03ATR84Q==",
      "dev": true
    },
    "node_modules/fast-json-stable-stringify": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/fast-json-stable-stringify/-/fast-json-stable-stringify-2.1.0.tgz",
      "integrity": "sha512-lhd/wF+Lk98HZoTCtlVraHtfh5XYijIjalXck7saUtuanSDyLMxnHhSXEDJqHxD7msR8D0uCmqlkwjCV8xvwHw==",
      "dev": true
    },
    "node_modules/fast-levenshtein": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz",
      "integrity": "sha1-PYpcZog6FqMMqGQ+hR8Zuqd5eRc=",
      "dev": true
    },
    "node_modules/fast-safe-stringify": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/fast-safe-stringify/-/fast-safe-stringify-2.1.1.tgz",
      "integrity": "sha512-W+KJc2dmILlPplD/H4K9l9LcAHAfPtP6BY84uVLXQ6Evcz9Lcg33Y2z1IVblT6xdY54PXYVHEv+0Wpq8Io6zkA=="
    },
    "node_modules/fast-url-parser": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/fast-url-parser/-/fast-url-parser-1.1.3.tgz",
      "integrity": "sha512-5jOCVXADYNuRkKFzNJ0dCCewsZiYo0dz8QNYljkOpFC6r2U4OBmKtvm/Tsuh4w1YYdDqDb31a8TVhBJ2OJKdqQ==",
      "dev": true,
      "dependencies": {
        "punycode": "^1.3.2"
      }
    },
    "node_modules/fb-watchman": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/fb-watchman/-/fb-watchman-2.0.1.tgz",
      "integrity": "sha512-DkPJKQeY6kKwmuMretBhr7G6Vodr7bFwDYTXIkfG1gjvNpaxBTQV3PbXg6bR1c1UP4jPOX0jHUbbHANL9vRjVg==",
      "dev": true,
      "dependencies": {
        "bser": "2.1.1"
      }
    },
    "node_modules/figures": {
      "version": "3.2.0",
      "resolved": "https://registry.npmjs.org/figures/-/figures-3.2.0.tgz",
      "integrity": "sha512-yaduQFRKLXYOGgEn6AZau90j3ggSOyiqXU0F9JZfeXYhNa+Jk4X+s45A2zg5jns87GAFa34BBm2kXw4XpNcbdg==",
      "dev": true,
      "dependencies": {
        "escape-string-regexp": "^1.0.5"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/file-entry-cache": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/file-entry-cache/-/file-entry-cache-5.0.1.tgz",
      "integrity": "sha512-bCg29ictuBaKUwwArK4ouCaqDgLZcysCFLmM/Yn/FDoqndh/9vNuQfXRDvTuXKLxfD/JtZQGKFT8MGcJBK644g==",
      "dev": true,
      "dependencies": {
        "flat-cache": "^2.0.1"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/filename-reserved-regex": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/filename-reserved-regex/-/filename-reserved-regex-2.0.0.tgz",
      "integrity": "sha1-q/c9+rc10EVECr/qLZHzieu/oik=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/filenamify": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/filenamify/-/filenamify-4.3.0.tgz",
      "integrity": "sha512-hcFKyUG57yWGAzu1CMt/dPzYZuv+jAJUT85bL8mrXvNe6hWj6yEHEc4EdcgiA6Z3oi1/9wXJdZPXF2dZNgwgOg==",
      "dev": true,
      "dependencies": {
        "filename-reserved-regex": "^2.0.0",
        "strip-outer": "^1.0.1",
        "trim-repeated": "^1.0.0"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/fill-range": {
      "version": "7.0.1",
      "resolved": "https://registry.npmjs.org/fill-range/-/fill-range-7.0.1.tgz",
      "integrity": "sha512-qOo9F+dMUmC2Lcb4BbVvnKJxTPjCm+RRpe4gDuGrzkL7mEVl/djYSu2OdQ2Pa302N4oqkSg9ir6jaLWJ2USVpQ==",
      "dev": true,
      "dependencies": {
        "to-regex-range": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/find-cache-dir": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/find-cache-dir/-/find-cache-dir-3.3.1.tgz",
      "integrity": "sha512-t2GDMt3oGC/v+BMwzmllWDuJF/xcDtE5j/fCGbqDD7OLuJkj0cfh1YSA5VKPvwMeLFLNDBkwOKZ2X85jGLVftQ==",
      "dev": true,
      "dependencies": {
        "commondir": "^1.0.1",
        "make-dir": "^3.0.2",
        "pkg-dir": "^4.1.0"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/avajs/find-cache-dir?sponsor=1"
      }
    },
    "node_modules/find-cache-dir/node_modules/pkg-dir": {
      "version": "4.2.0",
      "resolved": "https://registry.npmjs.org/pkg-dir/-/pkg-dir-4.2.0.tgz",
      "integrity": "sha512-HRDzbaKjC+AOWVXxAU/x54COGeIv9eb+6CkDSQoNTt4XyWoIJvuPsXizxu/Fr23EiekbtZwmh1IcIG/l/a10GQ==",
      "dev": true,
      "dependencies": {
        "find-up": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/find-up": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/find-up/-/find-up-4.1.0.tgz",
      "integrity": "sha512-PpOwAdQ/YlXQ2vj8a3h8IipDuYRi3wceVQQGYWxNINccq40Anw7BlsEXCMbt1Zt+OLA6Fq9suIpIWD0OsnISlw==",
      "dev": true,
      "dependencies": {
        "locate-path": "^5.0.0",
        "path-exists": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/flat-cache": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/flat-cache/-/flat-cache-2.0.1.tgz",
      "integrity": "sha512-LoQe6yDuUMDzQAEH8sgmh4Md6oZnc/7PjtwjNFSzveXqSHt6ka9fPBuso7IGf9Rz4uqnSnWiFH2B/zj24a5ReA==",
      "dev": true,
      "dependencies": {
        "flatted": "^2.0.0",
        "rimraf": "2.6.3",
        "write": "1.0.3"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/flat-cache/node_modules/rimraf": {
      "version": "2.6.3",
      "resolved": "https://registry.npmjs.org/rimraf/-/rimraf-2.6.3.tgz",
      "integrity": "sha512-mwqeW5XsA2qAejG46gYdENaxXjx9onRNCfn7L0duuP4hCuTIi/QO7PDK07KJfp1d+izWPrzEJDcSqBa0OZQriA==",
      "dev": true,
      "dependencies": {
        "glob": "^7.1.3"
      },
      "bin": {
        "rimraf": "bin.js"
      }
    },
    "node_modules/flatted": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/flatted/-/flatted-2.0.2.tgz",
      "integrity": "sha512-r5wGx7YeOwNWNlCA0wQ86zKyDLMQr+/RB8xy74M4hTphfmjlijTSSXGuH8rnvKZnfT9i+75zmd8jcKdMR4O6jA==",
      "dev": true
    },
    "node_modules/follow-redirects": {
      "version": "1.15.2",
      "resolved": "https://registry.npmjs.org/follow-redirects/-/follow-redirects-1.15.2.tgz",
      "integrity": "sha512-VQLG33o04KaQ8uYi2tVNbdrWp1QWxNNea+nmIB4EVM28v0hmP17z7aG1+wAkNzVq4KeXTq3221ye5qTJP91JwA==",
      "funding": [
        {
          "type": "individual",
          "url": "https://github.com/sponsors/RubenVerborgh"
        }
      ],
      "engines": {
        "node": ">=4.0"
      },
      "peerDependenciesMeta": {
        "debug": {
          "optional": true
        }
      }
    },
    "node_modules/for-in": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/for-in/-/for-in-1.0.2.tgz",
      "integrity": "sha1-gQaNKVqBQuwKxybG4iAMMPttXoA=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/forever-agent": {
      "version": "0.6.1",
      "resolved": "https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz",
      "integrity": "sha1-+8cfDEGt6zf5bFd60e1C2P2sypE=",
      "dev": true,
      "engines": {
        "node": "*"
      }
    },
    "node_modules/form-data": {
      "version": "2.3.3",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-2.3.3.tgz",
      "integrity": "sha512-1lLKB2Mu3aGP1Q/2eCOx0fNbRMe7XdwktwOruhfqqd0rIJWwN4Dh+E3hrPSlDCXnSR7UtZ1N38rVXm+6+MEhJQ==",
      "dev": true,
      "dependencies": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.6",
        "mime-types": "^2.1.12"
      },
      "engines": {
        "node": ">= 0.12"
      }
    },
    "node_modules/fragment-cache": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/fragment-cache/-/fragment-cache-0.2.1.tgz",
      "integrity": "sha1-QpD60n8T6Jvn8zeZxrxaCr//DRk=",
      "dev": true,
      "dependencies": {
        "map-cache": "^0.2.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/fs-extra": {
      "version": "8.1.0",
      "resolved": "https://registry.npmjs.org/fs-extra/-/fs-extra-8.1.0.tgz",
      "integrity": "sha512-yhlQgA6mnOJUKOsRUFsgJdQCvkKhcz8tlZG5HBQfReYZy46OwLcY+Zia0mtdHsOo9y/hP+CxMN0TU9QxoOtG4g==",
      "dev": true,
      "dependencies": {
        "graceful-fs": "^4.2.0",
        "jsonfile": "^4.0.0",
        "universalify": "^0.1.0"
      },
      "engines": {
        "node": ">=6 <7 || >=8"
      }
    },
    "node_modules/fs.realpath": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz",
      "integrity": "sha1-FQStJSMVjKpA20onh8sBQRmU6k8=",
      "dev": true
    },
    "node_modules/fsevents": {
      "version": "2.3.2",
      "resolved": "https://registry.npmjs.org/fsevents/-/fsevents-2.3.2.tgz",
      "integrity": "sha512-xiqMQR4xAeHTuB9uWm+fFRcIOgKBMiOBP+eXiyT7jsgVCq1bkVygt00oASowB7EdtpOHaaPgKt812P9ab+DDKA==",
      "dev": true,
      "hasInstallScript": true,
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": "^8.16.0 || ^10.6.0 || >=11.0.0"
      }
    },
    "node_modules/function-bind": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/function-bind/-/function-bind-1.1.1.tgz",
      "integrity": "sha512-yIovAzMX49sF8Yl58fSCWJ5svSLuaibPxXQJFLmBObTuCr0Mf1KiPopGM9NiFjiYBCbfaa2Fh6breQ6ANVTI0A==",
      "dev": true
    },
    "node_modules/functional-red-black-tree": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/functional-red-black-tree/-/functional-red-black-tree-1.0.1.tgz",
      "integrity": "sha1-GwqzvVU7Kg1jmdKcDj6gslIHgyc=",
      "dev": true
    },
    "node_modules/gensync": {
      "version": "1.0.0-beta.2",
      "resolved": "https://registry.npmjs.org/gensync/-/gensync-1.0.0-beta.2.tgz",
      "integrity": "sha512-3hN7NaskYvMDLQY55gnW3NQ+mesEAepTqlg+VEbj7zzqEMBVNhzcGYYeqFo/TlYz6eQiFcp1HcsCZO+nGgS8zg==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/get-caller-file": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/get-caller-file/-/get-caller-file-2.0.5.tgz",
      "integrity": "sha512-DyFP3BM/3YHTQOCUL/w0OZHR0lpKeGrxotcHWcqNEdnltqFwXVfhEBQ94eIo34AfQpo0rGki4cyIiftY06h2Fg==",
      "dev": true,
      "engines": {
        "node": "6.* || 8.* || >= 10.*"
      }
    },
    "node_modules/get-intrinsic": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/get-intrinsic/-/get-intrinsic-1.1.1.tgz",
      "integrity": "sha512-kWZrnVM42QCiEA2Ig1bG8zjoIMOgxWwYCEeNdwY6Tv/cOSeGpcoX4pXHfKUxNKVoArnrEr2e9srnAxxGIraS9Q==",
      "dev": true,
      "dependencies": {
        "function-bind": "^1.1.1",
        "has": "^1.0.3",
        "has-symbols": "^1.0.1"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/get-package-type": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/get-package-type/-/get-package-type-0.1.0.tgz",
      "integrity": "sha512-pjzuKtY64GYfWizNAJ0fr9VqttZkNiK2iS430LtIHzjBEr6bX8Am2zm4sW4Ro5wjWW5cAlRL1qAMTcXbjNAO2Q==",
      "dev": true,
      "engines": {
        "node": ">=8.0.0"
      }
    },
    "node_modules/get-stdin": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/get-stdin/-/get-stdin-6.0.0.tgz",
      "integrity": "sha512-jp4tHawyV7+fkkSKyvjuLZswblUtz+SQKzSWnBbii16BuZksJlU1wuBYXY75r+duh/llF1ur6oNwi+2ZzjKZ7g==",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/get-stream": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/get-stream/-/get-stream-5.2.0.tgz",
      "integrity": "sha512-nBF+F1rAZVCu/p7rjzgA+Yb4lfYXrpl7a6VmJrU8wF9I1CKvP/QwPNZHnOlwbTkY6dvtFIzFMSyQXbLoTQPRpA==",
      "dev": true,
      "dependencies": {
        "pump": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/get-value": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/get-value/-/get-value-2.0.6.tgz",
      "integrity": "sha1-3BXKHGcjh8p2vTesCjlbogQqLCg=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/getpass": {
      "version": "0.1.7",
      "resolved": "https://registry.npmjs.org/getpass/-/getpass-0.1.7.tgz",
      "integrity": "sha1-Xv+OPmhNVprkyysSgmBOi6YhSfo=",
      "dev": true,
      "dependencies": {
        "assert-plus": "^1.0.0"
      }
    },
    "node_modules/gh-pages": {
      "version": "3.2.3",
      "resolved": "https://registry.npmjs.org/gh-pages/-/gh-pages-3.2.3.tgz",
      "integrity": "sha512-jA1PbapQ1jqzacECfjUaO9gV8uBgU6XNMV0oXLtfCX3haGLe5Atq8BxlrADhbD6/UdG9j6tZLWAkAybndOXTJg==",
      "dev": true,
      "dependencies": {
        "async": "^2.6.1",
        "commander": "^2.18.0",
        "email-addresses": "^3.0.1",
        "filenamify": "^4.3.0",
        "find-cache-dir": "^3.3.1",
        "fs-extra": "^8.1.0",
        "globby": "^6.1.0"
      },
      "bin": {
        "gh-pages": "bin/gh-pages.js",
        "gh-pages-clean": "bin/gh-pages-clean.js"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/gh-pages/node_modules/commander": {
      "version": "2.20.3",
      "resolved": "https://registry.npmjs.org/commander/-/commander-2.20.3.tgz",
      "integrity": "sha512-GpVkmM8vF2vQUkj2LvZmD35JxeJOLCwJ9cUkugyk2nuhbv3+mJvpLYYt+0+USMxE+oj+ey/lJEnhZw75x/OMcQ==",
      "dev": true
    },
    "node_modules/glob": {
      "version": "7.1.7",
      "resolved": "https://registry.npmjs.org/glob/-/glob-7.1.7.tgz",
      "integrity": "sha512-OvD9ENzPLbegENnYP5UUfJIirTg4+XwMWGaQfQTY0JenxNvvIKP3U3/tAQSPIu/lHxXYSZmpXlUHeqAIdKzBLQ==",
      "dev": true,
      "dependencies": {
        "fs.realpath": "^1.0.0",
        "inflight": "^1.0.4",
        "inherits": "2",
        "minimatch": "^3.0.4",
        "once": "^1.3.0",
        "path-is-absolute": "^1.0.0"
      },
      "engines": {
        "node": "*"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/glob-parent": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/glob-parent/-/glob-parent-5.1.2.tgz",
      "integrity": "sha512-AOIgSQCepiJYwP3ARnGx+5VnTu2HBYdzbGP45eLw1vr3zB3vZLeyed1sC9hnbcOc9/SrMyM5RPQrkGz4aS9Zow==",
      "dev": true,
      "dependencies": {
        "is-glob": "^4.0.1"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/globals": {
      "version": "12.4.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-12.4.0.tgz",
      "integrity": "sha512-BWICuzzDvDoH54NHKCseDanAhE3CeDorgDL5MT6LMXXj2WCnd9UC2szdk4AWLfjdgNBCXLUanXYcpBBKOSWGwg==",
      "dev": true,
      "dependencies": {
        "type-fest": "^0.8.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/globby": {
      "version": "6.1.0",
      "resolved": "https://registry.npmjs.org/globby/-/globby-6.1.0.tgz",
      "integrity": "sha1-9abXDoOV4hyFj7BInWTfAkJNUGw=",
      "dev": true,
      "dependencies": {
        "array-union": "^1.0.1",
        "glob": "^7.0.3",
        "object-assign": "^4.0.1",
        "pify": "^2.0.0",
        "pinkie-promise": "^2.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/graceful-fs": {
      "version": "4.2.6",
      "resolved": "https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.2.6.tgz",
      "integrity": "sha512-nTnJ528pbqxYanhpDYsi4Rd8MAeaBA67+RZ10CM1m3bTAVFEDcd5AuA4a6W5YkGZ1iNXHzZz8T6TBKLeBuNriQ==",
      "dev": true
    },
    "node_modules/graphql": {
      "version": "15.5.3",
      "resolved": "https://registry.npmjs.org/graphql/-/graphql-15.5.3.tgz",
      "integrity": "sha512-sM+jXaO5KinTui6lbK/7b7H/Knj9BpjGxZ+Ki35v7YbUJxxdBCUqNM0h3CRVU1ZF9t5lNiBzvBCSYPvIwxPOQA==",
      "engines": {
        "node": ">= 10.x"
      }
    },
    "node_modules/graphql-tag": {
      "version": "2.12.4",
      "resolved": "https://registry.npmjs.org/graphql-tag/-/graphql-tag-2.12.4.tgz",
      "integrity": "sha512-VV1U4O+9x99EkNpNmCUV5RZwq6MnK4+pGbRYWG+lA/m3uo7TSqJF81OkcOP148gFP6fzdl7JWYBrwWVTS9jXww==",
      "dependencies": {
        "tslib": "^2.1.0"
      },
      "engines": {
        "node": ">=10"
      },
      "peerDependencies": {
        "graphql": "^0.9.0 || ^0.10.0 || ^0.11.0 || ^0.12.0 || ^0.13.0 || ^14.0.0 || ^15.0.0"
      }
    },
    "node_modules/graphql-tag/node_modules/tslib": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
      "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg=="
    },
    "node_modules/growly": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/growly/-/growly-1.3.0.tgz",
      "integrity": "sha1-8QdIy+dq+WS3yWyTxrzCivEgwIE=",
      "dev": true,
      "optional": true
    },
    "node_modules/handlebars": {
      "version": "4.7.7",
      "resolved": "https://registry.npmjs.org/handlebars/-/handlebars-4.7.7.tgz",
      "integrity": "sha512-aAcXm5OAfE/8IXkcZvCepKU3VzW1/39Fb5ZuqMtgI/hT8X2YgoMvBY5dLhq/cpOvw7Lk1nK/UF71aLG/ZnVYRA==",
      "dev": true,
      "dependencies": {
        "minimist": "^1.2.5",
        "neo-async": "^2.6.0",
        "source-map": "^0.6.1",
        "wordwrap": "^1.0.0"
      },
      "bin": {
        "handlebars": "bin/handlebars"
      },
      "engines": {
        "node": ">=0.4.7"
      },
      "optionalDependencies": {
        "uglify-js": "^3.1.4"
      }
    },
    "node_modules/har-schema": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/har-schema/-/har-schema-2.0.0.tgz",
      "integrity": "sha1-qUwiJOvKwEeCoNkDVSHyRzW37JI=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/har-validator": {
      "version": "5.1.5",
      "resolved": "https://registry.npmjs.org/har-validator/-/har-validator-5.1.5.tgz",
      "integrity": "sha512-nmT2T0lljbxdQZfspsno9hgrG3Uir6Ks5afism62poxqBM6sDnMEuPmzTq8XN0OEwqKLLdh1jQI3qyE66Nzb3w==",
      "deprecated": "this library is no longer supported",
      "dev": true,
      "dependencies": {
        "ajv": "^6.12.3",
        "har-schema": "^2.0.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/has": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/has/-/has-1.0.3.tgz",
      "integrity": "sha512-f2dvO0VU6Oej7RkWJGrehjbzMAjFp5/VKPp5tTpWIV4JHHZK1/BxbFRtf/siA2SWTe09caDmVtYYzWEIbBS4zw==",
      "dev": true,
      "dependencies": {
        "function-bind": "^1.1.1"
      },
      "engines": {
        "node": ">= 0.4.0"
      }
    },
    "node_modules/has-bigints": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/has-bigints/-/has-bigints-1.0.1.tgz",
      "integrity": "sha512-LSBS2LjbNBTf6287JEbEzvJgftkF5qFkmCo9hDRpAzKhUOlJ+hx8dd4USs00SgsUNwc4617J9ki5YtEClM2ffA==",
      "dev": true,
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-flag": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-3.0.0.tgz",
      "integrity": "sha1-tdRU3CGZriJWmfNGfloH87lVuv0=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/has-symbols": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/has-symbols/-/has-symbols-1.0.2.tgz",
      "integrity": "sha512-chXa79rL/UC2KlX17jo3vRGz0azaWEx5tGqZg5pO3NUyEJVB17dMruQlzCCOfUvElghKcm5194+BCRvi2Rv/Gw==",
      "dev": true,
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-value": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/has-value/-/has-value-1.0.0.tgz",
      "integrity": "sha1-GLKB2lhbHFxR3vJMkw7SmgvmsXc=",
      "dev": true,
      "dependencies": {
        "get-value": "^2.0.6",
        "has-values": "^1.0.0",
        "isobject": "^3.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/has-values": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/has-values/-/has-values-1.0.0.tgz",
      "integrity": "sha1-lbC2P+whRmGab+V/51Yo1aOe/k8=",
      "dev": true,
      "dependencies": {
        "is-number": "^3.0.0",
        "kind-of": "^4.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/has-values/node_modules/is-number": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/is-number/-/is-number-3.0.0.tgz",
      "integrity": "sha1-JP1iAaR4LPUFYcgQJ2r8fRLXEZU=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/has-values/node_modules/is-number/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/has-values/node_modules/kind-of": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-4.0.0.tgz",
      "integrity": "sha1-IIE989cSkosgc3hpGkUGb65y3Vc=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/hash.js": {
      "version": "1.1.7",
      "resolved": "https://registry.npmjs.org/hash.js/-/hash.js-1.1.7.tgz",
      "integrity": "sha512-taOaskGt4z4SOANNseOviYDvjEJinIkRgmp7LbKP2YTTmVxWBl87s/uzK9r+44BclBSp2X7K1hqeNfz9JbBeXA==",
      "dependencies": {
        "inherits": "^2.0.3",
        "minimalistic-assert": "^1.0.1"
      }
    },
    "node_modules/highlight.js": {
      "version": "10.7.3",
      "resolved": "https://registry.npmjs.org/highlight.js/-/highlight.js-10.7.3.tgz",
      "integrity": "sha512-tzcUFauisWKNHaRkN4Wjl/ZA07gENAjFl3J/c480dprkGTg5EQstgaNFqBfUqCq54kZRIEcreTsAgF/m2quD7A==",
      "dev": true,
      "engines": {
        "node": "*"
      }
    },
    "node_modules/hmac-drbg": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/hmac-drbg/-/hmac-drbg-1.0.1.tgz",
      "integrity": "sha1-0nRXAQJabHdabFRXk+1QL8DGSaE=",
      "dependencies": {
        "hash.js": "^1.0.3",
        "minimalistic-assert": "^1.0.0",
        "minimalistic-crypto-utils": "^1.0.1"
      }
    },
    "node_modules/hoist-non-react-statics": {
      "version": "3.3.2",
      "resolved": "https://registry.npmjs.org/hoist-non-react-statics/-/hoist-non-react-statics-3.3.2.tgz",
      "integrity": "sha512-/gGivxi8JPKWNm/W0jSmzcMPpfpPLc3dY/6GxhX2hQ9iGj3aDfklV4ET7NjKpSinLpJ5vafa9iiGIEZg10SfBw==",
      "dependencies": {
        "react-is": "^16.7.0"
      }
    },
    "node_modules/hosted-git-info": {
      "version": "2.8.9",
      "resolved": "https://registry.npmjs.org/hosted-git-info/-/hosted-git-info-2.8.9.tgz",
      "integrity": "sha512-mxIDAb9Lsm6DoOJ7xH+5+X4y1LU/4Hi50L9C5sIswK3JzULS4bwk1FvjdBgvYR4bzT4tuUQiC15FE2f5HbLvYw==",
      "dev": true
    },
    "node_modules/html-encoding-sniffer": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/html-encoding-sniffer/-/html-encoding-sniffer-1.0.2.tgz",
      "integrity": "sha512-71lZziiDnsuabfdYiUeWdCVyKuqwWi23L8YeIgV9jSSZHCtb6wB1BKWooH7L3tn4/FuZJMVWyNaIDr4RGmaSYw==",
      "dev": true,
      "dependencies": {
        "whatwg-encoding": "^1.0.1"
      }
    },
    "node_modules/html-escaper": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/html-escaper/-/html-escaper-2.0.2.tgz",
      "integrity": "sha512-H2iMtd0I4Mt5eYiapRdIDjp+XzelXQ0tFE4JS7YFwFevXXMmOp9myNrUvCg0D6ws8iqkRPBfKHgbwig1SmlLfg==",
      "dev": true
    },
    "node_modules/http-signature": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/http-signature/-/http-signature-1.2.0.tgz",
      "integrity": "sha1-muzZJRFHcvPZW2WmCruPfBj7rOE=",
      "dev": true,
      "dependencies": {
        "assert-plus": "^1.0.0",
        "jsprim": "^1.2.2",
        "sshpk": "^1.7.0"
      },
      "engines": {
        "node": ">=0.8",
        "npm": ">=1.3.7"
      }
    },
    "node_modules/human-signals": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/human-signals/-/human-signals-1.1.1.tgz",
      "integrity": "sha512-SEQu7vl8KjNL2eoGBLF3+wAjpsNfA9XMlXAYj/3EdaNfAlxKthD1xjEQfGOUhllCGGJVNY34bRr6lPINhNjyZw==",
      "dev": true,
      "engines": {
        "node": ">=8.12.0"
      }
    },
    "node_modules/husky": {
      "version": "8.0.2",
      "resolved": "https://registry.npmjs.org/husky/-/husky-8.0.2.tgz",
      "integrity": "sha512-Tkv80jtvbnkK3mYWxPZePGFpQ/tT3HNSs/sasF9P2YfkMezDl3ON37YN6jUUI4eTg5LcyVynlb6r4eyvOmspvg==",
      "dev": true,
      "bin": {
        "husky": "lib/bin.js"
      },
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/typicode"
      }
    },
    "node_modules/iconv-lite": {
      "version": "0.4.24",
      "resolved": "https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.24.tgz",
      "integrity": "sha512-v3MXnZAcvnywkTUEZomIActle7RXXeedOR31wwl7VlyoXO4Qi9arvSenNQWne1TcRwhCL1HwLI21bEqdpj8/rA==",
      "dev": true,
      "dependencies": {
        "safer-buffer": ">= 2.1.2 < 3"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/ignore": {
      "version": "4.0.6",
      "resolved": "https://registry.npmjs.org/ignore/-/ignore-4.0.6.tgz",
      "integrity": "sha512-cyFDKrqc/YdcWFniJhzI42+AzS+gNwmUzOSFcRCQYwySuBBBy/KjuxWLZ/FHEH6Moq1NizMOBWyTcv8O4OZIMg==",
      "dev": true,
      "engines": {
        "node": ">= 4"
      }
    },
    "node_modules/import-fresh": {
      "version": "3.3.0",
      "resolved": "https://registry.npmjs.org/import-fresh/-/import-fresh-3.3.0.tgz",
      "integrity": "sha512-veYYhQa+D1QBKznvhUHxb8faxlrwUnxseDAbAp457E0wLNio2bOSKnjYDhMj+YiAq61xrMGhQk9iXVk5FzgQMw==",
      "dev": true,
      "dependencies": {
        "parent-module": "^1.0.0",
        "resolve-from": "^4.0.0"
      },
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/import-local": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/import-local/-/import-local-3.0.2.tgz",
      "integrity": "sha512-vjL3+w0oulAVZ0hBHnxa/Nm5TAurf9YLQJDhqRZyqb+VKGOB6LU8t9H1Nr5CIo16vh9XfJTOoHwU0B71S557gA==",
      "dev": true,
      "dependencies": {
        "pkg-dir": "^4.2.0",
        "resolve-cwd": "^3.0.0"
      },
      "bin": {
        "import-local-fixture": "fixtures/cli.js"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/import-local/node_modules/pkg-dir": {
      "version": "4.2.0",
      "resolved": "https://registry.npmjs.org/pkg-dir/-/pkg-dir-4.2.0.tgz",
      "integrity": "sha512-HRDzbaKjC+AOWVXxAU/x54COGeIv9eb+6CkDSQoNTt4XyWoIJvuPsXizxu/Fr23EiekbtZwmh1IcIG/l/a10GQ==",
      "dev": true,
      "dependencies": {
        "find-up": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/imurmurhash": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz",
      "integrity": "sha1-khi5srkoojixPcT7a21XbyMUU+o=",
      "dev": true,
      "engines": {
        "node": ">=0.8.19"
      }
    },
    "node_modules/indent-string": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/indent-string/-/indent-string-4.0.0.tgz",
      "integrity": "sha512-EdDDZu4A2OyIK7Lr/2zG+w5jmbuk1DVBnEwREQvBzspBJkCEbRa8GxU1lghYcaGJCnRWibjDXlq779X1/y5xwg==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/inflight": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/inflight/-/inflight-1.0.6.tgz",
      "integrity": "sha1-Sb1jMdfQLQwJvJEKEHW6gWW1bfk=",
      "dev": true,
      "dependencies": {
        "once": "^1.3.0",
        "wrappy": "1"
      }
    },
    "node_modules/inherits": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/inherits/-/inherits-2.0.4.tgz",
      "integrity": "sha512-k/vGaX4/Yla3WzyMCvTQOXYeIHvqOKtnqBduzTHpzpQZzAskKMhZ2K+EnBiSM9zGSoIFeMpXKxa4dYeZIQqewQ=="
    },
    "node_modules/ini": {
      "version": "1.3.8",
      "resolved": "https://registry.npmjs.org/ini/-/ini-1.3.8.tgz",
      "integrity": "sha512-JV/yugV2uzW5iMRSiZAyDtQd+nxtUnjeLt0acNdw98kKLrvuRVyB80tsREOE7yvGVgalhZ6RNXCmEHkUKBKxew==",
      "dev": true
    },
    "node_modules/inquirer": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/inquirer/-/inquirer-7.3.3.tgz",
      "integrity": "sha512-JG3eIAj5V9CwcGvuOmoo6LB9kbAYT8HXffUl6memuszlwDC/qvFAJw49XJ5NROSFNPxp3iQg1GqkFhaY/CR0IA==",
      "dev": true,
      "dependencies": {
        "ansi-escapes": "^4.2.1",
        "chalk": "^4.1.0",
        "cli-cursor": "^3.1.0",
        "cli-width": "^3.0.0",
        "external-editor": "^3.0.3",
        "figures": "^3.0.0",
        "lodash": "^4.17.19",
        "mute-stream": "0.0.8",
        "run-async": "^2.4.0",
        "rxjs": "^6.6.0",
        "string-width": "^4.1.0",
        "strip-ansi": "^6.0.0",
        "through": "^2.3.6"
      },
      "engines": {
        "node": ">=8.0.0"
      }
    },
    "node_modules/inquirer/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/inquirer/node_modules/chalk": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-4.1.1.tgz",
      "integrity": "sha512-diHzdDKxcU+bAsUboHLPEDQiw0qEe0qd7SYUn3HgcFlWgbDcfLGswOHYeGrHKzG9z6UYf01d9VFMfZxPM1xZSg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/chalk/chalk?sponsor=1"
      }
    },
    "node_modules/inquirer/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/inquirer/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/inquirer/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/inquirer/node_modules/strip-ansi": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
      "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^5.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/inquirer/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/interpret": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/interpret/-/interpret-1.4.0.tgz",
      "integrity": "sha512-agE4QfB2Lkp9uICn7BAqoscw4SZP9kTE2hxiFI3jBPmXJfdqiahTbUuKGsMoN2GtqL9AxhYioAcVvgsb1HvRbA==",
      "dev": true,
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/ip-regex": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/ip-regex/-/ip-regex-2.1.0.tgz",
      "integrity": "sha1-+ni/XS5pE8kRzp+BnuUUa7bYROk=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/is-accessor-descriptor": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-1.0.0.tgz",
      "integrity": "sha512-m5hnHTkcVsPfqx3AKlyttIPb7J+XykHvJP2B9bZDjlhLIoEq4XoK64Vg7boZlVWYK6LUY94dYPEE7Lh0ZkZKcQ==",
      "dev": true,
      "dependencies": {
        "kind-of": "^6.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-arrayish": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/is-arrayish/-/is-arrayish-0.2.1.tgz",
      "integrity": "sha1-d8mYQFJ6qOyxqLppe4BkWnqSap0=",
      "dev": true
    },
    "node_modules/is-bigint": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/is-bigint/-/is-bigint-1.0.2.tgz",
      "integrity": "sha512-0JV5+SOCQkIdzjBK9buARcV804Ddu7A0Qet6sHi3FimE9ne6m4BGQZfRn+NZiXbBk4F4XmHfDZIipLj9pX8dSA==",
      "dev": true,
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-boolean-object": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/is-boolean-object/-/is-boolean-object-1.1.1.tgz",
      "integrity": "sha512-bXdQWkECBUIAcCkeH1unwJLIpZYaa5VvuygSyS/c2lf719mTKZDU5UdDRlpd01UjADgmW8RfqaP+mRaVPdr/Ng==",
      "dev": true,
      "dependencies": {
        "call-bind": "^1.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-buffer": {
      "version": "1.1.6",
      "resolved": "https://registry.npmjs.org/is-buffer/-/is-buffer-1.1.6.tgz",
      "integrity": "sha512-NcdALwpXkTm5Zvvbk7owOUSvVvBKDgKP5/ewfXEznmQFfs4ZRmanOeKBTjRVjka3QFoN6XJ+9F3USqfHqTaU5w==",
      "dev": true
    },
    "node_modules/is-callable": {
      "version": "1.2.3",
      "resolved": "https://registry.npmjs.org/is-callable/-/is-callable-1.2.3.tgz",
      "integrity": "sha512-J1DcMe8UYTBSrKezuIUTUwjXsho29693unXM2YhJUTR2txK/eG47bvNa/wipPFmZFgr/N6f1GA66dv0mEyTIyQ==",
      "dev": true,
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-ci": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/is-ci/-/is-ci-2.0.0.tgz",
      "integrity": "sha512-YfJT7rkpQB0updsdHLGWrvhBJfcfzNNawYDNIyQXJz0IViGf75O8EBPKSdvw2rF+LGCsX4FZ8tcr3b19LcZq4w==",
      "dev": true,
      "dependencies": {
        "ci-info": "^2.0.0"
      },
      "bin": {
        "is-ci": "bin.js"
      }
    },
    "node_modules/is-core-module": {
      "version": "2.4.0",
      "resolved": "https://registry.npmjs.org/is-core-module/-/is-core-module-2.4.0.tgz",
      "integrity": "sha512-6A2fkfq1rfeQZjxrZJGerpLCTHRNEBiSgnu0+obeJpEPZRUooHgsizvzv0ZjJwOz3iWIHdJtVWJ/tmPr3D21/A==",
      "dev": true,
      "dependencies": {
        "has": "^1.0.3"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-data-descriptor": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-1.0.0.tgz",
      "integrity": "sha512-jbRXy1FmtAoCjQkVmIVYwuuqDFUbaOeDjmed1tOGPrsMhtJA4rD9tkgA0F1qJ3gRFRXcHYVkdeaP50Q5rE/jLQ==",
      "dev": true,
      "dependencies": {
        "kind-of": "^6.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-date-object": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/is-date-object/-/is-date-object-1.0.4.tgz",
      "integrity": "sha512-/b4ZVsG7Z5XVtIxs/h9W8nvfLgSAyKYdtGWQLbqy6jA1icmgjf8WCoTKgeS4wy5tYaPePouzFMANbnj94c2Z+A==",
      "dev": true,
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-descriptor": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-1.0.2.tgz",
      "integrity": "sha512-2eis5WqQGV7peooDyLmNEPUrps9+SXX5c9pL3xEB+4e9HnGuDa7mB7kHxHw4CbqS9k1T2hOH3miL8n8WtiYVtg==",
      "dev": true,
      "dependencies": {
        "is-accessor-descriptor": "^1.0.0",
        "is-data-descriptor": "^1.0.0",
        "kind-of": "^6.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-docker": {
      "version": "2.2.1",
      "resolved": "https://registry.npmjs.org/is-docker/-/is-docker-2.2.1.tgz",
      "integrity": "sha512-F+i2BKsFrH66iaUFc0woD8sLy8getkwTwtOBjvs56Cx4CgJDeKQeqfz8wAYiSb8JOprWhHH5p77PbmYCvvUuXQ==",
      "dev": true,
      "bin": {
        "is-docker": "cli.js"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-extendable": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-1.0.1.tgz",
      "integrity": "sha512-arnXMxT1hhoKo9k1LZdmlNyJdDDfy2v0fXjFlmok4+i8ul/6WlbVge9bhM74OpNPQPMGUToDtz+KXa1PneJxOA==",
      "dev": true,
      "dependencies": {
        "is-plain-object": "^2.0.4"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-extglob": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/is-extglob/-/is-extglob-2.1.1.tgz",
      "integrity": "sha1-qIwCU1eR8C7TfHahueqXc8gz+MI=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-fullwidth-code-point": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-3.0.0.tgz",
      "integrity": "sha512-zymm5+u+sCsSWyD9qNaejV3DFvhCKclKdizYaJUuHA83RLjb7nSuGnddCHGv0hk+KY7BMAlsWeK4Ueg6EV6XQg==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/is-generator": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/is-generator/-/is-generator-1.0.3.tgz",
      "integrity": "sha1-wUwhBX7TbjKNuANHlmxpP4hjifM=",
      "dev": true
    },
    "node_modules/is-generator-fn": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/is-generator-fn/-/is-generator-fn-2.1.0.tgz",
      "integrity": "sha512-cTIB4yPYL/Grw0EaSzASzg6bBy9gqCofvWN8okThAYIxKJZC+udlRAmGbM0XLeniEJSs8uEgHPGuHSe1XsOLSQ==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/is-glob": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/is-glob/-/is-glob-4.0.1.tgz",
      "integrity": "sha512-5G0tKtBTFImOqDnLB2hG6Bp2qcKEFduo4tZu9MT/H6NQv/ghhy30o55ufafxJ/LdH79LLs2Kfrn85TLKyA7BUg==",
      "dev": true,
      "dependencies": {
        "is-extglob": "^2.1.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-negative-zero": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/is-negative-zero/-/is-negative-zero-2.0.1.tgz",
      "integrity": "sha512-2z6JzQvZRa9A2Y7xC6dQQm4FSTSTNWjKIYYTt4246eMTJmIo0Q+ZyOsU66X8lxK1AbB92dFeglPLrhwpeRKO6w==",
      "dev": true,
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-number": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/is-number/-/is-number-7.0.0.tgz",
      "integrity": "sha512-41Cifkg6e8TylSpdtTpeLVMqvSBEVzTttHvERD741+pnZ8ANv0004MRL43QKPDlK9cGvNp6NZWZUBlbGXYxxng==",
      "dev": true,
      "engines": {
        "node": ">=0.12.0"
      }
    },
    "node_modules/is-number-object": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/is-number-object/-/is-number-object-1.0.5.tgz",
      "integrity": "sha512-RU0lI/n95pMoUKu9v1BZP5MBcZuNSVJkMkAG2dJqC4z2GlkGUNeH68SuHuBKBD/XFe+LHZ+f9BKkLET60Niedw==",
      "dev": true,
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-plain-object": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/is-plain-object/-/is-plain-object-2.0.4.tgz",
      "integrity": "sha512-h5PpgXkWitc38BBMYawTYMWJHFZJVnBquFE57xFpjB8pJFiF6gZ+bU+WyI/yqXiFR5mdLsgYNaPe8uao6Uv9Og==",
      "dev": true,
      "dependencies": {
        "isobject": "^3.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-port-reachable": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/is-port-reachable/-/is-port-reachable-4.0.0.tgz",
      "integrity": "sha512-9UoipoxYmSk6Xy7QFgRv2HDyaysmgSG75TFQs6S+3pDM7ZhKTF/bskZV+0UlABHzKjNVhPjYCLfeZUEg1wXxig==",
      "dev": true,
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-regex": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/is-regex/-/is-regex-1.1.3.tgz",
      "integrity": "sha512-qSVXFz28HM7y+IWX6vLCsexdlvzT1PJNFSBuaQLQ5o0IEw8UDYW6/2+eCMVyIsbM8CNLX2a/QWmSpyxYEHY7CQ==",
      "dev": true,
      "dependencies": {
        "call-bind": "^1.0.2",
        "has-symbols": "^1.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-stream": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/is-stream/-/is-stream-2.0.0.tgz",
      "integrity": "sha512-XCoy+WlUr7d1+Z8GgSuXmpuUFC9fOhRXglJMx+dwLKTkL44Cjd4W1Z5P+BQZpr+cR93aGP4S/s7Ftw6Nd/kiEw==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/is-string": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/is-string/-/is-string-1.0.6.tgz",
      "integrity": "sha512-2gdzbKUuqtQ3lYNrUTQYoClPhm7oQu4UdpSZMp1/DGgkHBT8E2Z1l0yMdb6D4zNAxwDiMv8MdulKROJGNl0Q0w==",
      "dev": true,
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-symbol": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/is-symbol/-/is-symbol-1.0.4.tgz",
      "integrity": "sha512-C/CPBqKWnvdcxqIARxyOh4v1UUEOCHpgDa0WYgpKDFMszcrPcffg5uhwSgPCLD2WWxmq6isisz87tzT01tuGhg==",
      "dev": true,
      "dependencies": {
        "has-symbols": "^1.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-typedarray": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz",
      "integrity": "sha1-5HnICFjfDBsR3dppQPlgEfzaSpo=",
      "dev": true
    },
    "node_modules/is-windows": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/is-windows/-/is-windows-1.0.2.tgz",
      "integrity": "sha512-eXK1UInq2bPmjyX6e3VHIzMLobc4J94i4AWn+Hpq3OU5KkrRC96OAcR3PRJ/pGu6m8TRnBHP9dkXQVsT/COVIA==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-wsl": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/is-wsl/-/is-wsl-2.2.0.tgz",
      "integrity": "sha512-fKzAra0rGJUUBwGBgNkHZuToZcn+TtXHpeCgmkMJMMYx1sQDYaCSyjJBSCa2nH1DGm7s3n1oBnohoVTBaN7Lww==",
      "dev": true,
      "dependencies": {
        "is-docker": "^2.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/isarray": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/isarray/-/isarray-1.0.0.tgz",
      "integrity": "sha1-u5NdSFgsuhaMBoNJV6VKPgcSTxE=",
      "dev": true
    },
    "node_modules/isexe": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/isexe/-/isexe-2.0.0.tgz",
      "integrity": "sha1-6PvzdNxVb/iUehDcsFctYz8s+hA=",
      "dev": true
    },
    "node_modules/isobject": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
      "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/isstream": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz",
      "integrity": "sha1-R+Y/evVa+m+S4VAOaQ64uFKcCZo=",
      "dev": true
    },
    "node_modules/istanbul-lib-coverage": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/istanbul-lib-coverage/-/istanbul-lib-coverage-3.0.0.tgz",
      "integrity": "sha512-UiUIqxMgRDET6eR+o5HbfRYP1l0hqkWOs7vNxC/mggutCMUIhWMm8gAHb8tHlyfD3/l6rlgNA5cKdDzEAf6hEg==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/istanbul-lib-instrument": {
      "version": "4.0.3",
      "resolved": "https://registry.npmjs.org/istanbul-lib-instrument/-/istanbul-lib-instrument-4.0.3.tgz",
      "integrity": "sha512-BXgQl9kf4WTCPCCpmFGoJkz/+uhvm7h7PFKUYxh7qarQd3ER33vHG//qaE8eN25l07YqZPpHXU9I09l/RD5aGQ==",
      "dev": true,
      "dependencies": {
        "@babel/core": "^7.7.5",
        "@istanbuljs/schema": "^0.1.2",
        "istanbul-lib-coverage": "^3.0.0",
        "semver": "^6.3.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/istanbul-lib-instrument/node_modules/semver": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
      "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/istanbul-lib-report": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/istanbul-lib-report/-/istanbul-lib-report-3.0.0.tgz",
      "integrity": "sha512-wcdi+uAKzfiGT2abPpKZ0hSU1rGQjUQnLvtY5MpQ7QCTahD3VODhcu4wcfY1YtkGaDD5yuydOLINXsfbus9ROw==",
      "dev": true,
      "dependencies": {
        "istanbul-lib-coverage": "^3.0.0",
        "make-dir": "^3.0.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/istanbul-lib-report/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/istanbul-lib-report/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/istanbul-lib-source-maps": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/istanbul-lib-source-maps/-/istanbul-lib-source-maps-4.0.0.tgz",
      "integrity": "sha512-c16LpFRkR8vQXyHZ5nLpY35JZtzj1PQY1iZmesUbf1FZHbIupcWfjgOXBY9YHkLEQ6puz1u4Dgj6qmU/DisrZg==",
      "dev": true,
      "dependencies": {
        "debug": "^4.1.1",
        "istanbul-lib-coverage": "^3.0.0",
        "source-map": "^0.6.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/istanbul-reports": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/istanbul-reports/-/istanbul-reports-3.0.2.tgz",
      "integrity": "sha512-9tZvz7AiR3PEDNGiV9vIouQ/EAcqMXFmkcA1CDFTwOB98OZVDL0PH9glHotf5Ugp6GCOTypfzGWI/OqjWNCRUw==",
      "dev": true,
      "dependencies": {
        "html-escaper": "^2.0.0",
        "istanbul-lib-report": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/iterall": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/iterall/-/iterall-1.3.0.tgz",
      "integrity": "sha512-QZ9qOMdF+QLHxy1QIpUHUU1D5pS2CG2P69LF6L6CPjPYA/XMOmKV3PZpawHoAjHNyB0swdVTRxdYT4tbBbxqwg=="
    },
    "node_modules/jest": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest/-/jest-25.5.4.tgz",
      "integrity": "sha512-hHFJROBTqZahnO+X+PMtT6G2/ztqAZJveGqz//FnWWHurizkD05PQGzRZOhF3XP6z7SJmL+5tCfW8qV06JypwQ==",
      "dev": true,
      "dependencies": {
        "@jest/core": "^25.5.4",
        "import-local": "^3.0.2",
        "jest-cli": "^25.5.4"
      },
      "bin": {
        "jest": "bin/jest.js"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-changed-files": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-changed-files/-/jest-changed-files-25.5.0.tgz",
      "integrity": "sha512-EOw9QEqapsDT7mKF162m8HFzRPbmP8qJQny6ldVOdOVBz3ACgPm/1nAn5fPQ/NDaYhX/AHkrGwwkCncpAVSXcw==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "execa": "^3.2.0",
        "throat": "^5.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-cli": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-cli/-/jest-cli-25.5.4.tgz",
      "integrity": "sha512-rG8uJkIiOUpnREh1768/N3n27Cm+xPFkSNFO91tgg+8o2rXeVLStz+vkXkGr4UtzH6t1SNbjwoiswd7p4AhHTw==",
      "dev": true,
      "dependencies": {
        "@jest/core": "^25.5.4",
        "@jest/test-result": "^25.5.0",
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "exit": "^0.1.2",
        "graceful-fs": "^4.2.4",
        "import-local": "^3.0.2",
        "is-ci": "^2.0.0",
        "jest-config": "^25.5.4",
        "jest-util": "^25.5.0",
        "jest-validate": "^25.5.0",
        "prompts": "^2.0.1",
        "realpath-native": "^2.0.0",
        "yargs": "^15.3.1"
      },
      "bin": {
        "jest": "bin/jest.js"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-cli/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-cli/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-cli/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-cli/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-cli/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-cli/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-config": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-config/-/jest-config-25.5.4.tgz",
      "integrity": "sha512-SZwR91SwcdK6bz7Gco8qL7YY2sx8tFJYzvg216DLihTWf+LKY/DoJXpM9nTzYakSyfblbqeU48p/p7Jzy05Atg==",
      "dev": true,
      "dependencies": {
        "@babel/core": "^7.1.0",
        "@jest/test-sequencer": "^25.5.4",
        "@jest/types": "^25.5.0",
        "babel-jest": "^25.5.1",
        "chalk": "^3.0.0",
        "deepmerge": "^4.2.2",
        "glob": "^7.1.1",
        "graceful-fs": "^4.2.4",
        "jest-environment-jsdom": "^25.5.0",
        "jest-environment-node": "^25.5.0",
        "jest-get-type": "^25.2.6",
        "jest-jasmine2": "^25.5.4",
        "jest-regex-util": "^25.2.6",
        "jest-resolve": "^25.5.1",
        "jest-util": "^25.5.0",
        "jest-validate": "^25.5.0",
        "micromatch": "^4.0.2",
        "pretty-format": "^25.5.0",
        "realpath-native": "^2.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-config/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-config/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-config/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-config/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-config/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-config/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-diff": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-diff/-/jest-diff-25.5.0.tgz",
      "integrity": "sha512-z1kygetuPiREYdNIumRpAHY6RXiGmp70YHptjdaxTWGmA085W3iCnXNx0DhflK3vwrKmrRWyY1wUpkPMVxMK7A==",
      "dev": true,
      "dependencies": {
        "chalk": "^3.0.0",
        "diff-sequences": "^25.2.6",
        "jest-get-type": "^25.2.6",
        "pretty-format": "^25.5.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-diff/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-diff/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-diff/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-diff/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-diff/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-diff/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-docblock": {
      "version": "25.3.0",
      "resolved": "https://registry.npmjs.org/jest-docblock/-/jest-docblock-25.3.0.tgz",
      "integrity": "sha512-aktF0kCar8+zxRHxQZwxMy70stc9R1mOmrLsT5VO3pIT0uzGRSDAXxSlz4NqQWpuLjPpuMhPRl7H+5FRsvIQAg==",
      "dev": true,
      "dependencies": {
        "detect-newline": "^3.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-each": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-each/-/jest-each-25.5.0.tgz",
      "integrity": "sha512-QBogUxna3D8vtiItvn54xXde7+vuzqRrEeaw8r1s+1TG9eZLVJE5ZkKoSUlqFwRjnlaA4hyKGiu9OlkFIuKnjA==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "jest-get-type": "^25.2.6",
        "jest-util": "^25.5.0",
        "pretty-format": "^25.5.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-each/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-each/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-each/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-each/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-each/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-each/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-environment-jsdom": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-environment-jsdom/-/jest-environment-jsdom-25.5.0.tgz",
      "integrity": "sha512-7Jr02ydaq4jaWMZLY+Skn8wL5nVIYpWvmeatOHL3tOcV3Zw8sjnPpx+ZdeBfc457p8jCR9J6YCc+Lga0oIy62A==",
      "dev": true,
      "dependencies": {
        "@jest/environment": "^25.5.0",
        "@jest/fake-timers": "^25.5.0",
        "@jest/types": "^25.5.0",
        "jest-mock": "^25.5.0",
        "jest-util": "^25.5.0",
        "jsdom": "^15.2.1"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-environment-node": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-environment-node/-/jest-environment-node-25.5.0.tgz",
      "integrity": "sha512-iuxK6rQR2En9EID+2k+IBs5fCFd919gVVK5BeND82fYeLWPqvRcFNPKu9+gxTwfB5XwBGBvZ0HFQa+cHtIoslA==",
      "dev": true,
      "dependencies": {
        "@jest/environment": "^25.5.0",
        "@jest/fake-timers": "^25.5.0",
        "@jest/types": "^25.5.0",
        "jest-mock": "^25.5.0",
        "jest-util": "^25.5.0",
        "semver": "^6.3.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-environment-node/node_modules/semver": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
      "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/jest-get-type": {
      "version": "25.2.6",
      "resolved": "https://registry.npmjs.org/jest-get-type/-/jest-get-type-25.2.6.tgz",
      "integrity": "sha512-DxjtyzOHjObRM+sM1knti6or+eOgcGU4xVSb2HNP1TqO4ahsT+rqZg+nyqHWJSvWgKC5cG3QjGFBqxLghiF/Ig==",
      "dev": true,
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-haste-map": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/jest-haste-map/-/jest-haste-map-25.5.1.tgz",
      "integrity": "sha512-dddgh9UZjV7SCDQUrQ+5t9yy8iEgKc1AKqZR9YDww8xsVOtzPQSMVLDChc21+g29oTRexb9/B0bIlZL+sWmvAQ==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "@types/graceful-fs": "^4.1.2",
        "anymatch": "^3.0.3",
        "fb-watchman": "^2.0.0",
        "graceful-fs": "^4.2.4",
        "jest-serializer": "^25.5.0",
        "jest-util": "^25.5.0",
        "jest-worker": "^25.5.0",
        "micromatch": "^4.0.2",
        "sane": "^4.0.3",
        "walker": "^1.0.7",
        "which": "^2.0.2"
      },
      "engines": {
        "node": ">= 8.3"
      },
      "optionalDependencies": {
        "fsevents": "^2.1.2"
      }
    },
    "node_modules/jest-haste-map/node_modules/which": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/which/-/which-2.0.2.tgz",
      "integrity": "sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==",
      "dev": true,
      "dependencies": {
        "isexe": "^2.0.0"
      },
      "bin": {
        "node-which": "bin/node-which"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/jest-jasmine2": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-jasmine2/-/jest-jasmine2-25.5.4.tgz",
      "integrity": "sha512-9acbWEfbmS8UpdcfqnDO+uBUgKa/9hcRh983IHdM+pKmJPL77G0sWAAK0V0kr5LK3a8cSBfkFSoncXwQlRZfkQ==",
      "dev": true,
      "dependencies": {
        "@babel/traverse": "^7.1.0",
        "@jest/environment": "^25.5.0",
        "@jest/source-map": "^25.5.0",
        "@jest/test-result": "^25.5.0",
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "co": "^4.6.0",
        "expect": "^25.5.0",
        "is-generator-fn": "^2.0.0",
        "jest-each": "^25.5.0",
        "jest-matcher-utils": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-runtime": "^25.5.4",
        "jest-snapshot": "^25.5.1",
        "jest-util": "^25.5.0",
        "pretty-format": "^25.5.0",
        "throat": "^5.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-jasmine2/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-jasmine2/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-jasmine2/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-jasmine2/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-jasmine2/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-jasmine2/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-leak-detector": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-leak-detector/-/jest-leak-detector-25.5.0.tgz",
      "integrity": "sha512-rV7JdLsanS8OkdDpZtgBf61L5xZ4NnYLBq72r6ldxahJWWczZjXawRsoHyXzibM5ed7C2QRjpp6ypgwGdKyoVA==",
      "dev": true,
      "dependencies": {
        "jest-get-type": "^25.2.6",
        "pretty-format": "^25.5.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-matcher-utils": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-matcher-utils/-/jest-matcher-utils-25.5.0.tgz",
      "integrity": "sha512-VWI269+9JS5cpndnpCwm7dy7JtGQT30UHfrnM3mXl22gHGt/b7NkjBqXfbhZ8V4B7ANUsjK18PlSBmG0YH7gjw==",
      "dev": true,
      "dependencies": {
        "chalk": "^3.0.0",
        "jest-diff": "^25.5.0",
        "jest-get-type": "^25.2.6",
        "pretty-format": "^25.5.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-matcher-utils/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-matcher-utils/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-matcher-utils/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-matcher-utils/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-matcher-utils/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-matcher-utils/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-message-util": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-message-util/-/jest-message-util-25.5.0.tgz",
      "integrity": "sha512-ezddz3YCT/LT0SKAmylVyWWIGYoKHOFOFXx3/nA4m794lfVUskMcwhip6vTgdVrOtYdjeQeis2ypzes9mZb4EA==",
      "dev": true,
      "dependencies": {
        "@babel/code-frame": "^7.0.0",
        "@jest/types": "^25.5.0",
        "@types/stack-utils": "^1.0.1",
        "chalk": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "micromatch": "^4.0.2",
        "slash": "^3.0.0",
        "stack-utils": "^1.0.1"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-message-util/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-message-util/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-message-util/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-message-util/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-message-util/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-message-util/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-mock": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-mock/-/jest-mock-25.5.0.tgz",
      "integrity": "sha512-eXWuTV8mKzp/ovHc5+3USJMYsTBhyQ+5A1Mak35dey/RG8GlM4YWVylZuGgVXinaW6tpvk/RSecmF37FKUlpXA==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-pnp-resolver": {
      "version": "1.2.2",
      "resolved": "https://registry.npmjs.org/jest-pnp-resolver/-/jest-pnp-resolver-1.2.2.tgz",
      "integrity": "sha512-olV41bKSMm8BdnuMsewT4jqlZ8+3TCARAXjZGT9jcoSnrfUnRCqnMoF9XEeoWjbzObpqF9dRhHQj0Xb9QdF6/w==",
      "dev": true,
      "engines": {
        "node": ">=6"
      },
      "peerDependencies": {
        "jest-resolve": "*"
      },
      "peerDependenciesMeta": {
        "jest-resolve": {
          "optional": true
        }
      }
    },
    "node_modules/jest-regex-util": {
      "version": "25.2.6",
      "resolved": "https://registry.npmjs.org/jest-regex-util/-/jest-regex-util-25.2.6.tgz",
      "integrity": "sha512-KQqf7a0NrtCkYmZZzodPftn7fL1cq3GQAFVMn5Hg8uKx/fIenLEobNanUxb7abQ1sjADHBseG/2FGpsv/wr+Qw==",
      "dev": true,
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-resolve": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/jest-resolve/-/jest-resolve-25.5.1.tgz",
      "integrity": "sha512-Hc09hYch5aWdtejsUZhA+vSzcotf7fajSlPA6EZPE1RmPBAD39XtJhvHWFStid58iit4IPDLI/Da4cwdDmAHiQ==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "browser-resolve": "^1.11.3",
        "chalk": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "jest-pnp-resolver": "^1.2.1",
        "read-pkg-up": "^7.0.1",
        "realpath-native": "^2.0.0",
        "resolve": "^1.17.0",
        "slash": "^3.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-resolve-dependencies": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-resolve-dependencies/-/jest-resolve-dependencies-25.5.4.tgz",
      "integrity": "sha512-yFmbPd+DAQjJQg88HveObcGBA32nqNZ02fjYmtL16t1xw9bAttSn5UGRRhzMHIQbsep7znWvAvnD4kDqOFM0Uw==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "jest-regex-util": "^25.2.6",
        "jest-snapshot": "^25.5.1"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-resolve/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-resolve/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-resolve/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-resolve/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-resolve/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-resolve/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-runner": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-runner/-/jest-runner-25.5.4.tgz",
      "integrity": "sha512-V/2R7fKZo6blP8E9BL9vJ8aTU4TH2beuqGNxHbxi6t14XzTb+x90B3FRgdvuHm41GY8ch4xxvf0ATH4hdpjTqg==",
      "dev": true,
      "dependencies": {
        "@jest/console": "^25.5.0",
        "@jest/environment": "^25.5.0",
        "@jest/test-result": "^25.5.0",
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "exit": "^0.1.2",
        "graceful-fs": "^4.2.4",
        "jest-config": "^25.5.4",
        "jest-docblock": "^25.3.0",
        "jest-haste-map": "^25.5.1",
        "jest-jasmine2": "^25.5.4",
        "jest-leak-detector": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-resolve": "^25.5.1",
        "jest-runtime": "^25.5.4",
        "jest-util": "^25.5.0",
        "jest-worker": "^25.5.0",
        "source-map-support": "^0.5.6",
        "throat": "^5.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-runner/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-runner/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-runner/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-runner/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-runner/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-runner/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-runtime": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-runtime/-/jest-runtime-25.5.4.tgz",
      "integrity": "sha512-RWTt8LeWh3GvjYtASH2eezkc8AehVoWKK20udV6n3/gC87wlTbE1kIA+opCvNWyyPeBs6ptYsc6nyHUb1GlUVQ==",
      "dev": true,
      "dependencies": {
        "@jest/console": "^25.5.0",
        "@jest/environment": "^25.5.0",
        "@jest/globals": "^25.5.2",
        "@jest/source-map": "^25.5.0",
        "@jest/test-result": "^25.5.0",
        "@jest/transform": "^25.5.1",
        "@jest/types": "^25.5.0",
        "@types/yargs": "^15.0.0",
        "chalk": "^3.0.0",
        "collect-v8-coverage": "^1.0.0",
        "exit": "^0.1.2",
        "glob": "^7.1.3",
        "graceful-fs": "^4.2.4",
        "jest-config": "^25.5.4",
        "jest-haste-map": "^25.5.1",
        "jest-message-util": "^25.5.0",
        "jest-mock": "^25.5.0",
        "jest-regex-util": "^25.2.6",
        "jest-resolve": "^25.5.1",
        "jest-snapshot": "^25.5.1",
        "jest-util": "^25.5.0",
        "jest-validate": "^25.5.0",
        "realpath-native": "^2.0.0",
        "slash": "^3.0.0",
        "strip-bom": "^4.0.0",
        "yargs": "^15.3.1"
      },
      "bin": {
        "jest-runtime": "bin/jest-runtime.js"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-runtime/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-runtime/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-runtime/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-runtime/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-runtime/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-runtime/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-serializer": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-serializer/-/jest-serializer-25.5.0.tgz",
      "integrity": "sha512-LxD8fY1lByomEPflwur9o4e2a5twSQ7TaVNLlFUuToIdoJuBt8tzHfCsZ42Ok6LkKXWzFWf3AGmheuLAA7LcCA==",
      "dev": true,
      "dependencies": {
        "graceful-fs": "^4.2.4"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-snapshot": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/jest-snapshot/-/jest-snapshot-25.5.1.tgz",
      "integrity": "sha512-C02JE1TUe64p2v1auUJ2ze5vcuv32tkv9PyhEb318e8XOKF7MOyXdJ7kdjbvrp3ChPLU2usI7Rjxs97Dj5P0uQ==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.0.0",
        "@jest/types": "^25.5.0",
        "@types/prettier": "^1.19.0",
        "chalk": "^3.0.0",
        "expect": "^25.5.0",
        "graceful-fs": "^4.2.4",
        "jest-diff": "^25.5.0",
        "jest-get-type": "^25.2.6",
        "jest-matcher-utils": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-resolve": "^25.5.1",
        "make-dir": "^3.0.0",
        "natural-compare": "^1.4.0",
        "pretty-format": "^25.5.0",
        "semver": "^6.3.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-snapshot/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-snapshot/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-snapshot/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-snapshot/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-snapshot/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-snapshot/node_modules/semver": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
      "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/jest-snapshot/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-util": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-util/-/jest-util-25.5.0.tgz",
      "integrity": "sha512-KVlX+WWg1zUTB9ktvhsg2PXZVdkI1NBevOJSkTKYAyXyH4QSvh+Lay/e/v+bmaFfrkfx43xD8QTfgobzlEXdIA==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "is-ci": "^2.0.0",
        "make-dir": "^3.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-util/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-util/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-util/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-util/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-util/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-util/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-validate": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-validate/-/jest-validate-25.5.0.tgz",
      "integrity": "sha512-okUFKqhZIpo3jDdtUXUZ2LxGUZJIlfdYBvZb1aczzxrlyMlqdnnws9MOxezoLGhSaFc2XYaHNReNQfj5zPIWyQ==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "camelcase": "^5.3.1",
        "chalk": "^3.0.0",
        "jest-get-type": "^25.2.6",
        "leven": "^3.1.0",
        "pretty-format": "^25.5.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-validate/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-validate/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-validate/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-validate/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-validate/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-validate/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-watcher": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-watcher/-/jest-watcher-25.5.0.tgz",
      "integrity": "sha512-XrSfJnVASEl+5+bb51V0Q7WQx65dTSk7NL4yDdVjPnRNpM0hG+ncFmDYJo9O8jaSRcAitVbuVawyXCRoxGrT5Q==",
      "dev": true,
      "dependencies": {
        "@jest/test-result": "^25.5.0",
        "@jest/types": "^25.5.0",
        "ansi-escapes": "^4.2.1",
        "chalk": "^3.0.0",
        "jest-util": "^25.5.0",
        "string-length": "^3.1.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-watcher/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/jest-watcher/node_modules/chalk": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
      "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-watcher/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/jest-watcher/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/jest-watcher/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-watcher/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-worker": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-worker/-/jest-worker-25.5.0.tgz",
      "integrity": "sha512-/dsSmUkIy5EBGfv/IjjqmFxrNAUpBERfGs1oHROyD7yxjG/w+t0GOJDX8O1k32ySmd7+a5IhnJU2qQFcJ4n1vw==",
      "dev": true,
      "dependencies": {
        "merge-stream": "^2.0.0",
        "supports-color": "^7.0.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/jest-worker/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/jest-worker/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/js-sha3": {
      "version": "0.8.0",
      "resolved": "https://registry.npmjs.org/js-sha3/-/js-sha3-0.8.0.tgz",
      "integrity": "sha512-gF1cRrHhIzNfToc802P800N8PpXS+evLLXfsVpowqmAFR9uwbi89WvXg2QspOmXL8QL86J4T1EpFu+yUkwJY3Q=="
    },
    "node_modules/js-tokens": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/js-tokens/-/js-tokens-4.0.0.tgz",
      "integrity": "sha512-RdJUflcE3cUzKiMqQgsCu06FPu9UdIJO0beYbPhHN4k6apgJtifcoCtT9bcxOpYBtpD2kCM6Sbzg4CausW/PKQ=="
    },
    "node_modules/js-yaml": {
      "version": "3.14.1",
      "resolved": "https://registry.npmjs.org/js-yaml/-/js-yaml-3.14.1.tgz",
      "integrity": "sha512-okMH7OXXJ7YrN9Ok3/SXrnu4iX9yOk+25nqX4imS2npuvTYDmo/QEZoqwZkYaIDk3jVvBOTOIEgEhaLOynBS9g==",
      "dev": true,
      "dependencies": {
        "argparse": "^1.0.7",
        "esprima": "^4.0.0"
      },
      "bin": {
        "js-yaml": "bin/js-yaml.js"
      }
    },
    "node_modules/jsbn": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/jsbn/-/jsbn-0.1.1.tgz",
      "integrity": "sha1-peZUwuWi3rXyAdls77yoDA7y9RM=",
      "dev": true
    },
    "node_modules/jsdom": {
      "version": "15.2.1",
      "resolved": "https://registry.npmjs.org/jsdom/-/jsdom-15.2.1.tgz",
      "integrity": "sha512-fAl1W0/7T2G5vURSyxBzrJ1LSdQn6Tr5UX/xD4PXDx/PDgwygedfW6El/KIj3xJ7FU61TTYnc/l/B7P49Eqt6g==",
      "dev": true,
      "dependencies": {
        "abab": "^2.0.0",
        "acorn": "^7.1.0",
        "acorn-globals": "^4.3.2",
        "array-equal": "^1.0.0",
        "cssom": "^0.4.1",
        "cssstyle": "^2.0.0",
        "data-urls": "^1.1.0",
        "domexception": "^1.0.1",
        "escodegen": "^1.11.1",
        "html-encoding-sniffer": "^1.0.2",
        "nwsapi": "^2.2.0",
        "parse5": "5.1.0",
        "pn": "^1.1.0",
        "request": "^2.88.0",
        "request-promise-native": "^1.0.7",
        "saxes": "^3.1.9",
        "symbol-tree": "^3.2.2",
        "tough-cookie": "^3.0.1",
        "w3c-hr-time": "^1.0.1",
        "w3c-xmlserializer": "^1.1.2",
        "webidl-conversions": "^4.0.2",
        "whatwg-encoding": "^1.0.5",
        "whatwg-mimetype": "^2.3.0",
        "whatwg-url": "^7.0.0",
        "ws": "^7.0.0",
        "xml-name-validator": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      },
      "peerDependencies": {
        "canvas": "^2.5.0"
      },
      "peerDependenciesMeta": {
        "canvas": {
          "optional": true
        }
      }
    },
    "node_modules/jsesc": {
      "version": "2.5.2",
      "resolved": "https://registry.npmjs.org/jsesc/-/jsesc-2.5.2.tgz",
      "integrity": "sha512-OYu7XEzjkCQ3C5Ps3QIZsQfNpqoJyZZA99wd9aWd05NCtC5pWOkShK2mkL6HXQR6/Cy2lbNdPlZBpuQHXE63gA==",
      "dev": true,
      "bin": {
        "jsesc": "bin/jsesc"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/json-parse-even-better-errors": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/json-parse-even-better-errors/-/json-parse-even-better-errors-2.3.1.tgz",
      "integrity": "sha512-xyFwyhro/JEof6Ghe2iz2NcXoj2sloNsWr/XsERDK/oiPCfaNhl5ONfp+jQdAZRQQ0IJWNzH9zIZF7li91kh2w==",
      "dev": true
    },
    "node_modules/json-schema": {
      "version": "0.2.3",
      "resolved": "https://registry.npmjs.org/json-schema/-/json-schema-0.2.3.tgz",
      "integrity": "sha1-tIDIkuWaLwWVTOcnvT8qTogvnhM=",
      "dev": true
    },
    "node_modules/json-schema-traverse": {
      "version": "0.4.1",
      "resolved": "https://registry.npmjs.org/json-schema-traverse/-/json-schema-traverse-0.4.1.tgz",
      "integrity": "sha512-xbbCH5dCYU5T8LcEhhuh7HJ88HXuW3qsI3Y0zOZFKfZEHcpWiHU/Jxzk629Brsab/mMiHQti9wMP+845RPe3Vg==",
      "dev": true
    },
    "node_modules/json-stable-stringify-without-jsonify": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/json-stable-stringify-without-jsonify/-/json-stable-stringify-without-jsonify-1.0.1.tgz",
      "integrity": "sha1-nbe1lJatPzz+8wp1FC0tkwrXJlE=",
      "dev": true
    },
    "node_modules/json-stringify-safe": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/json-stringify-safe/-/json-stringify-safe-5.0.1.tgz",
      "integrity": "sha1-Epai1Y/UXxmg9s4B1lcB4sc1tus=",
      "dev": true
    },
    "node_modules/json5": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/json5/-/json5-2.2.0.tgz",
      "integrity": "sha512-f+8cldu7X/y7RAJurMEJmdoKXGB/X550w2Nr3tTbezL6RwEE/iMcm+tZnXeoZtKuOq6ft8+CqzEkrIgx1fPoQA==",
      "dev": true,
      "dependencies": {
        "minimist": "^1.2.5"
      },
      "bin": {
        "json5": "lib/cli.js"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/jsonfile": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/jsonfile/-/jsonfile-4.0.0.tgz",
      "integrity": "sha1-h3Gq4HmbZAdrdmQPygWPnBDjPss=",
      "dev": true,
      "optionalDependencies": {
        "graceful-fs": "^4.1.6"
      }
    },
    "node_modules/jsprim": {
      "version": "1.4.1",
      "resolved": "https://registry.npmjs.org/jsprim/-/jsprim-1.4.1.tgz",
      "integrity": "sha1-MT5mvB5cwG5Di8G3SZwuXFastqI=",
      "dev": true,
      "engines": [
        "node >=0.6.0"
      ],
      "dependencies": {
        "assert-plus": "1.0.0",
        "extsprintf": "1.3.0",
        "json-schema": "0.2.3",
        "verror": "1.10.0"
      }
    },
    "node_modules/kind-of": {
      "version": "6.0.3",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-6.0.3.tgz",
      "integrity": "sha512-dcS1ul+9tmeD95T+x28/ehLgd9mENa3LsvDTtzm3vyBEO7RPptvAD+t44WVXaUjTBRcrpFeFlC8WCruUR456hw==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/kleur": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/kleur/-/kleur-3.0.3.tgz",
      "integrity": "sha512-eTIzlVOSUR+JxdDFepEYcBMtZ9Qqdef+rnzWdRZuMbOywu5tO2w2N7rqjoANZ5k9vywhL6Br1VRjUIgTQx4E8w==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/knuth-shuffle-seeded": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/knuth-shuffle-seeded/-/knuth-shuffle-seeded-1.0.6.tgz",
      "integrity": "sha1-AfG2VzOqdUDuCNiwF0Fk0iCB5OE=",
      "dev": true,
      "dependencies": {
        "seed-random": "~2.2.0"
      }
    },
    "node_modules/leven": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/leven/-/leven-3.1.0.tgz",
      "integrity": "sha512-qsda+H8jTaUaN/x5vzW2rzc+8Rw4TAQ/4KjB46IwK5VH+IlVeeeje/EoZRpiXvIqjFgK84QffqPztGI3VBLG1A==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/levn": {
      "version": "0.3.0",
      "resolved": "https://registry.npmjs.org/levn/-/levn-0.3.0.tgz",
      "integrity": "sha1-OwmSTt+fCDwEkP3UwLxEIeBHZO4=",
      "dev": true,
      "dependencies": {
        "prelude-ls": "~1.1.2",
        "type-check": "~0.3.2"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/libphonenumber-js": {
      "version": "1.10.18",
      "resolved": "https://registry.npmjs.org/libphonenumber-js/-/libphonenumber-js-1.10.18.tgz",
      "integrity": "sha512-NS4ZEgNhwbcPz1gfSXCGFnQm0xEiyTSPRthIuWytDzOiEG9xnZ2FbLyfJC4tI2BMAAXpoWbNxHYH75pa3Dq9og=="
    },
    "node_modules/lines-and-columns": {
      "version": "1.1.6",
      "resolved": "https://registry.npmjs.org/lines-and-columns/-/lines-and-columns-1.1.6.tgz",
      "integrity": "sha1-HADHQ7QzzQpOgHWPe2SldEDZ/wA=",
      "dev": true
    },
    "node_modules/load-json-file": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/load-json-file/-/load-json-file-2.0.0.tgz",
      "integrity": "sha1-eUfkIUmvgNaWy/eXvKq8/h/inKg=",
      "dev": true,
      "dependencies": {
        "graceful-fs": "^4.1.2",
        "parse-json": "^2.2.0",
        "pify": "^2.0.0",
        "strip-bom": "^3.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/load-json-file/node_modules/parse-json": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/parse-json/-/parse-json-2.2.0.tgz",
      "integrity": "sha1-9ID0BDTvgHQfhGkJn43qGPVaTck=",
      "dev": true,
      "dependencies": {
        "error-ex": "^1.2.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/load-json-file/node_modules/strip-bom": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/strip-bom/-/strip-bom-3.0.0.tgz",
      "integrity": "sha1-IzTBjpx1n3vdVv3vfprj1YjmjtM=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/locate-path": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/locate-path/-/locate-path-5.0.0.tgz",
      "integrity": "sha512-t7hw9pI+WvuwNJXwk5zVHpyhIqzg2qTlklJOf0mVxGSbe3Fp2VieZcduNYjaLDoy6p9uGpQEGWG87WpMKlNq8g==",
      "dev": true,
      "dependencies": {
        "p-locate": "^4.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/lodash": {
      "version": "4.17.21",
      "resolved": "https://registry.npmjs.org/lodash/-/lodash-4.17.21.tgz",
      "integrity": "sha512-v2kDEe57lecTulaDIuNTPy3Ry4gLGJ6Z1O3vE1krgXZNrsQ+LFTGHVxVjcXPs17LhbZVGedAJv8XZ1tvj5FvSg=="
    },
    "node_modules/lodash.memoize": {
      "version": "4.1.2",
      "resolved": "https://registry.npmjs.org/lodash.memoize/-/lodash.memoize-4.1.2.tgz",
      "integrity": "sha1-vMbEmkKihA7Zl/Mj6tpezRguC/4=",
      "dev": true
    },
    "node_modules/lodash.sortby": {
      "version": "4.7.0",
      "resolved": "https://registry.npmjs.org/lodash.sortby/-/lodash.sortby-4.7.0.tgz",
      "integrity": "sha1-7dFMgk4sycHgsKG0K7UhBRakJDg=",
      "dev": true
    },
    "node_modules/lolex": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/lolex/-/lolex-5.1.2.tgz",
      "integrity": "sha512-h4hmjAvHTmd+25JSwrtTIuwbKdwg5NzZVRMLn9saij4SZaepCrTCxPr35H/3bjwfMJtN+t3CX8672UIkglz28A==",
      "dev": true,
      "dependencies": {
        "@sinonjs/commons": "^1.7.0"
      }
    },
    "node_modules/long": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/long/-/long-4.0.0.tgz",
      "integrity": "sha512-XsP+KhQif4bjX1kbuSiySJFNAehNxgLb6hPRGJ9QsUr8ajHkuXGdrHmFUTUUXhDwVX2R5bY4JNZEwbUiMhV+MA==",
      "dev": true
    },
    "node_modules/loose-envify": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/loose-envify/-/loose-envify-1.4.0.tgz",
      "integrity": "sha512-lyuxPGr/Wfhrlem2CL/UcnUc1zcqKAImBDzukY7Y5F/yQiNdko6+fRLevlw1HgMySw7f611UIY408EtxRSoK3Q==",
      "dependencies": {
        "js-tokens": "^3.0.0 || ^4.0.0"
      },
      "bin": {
        "loose-envify": "cli.js"
      }
    },
    "node_modules/lower-case": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/lower-case/-/lower-case-2.0.2.tgz",
      "integrity": "sha512-7fm3l3NAF9WfN6W3JOmf5drwpVqX78JtoGJ3A6W0a6ZnldM41w2fV5D490psKFTpMds8TJse/eHLFFsNHHjHgg==",
      "dev": true,
      "dependencies": {
        "tslib": "^2.0.3"
      }
    },
    "node_modules/lower-case/node_modules/tslib": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
      "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg==",
      "dev": true
    },
    "node_modules/lru-cache": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/lru-cache/-/lru-cache-6.0.0.tgz",
      "integrity": "sha512-Jo6dJ04CmSjuznwJSS3pUeWmd/H0ffTlkXXgwZi+eq1UCmqQwCh+eLsYOYCwY991i2Fah4h1BEMCx4qThGbsiA==",
      "dev": true,
      "dependencies": {
        "yallist": "^4.0.0"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/lunr": {
      "version": "2.3.9",
      "resolved": "https://registry.npmjs.org/lunr/-/lunr-2.3.9.tgz",
      "integrity": "sha512-zTU3DaZaF3Rt9rhN3uBMGQD3dD2/vFQqnvZCDv4dl5iOzq2IZQqTxu90r4E5J+nP70J3ilqVCrbho2eWaeW8Ow==",
      "dev": true
    },
    "node_modules/make-dir": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/make-dir/-/make-dir-3.1.0.tgz",
      "integrity": "sha512-g3FeP20LNwhALb/6Cz6Dd4F2ngze0jz7tbzrD2wAV+o9FeNHe4rL+yK2md0J/fiSf1sa1ADhXqi5+oVwOM/eGw==",
      "dev": true,
      "dependencies": {
        "semver": "^6.0.0"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/make-dir/node_modules/semver": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
      "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/make-error": {
      "version": "1.3.6",
      "resolved": "https://registry.npmjs.org/make-error/-/make-error-1.3.6.tgz",
      "integrity": "sha512-s8UhlNe7vPKomQhC1qFelMokr/Sc3AgNbso3n74mVPA5LTZwkB9NlXf4XPamLxJE8h0gh73rM94xvwRT2CVInw==",
      "dev": true
    },
    "node_modules/makeerror": {
      "version": "1.0.11",
      "resolved": "https://registry.npmjs.org/makeerror/-/makeerror-1.0.11.tgz",
      "integrity": "sha1-4BpckQnyr3lmDk6LlYd5AYT1qWw=",
      "dev": true,
      "dependencies": {
        "tmpl": "1.0.x"
      }
    },
    "node_modules/map-cache": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/map-cache/-/map-cache-0.2.2.tgz",
      "integrity": "sha1-wyq9C9ZSXZsFFkW7TyasXcmKDb8=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/map-visit": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/map-visit/-/map-visit-1.0.0.tgz",
      "integrity": "sha1-7Nyo8TFE5mDxtb1B8S80edmN+48=",
      "dev": true,
      "dependencies": {
        "object-visit": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/marked": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/marked/-/marked-1.0.0.tgz",
      "integrity": "sha512-Wo+L1pWTVibfrSr+TTtMuiMfNzmZWiOPeO7rZsQUY5bgsxpHesBEcIWJloWVTFnrMXnf/TL30eTFSGJddmQAng==",
      "dev": true,
      "bin": {
        "marked": "bin/marked"
      },
      "engines": {
        "node": ">= 8.16.2"
      }
    },
    "node_modules/merge-stream": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/merge-stream/-/merge-stream-2.0.0.tgz",
      "integrity": "sha512-abv/qOcuPfk3URPfDzmZU1LKmuw8kT+0nIHvKrKgFrwifol/doWcdA4ZqsWQ8ENrFKkd67Mfpo/LovbIUsbt3w==",
      "dev": true
    },
    "node_modules/micromatch": {
      "version": "4.0.4",
      "resolved": "https://registry.npmjs.org/micromatch/-/micromatch-4.0.4.tgz",
      "integrity": "sha512-pRmzw/XUcwXGpD9aI9q/0XOwLNygjETJ8y0ao0wdqprrzDa4YnxLcz7fQRZr8voh8V10kGhABbNcHVk5wHgWwg==",
      "dev": true,
      "dependencies": {
        "braces": "^3.0.1",
        "picomatch": "^2.2.3"
      },
      "engines": {
        "node": ">=8.6"
      }
    },
    "node_modules/mime-db": {
      "version": "1.48.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.48.0.tgz",
      "integrity": "sha512-FM3QwxV+TnZYQ2aRqhlKBMHxk10lTbMt3bBkMAp54ddrNeVSfcQYOOKuGuy3Ddrm38I04If834fOUSq1yzslJQ==",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/mime-types": {
      "version": "2.1.31",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.31.tgz",
      "integrity": "sha512-XGZnNzm3QvgKxa8dpzyhFTHmpP3l5YNusmne07VUOXxou9CqUqYa/HBy124RqtVh/O2pECas/MOcsDgpilPOPg==",
      "dependencies": {
        "mime-db": "1.48.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/mimic-fn": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/mimic-fn/-/mimic-fn-2.1.0.tgz",
      "integrity": "sha512-OqbOk5oEQeAZ8WXWydlu9HJjz9WVdEIvamMCcXmuqUYjTknH/sqsWvhQ3vgwKFRR1HpjvNBKQ37nbJgYzGqGcg==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/minimalistic-assert": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/minimalistic-assert/-/minimalistic-assert-1.0.1.tgz",
      "integrity": "sha512-UtJcAD4yEaGtjPezWuO9wC4nwUnVH/8/Im3yEHQP4b67cXlD/Qr9hdITCU1xDbSEXg2XKNaP8jsReV7vQd00/A=="
    },
    "node_modules/minimalistic-crypto-utils": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/minimalistic-crypto-utils/-/minimalistic-crypto-utils-1.0.1.tgz",
      "integrity": "sha1-9sAMHAsIIkblxNmd+4x8CDsrWCo="
    },
    "node_modules/minimatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/minimatch/-/minimatch-3.1.2.tgz",
      "integrity": "sha512-J7p63hRiAjw1NDEww1W7i37+ByIrOWO5XQQAzZ3VOcL0PNybwpfmV/N05zFAzwQ9USyEcX6t3UO+K5aqBQOIHw==",
      "dev": true,
      "dependencies": {
        "brace-expansion": "^1.1.7"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/minimist": {
      "version": "1.2.6",
      "resolved": "https://registry.npmjs.org/minimist/-/minimist-1.2.6.tgz",
      "integrity": "sha512-Jsjnk4bw3YJqYzbdyBiNsPWHPfO++UGG749Cxs6peCu5Xg4nrena6OVxOYxrQTqww0Jmwt+Ref8rggumkTLz9Q==",
      "dev": true
    },
    "node_modules/mixin-deep": {
      "version": "1.3.2",
      "resolved": "https://registry.npmjs.org/mixin-deep/-/mixin-deep-1.3.2.tgz",
      "integrity": "sha512-WRoDn//mXBiJ1H40rqa3vH0toePwSsGb45iInWlTySa+Uu4k3tYUSxa2v1KqAiLtvlrSzaExqS1gtk96A9zvEA==",
      "dev": true,
      "dependencies": {
        "for-in": "^1.0.2",
        "is-extendable": "^1.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/mkdirp": {
      "version": "0.5.5",
      "resolved": "https://registry.npmjs.org/mkdirp/-/mkdirp-0.5.5.tgz",
      "integrity": "sha512-NKmAlESf6jMGym1++R0Ra7wvhV+wFW63FaSOFPwRahvea0gMUcGUhVeAg/0BC0wiv9ih5NYPB1Wn1UEI1/L+xQ==",
      "dev": true,
      "dependencies": {
        "minimist": "^1.2.5"
      },
      "bin": {
        "mkdirp": "bin/cmd.js"
      }
    },
    "node_modules/ms": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.1.2.tgz",
      "integrity": "sha512-sGkPx+VjMtmA6MX27oA4FBFELFCZZ4S4XqeGOXCv68tT+jb3vk/RyaKWP0PTKyWtmLSM0b+adUTEvbs1PEaH2w==",
      "dev": true
    },
    "node_modules/mute-stream": {
      "version": "0.0.8",
      "resolved": "https://registry.npmjs.org/mute-stream/-/mute-stream-0.0.8.tgz",
      "integrity": "sha512-nnbWWOkoWyUsTjKrhgD0dcz22mdkSnpYqbEjIm2nhwhuxlSkpywJmBo8h0ZqJdkp73mb90SssHkN4rsRaBAfAA==",
      "dev": true
    },
    "node_modules/mz": {
      "version": "2.7.0",
      "resolved": "https://registry.npmjs.org/mz/-/mz-2.7.0.tgz",
      "integrity": "sha512-z81GNO7nnYMEhrGh9LeymoE4+Yr0Wn5McHIZMK5cfQCl+NDX08sCZgUc9/6MHni9IWuFLm1Z3HTCXu2z9fN62Q==",
      "dev": true,
      "dependencies": {
        "any-promise": "^1.0.0",
        "object-assign": "^4.0.1",
        "thenify-all": "^1.0.0"
      }
    },
    "node_modules/nanomatch": {
      "version": "1.2.13",
      "resolved": "https://registry.npmjs.org/nanomatch/-/nanomatch-1.2.13.tgz",
      "integrity": "sha512-fpoe2T0RbHwBTBUOftAfBPaDEi06ufaUai0mE6Yn1kacc3SnTErfb/h+X94VXzI64rKFHYImXSvdwGGCmwOqCA==",
      "dev": true,
      "dependencies": {
        "arr-diff": "^4.0.0",
        "array-unique": "^0.3.2",
        "define-property": "^2.0.2",
        "extend-shallow": "^3.0.2",
        "fragment-cache": "^0.2.1",
        "is-windows": "^1.0.2",
        "kind-of": "^6.0.2",
        "object.pick": "^1.3.0",
        "regex-not": "^1.0.0",
        "snapdragon": "^0.8.1",
        "to-regex": "^3.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/natural-compare": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/natural-compare/-/natural-compare-1.4.0.tgz",
      "integrity": "sha1-Sr6/7tdUHywnrPspvbvRXI1bpPc=",
      "dev": true
    },
    "node_modules/negotiator": {
      "version": "0.6.3",
      "resolved": "https://registry.npmjs.org/negotiator/-/negotiator-0.6.3.tgz",
      "integrity": "sha512-+EUsqGPLsM+j/zdChZjsnX51g4XrHFOIXwfnCVPGlQk/k5giakcKsuxCObBRu6DSm9opw/O6slWbJdghQM4bBg==",
      "dev": true,
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/neo-async": {
      "version": "2.6.2",
      "resolved": "https://registry.npmjs.org/neo-async/-/neo-async-2.6.2.tgz",
      "integrity": "sha512-Yd3UES5mWCSqR+qNT93S3UoYUkqAZ9lLg8a7g9rimsWmYGK8cVToA4/sF3RrshdyV3sAGMXVUmpMYOw+dLpOuw==",
      "dev": true
    },
    "node_modules/next-tick": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/next-tick/-/next-tick-1.0.0.tgz",
      "integrity": "sha1-yobR/ogoFpsBICCOPchCS524NCw=",
      "dev": true
    },
    "node_modules/nice-try": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/nice-try/-/nice-try-1.0.5.tgz",
      "integrity": "sha512-1nh45deeb5olNY7eX82BkPO7SSxR5SSYJiPTrTdFUVYwAl8CKMA5N9PjTYkHiRjisVcxcQ1HXdLhx2qxxJzLNQ==",
      "dev": true
    },
    "node_modules/no-case": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/no-case/-/no-case-3.0.4.tgz",
      "integrity": "sha512-fgAN3jGAh+RoxUGZHTSOLJIqUc2wmoBwGR4tbpNAKmmovFoWq0OdRkb0VkldReO2a2iBT/OEulG9XSUc10r3zg==",
      "dev": true,
      "dependencies": {
        "lower-case": "^2.0.2",
        "tslib": "^2.0.3"
      }
    },
    "node_modules/no-case/node_modules/tslib": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
      "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg==",
      "dev": true
    },
    "node_modules/node-fetch": {
      "version": "2.6.7",
      "resolved": "https://registry.npmjs.org/node-fetch/-/node-fetch-2.6.7.tgz",
      "integrity": "sha512-ZjMPFEfVx5j+y2yF35Kzx5sF7kDzxuDj6ziH4FFbOp87zKDZNx8yExJIb05OGF4Nlt9IHFIMBkRl41VdvcNdbQ==",
      "dependencies": {
        "whatwg-url": "^5.0.0"
      },
      "engines": {
        "node": "4.x || >=6.0.0"
      },
      "peerDependencies": {
        "encoding": "^0.1.0"
      },
      "peerDependenciesMeta": {
        "encoding": {
          "optional": true
        }
      }
    },
    "node_modules/node-fetch/node_modules/tr46": {
      "version": "0.0.3",
      "resolved": "https://registry.npmjs.org/tr46/-/tr46-0.0.3.tgz",
      "integrity": "sha512-N3WMsuqV66lT30CrXNbEjx4GEwlow3v6rr4mCcv6prnfwhS01rkgyFdjPNBYd9br7LpXV1+Emh01fHnq2Gdgrw=="
    },
    "node_modules/node-fetch/node_modules/webidl-conversions": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/webidl-conversions/-/webidl-conversions-3.0.1.tgz",
      "integrity": "sha512-2JAn3z8AR6rjK8Sm8orRC0h/bcl/DqL7tRPdGZ4I1CjdF+EaMLmYxBHyXuKL849eucPFhvBoxMsflfOb8kxaeQ=="
    },
    "node_modules/node-fetch/node_modules/whatwg-url": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/whatwg-url/-/whatwg-url-5.0.0.tgz",
      "integrity": "sha512-saE57nupxk6v3HY35+jzBwYa0rKSy0XR8JSxZPwgLr7ys0IBzhGviA1/TUGJLmSVqs8pb9AnvICXEuOHLprYTw==",
      "dependencies": {
        "tr46": "~0.0.3",
        "webidl-conversions": "^3.0.0"
      }
    },
    "node_modules/node-int64": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/node-int64/-/node-int64-0.4.0.tgz",
      "integrity": "sha1-h6kGXNs1XTGC2PlM4RGIuCXGijs=",
      "dev": true
    },
    "node_modules/node-modules-regexp": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/node-modules-regexp/-/node-modules-regexp-1.0.0.tgz",
      "integrity": "sha1-jZ2+KJZKSsVxLpExZCEHxx6Q7EA=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/node-notifier": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/node-notifier/-/node-notifier-6.0.0.tgz",
      "integrity": "sha512-SVfQ/wMw+DesunOm5cKqr6yDcvUTDl/yc97ybGHMrteNEY6oekXpNpS3lZwgLlwz0FLgHoiW28ZpmBHUDg37cw==",
      "dev": true,
      "optional": true,
      "dependencies": {
        "growly": "^1.3.0",
        "is-wsl": "^2.1.1",
        "semver": "^6.3.0",
        "shellwords": "^0.1.1",
        "which": "^1.3.1"
      }
    },
    "node_modules/node-notifier/node_modules/semver": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
      "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
      "dev": true,
      "optional": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/node-releases": {
      "version": "1.1.73",
      "resolved": "https://registry.npmjs.org/node-releases/-/node-releases-1.1.73.tgz",
      "integrity": "sha512-uW7fodD6pyW2FZNZnp/Z3hvWKeEW1Y8R1+1CnErE8cXFXzl5blBOoVB41CvMer6P6Q0S5FXDwcHgFd1Wj0U9zg==",
      "dev": true
    },
    "node_modules/normalize-package-data": {
      "version": "2.5.0",
      "resolved": "https://registry.npmjs.org/normalize-package-data/-/normalize-package-data-2.5.0.tgz",
      "integrity": "sha512-/5CMN3T0R4XTj4DcGaexo+roZSdSFW/0AOOTROrjxzCG1wrWXEsGbRKevjlIL+ZDE4sZlJr5ED4YW0yqmkK+eA==",
      "dev": true,
      "dependencies": {
        "hosted-git-info": "^2.1.4",
        "resolve": "^1.10.0",
        "semver": "2 || 3 || 4 || 5",
        "validate-npm-package-license": "^3.0.1"
      }
    },
    "node_modules/normalize-package-data/node_modules/semver": {
      "version": "5.7.1",
      "resolved": "https://registry.npmjs.org/semver/-/semver-5.7.1.tgz",
      "integrity": "sha512-sauaDf/PZdVgrLTNYHRtpXa1iRiKcaebiKQ1BJdpQlWH2lCvexQdX55snPFyK7QzpudqbCI0qXFfOasHdyNDGQ==",
      "dev": true,
      "bin": {
        "semver": "bin/semver"
      }
    },
    "node_modules/normalize-path": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/normalize-path/-/normalize-path-3.0.0.tgz",
      "integrity": "sha512-6eZs5Ls3WtCisHWp9S2GUy8dqkpGi4BVSz3GaqiE6ezub0512ESztXUwUB6C6IKbQkY2Pnb/mD4WYojCRwcwLA==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/npm-run-path": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/npm-run-path/-/npm-run-path-4.0.1.tgz",
      "integrity": "sha512-S48WzZW777zhNIrn7gxOlISNAqi9ZC/uQFnRdbeIHhZhCA6UqpkOT8T1G7BvfdgP4Er8gF4sUbaS0i7QvIfCWw==",
      "dev": true,
      "dependencies": {
        "path-key": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/npm-run-path/node_modules/path-key": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz",
      "integrity": "sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/nwsapi": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/nwsapi/-/nwsapi-2.2.0.tgz",
      "integrity": "sha512-h2AatdwYH+JHiZpv7pt/gSX1XoRGb7L/qSIeuqA6GwYoF9w1vP1cw42TO0aI2pNyshRK5893hNSl+1//vHK7hQ==",
      "dev": true
    },
    "node_modules/oauth-sign": {
      "version": "0.9.0",
      "resolved": "https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.9.0.tgz",
      "integrity": "sha512-fexhUFFPTGV8ybAtSIGbV6gOkSv8UtRbDBnAyLQw4QPKkgNlsH2ByPGtMUqdWkos6YCRmAqViwgZrJc/mRDzZQ==",
      "dev": true,
      "engines": {
        "node": "*"
      }
    },
    "node_modules/object-assign": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/object-assign/-/object-assign-4.1.1.tgz",
      "integrity": "sha1-IQmtx5ZYh8/AXLvUQsrIv7s2CGM=",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-copy": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/object-copy/-/object-copy-0.1.0.tgz",
      "integrity": "sha1-fn2Fi3gb18mRpBupde04EnVOmYw=",
      "dev": true,
      "dependencies": {
        "copy-descriptor": "^0.1.0",
        "define-property": "^0.2.5",
        "kind-of": "^3.0.3"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-copy/node_modules/define-property": {
      "version": "0.2.5",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
      "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
      "dev": true,
      "dependencies": {
        "is-descriptor": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-copy/node_modules/is-accessor-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
      "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-copy/node_modules/is-data-descriptor": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
      "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-copy/node_modules/is-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
      "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
      "dev": true,
      "dependencies": {
        "is-accessor-descriptor": "^0.1.6",
        "is-data-descriptor": "^0.1.4",
        "kind-of": "^5.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-copy/node_modules/is-descriptor/node_modules/kind-of": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
      "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-copy/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-inspect": {
      "version": "1.10.3",
      "resolved": "https://registry.npmjs.org/object-inspect/-/object-inspect-1.10.3.tgz",
      "integrity": "sha512-e5mCJlSH7poANfC8z8S9s9S2IN5/4Zb3aZ33f5s8YqoazCFzNLloLU8r5VCG+G7WoqLvAAZoVMcy3tp/3X0Plw==",
      "dev": true,
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/object-keys": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/object-keys/-/object-keys-1.1.1.tgz",
      "integrity": "sha512-NuAESUOUMrlIXOfHKzD6bpPu3tYt3xvjNdRIQ+FeT0lNb4K8WR70CaDxhuNguS2XG+GjkyMwOzsN5ZktImfhLA==",
      "dev": true,
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/object-visit": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/object-visit/-/object-visit-1.0.1.tgz",
      "integrity": "sha1-95xEk68MU3e1n+OdOV5BBC3QRbs=",
      "dev": true,
      "dependencies": {
        "isobject": "^3.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object.assign": {
      "version": "4.1.2",
      "resolved": "https://registry.npmjs.org/object.assign/-/object.assign-4.1.2.tgz",
      "integrity": "sha512-ixT2L5THXsApyiUPYKmW+2EHpXXe5Ii3M+f4e+aJFAHao5amFRW6J0OO6c/LU8Be47utCx2GL89hxGB6XSmKuQ==",
      "dev": true,
      "dependencies": {
        "call-bind": "^1.0.0",
        "define-properties": "^1.1.3",
        "has-symbols": "^1.0.1",
        "object-keys": "^1.1.1"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/object.pick": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/object.pick/-/object.pick-1.3.0.tgz",
      "integrity": "sha1-h6EKxMFpS9Lhy/U1kaZhQftd10c=",
      "dev": true,
      "dependencies": {
        "isobject": "^3.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object.values": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/object.values/-/object.values-1.1.4.tgz",
      "integrity": "sha512-TnGo7j4XSnKQoK3MfvkzqKCi0nVe/D9I9IjwTNYdb/fxYHpjrluHVOgw0AF6jrRFGMPHdfuidR09tIDiIvnaSg==",
      "dev": true,
      "dependencies": {
        "call-bind": "^1.0.2",
        "define-properties": "^1.1.3",
        "es-abstract": "^1.18.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/on-headers": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/on-headers/-/on-headers-1.0.2.tgz",
      "integrity": "sha512-pZAE+FJLoyITytdqK0U5s+FIpjN0JP3OzFi/u8Rx+EV5/W+JTWGXG8xFzevE7AjBfDqHv/8vL8qQsIhHnqRkrA==",
      "dev": true,
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/once": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/once/-/once-1.4.0.tgz",
      "integrity": "sha1-WDsap3WWHUsROsF9nFC6753Xa9E=",
      "dev": true,
      "dependencies": {
        "wrappy": "1"
      }
    },
    "node_modules/onetime": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/onetime/-/onetime-5.1.2.tgz",
      "integrity": "sha512-kbpaSSGJTWdAY5KPVeMOKXSrPtr8C8C7wodJbcsd51jRnmD+GZu8Y0VoU6Dm5Z4vWr0Ig/1NKuWRKf7j5aaYSg==",
      "dev": true,
      "dependencies": {
        "mimic-fn": "^2.1.0"
      },
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/optimism": {
      "version": "0.16.1",
      "resolved": "https://registry.npmjs.org/optimism/-/optimism-0.16.1.tgz",
      "integrity": "sha512-64i+Uw3otrndfq5kaoGNoY7pvOhSsjFEN4bdEFh80MWVk/dbgJfMv7VFDeCT8LxNAlEVhQmdVEbfE7X2nWNIIg==",
      "dependencies": {
        "@wry/context": "^0.6.0",
        "@wry/trie": "^0.3.0"
      }
    },
    "node_modules/optionator": {
      "version": "0.8.3",
      "resolved": "https://registry.npmjs.org/optionator/-/optionator-0.8.3.tgz",
      "integrity": "sha512-+IW9pACdk3XWmmTXG8m3upGUJst5XRGzxMRjXzAuJ1XnIFNvfhjjIuYkDvysnPQ7qzqVzLt78BCruntqRhWQbA==",
      "dev": true,
      "dependencies": {
        "deep-is": "~0.1.3",
        "fast-levenshtein": "~2.0.6",
        "levn": "~0.3.0",
        "prelude-ls": "~1.1.2",
        "type-check": "~0.3.2",
        "word-wrap": "~1.2.3"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/os-tmpdir": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/os-tmpdir/-/os-tmpdir-1.0.2.tgz",
      "integrity": "sha1-u+Z0BseaqFxc/sdm/lc0VV36EnQ=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/p-each-series": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/p-each-series/-/p-each-series-2.2.0.tgz",
      "integrity": "sha512-ycIL2+1V32th+8scbpTvyHNaHe02z0sjgh91XXjAk+ZeXoPN4Z46DVUnzdso0aX4KckKw0FNNFHdjZ2UsZvxiA==",
      "dev": true,
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/p-finally": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/p-finally/-/p-finally-2.0.1.tgz",
      "integrity": "sha512-vpm09aKwq6H9phqRQzecoDpD8TmVyGw70qmWlyq5onxY7tqyTTFVvxMykxQSQKILBSFlbXpypIw2T1Ml7+DDtw==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/p-limit": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/p-limit/-/p-limit-2.3.0.tgz",
      "integrity": "sha512-//88mFWSJx8lxCzwdAABTJL2MyWB12+eIY7MDL2SqLmAkeKU9qxRvWuSyTjm3FUmpBEMuFfckAIqEaVGUDxb6w==",
      "dev": true,
      "dependencies": {
        "p-try": "^2.0.0"
      },
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/p-locate": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/p-locate/-/p-locate-4.1.0.tgz",
      "integrity": "sha512-R79ZZ/0wAxKGu3oYMlz8jy/kbhsNrS7SKZ7PxEHBgJ5+F2mtFW2fK2cOtBh1cHYkQsbzFV7I+EoRKe6Yt0oK7A==",
      "dev": true,
      "dependencies": {
        "p-limit": "^2.2.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/p-try": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/p-try/-/p-try-2.2.0.tgz",
      "integrity": "sha512-R4nPAVTAU0B9D35/Gk3uJf/7XYbQcyohSKdvAxIRSNghFl4e71hVoGnBNQz9cWaXxO2I10KTC+3jMdvvoKw6dQ==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/pad-right": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/pad-right/-/pad-right-0.2.2.tgz",
      "integrity": "sha1-b7ySQEXSRPKiokRQMGDTv8YAl3Q=",
      "dev": true,
      "dependencies": {
        "repeat-string": "^1.5.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/parent-module": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/parent-module/-/parent-module-1.0.1.tgz",
      "integrity": "sha512-GQ2EWRpQV8/o+Aw8YqtfZZPfNRWZYkbidE9k5rpl/hC3vtHHBfGm2Ifi6qWV+coDGkrUKZAxE3Lot5kcsRlh+g==",
      "dev": true,
      "dependencies": {
        "callsites": "^3.0.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/parse-json": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/parse-json/-/parse-json-5.2.0.tgz",
      "integrity": "sha512-ayCKvm/phCGxOkYRSCM82iDwct8/EonSEgCSxWxD7ve6jHggsFl4fZVQBPRNgQoKiuV/odhFrGzQXZwbifC8Rg==",
      "dev": true,
      "dependencies": {
        "@babel/code-frame": "^7.0.0",
        "error-ex": "^1.3.1",
        "json-parse-even-better-errors": "^2.3.0",
        "lines-and-columns": "^1.1.6"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/parse5": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/parse5/-/parse5-5.1.0.tgz",
      "integrity": "sha512-fxNG2sQjHvlVAYmzBZS9YlDp6PTSSDwa98vkD4QgVDDCAo84z5X1t5XyJQ62ImdLXx5NdIIfihey6xpum9/gRQ==",
      "dev": true
    },
    "node_modules/pascalcase": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/pascalcase/-/pascalcase-0.1.1.tgz",
      "integrity": "sha1-s2PlXoAGym/iF4TS2yK9FdeRfxQ=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/path-exists": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/path-exists/-/path-exists-4.0.0.tgz",
      "integrity": "sha512-ak9Qy5Q7jYb2Wwcey5Fpvg2KoAc/ZIhLSLOSBmRmygPsGwkVVt0fZa0qrtMz+m6tJTAHfZQ8FnmB4MG4LWy7/w==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/path-is-absolute": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/path-is-absolute/-/path-is-absolute-1.0.1.tgz",
      "integrity": "sha1-F0uSaHNVNP+8es5r9TpanhtcX18=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/path-is-inside": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/path-is-inside/-/path-is-inside-1.0.2.tgz",
      "integrity": "sha512-DUWJr3+ULp4zXmol/SZkFf3JGsS9/SIv+Y3Rt93/UjPpDpklB5f1er4O3POIbUuUJ3FXgqte2Q7SrU6zAqwk8w==",
      "dev": true
    },
    "node_modules/path-key": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/path-key/-/path-key-2.0.1.tgz",
      "integrity": "sha1-QRyttXTFoUDTpLGRDUDYDMn0C0A=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/path-parse": {
      "version": "1.0.7",
      "resolved": "https://registry.npmjs.org/path-parse/-/path-parse-1.0.7.tgz",
      "integrity": "sha512-LDJzPVEEEPR+y48z93A0Ed0yXb8pAByGWo/k5YYdYgpY2/2EsOsksJrq7lOHxryrVOn1ejG6oAp8ahvOIQD8sw==",
      "dev": true
    },
    "node_modules/path-to-regexp": {
      "version": "2.2.1",
      "resolved": "https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-2.2.1.tgz",
      "integrity": "sha512-gu9bD6Ta5bwGrrU8muHzVOBFFREpp2iRkVfhBJahwJ6p6Xw20SjT0MxLnwkjOibQmGSYhiUnf2FLe7k+jcFmGQ==",
      "dev": true
    },
    "node_modules/path-type": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/path-type/-/path-type-2.0.0.tgz",
      "integrity": "sha1-8BLMuEFbcJb8LaoQVMPXI4lZTHM=",
      "dev": true,
      "dependencies": {
        "pify": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/performance-now": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/performance-now/-/performance-now-2.1.0.tgz",
      "integrity": "sha1-Ywn04OX6kT7BxpMHrjZLSzd8nns=",
      "dev": true
    },
    "node_modules/picomatch": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/picomatch/-/picomatch-2.3.0.tgz",
      "integrity": "sha512-lY1Q/PiJGC2zOv/z391WOTD+Z02bCgsFfvxoXXf6h7kv9o+WmsmzYqrAwY63sNgOxE4xEdq0WyUnXfKeBrSvYw==",
      "dev": true,
      "engines": {
        "node": ">=8.6"
      },
      "funding": {
        "url": "https://github.com/sponsors/jonschlinkert"
      }
    },
    "node_modules/pify": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/pify/-/pify-2.3.0.tgz",
      "integrity": "sha1-7RQaasBDqEnqWISY59yosVMw6Qw=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/pinkie": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz",
      "integrity": "sha1-clVrgM+g1IqXToDnckjoDtT3+HA=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/pinkie-promise": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz",
      "integrity": "sha1-ITXW36ejWMBprJsXh3YogihFD/o=",
      "dev": true,
      "dependencies": {
        "pinkie": "^2.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/pirates": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/pirates/-/pirates-4.0.1.tgz",
      "integrity": "sha512-WuNqLTbMI3tmfef2TKxlQmAiLHKtFhlsCZnPIpuv2Ow0RDVO8lfy1Opf4NUzlMXLjPl+Men7AuVdX6TA+s+uGA==",
      "dev": true,
      "dependencies": {
        "node-modules-regexp": "^1.0.0"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/pkg-dir": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/pkg-dir/-/pkg-dir-2.0.0.tgz",
      "integrity": "sha1-9tXREJ4Z1j7fQo4L1X4Sd3YVM0s=",
      "dev": true,
      "dependencies": {
        "find-up": "^2.1.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pkg-dir/node_modules/find-up": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/find-up/-/find-up-2.1.0.tgz",
      "integrity": "sha1-RdG35QbHF93UgndaK3eSCjwMV6c=",
      "dev": true,
      "dependencies": {
        "locate-path": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pkg-dir/node_modules/locate-path": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/locate-path/-/locate-path-2.0.0.tgz",
      "integrity": "sha1-K1aLJl7slExtnA3pw9u7ygNUzY4=",
      "dev": true,
      "dependencies": {
        "p-locate": "^2.0.0",
        "path-exists": "^3.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pkg-dir/node_modules/p-limit": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/p-limit/-/p-limit-1.3.0.tgz",
      "integrity": "sha512-vvcXsLAJ9Dr5rQOPk7toZQZJApBl2K4J6dANSsEuh6QI41JYcsS/qhTGa9ErIUUgK3WNQoJYvylxvjqmiqEA9Q==",
      "dev": true,
      "dependencies": {
        "p-try": "^1.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pkg-dir/node_modules/p-locate": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/p-locate/-/p-locate-2.0.0.tgz",
      "integrity": "sha1-IKAQOyIqcMj9OcwuWAaA893l7EM=",
      "dev": true,
      "dependencies": {
        "p-limit": "^1.1.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pkg-dir/node_modules/p-try": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/p-try/-/p-try-1.0.0.tgz",
      "integrity": "sha1-y8ec26+P1CKOE/Yh8rGiN8GyB7M=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pkg-dir/node_modules/path-exists": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/path-exists/-/path-exists-3.0.0.tgz",
      "integrity": "sha1-zg6+ql94yxiSXqfYENe1mwEP1RU=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pn": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/pn/-/pn-1.1.0.tgz",
      "integrity": "sha512-2qHaIQr2VLRFoxe2nASzsV6ef4yOOH+Fi9FBOVH6cqeSgUnoyySPZkxzLuzd+RYOQTRpROA0ztTMqxROKSb/nA==",
      "dev": true
    },
    "node_modules/posix-character-classes": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/posix-character-classes/-/posix-character-classes-0.1.1.tgz",
      "integrity": "sha1-AerA/jta9xoqbAL+q7jB/vfgDqs=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/prelude-ls": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/prelude-ls/-/prelude-ls-1.1.2.tgz",
      "integrity": "sha1-IZMqVJ9eUv/ZqCf1cOBL5iqX2lQ=",
      "dev": true,
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/prettier": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/prettier/-/prettier-2.0.5.tgz",
      "integrity": "sha512-7PtVymN48hGcO4fGjybyBSIWDsLU4H4XlvOHfq91pz9kkGlonzwTfYkaIEwiRg/dAJF9YlbsduBAgtYLi+8cFg==",
      "dev": true,
      "bin": {
        "prettier": "bin-prettier.js"
      },
      "engines": {
        "node": ">=10.13.0"
      }
    },
    "node_modules/pretty-format": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/pretty-format/-/pretty-format-25.5.0.tgz",
      "integrity": "sha512-kbo/kq2LQ/A/is0PQwsEHM7Ca6//bGPPvU6UnsdDRSKTWxT/ru/xb88v4BJf6a69H+uTytOEsTusT9ksd/1iWQ==",
      "dev": true,
      "dependencies": {
        "@jest/types": "^25.5.0",
        "ansi-regex": "^5.0.0",
        "ansi-styles": "^4.0.0",
        "react-is": "^16.12.0"
      },
      "engines": {
        "node": ">= 8.3"
      }
    },
    "node_modules/pretty-format/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/pretty-format/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/pretty-format/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/progress": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/progress/-/progress-2.0.3.tgz",
      "integrity": "sha512-7PiHtLll5LdnKIMw100I+8xJXR5gW2QwWYkT6iJva0bXitZKa/XMrSbdmg3r2Xnaidz9Qumd0VPaMrZlF9V9sA==",
      "dev": true,
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/prompts": {
      "version": "2.4.1",
      "resolved": "https://registry.npmjs.org/prompts/-/prompts-2.4.1.tgz",
      "integrity": "sha512-EQyfIuO2hPDsX1L/blblV+H7I0knhgAd82cVneCwcdND9B8AuCDuRcBH6yIcG4dFzlOUqbazQqwGjx5xmsNLuQ==",
      "dev": true,
      "dependencies": {
        "kleur": "^3.0.3",
        "sisteransi": "^1.0.5"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/prop-types": {
      "version": "15.7.2",
      "resolved": "https://registry.npmjs.org/prop-types/-/prop-types-15.7.2.tgz",
      "integrity": "sha512-8QQikdH7//R2vurIJSutZ1smHYTcLpRWEOlHnzcWHmBYrOGUysKwSsrC89BCiFj3CbrfJ/nXFdJepOVrY1GCHQ==",
      "dependencies": {
        "loose-envify": "^1.4.0",
        "object-assign": "^4.1.1",
        "react-is": "^16.8.1"
      }
    },
    "node_modules/protobufjs": {
      "version": "6.11.2",
      "resolved": "https://registry.npmjs.org/protobufjs/-/protobufjs-6.11.2.tgz",
      "integrity": "sha512-4BQJoPooKJl2G9j3XftkIXjoC9C0Av2NOrWmbLWT1vH32GcSUHjM0Arra6UfTsVyfMAuFzaLucXn1sadxJydAw==",
      "dev": true,
      "hasInstallScript": true,
      "dependencies": {
        "@protobufjs/aspromise": "^1.1.2",
        "@protobufjs/base64": "^1.1.2",
        "@protobufjs/codegen": "^2.0.4",
        "@protobufjs/eventemitter": "^1.1.0",
        "@protobufjs/fetch": "^1.1.0",
        "@protobufjs/float": "^1.0.2",
        "@protobufjs/inquire": "^1.1.0",
        "@protobufjs/path": "^1.1.2",
        "@protobufjs/pool": "^1.1.0",
        "@protobufjs/utf8": "^1.1.0",
        "@types/long": "^4.0.1",
        "@types/node": ">=13.7.0",
        "long": "^4.0.0"
      },
      "bin": {
        "pbjs": "bin/pbjs",
        "pbts": "bin/pbts"
      }
    },
    "node_modules/proxy-from-env": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/proxy-from-env/-/proxy-from-env-1.1.0.tgz",
      "integrity": "sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg=="
    },
    "node_modules/psl": {
      "version": "1.8.0",
      "resolved": "https://registry.npmjs.org/psl/-/psl-1.8.0.tgz",
      "integrity": "sha512-RIdOzyoavK+hA18OGGWDqUTsCLhtA7IcZ/6NCs4fFJaHBDab+pDDmDIByWFRQJq2Cd7r1OoQxBGKOaztq+hjIQ==",
      "dev": true
    },
    "node_modules/pump": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/pump/-/pump-3.0.0.tgz",
      "integrity": "sha512-LwZy+p3SFs1Pytd/jYct4wpv49HiYCqd9Rlc5ZVdk0V+8Yzv6jR5Blk3TRmPL1ft69TxP0IMZGJ+WPFU2BFhww==",
      "dev": true,
      "dependencies": {
        "end-of-stream": "^1.1.0",
        "once": "^1.3.1"
      }
    },
    "node_modules/punycode": {
      "version": "1.4.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-1.4.1.tgz",
      "integrity": "sha512-jmYNElW7yvO7TV33CjSmvSiE2yco3bV2czu/OzDKdMNVZQWfxCblURLhf+47syQRBntjfLdd/H0egrzIG+oaFQ==",
      "dev": true
    },
    "node_modules/qs": {
      "version": "6.5.2",
      "resolved": "https://registry.npmjs.org/qs/-/qs-6.5.2.tgz",
      "integrity": "sha512-N5ZAX4/LxJmF+7wN74pUD6qAh9/wnvdQcjq9TZjevvXzSUo7bfmw91saqMjzGS2xq91/odN2dW/WOl7qQHNDGA==",
      "dev": true,
      "engines": {
        "node": ">=0.6"
      }
    },
    "node_modules/range-parser": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz",
      "integrity": "sha512-kA5WQoNVo4t9lNx2kQNFCxKeBl5IbbSNBl1M/tLkw9WCn+hxNBAW5Qh8gdhs63CJnhjJ2zQWFoqPJP2sK1AV5A==",
      "dev": true,
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/rc": {
      "version": "1.2.8",
      "resolved": "https://registry.npmjs.org/rc/-/rc-1.2.8.tgz",
      "integrity": "sha512-y3bGgqKj3QBdxLbLkomlohkvsA8gdAiUQlSBJnBhfn+BPxg4bc62d8TcBW15wavDfgexCgccckhcZvywyQYPOw==",
      "dev": true,
      "dependencies": {
        "deep-extend": "^0.6.0",
        "ini": "~1.3.0",
        "minimist": "^1.2.0",
        "strip-json-comments": "~2.0.1"
      },
      "bin": {
        "rc": "cli.js"
      }
    },
    "node_modules/rc/node_modules/strip-json-comments": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-2.0.1.tgz",
      "integrity": "sha512-4gB8na07fecVVkOI6Rs4e7T6NOTki5EmL7TUduTs6bu3EdnSycntVJ4re8kgZA+wx9IueI2Y11bfbgwtzuE0KQ==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/react-is": {
      "version": "16.13.1",
      "resolved": "https://registry.npmjs.org/react-is/-/react-is-16.13.1.tgz",
      "integrity": "sha512-24e6ynE2H+OKt4kqsOvNd8kBpV65zoxbA4BVsEOB3ARVWQki/DHzaUoC5KuON/BiccDaCCTZBuOcfZs70kR8bQ=="
    },
    "node_modules/read-pkg": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/read-pkg/-/read-pkg-5.2.0.tgz",
      "integrity": "sha512-Ug69mNOpfvKDAc2Q8DRpMjjzdtrnv9HcSMX+4VsZxD1aZ6ZzrIE7rlzXBtWTyhULSMKg076AW6WR5iZpD0JiOg==",
      "dev": true,
      "dependencies": {
        "@types/normalize-package-data": "^2.4.0",
        "normalize-package-data": "^2.5.0",
        "parse-json": "^5.0.0",
        "type-fest": "^0.6.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/read-pkg-up": {
      "version": "7.0.1",
      "resolved": "https://registry.npmjs.org/read-pkg-up/-/read-pkg-up-7.0.1.tgz",
      "integrity": "sha512-zK0TB7Xd6JpCLmlLmufqykGE+/TlOePD6qKClNW7hHDKFh/J7/7gCWGR7joEQEW1bKq3a3yUZSObOoWLFQ4ohg==",
      "dev": true,
      "dependencies": {
        "find-up": "^4.1.0",
        "read-pkg": "^5.2.0",
        "type-fest": "^0.8.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/read-pkg/node_modules/type-fest": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/type-fest/-/type-fest-0.6.0.tgz",
      "integrity": "sha512-q+MB8nYR1KDLrgr4G5yemftpMC7/QLqVndBmEEdqzmNj5dcFOO4Oo8qlwZE3ULT3+Zim1F8Kq4cBnikNhlCMlg==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/realpath-native": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/realpath-native/-/realpath-native-2.0.0.tgz",
      "integrity": "sha512-v1SEYUOXXdbBZK8ZuNgO4TBjamPsiSgcFr0aP+tEKpQZK8vooEUqV6nm6Cv502mX4NF2EfsnVqtNAHG+/6Ur1Q==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/rechoir": {
      "version": "0.6.2",
      "resolved": "https://registry.npmjs.org/rechoir/-/rechoir-0.6.2.tgz",
      "integrity": "sha1-hSBLVNuoLVdC4oyWdW70OvUOM4Q=",
      "dev": true,
      "dependencies": {
        "resolve": "^1.1.6"
      },
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/reflect-metadata": {
      "version": "0.1.13",
      "resolved": "https://registry.npmjs.org/reflect-metadata/-/reflect-metadata-0.1.13.tgz",
      "integrity": "sha512-Ts1Y/anZELhSsjMcU605fU9RE4Oi3p5ORujwbIKXfWa+0Zxs510Qrmrce5/Jowq3cHSZSJqBjypxmHarc+vEWg==",
      "dev": true
    },
    "node_modules/regex-not": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/regex-not/-/regex-not-1.0.2.tgz",
      "integrity": "sha512-J6SDjUgDxQj5NusnOtdFxDwN/+HWykR8GELwctJ7mdqhcyy1xEc4SRFHUXvxTp661YaVKAjfRLZ9cCqS6tn32A==",
      "dev": true,
      "dependencies": {
        "extend-shallow": "^3.0.2",
        "safe-regex": "^1.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/regexpp": {
      "version": "3.2.0",
      "resolved": "https://registry.npmjs.org/regexpp/-/regexpp-3.2.0.tgz",
      "integrity": "sha512-pq2bWo9mVD43nbts2wGv17XLiNLya+GklZ8kaDLV2Z08gDCsGpnKn9BFMepvWuHCbyVvY7J5o5+BVvoQbmlJLg==",
      "dev": true,
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/mysticatea"
      }
    },
    "node_modules/registry-auth-token": {
      "version": "3.3.2",
      "resolved": "https://registry.npmjs.org/registry-auth-token/-/registry-auth-token-3.3.2.tgz",
      "integrity": "sha512-JL39c60XlzCVgNrO+qq68FoNb56w/m7JYvGR2jT5iR1xBrUA3Mfx5Twk5rqTThPmQKMWydGmq8oFtDlxfrmxnQ==",
      "dev": true,
      "dependencies": {
        "rc": "^1.1.6",
        "safe-buffer": "^5.0.1"
      }
    },
    "node_modules/registry-url": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/registry-url/-/registry-url-3.1.0.tgz",
      "integrity": "sha512-ZbgR5aZEdf4UKZVBPYIgaglBmSF2Hi94s2PcIHhRGFjKYu+chjJdYfHn4rt3hB6eCKLJ8giVIIfgMa1ehDfZKA==",
      "dev": true,
      "dependencies": {
        "rc": "^1.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/remove-trailing-separator": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/remove-trailing-separator/-/remove-trailing-separator-1.1.0.tgz",
      "integrity": "sha1-wkvOKig62tW8P1jg1IJJuSN52O8=",
      "dev": true
    },
    "node_modules/repeat-element": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/repeat-element/-/repeat-element-1.1.4.tgz",
      "integrity": "sha512-LFiNfRcSu7KK3evMyYOuCzv3L10TW7yC1G2/+StMjK8Y6Vqd2MG7r/Qjw4ghtuCOjFvlnms/iMmLqpvW/ES/WQ==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/repeat-string": {
      "version": "1.6.1",
      "resolved": "https://registry.npmjs.org/repeat-string/-/repeat-string-1.6.1.tgz",
      "integrity": "sha1-jcrkcOHIirwtYA//Sndihtp15jc=",
      "dev": true,
      "engines": {
        "node": ">=0.10"
      }
    },
    "node_modules/request": {
      "version": "2.88.2",
      "resolved": "https://registry.npmjs.org/request/-/request-2.88.2.tgz",
      "integrity": "sha512-MsvtOrfG9ZcrOwAW+Qi+F6HbD0CWXEh9ou77uOb7FM2WPhwT7smM833PzanhJLsgXjN89Ir6V2PczXNnMpwKhw==",
      "deprecated": "request has been deprecated, see https://github.com/request/request/issues/3142",
      "dev": true,
      "dependencies": {
        "aws-sign2": "~0.7.0",
        "aws4": "^1.8.0",
        "caseless": "~0.12.0",
        "combined-stream": "~1.0.6",
        "extend": "~3.0.2",
        "forever-agent": "~0.6.1",
        "form-data": "~2.3.2",
        "har-validator": "~5.1.3",
        "http-signature": "~1.2.0",
        "is-typedarray": "~1.0.0",
        "isstream": "~0.1.2",
        "json-stringify-safe": "~5.0.1",
        "mime-types": "~2.1.19",
        "oauth-sign": "~0.9.0",
        "performance-now": "^2.1.0",
        "qs": "~6.5.2",
        "safe-buffer": "^5.1.2",
        "tough-cookie": "~2.5.0",
        "tunnel-agent": "^0.6.0",
        "uuid": "^3.3.2"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/request-promise-core": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/request-promise-core/-/request-promise-core-1.1.4.tgz",
      "integrity": "sha512-TTbAfBBRdWD7aNNOoVOBH4pN/KigV6LyapYNNlAPA8JwbovRti1E88m3sYAwsLi5ryhPKsE9APwnjFTgdUjTpw==",
      "dev": true,
      "dependencies": {
        "lodash": "^4.17.19"
      },
      "engines": {
        "node": ">=0.10.0"
      },
      "peerDependencies": {
        "request": "^2.34"
      }
    },
    "node_modules/request-promise-native": {
      "version": "1.0.9",
      "resolved": "https://registry.npmjs.org/request-promise-native/-/request-promise-native-1.0.9.tgz",
      "integrity": "sha512-wcW+sIUiWnKgNY0dqCpOZkUbF/I+YPi+f09JZIDa39Ec+q82CpSYniDp+ISgTTbKmnpJWASeJBPZmoxH84wt3g==",
      "deprecated": "request-promise-native has been deprecated because it extends the now deprecated request package, see https://github.com/request/request/issues/3142",
      "dev": true,
      "dependencies": {
        "request-promise-core": "1.1.4",
        "stealthy-require": "^1.1.1",
        "tough-cookie": "^2.3.3"
      },
      "engines": {
        "node": ">=0.12.0"
      },
      "peerDependencies": {
        "request": "^2.34"
      }
    },
    "node_modules/request-promise-native/node_modules/punycode": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
      "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/request-promise-native/node_modules/tough-cookie": {
      "version": "2.5.0",
      "resolved": "https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.5.0.tgz",
      "integrity": "sha512-nlLsUzgm1kfLXSXfRZMc1KLAugd4hqJHDTvc2hDIwS3mZAfMEuMbc03SujMF+GEcpaX/qboeycw6iO8JwVv2+g==",
      "dev": true,
      "dependencies": {
        "psl": "^1.1.28",
        "punycode": "^2.1.1"
      },
      "engines": {
        "node": ">=0.8"
      }
    },
    "node_modules/request/node_modules/punycode": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
      "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/request/node_modules/tough-cookie": {
      "version": "2.5.0",
      "resolved": "https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.5.0.tgz",
      "integrity": "sha512-nlLsUzgm1kfLXSXfRZMc1KLAugd4hqJHDTvc2hDIwS3mZAfMEuMbc03SujMF+GEcpaX/qboeycw6iO8JwVv2+g==",
      "dev": true,
      "dependencies": {
        "psl": "^1.1.28",
        "punycode": "^2.1.1"
      },
      "engines": {
        "node": ">=0.8"
      }
    },
    "node_modules/request/node_modules/uuid": {
      "version": "3.4.0",
      "resolved": "https://registry.npmjs.org/uuid/-/uuid-3.4.0.tgz",
      "integrity": "sha512-HjSDRw6gZE5JMggctHBcjVak08+KEVhSIiDzFnT9S9aegmp85S/bReBVTb4QTFaRNptJ9kuYaNhnbNEOkbKb/A==",
      "deprecated": "Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.",
      "dev": true,
      "bin": {
        "uuid": "bin/uuid"
      }
    },
    "node_modules/require-directory": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/require-directory/-/require-directory-2.1.1.tgz",
      "integrity": "sha1-jGStX9MNqxyXbiNE/+f3kqam30I=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/require-from-string": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/require-from-string/-/require-from-string-2.0.2.tgz",
      "integrity": "sha512-Xf0nWe6RseziFMu+Ap9biiUbmplq6S9/p+7w7YXP/JBHhrUDDUhwa+vANyubuqfZWTveU//DYVGsDG7RKL/vEw==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/require-main-filename": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/require-main-filename/-/require-main-filename-2.0.0.tgz",
      "integrity": "sha512-NKN5kMDylKuldxYLSUfrbo5Tuzh4hd+2E8NPPX02mZtn1VuREQToYe/ZdlJy+J3uCpfaiGF05e7B8W0iXbQHmg==",
      "dev": true
    },
    "node_modules/resolve": {
      "version": "1.20.0",
      "resolved": "https://registry.npmjs.org/resolve/-/resolve-1.20.0.tgz",
      "integrity": "sha512-wENBPt4ySzg4ybFQW2TT1zMQucPK95HSh/nq2CFTZVOGut2+pQvSsgtda4d26YrYcr067wjbmzOG8byDPBX63A==",
      "dev": true,
      "dependencies": {
        "is-core-module": "^2.2.0",
        "path-parse": "^1.0.6"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/resolve-cwd": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/resolve-cwd/-/resolve-cwd-3.0.0.tgz",
      "integrity": "sha512-OrZaX2Mb+rJCpH/6CpSqt9xFVpN++x01XnN2ie9g6P5/3xelLAkXWVADpdz1IHD/KFfEXyE6V0U01OQ3UO2rEg==",
      "dev": true,
      "dependencies": {
        "resolve-from": "^5.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/resolve-cwd/node_modules/resolve-from": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/resolve-from/-/resolve-from-5.0.0.tgz",
      "integrity": "sha512-qYg9KP24dD5qka9J47d0aVky0N+b4fTU89LN9iDnjB5waksiC49rvMB0PrUJQGoTmH50XPiqOvAjDfaijGxYZw==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/resolve-from": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/resolve-from/-/resolve-from-4.0.0.tgz",
      "integrity": "sha512-pb/MYmXstAkysRFx8piNI1tGFNQIFA3vkE3Gq4EuA1dF6gHp/+vgZqsCGJapvy8N3Q+4o7FwvquPJcnZ7RYy4g==",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/resolve-url": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/resolve-url/-/resolve-url-0.2.1.tgz",
      "integrity": "sha1-LGN/53yJOv0qZj/iGqkIAGjiBSo=",
      "deprecated": "https://github.com/lydell/resolve-url#deprecated",
      "dev": true
    },
    "node_modules/restore-cursor": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/restore-cursor/-/restore-cursor-3.1.0.tgz",
      "integrity": "sha512-l+sSefzHpj5qimhFSE5a8nufZYAM3sBSVMAPtYkmC+4EH2anSGaEMXSD0izRQbu9nfyQ9y5JrVmp7E8oZrUjvA==",
      "dev": true,
      "dependencies": {
        "onetime": "^5.1.0",
        "signal-exit": "^3.0.2"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/ret": {
      "version": "0.1.15",
      "resolved": "https://registry.npmjs.org/ret/-/ret-0.1.15.tgz",
      "integrity": "sha512-TTlYpa+OL+vMMNG24xSlQGEJ3B/RzEfUlLct7b5G/ytav+wPrplCpVMFuwzXbkecJrb6IYo1iFb0S9v37754mg==",
      "dev": true,
      "engines": {
        "node": ">=0.12"
      }
    },
    "node_modules/rimraf": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/rimraf/-/rimraf-3.0.2.tgz",
      "integrity": "sha512-JZkJMZkAGFFPP2YqXZXPbMlMBgsxzE8ILs4lMIX/2o0L9UBw9O/Y3o6wFw/i9YLapcUJWwqbi3kdxIPdC62TIA==",
      "dev": true,
      "dependencies": {
        "glob": "^7.1.3"
      },
      "bin": {
        "rimraf": "bin.js"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/rsvp": {
      "version": "4.8.5",
      "resolved": "https://registry.npmjs.org/rsvp/-/rsvp-4.8.5.tgz",
      "integrity": "sha512-nfMOlASu9OnRJo1mbEk2cz0D56a1MBNrJ7orjRZQG10XDyuvwksKbuXNp6qa+kbn839HwjwhBzhFmdsaEAfauA==",
      "dev": true,
      "engines": {
        "node": "6.* || >= 7.*"
      }
    },
    "node_modules/run-async": {
      "version": "2.4.1",
      "resolved": "https://registry.npmjs.org/run-async/-/run-async-2.4.1.tgz",
      "integrity": "sha512-tvVnVv01b8c1RrA6Ep7JkStj85Guv/YrMcwqYQnwjsAS2cTmmPGBBjAjpCW7RrSodNSoE2/qg9O4bceNvUuDgQ==",
      "dev": true,
      "engines": {
        "node": ">=0.12.0"
      }
    },
    "node_modules/rxjs": {
      "version": "6.6.7",
      "resolved": "https://registry.npmjs.org/rxjs/-/rxjs-6.6.7.tgz",
      "integrity": "sha512-hTdwr+7yYNIT5n4AMYp85KA6yw2Va0FLa3Rguvbpa4W3I5xynaBZo41cM3XM+4Q6fRMj3sBYIR1VAmZMXYJvRQ==",
      "dev": true,
      "dependencies": {
        "tslib": "^1.9.0"
      },
      "engines": {
        "npm": ">=2.0.0"
      }
    },
    "node_modules/safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g==",
      "dev": true
    },
    "node_modules/safe-regex": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/safe-regex/-/safe-regex-1.1.0.tgz",
      "integrity": "sha1-QKNmnzsHfR6UPURinhV91IAjvy4=",
      "dev": true,
      "dependencies": {
        "ret": "~0.1.10"
      }
    },
    "node_modules/safer-buffer": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/safer-buffer/-/safer-buffer-2.1.2.tgz",
      "integrity": "sha512-YZo3K82SD7Riyi0E1EQPojLz7kpepnSQI9IyPbHHg1XXXevb5dJI7tpyN2ADxGcQbHG7vcyRHk0cbwqcQriUtg==",
      "dev": true
    },
    "node_modules/sane": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/sane/-/sane-4.1.0.tgz",
      "integrity": "sha512-hhbzAgTIX8O7SHfp2c8/kREfEn4qO/9q8C9beyY6+tvZ87EpoZ3i1RIEvp27YBswnNbY9mWd6paKVmKbAgLfZA==",
      "deprecated": "some dependency vulnerabilities fixed, support for node < 10 dropped, and newer ECMAScript syntax/features added",
      "dev": true,
      "dependencies": {
        "@cnakazawa/watch": "^1.0.3",
        "anymatch": "^2.0.0",
        "capture-exit": "^2.0.0",
        "exec-sh": "^0.3.2",
        "execa": "^1.0.0",
        "fb-watchman": "^2.0.0",
        "micromatch": "^3.1.4",
        "minimist": "^1.1.1",
        "walker": "~1.0.5"
      },
      "bin": {
        "sane": "src/cli.js"
      },
      "engines": {
        "node": "6.* || 8.* || >= 10.*"
      }
    },
    "node_modules/sane/node_modules/anymatch": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/anymatch/-/anymatch-2.0.0.tgz",
      "integrity": "sha512-5teOsQWABXHHBFP9y3skS5P3d/WfWXpv3FUpy+LorMrNYaT9pI4oLMQX7jzQ2KklNpGpWHzdCXTDT2Y3XGlZBw==",
      "dev": true,
      "dependencies": {
        "micromatch": "^3.1.4",
        "normalize-path": "^2.1.1"
      }
    },
    "node_modules/sane/node_modules/braces": {
      "version": "2.3.2",
      "resolved": "https://registry.npmjs.org/braces/-/braces-2.3.2.tgz",
      "integrity": "sha512-aNdbnj9P8PjdXU4ybaWLK2IF3jc/EoDYbC7AazW6to3TRsfXxscC9UXOB5iDiEQrkyIbWp2SLQda4+QAa7nc3w==",
      "dev": true,
      "dependencies": {
        "arr-flatten": "^1.1.0",
        "array-unique": "^0.3.2",
        "extend-shallow": "^2.0.1",
        "fill-range": "^4.0.0",
        "isobject": "^3.0.1",
        "repeat-element": "^1.1.2",
        "snapdragon": "^0.8.1",
        "snapdragon-node": "^2.0.1",
        "split-string": "^3.0.2",
        "to-regex": "^3.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/braces/node_modules/extend-shallow": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
      "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
      "dev": true,
      "dependencies": {
        "is-extendable": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/execa": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/execa/-/execa-1.0.0.tgz",
      "integrity": "sha512-adbxcyWV46qiHyvSp50TKt05tB4tK3HcmF7/nxfAdhnox83seTDbwnaqKO4sXRy7roHAIFqJP/Rw/AuEbX61LA==",
      "dev": true,
      "dependencies": {
        "cross-spawn": "^6.0.0",
        "get-stream": "^4.0.0",
        "is-stream": "^1.1.0",
        "npm-run-path": "^2.0.0",
        "p-finally": "^1.0.0",
        "signal-exit": "^3.0.0",
        "strip-eof": "^1.0.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/sane/node_modules/fill-range": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/fill-range/-/fill-range-4.0.0.tgz",
      "integrity": "sha1-1USBHUKPmOsGpj3EAtJAPDKMOPc=",
      "dev": true,
      "dependencies": {
        "extend-shallow": "^2.0.1",
        "is-number": "^3.0.0",
        "repeat-string": "^1.6.1",
        "to-regex-range": "^2.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/fill-range/node_modules/extend-shallow": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
      "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
      "dev": true,
      "dependencies": {
        "is-extendable": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/get-stream": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/get-stream/-/get-stream-4.1.0.tgz",
      "integrity": "sha512-GMat4EJ5161kIy2HevLlr4luNjBgvmj413KaQA7jt4V8B4RDsfpHk7WQ9GVqfYyyx8OS/L66Kox+rJRNklLK7w==",
      "dev": true,
      "dependencies": {
        "pump": "^3.0.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/sane/node_modules/is-extendable": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
      "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/is-number": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/is-number/-/is-number-3.0.0.tgz",
      "integrity": "sha1-JP1iAaR4LPUFYcgQJ2r8fRLXEZU=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/is-number/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/is-stream": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/is-stream/-/is-stream-1.1.0.tgz",
      "integrity": "sha1-EtSj3U5o4Lec6428hBc66A2RykQ=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/micromatch": {
      "version": "3.1.10",
      "resolved": "https://registry.npmjs.org/micromatch/-/micromatch-3.1.10.tgz",
      "integrity": "sha512-MWikgl9n9M3w+bpsY3He8L+w9eF9338xRl8IAO5viDizwSzziFEyUzo2xrrloB64ADbTf8uA8vRqqttDTOmccg==",
      "dev": true,
      "dependencies": {
        "arr-diff": "^4.0.0",
        "array-unique": "^0.3.2",
        "braces": "^2.3.1",
        "define-property": "^2.0.2",
        "extend-shallow": "^3.0.2",
        "extglob": "^2.0.4",
        "fragment-cache": "^0.2.1",
        "kind-of": "^6.0.2",
        "nanomatch": "^1.2.9",
        "object.pick": "^1.3.0",
        "regex-not": "^1.0.0",
        "snapdragon": "^0.8.1",
        "to-regex": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/normalize-path": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/normalize-path/-/normalize-path-2.1.1.tgz",
      "integrity": "sha1-GrKLVW4Zg2Oowab35vogE3/mrtk=",
      "dev": true,
      "dependencies": {
        "remove-trailing-separator": "^1.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sane/node_modules/npm-run-path": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/npm-run-path/-/npm-run-path-2.0.2.tgz",
      "integrity": "sha1-NakjLfo11wZ7TLLd8jV7GHFTbF8=",
      "dev": true,
      "dependencies": {
        "path-key": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/sane/node_modules/p-finally": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/p-finally/-/p-finally-1.0.0.tgz",
      "integrity": "sha1-P7z7FbiZpEEjs0ttzBi3JDNqLK4=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/sane/node_modules/to-regex-range": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/to-regex-range/-/to-regex-range-2.1.1.tgz",
      "integrity": "sha1-fIDBe53+vlmeJzZ+DU3VWQFB2zg=",
      "dev": true,
      "dependencies": {
        "is-number": "^3.0.0",
        "repeat-string": "^1.6.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/saxes": {
      "version": "3.1.11",
      "resolved": "https://registry.npmjs.org/saxes/-/saxes-3.1.11.tgz",
      "integrity": "sha512-Ydydq3zC+WYDJK1+gRxRapLIED9PWeSuuS41wqyoRmzvhhh9nc+QQrVMKJYzJFULazeGhzSV0QleN2wD3boh2g==",
      "dev": true,
      "dependencies": {
        "xmlchars": "^2.1.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/scrypt-js": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/scrypt-js/-/scrypt-js-3.0.1.tgz",
      "integrity": "sha512-cdwTTnqPu0Hyvf5in5asVdZocVDTNRmR7XEcJuIzMjJeSHybHl7vpB66AzwTaIg6CLSbtjcxc8fqcySfnTkccA=="
    },
    "node_modules/seed-random": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/seed-random/-/seed-random-2.2.0.tgz",
      "integrity": "sha1-KpsZ4lCoFwmSMaW5mk2vgLf77VQ=",
      "dev": true
    },
    "node_modules/semver": {
      "version": "7.3.5",
      "resolved": "https://registry.npmjs.org/semver/-/semver-7.3.5.tgz",
      "integrity": "sha512-PoeGJYh8HK4BTO/a9Tf6ZG3veo/A7ZVsYrSA6J8ny9nb3B1VrpkuN+z9OE5wfE5p6H4LchYZsegiQgbJD94ZFQ==",
      "dev": true,
      "dependencies": {
        "lru-cache": "^6.0.0"
      },
      "bin": {
        "semver": "bin/semver.js"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/serve": {
      "version": "14.1.2",
      "resolved": "https://registry.npmjs.org/serve/-/serve-14.1.2.tgz",
      "integrity": "sha512-luwVfJwbeE7dhCKeRU0vIBpt4bXdbAfzwsWJIQ5eqrIW2e+4nLWXbSlZ0WzelSFHQq+FlueOW6dr90jEewS9zw==",
      "dev": true,
      "dependencies": {
        "@zeit/schemas": "2.21.0",
        "ajv": "8.11.0",
        "arg": "5.0.2",
        "boxen": "7.0.0",
        "chalk": "5.0.1",
        "chalk-template": "0.4.0",
        "clipboardy": "3.0.0",
        "compression": "1.7.4",
        "is-port-reachable": "4.0.0",
        "serve-handler": "6.1.5",
        "update-check": "1.5.4"
      },
      "bin": {
        "serve": "build/main.js"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/serve-handler": {
      "version": "6.1.5",
      "resolved": "https://registry.npmjs.org/serve-handler/-/serve-handler-6.1.5.tgz",
      "integrity": "sha512-ijPFle6Hwe8zfmBxJdE+5fta53fdIY0lHISJvuikXB3VYFafRjMRpOffSPvCYsbKyBA7pvy9oYr/BT1O3EArlg==",
      "dev": true,
      "dependencies": {
        "bytes": "3.0.0",
        "content-disposition": "0.5.2",
        "fast-url-parser": "1.1.3",
        "mime-types": "2.1.18",
        "minimatch": "3.1.2",
        "path-is-inside": "1.0.2",
        "path-to-regexp": "2.2.1",
        "range-parser": "1.2.0"
      }
    },
    "node_modules/serve-handler/node_modules/mime-db": {
      "version": "1.33.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.33.0.tgz",
      "integrity": "sha512-BHJ/EKruNIqJf/QahvxwQZXKygOQ256myeN/Ew+THcAa5q+PjyTTMMeNQC4DZw5AwfvelsUrA6B67NKMqXDbzQ==",
      "dev": true,
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/serve-handler/node_modules/mime-types": {
      "version": "2.1.18",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.18.tgz",
      "integrity": "sha512-lc/aahn+t4/SWV/qcmumYjymLsWfN3ELhpmVuUFjgsORruuZPVSwAQryq+HHGvO/SI2KVX26bx+En+zhM8g8hQ==",
      "dev": true,
      "dependencies": {
        "mime-db": "~1.33.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/serve/node_modules/ajv": {
      "version": "8.11.0",
      "resolved": "https://registry.npmjs.org/ajv/-/ajv-8.11.0.tgz",
      "integrity": "sha512-wGgprdCvMalC0BztXvitD2hC04YffAvtsUn93JbGXYLAtCUO4xd17mCCZQxUOItiBwZvJScWo8NIvQMQ71rdpg==",
      "dev": true,
      "dependencies": {
        "fast-deep-equal": "^3.1.1",
        "json-schema-traverse": "^1.0.0",
        "require-from-string": "^2.0.2",
        "uri-js": "^4.2.2"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/epoberezkin"
      }
    },
    "node_modules/serve/node_modules/chalk": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-5.0.1.tgz",
      "integrity": "sha512-Fo07WOYGqMfCWHOzSXOt2CxDbC6skS/jO9ynEcmpANMoPrD+W1r1K6Vx7iNm+AQmETU1Xr2t+n8nzkV9t6xh3w==",
      "dev": true,
      "engines": {
        "node": "^12.17.0 || ^14.13 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/chalk/chalk?sponsor=1"
      }
    },
    "node_modules/serve/node_modules/json-schema-traverse": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/json-schema-traverse/-/json-schema-traverse-1.0.0.tgz",
      "integrity": "sha512-NM8/P9n3XjXhIZn1lLhkFaACTOURQXjWhV4BA/RnOv8xvgqtqpAX9IO4mRQxSx1Rlo4tqzeqb0sOlruaOy3dug==",
      "dev": true
    },
    "node_modules/set-blocking": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/set-blocking/-/set-blocking-2.0.0.tgz",
      "integrity": "sha1-BF+XgtARrppoA93TgrJDkrPYkPc=",
      "dev": true
    },
    "node_modules/set-value": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/set-value/-/set-value-2.0.1.tgz",
      "integrity": "sha512-JxHc1weCN68wRY0fhCoXpyK55m/XPHafOmK4UWD7m2CI14GMcFypt4w/0+NV5f/ZMby2F6S2wwA7fgynh9gWSw==",
      "dev": true,
      "dependencies": {
        "extend-shallow": "^2.0.1",
        "is-extendable": "^0.1.1",
        "is-plain-object": "^2.0.3",
        "split-string": "^3.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/set-value/node_modules/extend-shallow": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
      "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
      "dev": true,
      "dependencies": {
        "is-extendable": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/set-value/node_modules/is-extendable": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
      "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/shebang-command": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/shebang-command/-/shebang-command-1.2.0.tgz",
      "integrity": "sha1-RKrGW2lbAzmJaMOfNj/uXer98eo=",
      "dev": true,
      "dependencies": {
        "shebang-regex": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/shebang-regex": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/shebang-regex/-/shebang-regex-1.0.0.tgz",
      "integrity": "sha1-2kL0l0DAtC2yypcoVxyxkMmO/qM=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/shelljs": {
      "version": "0.8.5",
      "resolved": "https://registry.npmjs.org/shelljs/-/shelljs-0.8.5.tgz",
      "integrity": "sha512-TiwcRcrkhHvbrZbnRcFYMLl30Dfov3HKqzp5tO5b4pt6G/SezKcYhmDg15zXVBswHmctSAQKznqNW2LO5tTDow==",
      "dev": true,
      "dependencies": {
        "glob": "^7.0.0",
        "interpret": "^1.0.0",
        "rechoir": "^0.6.2"
      },
      "bin": {
        "shjs": "bin/shjs"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/shellwords": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/shellwords/-/shellwords-0.1.1.tgz",
      "integrity": "sha512-vFwSUfQvqybiICwZY5+DAWIPLKsWO31Q91JSKl3UYv+K5c2QRPzn0qzec6QPu1Qc9eHYItiP3NdJqNVqetYAww==",
      "dev": true,
      "optional": true
    },
    "node_modules/signal-exit": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/signal-exit/-/signal-exit-3.0.3.tgz",
      "integrity": "sha512-VUJ49FC8U1OxwZLxIbTTrDvLnf/6TDgxZcK8wxR8zs13xpx7xbG60ndBlhNrFi2EMuFRoeDoJO7wthSLq42EjA==",
      "dev": true
    },
    "node_modules/sisteransi": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/sisteransi/-/sisteransi-1.0.5.tgz",
      "integrity": "sha512-bLGGlR1QxBcynn2d5YmDX4MGjlZvy2MRBDRNHLJ8VI6l6+9FUiyTFNJ0IveOSP0bcXgVDPRcfGqA0pjaqUpfVg==",
      "dev": true
    },
    "node_modules/slash": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/slash/-/slash-3.0.0.tgz",
      "integrity": "sha512-g9Q1haeby36OSStwb4ntCGGGaKsaVSjQ68fBxoQcutl5fS1vuY18H3wSt3jFyFtrkx+Kz0V1G85A4MyAdDMi2Q==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/slice-ansi": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/slice-ansi/-/slice-ansi-2.1.0.tgz",
      "integrity": "sha512-Qu+VC3EwYLldKa1fCxuuvULvSJOKEgk9pi8dZeCVK7TqBfUNTH4sFkk4joj8afVSfAYgJoSOetjx9QWOJ5mYoQ==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^3.2.0",
        "astral-regex": "^1.0.0",
        "is-fullwidth-code-point": "^2.0.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/slice-ansi/node_modules/is-fullwidth-code-point": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz",
      "integrity": "sha1-o7MKXE8ZkYMWeqq5O+764937ZU8=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/snapdragon": {
      "version": "0.8.2",
      "resolved": "https://registry.npmjs.org/snapdragon/-/snapdragon-0.8.2.tgz",
      "integrity": "sha512-FtyOnWN/wCHTVXOMwvSv26d+ko5vWlIDD6zoUJ7LW8vh+ZBC8QdljveRP+crNrtBwioEUWy/4dMtbBjA4ioNlg==",
      "dev": true,
      "dependencies": {
        "base": "^0.11.1",
        "debug": "^2.2.0",
        "define-property": "^0.2.5",
        "extend-shallow": "^2.0.1",
        "map-cache": "^0.2.2",
        "source-map": "^0.5.6",
        "source-map-resolve": "^0.5.0",
        "use": "^3.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon-node": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/snapdragon-node/-/snapdragon-node-2.1.1.tgz",
      "integrity": "sha512-O27l4xaMYt/RSQ5TR3vpWCAB5Kb/czIcqUFOM/C4fYcLnbZUc1PkjTAMjof2pBWaSTwOUd6qUHcFGVGj7aIwnw==",
      "dev": true,
      "dependencies": {
        "define-property": "^1.0.0",
        "isobject": "^3.0.0",
        "snapdragon-util": "^3.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon-node/node_modules/define-property": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
      "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
      "dev": true,
      "dependencies": {
        "is-descriptor": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon-util": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/snapdragon-util/-/snapdragon-util-3.0.1.tgz",
      "integrity": "sha512-mbKkMdQKsjX4BAL4bRYTj21edOf8cN7XHdYUJEe+Zn99hVEYcMvKPct1IqNe7+AZPirn8BCDOQBHQZknqmKlZQ==",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.2.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon-util/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/debug": {
      "version": "2.6.9",
      "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
      "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
      "dev": true,
      "dependencies": {
        "ms": "2.0.0"
      }
    },
    "node_modules/snapdragon/node_modules/define-property": {
      "version": "0.2.5",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
      "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
      "dev": true,
      "dependencies": {
        "is-descriptor": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/extend-shallow": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
      "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
      "dev": true,
      "dependencies": {
        "is-extendable": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/is-accessor-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
      "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/is-accessor-descriptor/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/is-data-descriptor": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
      "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/is-data-descriptor/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/is-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
      "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
      "dev": true,
      "dependencies": {
        "is-accessor-descriptor": "^0.1.6",
        "is-data-descriptor": "^0.1.4",
        "kind-of": "^5.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/is-extendable": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
      "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/kind-of": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
      "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/snapdragon/node_modules/ms": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
      "integrity": "sha1-VgiurfwAvmwpAd9fmGF4jeDVl8g=",
      "dev": true
    },
    "node_modules/snapdragon/node_modules/source-map": {
      "version": "0.5.7",
      "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.5.7.tgz",
      "integrity": "sha1-igOdLRAh0i0eoUyA2OpGi6LvP8w=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/source-map": {
      "version": "0.6.1",
      "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.6.1.tgz",
      "integrity": "sha512-UjgapumWlbMhkBgzT7Ykc5YXUT46F0iKu8SGXq0bcwP5dz/h0Plj6enJqjz1Zbq2l5WaqYnrVbwWOWMyF3F47g==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/source-map-resolve": {
      "version": "0.5.3",
      "resolved": "https://registry.npmjs.org/source-map-resolve/-/source-map-resolve-0.5.3.tgz",
      "integrity": "sha512-Htz+RnsXWk5+P2slx5Jh3Q66vhQj1Cllm0zvnaY98+NFx+Dv2CF/f5O/t8x+KaNdrdIAsruNzoh/KpialbqAnw==",
      "deprecated": "See https://github.com/lydell/source-map-resolve#deprecated",
      "dev": true,
      "dependencies": {
        "atob": "^2.1.2",
        "decode-uri-component": "^0.2.0",
        "resolve-url": "^0.2.1",
        "source-map-url": "^0.4.0",
        "urix": "^0.1.0"
      }
    },
    "node_modules/source-map-support": {
      "version": "0.5.19",
      "resolved": "https://registry.npmjs.org/source-map-support/-/source-map-support-0.5.19.tgz",
      "integrity": "sha512-Wonm7zOCIJzBGQdB+thsPar0kYuCIzYvxZwlBa87yi/Mdjv7Tip2cyVbLj5o0cFPN4EVkuTwb3GDDyUx2DGnGw==",
      "dev": true,
      "dependencies": {
        "buffer-from": "^1.0.0",
        "source-map": "^0.6.0"
      }
    },
    "node_modules/source-map-url": {
      "version": "0.4.1",
      "resolved": "https://registry.npmjs.org/source-map-url/-/source-map-url-0.4.1.tgz",
      "integrity": "sha512-cPiFOTLUKvJFIg4SKVScy4ilPPW6rFgMgfuZJPNoDuMs3nC1HbMUycBoJw77xFIp6z1UJQJOfx6C9GMH80DiTw==",
      "deprecated": "See https://github.com/lydell/source-map-url#deprecated",
      "dev": true
    },
    "node_modules/spdx-correct": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/spdx-correct/-/spdx-correct-3.1.1.tgz",
      "integrity": "sha512-cOYcUWwhCuHCXi49RhFRCyJEK3iPj1Ziz9DpViV3tbZOwXD49QzIN3MpOLJNxh2qwq2lJJZaKMVw9qNi4jTC0w==",
      "dev": true,
      "dependencies": {
        "spdx-expression-parse": "^3.0.0",
        "spdx-license-ids": "^3.0.0"
      }
    },
    "node_modules/spdx-exceptions": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/spdx-exceptions/-/spdx-exceptions-2.3.0.tgz",
      "integrity": "sha512-/tTrYOC7PPI1nUAgx34hUpqXuyJG+DTHJTnIULG4rDygi4xu/tfgmq1e1cIRwRzwZgo4NLySi+ricLkZkw4i5A==",
      "dev": true
    },
    "node_modules/spdx-expression-parse": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/spdx-expression-parse/-/spdx-expression-parse-3.0.1.tgz",
      "integrity": "sha512-cbqHunsQWnJNE6KhVSMsMeH5H/L9EpymbzqTQ3uLwNCLZ1Q481oWaofqH7nO6V07xlXwY6PhQdQ2IedWx/ZK4Q==",
      "dev": true,
      "dependencies": {
        "spdx-exceptions": "^2.1.0",
        "spdx-license-ids": "^3.0.0"
      }
    },
    "node_modules/spdx-license-ids": {
      "version": "3.0.9",
      "resolved": "https://registry.npmjs.org/spdx-license-ids/-/spdx-license-ids-3.0.9.tgz",
      "integrity": "sha512-Ki212dKK4ogX+xDo4CtOZBVIwhsKBEfsEEcwmJfLQzirgc2jIWdzg40Unxz/HzEUqM1WFzVlQSMF9kZZ2HboLQ==",
      "dev": true
    },
    "node_modules/split-string": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/split-string/-/split-string-3.1.0.tgz",
      "integrity": "sha512-NzNVhJDYpwceVVii8/Hu6DKfD2G+NrQHlS/V/qgv763EYudVwEcMQNxd2lh+0VrUByXN/oJkl5grOhYWvQUYiw==",
      "dev": true,
      "dependencies": {
        "extend-shallow": "^3.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sprintf-js": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/sprintf-js/-/sprintf-js-1.0.3.tgz",
      "integrity": "sha1-BOaSb2YolTVPPdAVIDYzuFcpfiw=",
      "dev": true
    },
    "node_modules/sshpk": {
      "version": "1.16.1",
      "resolved": "https://registry.npmjs.org/sshpk/-/sshpk-1.16.1.tgz",
      "integrity": "sha512-HXXqVUq7+pcKeLqqZj6mHFUMvXtOJt1uoUx09pFW6011inTMxqI8BA8PM95myrIyyKwdnzjdFjLiE6KBPVtJIg==",
      "dev": true,
      "dependencies": {
        "asn1": "~0.2.3",
        "assert-plus": "^1.0.0",
        "bcrypt-pbkdf": "^1.0.0",
        "dashdash": "^1.12.0",
        "ecc-jsbn": "~0.1.1",
        "getpass": "^0.1.1",
        "jsbn": "~0.1.0",
        "safer-buffer": "^2.0.2",
        "tweetnacl": "~0.14.0"
      },
      "bin": {
        "sshpk-conv": "bin/sshpk-conv",
        "sshpk-sign": "bin/sshpk-sign",
        "sshpk-verify": "bin/sshpk-verify"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/stack-chain": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/stack-chain/-/stack-chain-2.0.0.tgz",
      "integrity": "sha512-GGrHXePi305aW7XQweYZZwiRwR7Js3MWoK/EHzzB9ROdc75nCnjSJVi21rdAGxFl+yCx2L2qdfl5y7NO4lTyqg==",
      "dev": true
    },
    "node_modules/stack-generator": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/stack-generator/-/stack-generator-2.0.5.tgz",
      "integrity": "sha512-/t1ebrbHkrLrDuNMdeAcsvynWgoH/i4o8EGGfX7dEYDoTXOYVAkEpFdtshlvabzc6JlJ8Kf9YdFEoz7JkzGN9Q==",
      "dev": true,
      "dependencies": {
        "stackframe": "^1.1.1"
      }
    },
    "node_modules/stack-utils": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/stack-utils/-/stack-utils-1.0.5.tgz",
      "integrity": "sha512-KZiTzuV3CnSnSvgMRrARVCj+Ht7rMbauGDK0LdVFRGyenwdylpajAp4Q0i6SX8rEmbTpMMf6ryq2gb8pPq2WgQ==",
      "dev": true,
      "dependencies": {
        "escape-string-regexp": "^2.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/stack-utils/node_modules/escape-string-regexp": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-2.0.0.tgz",
      "integrity": "sha512-UpzcLCXolUWcNu5HtVMHYdXJjArjsF9C0aNnquZYY4uW/Vu0miy5YoWvbV345HauVvcAUnpRuhMMcqTcGOY2+w==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/stackframe": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/stackframe/-/stackframe-1.2.0.tgz",
      "integrity": "sha512-GrdeshiRmS1YLMYgzF16olf2jJ/IzxXY9lhKOskuVziubpTYcYqyOwYeJKzQkwy7uN0fYSsbsC4RQaXf9LCrYA==",
      "dev": true
    },
    "node_modules/stacktrace-gps": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/stacktrace-gps/-/stacktrace-gps-3.0.4.tgz",
      "integrity": "sha512-qIr8x41yZVSldqdqe6jciXEaSCKw1U8XTXpjDuy0ki/apyTn/r3w9hDAAQOhZdxvsC93H+WwwEu5cq5VemzYeg==",
      "dev": true,
      "dependencies": {
        "source-map": "0.5.6",
        "stackframe": "^1.1.1"
      }
    },
    "node_modules/stacktrace-gps/node_modules/source-map": {
      "version": "0.5.6",
      "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz",
      "integrity": "sha1-dc449SvwczxafwwRjYEzSiu19BI=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/stacktrace-js": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/stacktrace-js/-/stacktrace-js-2.0.2.tgz",
      "integrity": "sha512-Je5vBeY4S1r/RnLydLl0TBTi3F2qdfWmYsGvtfZgEI+SCprPppaIhQf5nGcal4gI4cGpCV/duLcAzT1np6sQqg==",
      "dev": true,
      "dependencies": {
        "error-stack-parser": "^2.0.6",
        "stack-generator": "^2.0.5",
        "stacktrace-gps": "^3.0.4"
      }
    },
    "node_modules/static-extend": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/static-extend/-/static-extend-0.1.2.tgz",
      "integrity": "sha1-YICcOcv/VTNyJv1eC1IPNB8ftcY=",
      "dev": true,
      "dependencies": {
        "define-property": "^0.2.5",
        "object-copy": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/static-extend/node_modules/define-property": {
      "version": "0.2.5",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
      "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
      "dev": true,
      "dependencies": {
        "is-descriptor": "^0.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/static-extend/node_modules/is-accessor-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
      "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/static-extend/node_modules/is-accessor-descriptor/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/static-extend/node_modules/is-data-descriptor": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
      "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/static-extend/node_modules/is-data-descriptor/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/static-extend/node_modules/is-descriptor": {
      "version": "0.1.6",
      "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
      "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
      "dev": true,
      "dependencies": {
        "is-accessor-descriptor": "^0.1.6",
        "is-data-descriptor": "^0.1.4",
        "kind-of": "^5.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/static-extend/node_modules/kind-of": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
      "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/stealthy-require": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/stealthy-require/-/stealthy-require-1.1.1.tgz",
      "integrity": "sha1-NbCYdbT/SfJqd35QmzCQoyJr8ks=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/string-argv": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/string-argv/-/string-argv-0.3.1.tgz",
      "integrity": "sha512-a1uQGz7IyVy9YwhqjZIZu1c8JO8dNIe20xBmSS6qu9kv++k3JGzCVmprbNN5Kn+BgzD5E7YYwg1CcjuJMRNsvg==",
      "dev": true,
      "engines": {
        "node": ">=0.6.19"
      }
    },
    "node_modules/string-length": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/string-length/-/string-length-3.1.0.tgz",
      "integrity": "sha512-Ttp5YvkGm5v9Ijagtaz1BnN+k9ObpvS0eIBblPMp2YWL8FBmi9qblQ9fexc2k/CXFgrTIteU3jAw3payCnwSTA==",
      "dev": true,
      "dependencies": {
        "astral-regex": "^1.0.0",
        "strip-ansi": "^5.2.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/string-width": {
      "version": "4.2.2",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-4.2.2.tgz",
      "integrity": "sha512-XBJbT3N4JhVumXE0eoLU9DCjcaF92KLNqTmFCnG1pf8duUxFGwtP6AD6nkjw9a3IdiRtL3E2w3JDiE/xi3vOeA==",
      "dev": true,
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/string-width/node_modules/strip-ansi": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
      "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^5.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/string.prototype.trimend": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/string.prototype.trimend/-/string.prototype.trimend-1.0.4.tgz",
      "integrity": "sha512-y9xCjw1P23Awk8EvTpcyL2NIr1j7wJ39f+k6lvRnSMz+mz9CGz9NYPelDk42kOz6+ql8xjfK8oYzy3jAP5QU5A==",
      "dev": true,
      "dependencies": {
        "call-bind": "^1.0.2",
        "define-properties": "^1.1.3"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/string.prototype.trimstart": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/string.prototype.trimstart/-/string.prototype.trimstart-1.0.4.tgz",
      "integrity": "sha512-jh6e984OBfvxS50tdY2nRZnoC5/mLFKOREQfw8t5yytkoUsJRNxvI/E39qu1sD0OtWI3OC0XgKSmcWwziwYuZw==",
      "dev": true,
      "dependencies": {
        "call-bind": "^1.0.2",
        "define-properties": "^1.1.3"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/strip-ansi": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-5.2.0.tgz",
      "integrity": "sha512-DuRs1gKbBqsMKIZlrffwlug8MHkcnpjs5VPmL1PAh+mA30U0DTotfDZ0d2UUsXpPmPmMMJ6W773MaA3J+lbiWA==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^4.1.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/strip-ansi/node_modules/ansi-regex": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-4.1.1.tgz",
      "integrity": "sha512-ILlv4k/3f6vfQ4OoP2AGvirOktlQ98ZEL1k9FaQjxa3L1abBgbuTDAdPOpvbGncC0BTVQrl+OM8xZGK6tWXt7g==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/strip-bom": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/strip-bom/-/strip-bom-4.0.0.tgz",
      "integrity": "sha512-3xurFv5tEgii33Zi8Jtp55wEIILR9eh34FAW00PZf+JnSsTmV/ioewSgQl97JHvgjoRGwPShsWm+IdrxB35d0w==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-eof": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/strip-eof/-/strip-eof-1.0.0.tgz",
      "integrity": "sha1-u0P/VZim6wXYm1n80SnJgzE2Br8=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/strip-final-newline": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/strip-final-newline/-/strip-final-newline-2.0.0.tgz",
      "integrity": "sha512-BrpvfNAE3dcvq7ll3xVumzjKjZQ5tI1sEUIKr3Uoks0XUl45St3FlatVqef9prk4jRDzhW6WZg+3bk93y6pLjA==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/strip-json-comments": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-3.1.1.tgz",
      "integrity": "sha512-6fPc+R4ihwqP6N/aIv2f1gMH8lOVtWQHoqC4yK6oSDVVocumAsfCqjkXnqiYMhmMwS/mEHLp7Vehlt3ql6lEig==",
      "dev": true,
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/strip-outer": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/strip-outer/-/strip-outer-1.0.1.tgz",
      "integrity": "sha512-k55yxKHwaXnpYGsOzg4Vl8+tDrWylxDEpknGjhTiZB8dFRU5rTo9CAzeycivxV3s+zlTKwrs6WxMxR95n26kwg==",
      "dev": true,
      "dependencies": {
        "escape-string-regexp": "^1.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/subscriptions-transport-ws": {
      "version": "0.9.18",
      "resolved": "https://registry.npmjs.org/subscriptions-transport-ws/-/subscriptions-transport-ws-0.9.18.tgz",
      "integrity": "sha512-tztzcBTNoEbuErsVQpTN2xUNN/efAZXyCyL5m3x4t6SKrEiTL2N8SaKWBFWM4u56pL79ULif3zjyeq+oV+nOaA==",
      "deprecated": "The `subscriptions-transport-ws` package is no longer maintained. We recommend you use `graphql-ws` instead. For help migrating Apollo software to `graphql-ws`, see https://www.apollographql.com/docs/apollo-server/data/subscriptions/#switching-from-subscriptions-transport-ws    For general help using `graphql-ws`, see https://github.com/enisdenjo/graphql-ws/blob/master/README.md",
      "dependencies": {
        "backo2": "^1.0.2",
        "eventemitter3": "^3.1.0",
        "iterall": "^1.2.1",
        "symbol-observable": "^1.0.4",
        "ws": "^5.2.0"
      },
      "peerDependencies": {
        "graphql": ">=0.10.0"
      }
    },
    "node_modules/subscriptions-transport-ws/node_modules/symbol-observable": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/symbol-observable/-/symbol-observable-1.2.0.tgz",
      "integrity": "sha512-e900nM8RRtGhlV36KGEU9k65K3mPb1WV70OdjfxlG2EAuM1noi/E/BaW/uMhL7bPEssK8QV57vN3esixjUvcXQ==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/subscriptions-transport-ws/node_modules/ws": {
      "version": "5.2.3",
      "resolved": "https://registry.npmjs.org/ws/-/ws-5.2.3.tgz",
      "integrity": "sha512-jZArVERrMsKUatIdnLzqvcfydI85dvd/Fp1u/VOpfdDWQ4c9qWXe+VIeAbQ5FrDwciAkr+lzofXLz3Kuf26AOA==",
      "dependencies": {
        "async-limiter": "~1.0.0"
      }
    },
    "node_modules/supports-color": {
      "version": "5.5.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-5.5.0.tgz",
      "integrity": "sha512-QjVjwdXIt408MIiAqCX4oUKsgU2EqAGzs2Ppkm4aQYbjm+ZEWEcW4SfFNTr4uMNZma0ey4f5lgLrkB0aX0QMow==",
      "dev": true,
      "dependencies": {
        "has-flag": "^3.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/supports-hyperlinks": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/supports-hyperlinks/-/supports-hyperlinks-2.2.0.tgz",
      "integrity": "sha512-6sXEzV5+I5j8Bmq9/vUphGRM/RJNT9SCURJLjwfOg51heRtguGWDzcaBlgAzKhQa0EVNpPEKzQuBwZ8S8WaCeQ==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0",
        "supports-color": "^7.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/supports-hyperlinks/node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/supports-hyperlinks/node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/symbol-observable": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/symbol-observable/-/symbol-observable-4.0.0.tgz",
      "integrity": "sha512-b19dMThMV4HVFynSAM1++gBHAbk2Tc/osgLIBZMKsyqh34jb2e8Os7T6ZW/Bt3pJFdBTd2JwAnAAEQV7rSNvcQ==",
      "engines": {
        "node": ">=0.10"
      }
    },
    "node_modules/symbol-tree": {
      "version": "3.2.4",
      "resolved": "https://registry.npmjs.org/symbol-tree/-/symbol-tree-3.2.4.tgz",
      "integrity": "sha512-9QNk5KwDF+Bvz+PyObkmSYjI5ksVUYtjW7AU22r2NKcfLJcXp96hkDWU3+XndOsUb+AQ9QhfzfCT2O+CNWT5Tw==",
      "dev": true
    },
    "node_modules/table": {
      "version": "5.4.6",
      "resolved": "https://registry.npmjs.org/table/-/table-5.4.6.tgz",
      "integrity": "sha512-wmEc8m4fjnob4gt5riFRtTu/6+4rSe12TpAELNSqHMfF3IqnA+CH37USM6/YR3qRZv7e56kAEAtd6nKZaxe0Ug==",
      "dev": true,
      "dependencies": {
        "ajv": "^6.10.2",
        "lodash": "^4.17.14",
        "slice-ansi": "^2.1.0",
        "string-width": "^3.0.0"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/table/node_modules/emoji-regex": {
      "version": "7.0.3",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-7.0.3.tgz",
      "integrity": "sha512-CwBLREIQ7LvYFB0WyRvwhq5N5qPhc6PMjD6bYggFlI5YyDgl+0vxq5VHbMOFqLg7hfWzmu8T5Z1QofhmTIhItA==",
      "dev": true
    },
    "node_modules/table/node_modules/is-fullwidth-code-point": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz",
      "integrity": "sha1-o7MKXE8ZkYMWeqq5O+764937ZU8=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/table/node_modules/string-width": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-3.1.0.tgz",
      "integrity": "sha512-vafcv6KjVZKSgz06oM/H6GDBrAtz8vdhQakGjFIvNrHA6y3HCF1CInLy+QLq8dTJPQ1b+KDUqDFctkdRW44e1w==",
      "dev": true,
      "dependencies": {
        "emoji-regex": "^7.0.1",
        "is-fullwidth-code-point": "^2.0.0",
        "strip-ansi": "^5.1.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/terminal-link": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/terminal-link/-/terminal-link-2.1.1.tgz",
      "integrity": "sha512-un0FmiRUQNr5PJqy9kP7c40F5BOfpGlYTrxonDChEZB7pzZxRNp/bt+ymiy9/npwXya9KH99nJ/GXFIiUkYGFQ==",
      "dev": true,
      "dependencies": {
        "ansi-escapes": "^4.2.1",
        "supports-hyperlinks": "^2.0.0"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/test-exclude": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/test-exclude/-/test-exclude-6.0.0.tgz",
      "integrity": "sha512-cAGWPIyOHU6zlmg88jwm7VRyXnMN7iV68OGAbYDk/Mh/xC/pzVPlQtY6ngoIH/5/tciuhGfvESU8GrHrcxD56w==",
      "dev": true,
      "dependencies": {
        "@istanbuljs/schema": "^0.1.2",
        "glob": "^7.1.4",
        "minimatch": "^3.0.4"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/text-table": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/text-table/-/text-table-0.2.0.tgz",
      "integrity": "sha1-f17oI66AUgfACvLfSoTsP8+lcLQ=",
      "dev": true
    },
    "node_modules/thenify": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/thenify/-/thenify-3.3.1.tgz",
      "integrity": "sha512-RVZSIV5IG10Hk3enotrhvz0T9em6cyHBLkH/YAZuKqd8hRkKhSfCGIcP2KUY0EPxndzANBmNllzWPwak+bheSw==",
      "dev": true,
      "dependencies": {
        "any-promise": "^1.0.0"
      }
    },
    "node_modules/thenify-all": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/thenify-all/-/thenify-all-1.6.0.tgz",
      "integrity": "sha1-GhkY1ALY/D+Y+/I02wvMjMEOlyY=",
      "dev": true,
      "dependencies": {
        "thenify": ">= 3.1.0 < 4"
      },
      "engines": {
        "node": ">=0.8"
      }
    },
    "node_modules/throat": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/throat/-/throat-5.0.0.tgz",
      "integrity": "sha512-fcwX4mndzpLQKBS1DVYhGAcYaYt7vsHNIvQV+WXMvnow5cgjPphq5CaayLaGsjRdSCKZFNGt7/GYAuXaNOiYCA==",
      "dev": true
    },
    "node_modules/through": {
      "version": "2.3.8",
      "resolved": "https://registry.npmjs.org/through/-/through-2.3.8.tgz",
      "integrity": "sha1-DdTJ/6q8NXlgsbckEV1+Doai4fU=",
      "dev": true
    },
    "node_modules/tmp": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/tmp/-/tmp-0.2.1.tgz",
      "integrity": "sha512-76SUhtfqR2Ijn+xllcI5P1oyannHNHByD80W1q447gU3mp9G9PSpGdWmjUOHRDPiHYacIk66W7ubDTuPF3BEtQ==",
      "dev": true,
      "dependencies": {
        "rimraf": "^3.0.0"
      },
      "engines": {
        "node": ">=8.17.0"
      }
    },
    "node_modules/tmpl": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/tmpl/-/tmpl-1.0.5.tgz",
      "integrity": "sha512-3f0uOEAQwIqGuWW2MVzYg8fV/QNnc/IpuJNG837rLuczAaLVHslWHZQj4IGiEl5Hs3kkbhwL9Ab7Hrsmuj+Smw==",
      "dev": true
    },
    "node_modules/to-fast-properties": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/to-fast-properties/-/to-fast-properties-2.0.0.tgz",
      "integrity": "sha1-3F5pjL0HkmW8c+A3doGk5Og/YW4=",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/to-object-path": {
      "version": "0.3.0",
      "resolved": "https://registry.npmjs.org/to-object-path/-/to-object-path-0.3.0.tgz",
      "integrity": "sha1-KXWIt7Dn4KwI4E5nL4XB9JmeF68=",
      "dev": true,
      "dependencies": {
        "kind-of": "^3.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/to-object-path/node_modules/kind-of": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
      "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
      "dev": true,
      "dependencies": {
        "is-buffer": "^1.1.5"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/to-regex": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/to-regex/-/to-regex-3.0.2.tgz",
      "integrity": "sha512-FWtleNAtZ/Ki2qtqej2CXTOayOH9bHDQF+Q48VpWyDXjbYxA4Yz8iDB31zXOBUlOHHKidDbqGVrTUvQMPmBGBw==",
      "dev": true,
      "dependencies": {
        "define-property": "^2.0.2",
        "extend-shallow": "^3.0.2",
        "regex-not": "^1.0.2",
        "safe-regex": "^1.1.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/to-regex-range": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/to-regex-range/-/to-regex-range-5.0.1.tgz",
      "integrity": "sha512-65P7iz6X5yEr1cwcgvQxbbIw7Uk3gOy5dIdtZ4rDveLqhrdJP+Li/Hx6tyK0NEb+2GCyneCMJiGqrADCSNk8sQ==",
      "dev": true,
      "dependencies": {
        "is-number": "^7.0.0"
      },
      "engines": {
        "node": ">=8.0"
      }
    },
    "node_modules/tough-cookie": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/tough-cookie/-/tough-cookie-3.0.1.tgz",
      "integrity": "sha512-yQyJ0u4pZsv9D4clxO69OEjLWYw+jbgspjTue4lTQZLfV0c5l1VmK2y1JK8E9ahdpltPOaAThPcp5nKPUgSnsg==",
      "dev": true,
      "dependencies": {
        "ip-regex": "^2.1.0",
        "psl": "^1.1.28",
        "punycode": "^2.1.1"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/tough-cookie/node_modules/punycode": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
      "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/tr46": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/tr46/-/tr46-1.0.1.tgz",
      "integrity": "sha1-qLE/1r/SSJUZZ0zN5VujaTtwbQk=",
      "dev": true,
      "dependencies": {
        "punycode": "^2.1.0"
      }
    },
    "node_modules/tr46/node_modules/punycode": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
      "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/trim-repeated": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/trim-repeated/-/trim-repeated-1.0.0.tgz",
      "integrity": "sha1-42RqLqTokTEr9+rObPsFOAvAHCE=",
      "dev": true,
      "dependencies": {
        "escape-string-regexp": "^1.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/ts-invariant": {
      "version": "0.9.3",
      "resolved": "https://registry.npmjs.org/ts-invariant/-/ts-invariant-0.9.3.tgz",
      "integrity": "sha512-HinBlTbFslQI0OHP07JLsSXPibSegec6r9ai5xxq/qHYCsIQbzpymLpDhAUsnXcSrDEcd0L62L8vsOEdzM0qlA==",
      "dependencies": {
        "tslib": "^2.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/ts-invariant/node_modules/tslib": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
      "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
    },
    "node_modules/ts-jest": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/ts-jest/-/ts-jest-25.5.1.tgz",
      "integrity": "sha512-kHEUlZMK8fn8vkxDjwbHlxXRB9dHYpyzqKIGDNxbzs+Rz+ssNDSDNusEK8Fk/sDd4xE6iKoQLfFkFVaskmTJyw==",
      "dev": true,
      "dependencies": {
        "bs-logger": "0.x",
        "buffer-from": "1.x",
        "fast-json-stable-stringify": "2.x",
        "json5": "2.x",
        "lodash.memoize": "4.x",
        "make-error": "1.x",
        "micromatch": "4.x",
        "mkdirp": "0.x",
        "semver": "6.x",
        "yargs-parser": "18.x"
      },
      "bin": {
        "ts-jest": "cli.js"
      },
      "engines": {
        "node": ">= 8"
      },
      "peerDependencies": {
        "jest": ">=25 <26",
        "typescript": ">=3.4 <4.0"
      }
    },
    "node_modules/ts-jest/node_modules/semver": {
      "version": "6.3.0",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
      "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/ts-node": {
      "version": "8.10.2",
      "resolved": "https://registry.npmjs.org/ts-node/-/ts-node-8.10.2.tgz",
      "integrity": "sha512-ISJJGgkIpDdBhWVu3jufsWpK3Rzo7bdiIXJjQc0ynKxVOVcg2oIrf2H2cejminGrptVc6q6/uynAHNCuWGbpVA==",
      "dev": true,
      "dependencies": {
        "arg": "^4.1.0",
        "diff": "^4.0.1",
        "make-error": "^1.1.1",
        "source-map-support": "^0.5.17",
        "yn": "3.1.1"
      },
      "bin": {
        "ts-node": "dist/bin.js",
        "ts-node-script": "dist/bin-script.js",
        "ts-node-transpile-only": "dist/bin-transpile.js",
        "ts-script": "dist/bin-script-deprecated.js"
      },
      "engines": {
        "node": ">=6.0.0"
      },
      "peerDependencies": {
        "typescript": ">=2.7"
      }
    },
    "node_modules/ts-node/node_modules/arg": {
      "version": "4.1.3",
      "resolved": "https://registry.npmjs.org/arg/-/arg-4.1.3.tgz",
      "integrity": "sha512-58S9QDqG0Xx27YwPSt9fJxivjYl432YCwfDMfZ+71RAqUrZef7LrKQZ3LHLOwCS4FLNBplP533Zx895SeOCHvA==",
      "dev": true
    },
    "node_modules/tslib": {
      "version": "1.14.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-1.14.1.tgz",
      "integrity": "sha512-Xni35NKzjgMrwevysHTCArtLDpPvye8zV/0E4EyYn43P7/7qvQwPh9BGkHewbMulVntbigmcT7rdX3BNo9wRJg==",
      "dev": true
    },
    "node_modules/tsutils": {
      "version": "3.21.0",
      "resolved": "https://registry.npmjs.org/tsutils/-/tsutils-3.21.0.tgz",
      "integrity": "sha512-mHKK3iUXL+3UF6xL5k0PEhKRUBKPBCv/+RkEOpjRWxxx27KKRBmmA60A9pgOUvMi8GKhRMPEmjBRPzs2W7O1OA==",
      "dev": true,
      "dependencies": {
        "tslib": "^1.8.1"
      },
      "engines": {
        "node": ">= 6"
      },
      "peerDependencies": {
        "typescript": ">=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta"
      }
    },
    "node_modules/tunnel-agent": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.6.0.tgz",
      "integrity": "sha1-J6XeoGs2sEoKmWZ3SykIaPD8QP0=",
      "dev": true,
      "dependencies": {
        "safe-buffer": "^5.0.1"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/tweetnacl": {
      "version": "0.14.5",
      "resolved": "https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.5.tgz",
      "integrity": "sha1-WuaBd/GS1EViadEIr6k/+HQ/T2Q=",
      "dev": true
    },
    "node_modules/type": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/type/-/type-1.2.0.tgz",
      "integrity": "sha512-+5nt5AAniqsCnu2cEQQdpzCAh33kVx8n0VoFidKpB1dVVLAN/F+bgVOqOJqOnEnrhp222clB5p3vUlD+1QAnfg==",
      "dev": true
    },
    "node_modules/type-check": {
      "version": "0.3.2",
      "resolved": "https://registry.npmjs.org/type-check/-/type-check-0.3.2.tgz",
      "integrity": "sha1-WITKtRLPHTVeP7eE8wgEsrUg23I=",
      "dev": true,
      "dependencies": {
        "prelude-ls": "~1.1.2"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/type-detect": {
      "version": "4.0.8",
      "resolved": "https://registry.npmjs.org/type-detect/-/type-detect-4.0.8.tgz",
      "integrity": "sha512-0fr/mIH1dlO+x7TlcMy+bIDqKPsw/70tVyeHW787goQjhmqaZe10uwLujubK9q9Lg6Fiho1KUKDYz0Z7k7g5/g==",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/type-fest": {
      "version": "0.8.1",
      "resolved": "https://registry.npmjs.org/type-fest/-/type-fest-0.8.1.tgz",
      "integrity": "sha512-4dbzIzqvjtgiM5rw1k5rEHtBANKmdudhGyBEajN01fEyhaAIhsoKNy6y7+IN93IfpFtwY9iqi7kD+xwKhQsNJA==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/typedarray-to-buffer": {
      "version": "3.1.5",
      "resolved": "https://registry.npmjs.org/typedarray-to-buffer/-/typedarray-to-buffer-3.1.5.tgz",
      "integrity": "sha512-zdu8XMNEDepKKR+XYOXAVPtWui0ly0NtohUscw+UmaHiAWT8hrV1rr//H6V+0DvJ3OQ19S979M0laLfX8rm82Q==",
      "dev": true,
      "dependencies": {
        "is-typedarray": "^1.0.0"
      }
    },
    "node_modules/typedoc": {
      "version": "0.17.8",
      "resolved": "https://registry.npmjs.org/typedoc/-/typedoc-0.17.8.tgz",
      "integrity": "sha512-/OyrHCJ8jtzu+QZ+771YaxQ9s4g5Z3XsQE3Ma7q+BL392xxBn4UMvvCdVnqKC2T/dz03/VXSLVKOP3lHmDdc/w==",
      "dev": true,
      "dependencies": {
        "fs-extra": "^8.1.0",
        "handlebars": "^4.7.6",
        "highlight.js": "^10.0.0",
        "lodash": "^4.17.15",
        "lunr": "^2.3.8",
        "marked": "1.0.0",
        "minimatch": "^3.0.0",
        "progress": "^2.0.3",
        "shelljs": "^0.8.4",
        "typedoc-default-themes": "^0.10.2"
      },
      "bin": {
        "typedoc": "bin/typedoc"
      },
      "engines": {
        "node": ">= 8.0.0"
      },
      "peerDependencies": {
        "typescript": ">=3.8.3"
      }
    },
    "node_modules/typedoc-default-themes": {
      "version": "0.10.2",
      "resolved": "https://registry.npmjs.org/typedoc-default-themes/-/typedoc-default-themes-0.10.2.tgz",
      "integrity": "sha512-zo09yRj+xwLFE3hyhJeVHWRSPuKEIAsFK5r2u47KL/HBKqpwdUSanoaz5L34IKiSATFrjG5ywmIu98hPVMfxZg==",
      "dev": true,
      "dependencies": {
        "lunr": "^2.3.8"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/typescript": {
      "version": "3.9.3",
      "resolved": "https://registry.npmjs.org/typescript/-/typescript-3.9.3.tgz",
      "integrity": "sha512-D/wqnB2xzNFIcoBG9FG8cXRDjiqSTbG2wd8DMZeQyJlP1vfTkIxH4GKveWaEBYySKIg+USu+E+EDIR47SqnaMQ==",
      "dev": true,
      "bin": {
        "tsc": "bin/tsc",
        "tsserver": "bin/tsserver"
      },
      "engines": {
        "node": ">=4.2.0"
      }
    },
    "node_modules/uglify-js": {
      "version": "3.13.9",
      "resolved": "https://registry.npmjs.org/uglify-js/-/uglify-js-3.13.9.tgz",
      "integrity": "sha512-wZbyTQ1w6Y7fHdt8sJnHfSIuWeDgk6B5rCb4E/AM6QNNPbOMIZph21PW5dRB3h7Df0GszN+t7RuUH6sWK5bF0g==",
      "dev": true,
      "optional": true,
      "bin": {
        "uglifyjs": "bin/uglifyjs"
      },
      "engines": {
        "node": ">=0.8.0"
      }
    },
    "node_modules/unbox-primitive": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/unbox-primitive/-/unbox-primitive-1.0.1.tgz",
      "integrity": "sha512-tZU/3NqK3dA5gpE1KtyiJUrEB0lxnGkMFHptJ7q6ewdZ8s12QrODwNbhIJStmJkd1QDXa1NRA8aF2A1zk/Ypyw==",
      "dev": true,
      "dependencies": {
        "function-bind": "^1.1.1",
        "has-bigints": "^1.0.1",
        "has-symbols": "^1.0.2",
        "which-boxed-primitive": "^1.0.2"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/union-value": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/union-value/-/union-value-1.0.1.tgz",
      "integrity": "sha512-tJfXmxMeWYnczCVs7XAEvIV7ieppALdyepWMkHkwciRpZraG/xwT+s2JN8+pr1+8jCRf80FFzvr+MpQeeoF4Xg==",
      "dev": true,
      "dependencies": {
        "arr-union": "^3.1.0",
        "get-value": "^2.0.6",
        "is-extendable": "^0.1.1",
        "set-value": "^2.0.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/union-value/node_modules/is-extendable": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
      "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/universalify": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/universalify/-/universalify-0.1.2.tgz",
      "integrity": "sha512-rBJeI5CXAlmy1pV+617WB9J63U6XcazHHF2f2dbJix4XzpUF0RS3Zbj0FGIOCAva5P/d/GBOYaACQ1w+0azUkg==",
      "dev": true,
      "engines": {
        "node": ">= 4.0.0"
      }
    },
    "node_modules/unset-value": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/unset-value/-/unset-value-1.0.0.tgz",
      "integrity": "sha1-g3aHP30jNRef+x5vw6jtDfyKtVk=",
      "dev": true,
      "dependencies": {
        "has-value": "^0.3.1",
        "isobject": "^3.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/unset-value/node_modules/has-value": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/has-value/-/has-value-0.3.1.tgz",
      "integrity": "sha1-ex9YutpiyoJ+wKIHgCVlSEWZXh8=",
      "dev": true,
      "dependencies": {
        "get-value": "^2.0.3",
        "has-values": "^0.1.4",
        "isobject": "^2.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/unset-value/node_modules/has-value/node_modules/isobject": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/isobject/-/isobject-2.1.0.tgz",
      "integrity": "sha1-8GVWEJaj8dou9GJy+BXIQNh+DIk=",
      "dev": true,
      "dependencies": {
        "isarray": "1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/unset-value/node_modules/has-values": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/has-values/-/has-values-0.1.4.tgz",
      "integrity": "sha1-bWHeldkd/Km5oCCJrThL/49it3E=",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/update-check": {
      "version": "1.5.4",
      "resolved": "https://registry.npmjs.org/update-check/-/update-check-1.5.4.tgz",
      "integrity": "sha512-5YHsflzHP4t1G+8WGPlvKbJEbAJGCgw+Em+dGR1KmBUbr1J36SJBqlHLjR7oob7sco5hWHGQVcr9B2poIVDDTQ==",
      "dev": true,
      "dependencies": {
        "registry-auth-token": "3.3.2",
        "registry-url": "3.1.0"
      }
    },
    "node_modules/upper-case-first": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/upper-case-first/-/upper-case-first-2.0.2.tgz",
      "integrity": "sha512-514ppYHBaKwfJRK/pNC6c/OxfGa0obSnAl106u97Ed0I625Nin96KAjttZF6ZL3e1XLtphxnqrOi9iWgm+u+bg==",
      "dev": true,
      "dependencies": {
        "tslib": "^2.0.3"
      }
    },
    "node_modules/upper-case-first/node_modules/tslib": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
      "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg==",
      "dev": true
    },
    "node_modules/uri-js": {
      "version": "4.4.1",
      "resolved": "https://registry.npmjs.org/uri-js/-/uri-js-4.4.1.tgz",
      "integrity": "sha512-7rKUyy33Q1yc98pQ1DAmLtwX109F7TIfWlW1Ydo8Wl1ii1SeHieeh0HHfPeL2fMXK6z0s8ecKs9frCuLJvndBg==",
      "dev": true,
      "dependencies": {
        "punycode": "^2.1.0"
      }
    },
    "node_modules/uri-js/node_modules/punycode": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
      "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/urix": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/urix/-/urix-0.1.0.tgz",
      "integrity": "sha1-2pN/emLiH+wf0Y1Js1wpNQZ6bHI=",
      "deprecated": "Please see https://github.com/lydell/urix#deprecated",
      "dev": true
    },
    "node_modules/use": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/use/-/use-3.1.1.tgz",
      "integrity": "sha512-cwESVXlO3url9YWlFW/TA9cshCEhtu7IKJ/p5soJ/gGpj7vbvFrAY/eIioQ6Dw23KjZhYgiIo8HOs1nQ2vr/oQ==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/util-arity": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/util-arity/-/util-arity-1.1.0.tgz",
      "integrity": "sha1-WdAa8f2z/t4KxOYysKtfbOl8kzA=",
      "dev": true
    },
    "node_modules/uuid": {
      "version": "8.3.2",
      "resolved": "https://registry.npmjs.org/uuid/-/uuid-8.3.2.tgz",
      "integrity": "sha512-+NYs2QeMWy+GWFOEm9xnn6HCDp0l7QBD7ml8zLUmJ+93Q5NF0NocErnwkTkXVFNiX3/fpC6afS8Dhb/gz7R7eg==",
      "dev": true,
      "bin": {
        "uuid": "dist/bin/uuid"
      }
    },
    "node_modules/v8-compile-cache": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/v8-compile-cache/-/v8-compile-cache-2.3.0.tgz",
      "integrity": "sha512-l8lCEmLcLYZh4nbunNZvQCJc5pv7+RCwa8q/LdUx8u7lsWvPDKmpodJAJNwkAhJC//dFY48KuIEmjtd4RViDrA==",
      "dev": true
    },
    "node_modules/v8-to-istanbul": {
      "version": "4.1.4",
      "resolved": "https://registry.npmjs.org/v8-to-istanbul/-/v8-to-istanbul-4.1.4.tgz",
      "integrity": "sha512-Rw6vJHj1mbdK8edjR7+zuJrpDtKIgNdAvTSAcpYfgMIw+u2dPDntD3dgN4XQFLU2/fvFQdzj+EeSGfd/jnY5fQ==",
      "dev": true,
      "dependencies": {
        "@types/istanbul-lib-coverage": "^2.0.1",
        "convert-source-map": "^1.6.0",
        "source-map": "^0.7.3"
      },
      "engines": {
        "node": "8.x.x || >=10.10.0"
      }
    },
    "node_modules/v8-to-istanbul/node_modules/source-map": {
      "version": "0.7.3",
      "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.7.3.tgz",
      "integrity": "sha512-CkCj6giN3S+n9qrYiBTX5gystlENnRW5jZeNLHpe6aue+SrHcG5VYwujhW9s4dY31mEGsxBDrHR6oI69fTXsaQ==",
      "dev": true,
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/validate-npm-package-license": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/validate-npm-package-license/-/validate-npm-package-license-3.0.4.tgz",
      "integrity": "sha512-DpKm2Ui/xN7/HQKCtpZxoRWBhZ9Z0kqtygG8XCgNQ8ZlDnxuQmWhj566j8fN4Cu3/JmbhsDo7fcAJq4s9h27Ew==",
      "dev": true,
      "dependencies": {
        "spdx-correct": "^3.0.0",
        "spdx-expression-parse": "^3.0.0"
      }
    },
    "node_modules/validator": {
      "version": "13.7.0",
      "resolved": "https://registry.npmjs.org/validator/-/validator-13.7.0.tgz",
      "integrity": "sha512-nYXQLCBkpJ8X6ltALua9dRrZDHVYxjJ1wgskNt1lH9fzGjs3tgojGSCBjmEPwkWS1y29+DrizMTW19Pr9uB2nw==",
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/vary": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/vary/-/vary-1.1.2.tgz",
      "integrity": "sha512-BNGbWLfd0eUPabhkXUVm0j8uuvREyTh5ovRa/dyow/BqAbZJyC+5fU+IzQOzmAKzYqYRAISoRhdQr3eIZ/PXqg==",
      "dev": true,
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/verror": {
      "version": "1.10.0",
      "resolved": "https://registry.npmjs.org/verror/-/verror-1.10.0.tgz",
      "integrity": "sha1-OhBcoXBTr1XW4nDB+CiGguGNpAA=",
      "dev": true,
      "engines": [
        "node >=0.6.0"
      ],
      "dependencies": {
        "assert-plus": "^1.0.0",
        "core-util-is": "1.0.2",
        "extsprintf": "^1.2.0"
      }
    },
    "node_modules/w3c-hr-time": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/w3c-hr-time/-/w3c-hr-time-1.0.2.tgz",
      "integrity": "sha512-z8P5DvDNjKDoFIHK7q8r8lackT6l+jo/Ye3HOle7l9nICP9lf1Ci25fy9vHd0JOWewkIFzXIEig3TdKT7JQ5fQ==",
      "deprecated": "Use your platform's native performance.now() and performance.timeOrigin.",
      "dev": true,
      "dependencies": {
        "browser-process-hrtime": "^1.0.0"
      }
    },
    "node_modules/w3c-xmlserializer": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/w3c-xmlserializer/-/w3c-xmlserializer-1.1.2.tgz",
      "integrity": "sha512-p10l/ayESzrBMYWRID6xbuCKh2Fp77+sA0doRuGn4tTIMrrZVeqfpKjXHY+oDh3K4nLdPgNwMTVP6Vp4pvqbNg==",
      "dev": true,
      "dependencies": {
        "domexception": "^1.0.1",
        "webidl-conversions": "^4.0.2",
        "xml-name-validator": "^3.0.0"
      }
    },
    "node_modules/walker": {
      "version": "1.0.7",
      "resolved": "https://registry.npmjs.org/walker/-/walker-1.0.7.tgz",
      "integrity": "sha1-L3+bj9ENZ3JisYqITijRlhjgKPs=",
      "dev": true,
      "dependencies": {
        "makeerror": "1.0.x"
      }
    },
    "node_modules/webidl-conversions": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/webidl-conversions/-/webidl-conversions-4.0.2.tgz",
      "integrity": "sha512-YQ+BmxuTgd6UXZW3+ICGfyqRyHXVlD5GtQr5+qjiNW7bF0cqrzX500HVXPBOvgXb5YnzDd+h0zqyv61KUD7+Sg==",
      "dev": true
    },
    "node_modules/whatwg-encoding": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/whatwg-encoding/-/whatwg-encoding-1.0.5.tgz",
      "integrity": "sha512-b5lim54JOPN9HtzvK9HFXvBma/rnfFeqsic0hSpjtDbVxR3dJKLc+KB4V6GgiGOvl7CY/KNh8rxSo9DKQrnUEw==",
      "dev": true,
      "dependencies": {
        "iconv-lite": "0.4.24"
      }
    },
    "node_modules/whatwg-mimetype": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/whatwg-mimetype/-/whatwg-mimetype-2.3.0.tgz",
      "integrity": "sha512-M4yMwr6mAnQz76TbJm914+gPpB/nCwvZbJU28cUD6dR004SAxDLOOSUaB1JDRqLtaOV/vi0IC5lEAGFgrjGv/g==",
      "dev": true
    },
    "node_modules/whatwg-url": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/whatwg-url/-/whatwg-url-7.1.0.tgz",
      "integrity": "sha512-WUu7Rg1DroM7oQvGWfOiAK21n74Gg+T4elXEQYkOhtyLeWiJFoOGLXPKI/9gzIie9CtwVLm8wtw6YJdKyxSjeg==",
      "dev": true,
      "dependencies": {
        "lodash.sortby": "^4.7.0",
        "tr46": "^1.0.1",
        "webidl-conversions": "^4.0.2"
      }
    },
    "node_modules/which": {
      "version": "1.3.1",
      "resolved": "https://registry.npmjs.org/which/-/which-1.3.1.tgz",
      "integrity": "sha512-HxJdYWq1MTIQbJ3nw0cqssHoTNU267KlrDuGZ1WYlxDStUtKUhOaJmh112/TZmHxxUfuJqPXSOm7tDyas0OSIQ==",
      "dev": true,
      "dependencies": {
        "isexe": "^2.0.0"
      },
      "bin": {
        "which": "bin/which"
      }
    },
    "node_modules/which-boxed-primitive": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/which-boxed-primitive/-/which-boxed-primitive-1.0.2.tgz",
      "integrity": "sha512-bwZdv0AKLpplFY2KZRX6TvyuN7ojjr7lwkg6ml0roIy9YeuSr7JS372qlNW18UQYzgYK9ziGcerWqZOmEn9VNg==",
      "dev": true,
      "dependencies": {
        "is-bigint": "^1.0.1",
        "is-boolean-object": "^1.1.0",
        "is-number-object": "^1.0.4",
        "is-string": "^1.0.5",
        "is-symbol": "^1.0.3"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/which-module": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/which-module/-/which-module-2.0.0.tgz",
      "integrity": "sha1-2e8H3Od7mQK4o6j6SzHD4/fm6Ho=",
      "dev": true
    },
    "node_modules/widest-line": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/widest-line/-/widest-line-4.0.1.tgz",
      "integrity": "sha512-o0cyEG0e8GPzT4iGHphIOh0cJOV8fivsXxddQasHPHfoZf1ZexrfeA21w2NaEN1RHE+fXlfISmOE8R9N3u3Qig==",
      "dev": true,
      "dependencies": {
        "string-width": "^5.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/widest-line/node_modules/ansi-regex": {
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-6.0.1.tgz",
      "integrity": "sha512-n5M855fKb2SsfMIiFFoVrABHJC8QtHwVx+mHWP3QcEqBHYienj5dHSgjbxtC0WEZXYt4wcD6zrQElDPhFuZgfA==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-regex?sponsor=1"
      }
    },
    "node_modules/widest-line/node_modules/emoji-regex": {
      "version": "9.2.2",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-9.2.2.tgz",
      "integrity": "sha512-L18DaJsXSUk2+42pv8mLs5jJT2hqFkFE4j21wOmgbUqsZ2hL72NsUU785g9RXgo3s0ZNgVl42TiHp3ZtOv/Vyg==",
      "dev": true
    },
    "node_modules/widest-line/node_modules/string-width": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-5.1.2.tgz",
      "integrity": "sha512-HnLOCR3vjcY8beoNLtcjZ5/nxn2afmME6lhrDrebokqMap+XbeW8n9TXpPDOqdGK5qcI3oT0GKTW6wC7EMiVqA==",
      "dev": true,
      "dependencies": {
        "eastasianwidth": "^0.2.0",
        "emoji-regex": "^9.2.2",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/widest-line/node_modules/strip-ansi": {
      "version": "7.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-7.0.1.tgz",
      "integrity": "sha512-cXNxvT8dFNRVfhVME3JAe98mkXDYN2O1l7jmcwMnOslDeESg1rF/OZMtK0nRAhiari1unG5cD4jG3rapUAkLbw==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^6.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/strip-ansi?sponsor=1"
      }
    },
    "node_modules/word-wrap": {
      "version": "1.2.3",
      "resolved": "https://registry.npmjs.org/word-wrap/-/word-wrap-1.2.3.tgz",
      "integrity": "sha512-Hz/mrNwitNRh/HUAtM/VT/5VH+ygD6DV7mYKZAtHOrbs8U7lvPS6xf7EJKMF0uW1KJCl0H701g3ZGus+muE5vQ==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/wordwrap": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/wordwrap/-/wordwrap-1.0.0.tgz",
      "integrity": "sha1-J1hIEIkUVqQXHI0CJkQa3pDLyus=",
      "dev": true
    },
    "node_modules/wrap-ansi": {
      "version": "6.2.0",
      "resolved": "https://registry.npmjs.org/wrap-ansi/-/wrap-ansi-6.2.0.tgz",
      "integrity": "sha512-r6lPcBGxZXlIcymEu7InxDMhdW0KDxpLgoFLcguasxCaJ/SOIZwINatK9KY/tf+ZrlywOKU0UDj3ATXUBfxJXA==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.0.0",
        "string-width": "^4.1.0",
        "strip-ansi": "^6.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/wrap-ansi/node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/wrap-ansi/node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true
    },
    "node_modules/wrap-ansi/node_modules/strip-ansi": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
      "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^5.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrappy": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz",
      "integrity": "sha1-tSQ9jz7BqjXxNkYFvA0QNuMKtp8=",
      "dev": true
    },
    "node_modules/write": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/write/-/write-1.0.3.tgz",
      "integrity": "sha512-/lg70HAjtkUgWPVZhZcm+T4hkL8Zbtp1nFNOn3lRrxnlv50SRBv7cR7RqR+GMsd3hUXy9hWBo4CHTbFTcOYwig==",
      "dev": true,
      "dependencies": {
        "mkdirp": "^0.5.1"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/write-file-atomic": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/write-file-atomic/-/write-file-atomic-3.0.3.tgz",
      "integrity": "sha512-AvHcyZ5JnSfq3ioSyjrBkH9yW4m7Ayk8/9My/DD9onKeu/94fwrMocemO2QAJFAlnnDN+ZDS+ZjAR5ua1/PV/Q==",
      "dev": true,
      "dependencies": {
        "imurmurhash": "^0.1.4",
        "is-typedarray": "^1.0.0",
        "signal-exit": "^3.0.2",
        "typedarray-to-buffer": "^3.1.5"
      }
    },
    "node_modules/ws": {
      "version": "7.4.6",
      "resolved": "https://registry.npmjs.org/ws/-/ws-7.4.6.tgz",
      "integrity": "sha512-YmhHDO4MzaDLB+M9ym/mDA5z0naX8j7SIlT8f8z+I0VtzsRbekxEutHSme7NPS2qE8StCYQNUnfWdXta/Yu85A==",
      "engines": {
        "node": ">=8.3.0"
      },
      "peerDependencies": {
        "bufferutil": "^4.0.1",
        "utf-8-validate": "^5.0.2"
      },
      "peerDependenciesMeta": {
        "bufferutil": {
          "optional": true
        },
        "utf-8-validate": {
          "optional": true
        }
      }
    },
    "node_modules/xml-name-validator": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/xml-name-validator/-/xml-name-validator-3.0.0.tgz",
      "integrity": "sha512-A5CUptxDsvxKJEU3yO6DuWBSJz/qizqzJKOMIfUJHETbBw/sFaDxgd6fxm1ewUaM0jZ444Fc5vC5ROYurg/4Pw==",
      "dev": true
    },
    "node_modules/xmlchars": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/xmlchars/-/xmlchars-2.2.0.tgz",
      "integrity": "sha512-JZnDKK8B0RCDw84FNdDAIpZK+JuJw+s7Lz8nksI7SIuU3UXJJslUthsi+uWBUYOwPFwW7W7PRLRfUKpxjtjFCw==",
      "dev": true
    },
    "node_modules/y18n": {
      "version": "4.0.3",
      "resolved": "https://registry.npmjs.org/y18n/-/y18n-4.0.3.tgz",
      "integrity": "sha512-JKhqTOwSrqNA1NY5lSztJ1GrBiUodLMmIZuLiDaMRJ+itFd+ABVE8XBjOvIWL+rSqNDC74LCSFmlb/U4UZ4hJQ==",
      "dev": true
    },
    "node_modules/yallist": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/yallist/-/yallist-4.0.0.tgz",
      "integrity": "sha512-3wdGidZyq5PB084XLES5TpOSRA3wjXAlIWMhum2kRcv/41Sn2emQ0dycQW4uZXLejwKvg6EsvbdlVL+FYEct7A==",
      "dev": true
    },
    "node_modules/yargs": {
      "version": "15.4.1",
      "resolved": "https://registry.npmjs.org/yargs/-/yargs-15.4.1.tgz",
      "integrity": "sha512-aePbxDmcYW++PaqBsJ+HYUFwCdv4LVvdnhBy78E57PIor8/OVvhMrADFFEDh8DHDFRv/O9i3lPhsENjO7QX0+A==",
      "dev": true,
      "dependencies": {
        "cliui": "^6.0.0",
        "decamelize": "^1.2.0",
        "find-up": "^4.1.0",
        "get-caller-file": "^2.0.1",
        "require-directory": "^2.1.1",
        "require-main-filename": "^2.0.0",
        "set-blocking": "^2.0.0",
        "string-width": "^4.2.0",
        "which-module": "^2.0.0",
        "y18n": "^4.0.0",
        "yargs-parser": "^18.1.2"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/yargs-parser": {
      "version": "18.1.3",
      "resolved": "https://registry.npmjs.org/yargs-parser/-/yargs-parser-18.1.3.tgz",
      "integrity": "sha512-o50j0JeToy/4K6OZcaQmW6lyXXKhq7csREXcDwk2omFPJEwUNOVtJKvmDr9EI1fAJZUyZcRF7kxGBWmRXudrCQ==",
      "dev": true,
      "dependencies": {
        "camelcase": "^5.0.0",
        "decamelize": "^1.2.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/yn": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/yn/-/yn-3.1.1.tgz",
      "integrity": "sha512-Ux4ygGWsu2c7isFWe8Yu1YluJmqVhxqK2cLXNQA5AcC3QfbGNpM7fu0Y8b/z16pXLnFxZYvWhd3fhBY9DLmC6Q==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/zen-observable": {
      "version": "0.8.15",
      "resolved": "https://registry.npmjs.org/zen-observable/-/zen-observable-0.8.15.tgz",
      "integrity": "sha512-PQ2PC7R9rslx84ndNBZB/Dkv8V8fZEpk83RLgXtYd0fwUgEjseMn1Dgajh2x6S8QbZAFa9p2qVCEuYZNgve0dQ=="
    },
    "node_modules/zen-observable-ts": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/zen-observable-ts/-/zen-observable-ts-1.1.0.tgz",
      "integrity": "sha512-1h4zlLSqI2cRLPJUHJFL8bCWHhkpuXkF+dbGkRaWjgDIG26DmzyshUMrdV/rL3UnR+mhaX4fRq8LPouq0MYYIA==",
      "dependencies": {
        "@types/zen-observable": "0.8.3",
        "zen-observable": "0.8.15"
      }
    }
  },
  "dependencies": {
    "@apollo/client": {
      "version": "3.4.0",
      "resolved": "https://registry.npmjs.org/@apollo/client/-/client-3.4.0.tgz",
      "integrity": "sha512-ASGw+L1KYLm3Syl5lJKFB6nLEuthBUcvSYhI6p4g4hi+kMli6+UarMONuIYmTBUec2KcQCfs4uwi3bd0xWQ8zg==",
      "requires": {
        "@graphql-typed-document-node/core": "^3.0.0",
        "@wry/context": "^0.6.0",
        "@wry/equality": "^0.5.0",
        "@wry/trie": "^0.3.0",
        "graphql-tag": "^2.12.3",
        "hoist-non-react-statics": "^3.3.2",
        "optimism": "^0.16.1",
        "prop-types": "^15.7.2",
        "symbol-observable": "^4.0.0",
        "ts-invariant": "^0.9.0",
        "tslib": "^2.3.0",
        "zen-observable-ts": "^1.1.0"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.1",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
          "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
        }
      }
    },
    "@babel/code-frame": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.14.5.tgz",
      "integrity": "sha512-9pzDqyc6OLDaqe+zbACgFkb6fKMNG6CObKpnYXChRsvYGyEdc7CA2BaqeOM+vOtCS5ndmJicPJhKAwYRI6UfFw==",
      "dev": true,
      "requires": {
        "@babel/highlight": "^7.14.5"
      }
    },
    "@babel/compat-data": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/compat-data/-/compat-data-7.14.5.tgz",
      "integrity": "sha512-kixrYn4JwfAVPa0f2yfzc2AWti6WRRyO3XjWW5PJAvtE11qhSayrrcrEnee05KAtNaPC+EwehE8Qt1UedEVB8w==",
      "dev": true
    },
    "@babel/core": {
      "version": "7.14.6",
      "resolved": "https://registry.npmjs.org/@babel/core/-/core-7.14.6.tgz",
      "integrity": "sha512-gJnOEWSqTk96qG5BoIrl5bVtc23DCycmIePPYnamY9RboYdI4nFy5vAQMSl81O5K/W0sLDWfGysnOECC+KUUCA==",
      "dev": true,
      "requires": {
        "@babel/code-frame": "^7.14.5",
        "@babel/generator": "^7.14.5",
        "@babel/helper-compilation-targets": "^7.14.5",
        "@babel/helper-module-transforms": "^7.14.5",
        "@babel/helpers": "^7.14.6",
        "@babel/parser": "^7.14.6",
        "@babel/template": "^7.14.5",
        "@babel/traverse": "^7.14.5",
        "@babel/types": "^7.14.5",
        "convert-source-map": "^1.7.0",
        "debug": "^4.1.0",
        "gensync": "^1.0.0-beta.2",
        "json5": "^2.1.2",
        "semver": "^6.3.0",
        "source-map": "^0.5.0"
      },
      "dependencies": {
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
          "dev": true
        },
        "source-map": {
          "version": "0.5.7",
          "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.5.7.tgz",
          "integrity": "sha1-igOdLRAh0i0eoUyA2OpGi6LvP8w=",
          "dev": true
        }
      }
    },
    "@babel/generator": {
      "version": "7.14.8",
      "resolved": "https://registry.npmjs.org/@babel/generator/-/generator-7.14.8.tgz",
      "integrity": "sha512-cYDUpvIzhBVnMzRoY1fkSEhK/HmwEVwlyULYgn/tMQYd6Obag3ylCjONle3gdErfXBW61SVTlR9QR7uWlgeIkg==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.14.8",
        "jsesc": "^2.5.1",
        "source-map": "^0.5.0"
      },
      "dependencies": {
        "source-map": {
          "version": "0.5.7",
          "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.5.7.tgz",
          "integrity": "sha1-igOdLRAh0i0eoUyA2OpGi6LvP8w=",
          "dev": true
        }
      }
    },
    "@babel/helper-compilation-targets": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-compilation-targets/-/helper-compilation-targets-7.14.5.tgz",
      "integrity": "sha512-v+QtZqXEiOnpO6EYvlImB6zCD2Lel06RzOPzmkz/D/XgQiUu3C/Jb1LOqSt/AIA34TYi/Q+KlT8vTQrgdxkbLw==",
      "dev": true,
      "requires": {
        "@babel/compat-data": "^7.14.5",
        "@babel/helper-validator-option": "^7.14.5",
        "browserslist": "^4.16.6",
        "semver": "^6.3.0"
      },
      "dependencies": {
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
          "dev": true
        }
      }
    },
    "@babel/helper-function-name": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-function-name/-/helper-function-name-7.14.5.tgz",
      "integrity": "sha512-Gjna0AsXWfFvrAuX+VKcN/aNNWonizBj39yGwUzVDVTlMYJMK2Wp6xdpy72mfArFq5uK+NOuexfzZlzI1z9+AQ==",
      "dev": true,
      "requires": {
        "@babel/helper-get-function-arity": "^7.14.5",
        "@babel/template": "^7.14.5",
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-get-function-arity": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-get-function-arity/-/helper-get-function-arity-7.14.5.tgz",
      "integrity": "sha512-I1Db4Shst5lewOM4V+ZKJzQ0JGGaZ6VY1jYvMghRjqs6DWgxLCIyFt30GlnKkfUeFLpJt2vzbMVEXVSXlIFYUg==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-hoist-variables": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-hoist-variables/-/helper-hoist-variables-7.14.5.tgz",
      "integrity": "sha512-R1PXiz31Uc0Vxy4OEOm07x0oSjKAdPPCh3tPivn/Eo8cvz6gveAeuyUUPB21Hoiif0uoPQSSdhIPS3352nvdyQ==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-member-expression-to-functions": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-member-expression-to-functions/-/helper-member-expression-to-functions-7.14.5.tgz",
      "integrity": "sha512-UxUeEYPrqH1Q/k0yRku1JE7dyfyehNwT6SVkMHvYvPDv4+uu627VXBckVj891BO8ruKBkiDoGnZf4qPDD8abDQ==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-module-imports": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-imports/-/helper-module-imports-7.14.5.tgz",
      "integrity": "sha512-SwrNHu5QWS84XlHwGYPDtCxcA0hrSlL2yhWYLgeOc0w7ccOl2qv4s/nARI0aYZW+bSwAL5CukeXA47B/1NKcnQ==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-module-transforms": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-transforms/-/helper-module-transforms-7.14.5.tgz",
      "integrity": "sha512-iXpX4KW8LVODuAieD7MzhNjmM6dzYY5tfRqT+R9HDXWl0jPn/djKmA+G9s/2C2T9zggw5tK1QNqZ70USfedOwA==",
      "dev": true,
      "requires": {
        "@babel/helper-module-imports": "^7.14.5",
        "@babel/helper-replace-supers": "^7.14.5",
        "@babel/helper-simple-access": "^7.14.5",
        "@babel/helper-split-export-declaration": "^7.14.5",
        "@babel/helper-validator-identifier": "^7.14.5",
        "@babel/template": "^7.14.5",
        "@babel/traverse": "^7.14.5",
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-optimise-call-expression": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-optimise-call-expression/-/helper-optimise-call-expression-7.14.5.tgz",
      "integrity": "sha512-IqiLIrODUOdnPU9/F8ib1Fx2ohlgDhxnIDU7OEVi+kAbEZcyiF7BLU8W6PfvPi9LzztjS7kcbzbmL7oG8kD6VA==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-plugin-utils": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-plugin-utils/-/helper-plugin-utils-7.14.5.tgz",
      "integrity": "sha512-/37qQCE3K0vvZKwoK4XU/irIJQdIfCJuhU5eKnNxpFDsOkgFaUAwbv+RYw6eYgsC0E4hS7r5KqGULUogqui0fQ==",
      "dev": true
    },
    "@babel/helper-replace-supers": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-replace-supers/-/helper-replace-supers-7.14.5.tgz",
      "integrity": "sha512-3i1Qe9/8x/hCHINujn+iuHy+mMRLoc77b2nI9TB0zjH1hvn9qGlXjWlggdwUcju36PkPCy/lpM7LLUdcTyH4Ow==",
      "dev": true,
      "requires": {
        "@babel/helper-member-expression-to-functions": "^7.14.5",
        "@babel/helper-optimise-call-expression": "^7.14.5",
        "@babel/traverse": "^7.14.5",
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-simple-access": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-simple-access/-/helper-simple-access-7.14.5.tgz",
      "integrity": "sha512-nfBN9xvmCt6nrMZjfhkl7i0oTV3yxR4/FztsbOASyTvVcoYd0TRHh7eMLdlEcCqobydC0LAF3LtC92Iwxo0wyw==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-split-export-declaration": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-split-export-declaration/-/helper-split-export-declaration-7.14.5.tgz",
      "integrity": "sha512-hprxVPu6e5Kdp2puZUmvOGjaLv9TCe58E/Fl6hRq4YiVQxIcNvuq6uTM2r1mT/oPskuS9CgR+I94sqAYv0NGKA==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/helper-validator-identifier": {
      "version": "7.15.7",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-identifier/-/helper-validator-identifier-7.15.7.tgz",
      "integrity": "sha512-K4JvCtQqad9OY2+yTU8w+E82ywk/fe+ELNlt1G8z3bVGlZfn/hOcQQsUhGhW/N+tb3fxK800wLtKOE/aM0m72w==",
      "dev": true
    },
    "@babel/helper-validator-option": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-option/-/helper-validator-option-7.14.5.tgz",
      "integrity": "sha512-OX8D5eeX4XwcroVW45NMvoYaIuFI+GQpA2a8Gi+X/U/cDUIRsV37qQfF905F0htTRCREQIB4KqPeaveRJUl3Ow==",
      "dev": true
    },
    "@babel/helpers": {
      "version": "7.14.6",
      "resolved": "https://registry.npmjs.org/@babel/helpers/-/helpers-7.14.6.tgz",
      "integrity": "sha512-yesp1ENQBiLI+iYHSJdoZKUtRpfTlL1grDIX9NRlAVppljLw/4tTyYupIB7uIYmC3stW/imAv8EqaKaS/ibmeA==",
      "dev": true,
      "requires": {
        "@babel/template": "^7.14.5",
        "@babel/traverse": "^7.14.5",
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/highlight": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/highlight/-/highlight-7.14.5.tgz",
      "integrity": "sha512-qf9u2WFWVV0MppaL877j2dBtQIDgmidgjGk5VIMw3OadXvYaXn66U1BFlH2t4+t3i+8PhedppRv+i40ABzd+gg==",
      "dev": true,
      "requires": {
        "@babel/helper-validator-identifier": "^7.14.5",
        "chalk": "^2.0.0",
        "js-tokens": "^4.0.0"
      }
    },
    "@babel/parser": {
      "version": "7.14.6",
      "resolved": "https://registry.npmjs.org/@babel/parser/-/parser-7.14.6.tgz",
      "integrity": "sha512-oG0ej7efjEXxb4UgE+klVx+3j4MVo+A2vCzm7OUN4CLo6WhQ+vSOD2yJ8m7B+DghObxtLxt3EfgMWpq+AsWehQ==",
      "dev": true
    },
    "@babel/plugin-syntax-async-generators": {
      "version": "7.8.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-async-generators/-/plugin-syntax-async-generators-7.8.4.tgz",
      "integrity": "sha512-tycmZxkGfZaxhMRbXlPXuVFpdWlXpir2W4AMhSJgRKzk/eDlIXOhb2LHWoLpDF7TEHylV5zNhykX6KAgHJmTNw==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-bigint": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-bigint/-/plugin-syntax-bigint-7.8.3.tgz",
      "integrity": "sha512-wnTnFlG+YxQm3vDxpGE57Pj0srRU4sHE/mDkt1qv2YJJSeUAec2ma4WLUnUPeKjyrfntVwe/N6dCXpU+zL3Npg==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-class-properties": {
      "version": "7.12.13",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-class-properties/-/plugin-syntax-class-properties-7.12.13.tgz",
      "integrity": "sha512-fm4idjKla0YahUNgFNLCB0qySdsoPiZP3iQE3rky0mBUtMZ23yDJ9SJdg6dXTSDnulOVqiF3Hgr9nbXvXTQZYA==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.12.13"
      }
    },
    "@babel/plugin-syntax-import-meta": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-import-meta/-/plugin-syntax-import-meta-7.10.4.tgz",
      "integrity": "sha512-Yqfm+XDx0+Prh3VSeEQCPU81yC+JWZ2pDPFSS4ZdpfZhp4MkFMaDC1UqseovEKwSUpnIL7+vK+Clp7bfh0iD7g==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-syntax-json-strings": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-json-strings/-/plugin-syntax-json-strings-7.8.3.tgz",
      "integrity": "sha512-lY6kdGpWHvjoe2vk4WrAapEuBR69EMxZl+RoGRhrFGNYVK8mOPAW8VfbT/ZgrFbXlDNiiaxQnAtgVCZ6jv30EA==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-logical-assignment-operators": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-logical-assignment-operators/-/plugin-syntax-logical-assignment-operators-7.10.4.tgz",
      "integrity": "sha512-d8waShlpFDinQ5MtvGU9xDAOzKH47+FFoney2baFIoMr952hKOLp1HR7VszoZvOsV/4+RRszNY7D17ba0te0ig==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-syntax-nullish-coalescing-operator": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-nullish-coalescing-operator/-/plugin-syntax-nullish-coalescing-operator-7.8.3.tgz",
      "integrity": "sha512-aSff4zPII1u2QD7y+F8oDsz19ew4IGEJg9SVW+bqwpwtfFleiQDMdzA/R+UlWDzfnHFCxxleFT0PMIrR36XLNQ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-numeric-separator": {
      "version": "7.10.4",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-numeric-separator/-/plugin-syntax-numeric-separator-7.10.4.tgz",
      "integrity": "sha512-9H6YdfkcK/uOnY/K7/aA2xpzaAgkQn37yzWUMRK7OaPOqOpGS1+n0H5hxT9AUw9EsSjPW8SVyMJwYRtWs3X3ug==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.10.4"
      }
    },
    "@babel/plugin-syntax-object-rest-spread": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-object-rest-spread/-/plugin-syntax-object-rest-spread-7.8.3.tgz",
      "integrity": "sha512-XoqMijGZb9y3y2XskN+P1wUGiVwWZ5JmoDRwx5+3GmEplNyVM2s2Dg8ILFQm8rWM48orGy5YpI5Bl8U1y7ydlA==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-optional-catch-binding": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-optional-catch-binding/-/plugin-syntax-optional-catch-binding-7.8.3.tgz",
      "integrity": "sha512-6VPD0Pc1lpTqw0aKoeRTMiB+kWhAoT24PA+ksWSBrFtl5SIRVpZlwN3NNPQjehA2E/91FV3RjLWoVTglWcSV3Q==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/plugin-syntax-optional-chaining": {
      "version": "7.8.3",
      "resolved": "https://registry.npmjs.org/@babel/plugin-syntax-optional-chaining/-/plugin-syntax-optional-chaining-7.8.3.tgz",
      "integrity": "sha512-KoK9ErH1MBlCPxV0VANkXW2/dw4vlbGDrFgz8bmUsBGYkFRcbRwMh6cIJubdPrkxRwuGdtCk0v/wPTKbQgBjkg==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.8.0"
      }
    },
    "@babel/template": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/template/-/template-7.14.5.tgz",
      "integrity": "sha512-6Z3Po85sfxRGachLULUhOmvAaOo7xCvqGQtxINai2mEGPFm6pQ4z5QInFnUrRpfoSV60BnjyF5F3c+15fxFV1g==",
      "dev": true,
      "requires": {
        "@babel/code-frame": "^7.14.5",
        "@babel/parser": "^7.14.5",
        "@babel/types": "^7.14.5"
      }
    },
    "@babel/traverse": {
      "version": "7.14.5",
      "resolved": "https://registry.npmjs.org/@babel/traverse/-/traverse-7.14.5.tgz",
      "integrity": "sha512-G3BiS15vevepdmFqmUc9X+64y0viZYygubAMO8SvBmKARuF6CPSZtH4Ng9vi/lrWlZFGe3FWdXNy835akH8Glg==",
      "dev": true,
      "requires": {
        "@babel/code-frame": "^7.14.5",
        "@babel/generator": "^7.14.5",
        "@babel/helper-function-name": "^7.14.5",
        "@babel/helper-hoist-variables": "^7.14.5",
        "@babel/helper-split-export-declaration": "^7.14.5",
        "@babel/parser": "^7.14.5",
        "@babel/types": "^7.14.5",
        "debug": "^4.1.0",
        "globals": "^11.1.0"
      },
      "dependencies": {
        "globals": {
          "version": "11.12.0",
          "resolved": "https://registry.npmjs.org/globals/-/globals-11.12.0.tgz",
          "integrity": "sha512-WOBp/EEGUiIsJSp7wcv/y6MO+lV9UoncWqxuFfm8eBwzWNgyfBd6Gz+IeKQ9jCmyhoH99g15M3T+QaVHFjizVA==",
          "dev": true
        }
      }
    },
    "@babel/types": {
      "version": "7.14.8",
      "resolved": "https://registry.npmjs.org/@babel/types/-/types-7.14.8.tgz",
      "integrity": "sha512-iob4soQa7dZw8nodR/KlOQkPh9S4I8RwCxwRIFuiMRYjOzH/KJzdUfDgz6cGi5dDaclXF4P2PAhCdrBJNIg68Q==",
      "dev": true,
      "requires": {
        "@babel/helper-validator-identifier": "^7.14.8",
        "to-fast-properties": "^2.0.0"
      }
    },
    "@bcoe/v8-coverage": {
      "version": "0.2.3",
      "resolved": "https://registry.npmjs.org/@bcoe/v8-coverage/-/v8-coverage-0.2.3.tgz",
      "integrity": "sha512-0hYQ8SB4Db5zvZB4axdMHGwEaQjkZzFjQiN9LVYvIFB2nSUHW9tYpxWriPrWDASIxiaXax83REcLxuSdnGPZtw==",
      "dev": true
    },
    "@cnakazawa/watch": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/@cnakazawa/watch/-/watch-1.0.4.tgz",
      "integrity": "sha512-v9kIhKwjeZThiWrLmj0y17CWoyddASLj9O2yvbZkbvw/N3rWOYy9zkV66ursAoVr0mV15bL8g0c4QZUE6cdDoQ==",
      "dev": true,
      "requires": {
        "exec-sh": "^0.3.2",
        "minimist": "^1.2.0"
      }
    },
    "@cucumber/create-meta": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/@cucumber/create-meta/-/create-meta-2.0.4.tgz",
      "integrity": "sha512-upbfuih3NVm1efWSbPGH7HI6O2O037QRAPLMgTDIGaf2lfcrMCgB/qkqPHk8DOUuz7Vjpg5tFFoJODSDcxtNOA==",
      "dev": true,
      "requires": {
        "@cucumber/messages": "^13.1.0",
        "ts-node": "^9.0.0",
        "typescript": "^4.0.5"
      },
      "dependencies": {
        "arg": {
          "version": "4.1.3",
          "resolved": "https://registry.npmjs.org/arg/-/arg-4.1.3.tgz",
          "integrity": "sha512-58S9QDqG0Xx27YwPSt9fJxivjYl432YCwfDMfZ+71RAqUrZef7LrKQZ3LHLOwCS4FLNBplP533Zx895SeOCHvA==",
          "dev": true
        },
        "ts-node": {
          "version": "9.1.1",
          "resolved": "https://registry.npmjs.org/ts-node/-/ts-node-9.1.1.tgz",
          "integrity": "sha512-hPlt7ZACERQGf03M253ytLY3dHbGNGrAq9qIHWUY9XHYl1z7wYngSr3OQ5xmui8o2AaxsONxIzjafLUiWBo1Fg==",
          "dev": true,
          "requires": {
            "arg": "^4.1.0",
            "create-require": "^1.1.0",
            "diff": "^4.0.1",
            "make-error": "^1.1.1",
            "source-map-support": "^0.5.17",
            "yn": "3.1.1"
          }
        },
        "typescript": {
          "version": "4.3.3",
          "resolved": "https://registry.npmjs.org/typescript/-/typescript-4.3.3.tgz",
          "integrity": "sha512-rUvLW0WtF7PF2b9yenwWUi9Da9euvDRhmH7BLyBG4DCFfOJ850LGNknmRpp8Z8kXNUPObdZQEfKOiHtXuQHHKA==",
          "dev": true
        }
      }
    },
    "@cucumber/cucumber": {
      "version": "7.0.0-rc.0",
      "resolved": "https://registry.npmjs.org/@cucumber/cucumber/-/cucumber-7.0.0-rc.0.tgz",
      "integrity": "sha512-OUuFR78NB0hSuwA3tuVeshfHCVbd5yn6i8/NkftVP3QxyKD3wM01ngV4Fo/WckLffTIj0RCHEPaIV80icv2jgQ==",
      "dev": true,
      "requires": {
        "@cucumber/create-meta": "^2.0.2",
        "@cucumber/cucumber-expressions": "^10.3.0",
        "@cucumber/gherkin": "^15.0.2",
        "@cucumber/messages": "^13.0.1",
        "@cucumber/query": "^7.0.0",
        "@cucumber/tag-expressions": "^2.0.4",
        "assertion-error-formatter": "^3.0.0",
        "bluebird": "^3.7.2",
        "capital-case": "^1.0.3",
        "cli-table3": "^0.6.0",
        "colors": "^1.4.0",
        "commander": "^5.0.0",
        "duration": "^0.2.2",
        "durations": "^3.4.2",
        "figures": "^3.2.0",
        "glob": "^7.1.6",
        "indent-string": "^4.0.0",
        "is-generator": "^1.0.3",
        "is-stream": "^2.0.0",
        "knuth-shuffle-seeded": "^1.0.6",
        "lodash": "^4.17.20",
        "mz": "^2.7.0",
        "progress": "^2.0.3",
        "read-pkg-up": "^7.0.1",
        "resolve": "^1.17.0",
        "stack-chain": "^2.0.0",
        "stacktrace-js": "^2.0.2",
        "string-argv": "^0.3.1",
        "tmp": "^0.2.1",
        "util-arity": "^1.1.0",
        "verror": "^1.10.0"
      }
    },
    "@cucumber/cucumber-expressions": {
      "version": "10.3.0",
      "resolved": "https://registry.npmjs.org/@cucumber/cucumber-expressions/-/cucumber-expressions-10.3.0.tgz",
      "integrity": "sha512-ZoDb6UPXPmYnRpAye2AoSO7T2j345MDH+D64ikLlXU4WT+83fvma7ULrx3B9IfNlIQOKuE2dodi4uPu95uPjbA==",
      "dev": true,
      "requires": {
        "becke-ch--regex--s0-0-v1--base--pl--lib": "^1.4.0"
      }
    },
    "@cucumber/gherkin": {
      "version": "15.0.2",
      "resolved": "https://registry.npmjs.org/@cucumber/gherkin/-/gherkin-15.0.2.tgz",
      "integrity": "sha512-E8GIulakxjXPlGatW6DxYQ1jJSHvT9mDLginqe7AkjyIjBuddQvXFShI/4fdYa6XaF3gO4ybhQvHtcza/1ob/Q==",
      "dev": true,
      "requires": {
        "@cucumber/messages": "^13.0.1",
        "@teppeis/multimaps": "^1.1.0",
        "commander": "^6.0.0",
        "source-map-support": "^0.5.19"
      },
      "dependencies": {
        "commander": {
          "version": "6.2.1",
          "resolved": "https://registry.npmjs.org/commander/-/commander-6.2.1.tgz",
          "integrity": "sha512-U7VdrJFnJgo4xjrHpTzu0yrHPGImdsmD95ZlgYSEajAn2JKzDhDTPG9kBTefmObL2w/ngeZnilk+OV9CG3d7UA==",
          "dev": true
        }
      }
    },
    "@cucumber/messages": {
      "version": "13.2.1",
      "resolved": "https://registry.npmjs.org/@cucumber/messages/-/messages-13.2.1.tgz",
      "integrity": "sha512-2cu6P1JsEcH0/RlMx302KOK9rkKDHYS1H+6/VhQ6L+yrVW458wOU3CiVgurLn3heCDdJH8r4L87pkSwt0rxiGQ==",
      "dev": true,
      "requires": {
        "@types/uuid": "^8.3.0",
        "protobufjs": "^6.10.2",
        "uuid": "^8.3.1"
      }
    },
    "@cucumber/query": {
      "version": "7.0.1",
      "resolved": "https://registry.npmjs.org/@cucumber/query/-/query-7.0.1.tgz",
      "integrity": "sha512-Ocxtm0LLLbYa3TwZZFzHG4/uHnb7GkYNUsRzf+bLyKOYymkffMkgLcITkx+X4Kw/tq+xzzHh3z/YivEAXxBJdQ==",
      "dev": true,
      "requires": {
        "@cucumber/messages": "^13.2.1",
        "@teppeis/multimaps": "^1.1.0"
      }
    },
    "@cucumber/tag-expressions": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/@cucumber/tag-expressions/-/tag-expressions-2.0.4.tgz",
      "integrity": "sha512-HiNncmg/gS34yNpMFAeoIyUHqLFFN92MXIj3rs+BKo7vn16SxvYsigDvd2PAHyjSIThsp9TO1XDtl0SLKVB58g==",
      "dev": true
    },
    "@etherspot/contracts": {
      "version": "1.9.9",
      "resolved": "https://registry.npmjs.org/@etherspot/contracts/-/contracts-1.9.9.tgz",
      "integrity": "sha512-n53Z39VNmRxPR7XWZ8gkj+gmeMrJka6RfJLRWCDUbVGyKd1sLixd+8e2qqobrpcBYn4uazqAvzWokfqLp5wxRw=="
    },
    "@ethersproject/abi": {
      "version": "5.6.3",
      "resolved": "https://registry.npmjs.org/@ethersproject/abi/-/abi-5.6.3.tgz",
      "integrity": "sha512-CxKTdoZY4zDJLWXG6HzNH6znWK0M79WzzxHegDoecE3+K32pzfHOzuXg2/oGSTecZynFgpkjYXNPOqXVJlqClw==",
      "dev": true,
      "requires": {
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/hash": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "@ethersproject/abstract-provider": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/abstract-provider/-/abstract-provider-5.6.1.tgz",
      "integrity": "sha512-BxlIgogYJtp1FS8Muvj8YfdClk3unZH0vRMVX791Z9INBNT/kuACZ9GzaY1Y4yFq+YSy6/w4gzj3HCRKrK9hsQ==",
      "dev": true,
      "requires": {
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/networks": "^5.6.3",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/transactions": "^5.6.2",
        "@ethersproject/web": "^5.6.1"
      }
    },
    "@ethersproject/abstract-signer": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/abstract-signer/-/abstract-signer-5.6.2.tgz",
      "integrity": "sha512-n1r6lttFBG0t2vNiI3HoWaS/KdOt8xyDjzlP2cuevlWLG6EX0OwcKLyG/Kp/cuwNxdy/ous+R/DEMdTUwWQIjQ==",
      "dev": true,
      "requires": {
        "@ethersproject/abstract-provider": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0"
      }
    },
    "@ethersproject/address": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/address/-/address-5.6.1.tgz",
      "integrity": "sha512-uOgF0kS5MJv9ZvCz7x6T2EXJSzotiybApn4XlOgoTX0xdtyVIJ7pF+6cGPxiEq/dpBiTfMiw7Yc81JcwhSYA0Q==",
      "dev": true,
      "requires": {
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/rlp": "^5.6.1"
      }
    },
    "@ethersproject/base64": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/base64/-/base64-5.6.1.tgz",
      "integrity": "sha512-qB76rjop6a0RIYYMiB4Eh/8n+Hxu2NIZm8S/Q7kNo5pmZfXhHGHmS4MinUainiBC54SCyRnwzL+KZjj8zbsSsw==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1"
      }
    },
    "@ethersproject/basex": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/basex/-/basex-5.6.1.tgz",
      "integrity": "sha512-a52MkVz4vuBXR06nvflPMotld1FJWSj2QT0985v7P/emPZO00PucFAkbcmq2vpVU7Ts7umKiSI6SppiLykVWsA==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/properties": "^5.6.0"
      }
    },
    "@ethersproject/bignumber": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/bignumber/-/bignumber-5.6.2.tgz",
      "integrity": "sha512-v7+EEUbhGqT3XJ9LMPsKvXYHFc8eHxTowFCG/HgJErmq4XHJ2WR7aeyICg3uTOAQ7Icn0GFHAohXEhxQHq4Ubw==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "bn.js": "^5.2.1"
      }
    },
    "@ethersproject/bytes": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/bytes/-/bytes-5.6.1.tgz",
      "integrity": "sha512-NwQt7cKn5+ZE4uDn+X5RAXLp46E1chXoaMmrxAyA0rblpxz8t58lVkrHXoRIn0lz1joQElQ8410GqhTqMOwc6g==",
      "dev": true,
      "requires": {
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "@ethersproject/constants": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/constants/-/constants-5.6.1.tgz",
      "integrity": "sha512-QSq9WVnZbxXYFftrjSjZDUshp6/eKp6qrtdBtUCm0QxCV5z1fG/w3kdlcsjMCQuQHUnAclKoK7XpXMezhRDOLg==",
      "dev": true,
      "requires": {
        "@ethersproject/bignumber": "^5.6.2"
      }
    },
    "@ethersproject/contracts": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/contracts/-/contracts-5.6.2.tgz",
      "integrity": "sha512-hguUA57BIKi6WY0kHvZp6PwPlWF87MCeB4B7Z7AbUpTxfFXFdn/3b0GmjZPagIHS+3yhcBJDnuEfU4Xz+Ks/8g==",
      "dev": true,
      "requires": {
        "@ethersproject/abi": "^5.6.3",
        "@ethersproject/abstract-provider": "^5.6.1",
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/transactions": "^5.6.2"
      }
    },
    "@ethersproject/hash": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/hash/-/hash-5.6.1.tgz",
      "integrity": "sha512-L1xAHurbaxG8VVul4ankNX5HgQ8PNCTrnVXEiFnE9xoRnaUcgfD12tZINtDinSllxPLCtGwguQxJ5E6keE84pA==",
      "dev": true,
      "requires": {
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "@ethersproject/hdnode": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/hdnode/-/hdnode-5.6.2.tgz",
      "integrity": "sha512-tERxW8Ccf9CxW2db3WsN01Qao3wFeRsfYY9TCuhmG0xNpl2IO8wgXU3HtWIZ49gUWPggRy4Yg5axU0ACaEKf1Q==",
      "dev": true,
      "requires": {
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/basex": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/pbkdf2": "^5.6.1",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/sha2": "^5.6.1",
        "@ethersproject/signing-key": "^5.6.2",
        "@ethersproject/strings": "^5.6.1",
        "@ethersproject/transactions": "^5.6.2",
        "@ethersproject/wordlists": "^5.6.1"
      }
    },
    "@ethersproject/json-wallets": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/json-wallets/-/json-wallets-5.6.1.tgz",
      "integrity": "sha512-KfyJ6Zwz3kGeX25nLihPwZYlDqamO6pfGKNnVMWWfEVVp42lTfCZVXXy5Ie8IZTN0HKwAngpIPi7gk4IJzgmqQ==",
      "dev": true,
      "requires": {
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/hdnode": "^5.6.2",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/pbkdf2": "^5.6.1",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/random": "^5.6.1",
        "@ethersproject/strings": "^5.6.1",
        "@ethersproject/transactions": "^5.6.2",
        "aes-js": "3.0.0",
        "scrypt-js": "3.0.1"
      }
    },
    "@ethersproject/keccak256": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/keccak256/-/keccak256-5.6.1.tgz",
      "integrity": "sha512-bB7DQHCTRDooZZdL3lk9wpL0+XuG3XLGHLh3cePnybsO3V0rdCAOQGpn/0R3aODmnTOOkCATJiD2hnL+5bwthA==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "js-sha3": "0.8.0"
      }
    },
    "@ethersproject/logger": {
      "version": "5.6.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/logger/-/logger-5.6.0.tgz",
      "integrity": "sha512-BiBWllUROH9w+P21RzoxJKzqoqpkyM1pRnEKG69bulE9TSQD8SAIvTQqIMZmmCO8pUNkgLP1wndX1gKghSpBmg==",
      "dev": true
    },
    "@ethersproject/networks": {
      "version": "5.6.3",
      "resolved": "https://registry.npmjs.org/@ethersproject/networks/-/networks-5.6.3.tgz",
      "integrity": "sha512-QZxRH7cA5Ut9TbXwZFiCyuPchdWi87ZtVNHWZd0R6YFgYtes2jQ3+bsslJ0WdyDe0i6QumqtoYqvY3rrQFRZOQ==",
      "dev": true,
      "requires": {
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "@ethersproject/pbkdf2": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/pbkdf2/-/pbkdf2-5.6.1.tgz",
      "integrity": "sha512-k4gRQ+D93zDRPNUfmduNKq065uadC2YjMP/CqwwX5qG6R05f47boq6pLZtV/RnC4NZAYOPH1Cyo54q0c9sshRQ==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/sha2": "^5.6.1"
      }
    },
    "@ethersproject/properties": {
      "version": "5.6.0",
      "resolved": "https://registry.npmjs.org/@ethersproject/properties/-/properties-5.6.0.tgz",
      "integrity": "sha512-szoOkHskajKePTJSZ46uHUWWkbv7TzP2ypdEK6jGMqJaEt2sb0jCgfBo0gH0m2HBpRixMuJ6TBRaQCF7a9DoCg==",
      "dev": true,
      "requires": {
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "@ethersproject/providers": {
      "version": "5.6.8",
      "resolved": "https://registry.npmjs.org/@ethersproject/providers/-/providers-5.6.8.tgz",
      "integrity": "sha512-Wf+CseT/iOJjrGtAOf3ck9zS7AgPmr2fZ3N97r4+YXN3mBePTG2/bJ8DApl9mVwYL+RpYbNxMEkEp4mPGdwG/w==",
      "dev": true,
      "requires": {
        "@ethersproject/abstract-provider": "^5.6.1",
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/base64": "^5.6.1",
        "@ethersproject/basex": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/hash": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/networks": "^5.6.3",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/random": "^5.6.1",
        "@ethersproject/rlp": "^5.6.1",
        "@ethersproject/sha2": "^5.6.1",
        "@ethersproject/strings": "^5.6.1",
        "@ethersproject/transactions": "^5.6.2",
        "@ethersproject/web": "^5.6.1",
        "bech32": "1.1.4",
        "ws": "7.4.6"
      }
    },
    "@ethersproject/random": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/random/-/random-5.6.1.tgz",
      "integrity": "sha512-/wtPNHwbmng+5yi3fkipA8YBT59DdkGRoC2vWk09Dci/q5DlgnMkhIycjHlavrvrjJBkFjO/ueLyT+aUDfc4lA==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "@ethersproject/rlp": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/rlp/-/rlp-5.6.1.tgz",
      "integrity": "sha512-uYjmcZx+DKlFUk7a5/W9aQVaoEC7+1MOBgNtvNg13+RnuUwT4F0zTovC0tmay5SmRslb29V1B7Y5KCri46WhuQ==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "@ethersproject/sha2": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/sha2/-/sha2-5.6.1.tgz",
      "integrity": "sha512-5K2GyqcW7G4Yo3uenHegbXRPDgARpWUiXc6RiF7b6i/HXUoWlb7uCARh7BAHg7/qT/Q5ydofNwiZcim9qpjB6g==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "hash.js": "1.1.7"
      }
    },
    "@ethersproject/signing-key": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/signing-key/-/signing-key-5.6.2.tgz",
      "integrity": "sha512-jVbu0RuP7EFpw82vHcL+GP35+KaNruVAZM90GxgQnGqB6crhBqW/ozBfFvdeImtmb4qPko0uxXjn8l9jpn0cwQ==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "bn.js": "^5.2.1",
        "elliptic": "6.5.4",
        "hash.js": "1.1.7"
      }
    },
    "@ethersproject/solidity": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/solidity/-/solidity-5.6.1.tgz",
      "integrity": "sha512-KWqVLkUUoLBfL1iwdzUVlkNqAUIFMpbbeH0rgCfKmJp0vFtY4AsaN91gHKo9ZZLkC4UOm3cI3BmMV4N53BOq4g==",
      "dev": true,
      "requires": {
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/sha2": "^5.6.1",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "@ethersproject/strings": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/strings/-/strings-5.6.1.tgz",
      "integrity": "sha512-2X1Lgk6Jyfg26MUnsHiT456U9ijxKUybz8IM1Vih+NJxYtXhmvKBcHOmvGqpFSVJ0nQ4ZCoIViR8XlRw1v/+Cw==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "@ethersproject/transactions": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/transactions/-/transactions-5.6.2.tgz",
      "integrity": "sha512-BuV63IRPHmJvthNkkt9G70Ullx6AcM+SDc+a8Aw/8Yew6YwT51TcBKEp1P4oOQ/bP25I18JJr7rcFRgFtU9B2Q==",
      "dev": true,
      "requires": {
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/rlp": "^5.6.1",
        "@ethersproject/signing-key": "^5.6.2"
      }
    },
    "@ethersproject/units": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/units/-/units-5.6.1.tgz",
      "integrity": "sha512-rEfSEvMQ7obcx3KWD5EWWx77gqv54K6BKiZzKxkQJqtpriVsICrktIQmKl8ReNToPeIYPnFHpXvKpi068YFZXw==",
      "dev": true,
      "requires": {
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/constants": "^5.6.1",
        "@ethersproject/logger": "^5.6.0"
      }
    },
    "@ethersproject/wallet": {
      "version": "5.6.2",
      "resolved": "https://registry.npmjs.org/@ethersproject/wallet/-/wallet-5.6.2.tgz",
      "integrity": "sha512-lrgh0FDQPuOnHcF80Q3gHYsSUODp6aJLAdDmDV0xKCN/T7D99ta1jGVhulg3PY8wiXEngD0DfM0I2XKXlrqJfg==",
      "dev": true,
      "requires": {
        "@ethersproject/abstract-provider": "^5.6.1",
        "@ethersproject/abstract-signer": "^5.6.2",
        "@ethersproject/address": "^5.6.1",
        "@ethersproject/bignumber": "^5.6.2",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/hash": "^5.6.1",
        "@ethersproject/hdnode": "^5.6.2",
        "@ethersproject/json-wallets": "^5.6.1",
        "@ethersproject/keccak256": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/random": "^5.6.1",
        "@ethersproject/signing-key": "^5.6.2",
        "@ethersproject/transactions": "^5.6.2",
        "@ethersproject/wordlists": "^5.6.1"
      }
    },
    "@ethersproject/web": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/web/-/web-5.6.1.tgz",
      "integrity": "sha512-/vSyzaQlNXkO1WV+RneYKqCJwualcUdx/Z3gseVovZP0wIlOFcCE1hkRhKBH8ImKbGQbMl9EAAyJFrJu7V0aqA==",
      "dev": true,
      "requires": {
        "@ethersproject/base64": "^5.6.1",
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "@ethersproject/wordlists": {
      "version": "5.6.1",
      "resolved": "https://registry.npmjs.org/@ethersproject/wordlists/-/wordlists-5.6.1.tgz",
      "integrity": "sha512-wiPRgBpNbNwCQFoCr8bcWO8o5I810cqO6mkdtKfLKFlLxeCWcnzDi4Alu8iyNzlhYuS9npCwivMbRWF19dyblw==",
      "dev": true,
      "requires": {
        "@ethersproject/bytes": "^5.6.1",
        "@ethersproject/hash": "^5.6.1",
        "@ethersproject/logger": "^5.6.0",
        "@ethersproject/properties": "^5.6.0",
        "@ethersproject/strings": "^5.6.1"
      }
    },
    "@graphql-typed-document-node/core": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/@graphql-typed-document-node/core/-/core-3.1.0.tgz",
      "integrity": "sha512-wYn6r8zVZyQJ6rQaALBEln5B1pzxb9shV5Ef97kTvn6yVGrqyXVnDqnU24MXnFubR+rZjBY9NWuxX3FB2sTsjg==",
      "requires": {}
    },
    "@istanbuljs/load-nyc-config": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@istanbuljs/load-nyc-config/-/load-nyc-config-1.1.0.tgz",
      "integrity": "sha512-VjeHSlIzpv/NyD3N0YuHfXOPDIixcA1q2ZV98wsMqcYlPmv2n3Yb2lYP9XMElnaFVXg5A7YLTeLu6V84uQDjmQ==",
      "dev": true,
      "requires": {
        "camelcase": "^5.3.1",
        "find-up": "^4.1.0",
        "get-package-type": "^0.1.0",
        "js-yaml": "^3.13.1",
        "resolve-from": "^5.0.0"
      },
      "dependencies": {
        "resolve-from": {
          "version": "5.0.0",
          "resolved": "https://registry.npmjs.org/resolve-from/-/resolve-from-5.0.0.tgz",
          "integrity": "sha512-qYg9KP24dD5qka9J47d0aVky0N+b4fTU89LN9iDnjB5waksiC49rvMB0PrUJQGoTmH50XPiqOvAjDfaijGxYZw==",
          "dev": true
        }
      }
    },
    "@istanbuljs/schema": {
      "version": "0.1.3",
      "resolved": "https://registry.npmjs.org/@istanbuljs/schema/-/schema-0.1.3.tgz",
      "integrity": "sha512-ZXRY4jNvVgSVQ8DL3LTcakaAtXwTVUxE81hslsyD2AtoXW/wVob10HkOJ1X/pAlcI7D+2YoZKg5do8G/w6RYgA==",
      "dev": true
    },
    "@jest/console": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/console/-/console-25.5.0.tgz",
      "integrity": "sha512-T48kZa6MK1Y6k4b89sexwmSF4YLeZS/Udqg3Jj3jG/cHH+N/sLFCEoXEDMOKugJQ9FxPN1osxIknvKkxt6MKyw==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "jest-message-util": "^25.5.0",
        "jest-util": "^25.5.0",
        "slash": "^3.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "@jest/core": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/@jest/core/-/core-25.5.4.tgz",
      "integrity": "sha512-3uSo7laYxF00Dg/DMgbn4xMJKmDdWvZnf89n8Xj/5/AeQ2dOQmn6b6Hkj/MleyzZWXpwv+WSdYWl4cLsy2JsoA==",
      "dev": true,
      "requires": {
        "@jest/console": "^25.5.0",
        "@jest/reporters": "^25.5.1",
        "@jest/test-result": "^25.5.0",
        "@jest/transform": "^25.5.1",
        "@jest/types": "^25.5.0",
        "ansi-escapes": "^4.2.1",
        "chalk": "^3.0.0",
        "exit": "^0.1.2",
        "graceful-fs": "^4.2.4",
        "jest-changed-files": "^25.5.0",
        "jest-config": "^25.5.4",
        "jest-haste-map": "^25.5.1",
        "jest-message-util": "^25.5.0",
        "jest-regex-util": "^25.2.6",
        "jest-resolve": "^25.5.1",
        "jest-resolve-dependencies": "^25.5.4",
        "jest-runner": "^25.5.4",
        "jest-runtime": "^25.5.4",
        "jest-snapshot": "^25.5.1",
        "jest-util": "^25.5.0",
        "jest-validate": "^25.5.0",
        "jest-watcher": "^25.5.0",
        "micromatch": "^4.0.2",
        "p-each-series": "^2.1.0",
        "realpath-native": "^2.0.0",
        "rimraf": "^3.0.0",
        "slash": "^3.0.0",
        "strip-ansi": "^6.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "strip-ansi": {
          "version": "6.0.0",
          "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
          "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
          "dev": true,
          "requires": {
            "ansi-regex": "^5.0.0"
          }
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "@jest/environment": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/environment/-/environment-25.5.0.tgz",
      "integrity": "sha512-U2VXPEqL07E/V7pSZMSQCvV5Ea4lqOlT+0ZFijl/i316cRMHvZ4qC+jBdryd+lmRetjQo0YIQr6cVPNxxK87mA==",
      "dev": true,
      "requires": {
        "@jest/fake-timers": "^25.5.0",
        "@jest/types": "^25.5.0",
        "jest-mock": "^25.5.0"
      }
    },
    "@jest/fake-timers": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/fake-timers/-/fake-timers-25.5.0.tgz",
      "integrity": "sha512-9y2+uGnESw/oyOI3eww9yaxdZyHq7XvprfP/eeoCsjqKYts2yRlsHS/SgjPDV8FyMfn2nbMy8YzUk6nyvdLOpQ==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-mock": "^25.5.0",
        "jest-util": "^25.5.0",
        "lolex": "^5.0.0"
      }
    },
    "@jest/globals": {
      "version": "25.5.2",
      "resolved": "https://registry.npmjs.org/@jest/globals/-/globals-25.5.2.tgz",
      "integrity": "sha512-AgAS/Ny7Q2RCIj5kZ+0MuKM1wbF0WMLxbCVl/GOMoCNbODRdJ541IxJ98xnZdVSZXivKpJlNPIWa3QmY0l4CXA==",
      "dev": true,
      "requires": {
        "@jest/environment": "^25.5.0",
        "@jest/types": "^25.5.0",
        "expect": "^25.5.0"
      }
    },
    "@jest/reporters": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/@jest/reporters/-/reporters-25.5.1.tgz",
      "integrity": "sha512-3jbd8pPDTuhYJ7vqiHXbSwTJQNavczPs+f1kRprRDxETeE3u6srJ+f0NPuwvOmk+lmunZzPkYWIFZDLHQPkviw==",
      "dev": true,
      "requires": {
        "@bcoe/v8-coverage": "^0.2.3",
        "@jest/console": "^25.5.0",
        "@jest/test-result": "^25.5.0",
        "@jest/transform": "^25.5.1",
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "collect-v8-coverage": "^1.0.0",
        "exit": "^0.1.2",
        "glob": "^7.1.2",
        "graceful-fs": "^4.2.4",
        "istanbul-lib-coverage": "^3.0.0",
        "istanbul-lib-instrument": "^4.0.0",
        "istanbul-lib-report": "^3.0.0",
        "istanbul-lib-source-maps": "^4.0.0",
        "istanbul-reports": "^3.0.2",
        "jest-haste-map": "^25.5.1",
        "jest-resolve": "^25.5.1",
        "jest-util": "^25.5.0",
        "jest-worker": "^25.5.0",
        "node-notifier": "^6.0.0",
        "slash": "^3.0.0",
        "source-map": "^0.6.0",
        "string-length": "^3.1.0",
        "terminal-link": "^2.0.0",
        "v8-to-istanbul": "^4.1.3"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "@jest/source-map": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/source-map/-/source-map-25.5.0.tgz",
      "integrity": "sha512-eIGx0xN12yVpMcPaVpjXPnn3N30QGJCJQSkEDUt9x1fI1Gdvb07Ml6K5iN2hG7NmMP6FDmtPEssE3z6doOYUwQ==",
      "dev": true,
      "requires": {
        "callsites": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "source-map": "^0.6.0"
      }
    },
    "@jest/test-result": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/test-result/-/test-result-25.5.0.tgz",
      "integrity": "sha512-oV+hPJgXN7IQf/fHWkcS99y0smKLU2czLBJ9WA0jHITLst58HpQMtzSYxzaBvYc6U5U6jfoMthqsUlUlbRXs0A==",
      "dev": true,
      "requires": {
        "@jest/console": "^25.5.0",
        "@jest/types": "^25.5.0",
        "@types/istanbul-lib-coverage": "^2.0.0",
        "collect-v8-coverage": "^1.0.0"
      }
    },
    "@jest/test-sequencer": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/@jest/test-sequencer/-/test-sequencer-25.5.4.tgz",
      "integrity": "sha512-pTJGEkSeg1EkCO2YWq6hbFvKNXk8ejqlxiOg1jBNLnWrgXOkdY6UmqZpwGFXNnRt9B8nO1uWMzLLZ4eCmhkPNA==",
      "dev": true,
      "requires": {
        "@jest/test-result": "^25.5.0",
        "graceful-fs": "^4.2.4",
        "jest-haste-map": "^25.5.1",
        "jest-runner": "^25.5.4",
        "jest-runtime": "^25.5.4"
      }
    },
    "@jest/transform": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/@jest/transform/-/transform-25.5.1.tgz",
      "integrity": "sha512-Y8CEoVwXb4QwA6Y/9uDkn0Xfz0finGkieuV0xkdF9UtZGJeLukD5nLkaVrVsODB1ojRWlaoD0AJZpVHCSnJEvg==",
      "dev": true,
      "requires": {
        "@babel/core": "^7.1.0",
        "@jest/types": "^25.5.0",
        "babel-plugin-istanbul": "^6.0.0",
        "chalk": "^3.0.0",
        "convert-source-map": "^1.4.0",
        "fast-json-stable-stringify": "^2.0.0",
        "graceful-fs": "^4.2.4",
        "jest-haste-map": "^25.5.1",
        "jest-regex-util": "^25.2.6",
        "jest-util": "^25.5.0",
        "micromatch": "^4.0.2",
        "pirates": "^4.0.1",
        "realpath-native": "^2.0.0",
        "slash": "^3.0.0",
        "source-map": "^0.6.1",
        "write-file-atomic": "^3.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "@jest/types": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/@jest/types/-/types-25.5.0.tgz",
      "integrity": "sha512-OXD0RgQ86Tu3MazKo8bnrkDRaDXXMGUqd+kTtLtK1Zb7CRzQcaSRPPPV37SvYTdevXEBVxe0HXylEjs8ibkmCw==",
      "dev": true,
      "requires": {
        "@types/istanbul-lib-coverage": "^2.0.0",
        "@types/istanbul-reports": "^1.1.1",
        "@types/yargs": "^15.0.0",
        "chalk": "^3.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "@lifi/sdk": {
      "version": "1.6.4",
      "resolved": "https://registry.npmjs.org/@lifi/sdk/-/sdk-1.6.4.tgz",
      "integrity": "sha512-g2wjHoXjM9QmTNAezMeHuFcUrfzn/6MSTSTRiWVgFOXcQt7e8guzn9tqLj+4Q24xwPlLB6nj0Coz2JX8dh1spA==",
      "requires": {
        "@ethersproject/abi": "^5.7.0",
        "@ethersproject/contracts": "^5.7.0",
        "@lifi/types": "^1.16.0",
        "axios": "^1.1.3",
        "bignumber.js": "^9.1.0",
        "eth-rpc-errors": "^4.0.3",
        "ethers": "^5.7.2"
      },
      "dependencies": {
        "@ethersproject/abi": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/abi/-/abi-5.7.0.tgz",
          "integrity": "sha512-351ktp42TiRcYB3H1OP8yajPeAQstMW/yCFokj/AthP9bLHzQFPlOrxOcwYEDkUAICmOHljvN4K39OMTMUa9RA==",
          "requires": {
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/hash": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "@ethersproject/abstract-provider": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/abstract-provider/-/abstract-provider-5.7.0.tgz",
          "integrity": "sha512-R41c9UkchKCpAqStMYUpdunjo3pkEvZC3FAwZn5S5MGbXoMQOHIdHItezTETxAO5bevtMApSyEhn9+CHcDsWBw==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/networks": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "@ethersproject/web": "^5.7.0"
          }
        },
        "@ethersproject/abstract-signer": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/abstract-signer/-/abstract-signer-5.7.0.tgz",
          "integrity": "sha512-a16V8bq1/Cz+TGCkE2OPMTOUDLS3grCpdjoJCYNnVBbdYEMSgKrU0+B90s8b6H+ByYTBZN7a3g76jdIJi7UfKQ==",
          "requires": {
            "@ethersproject/abstract-provider": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0"
          }
        },
        "@ethersproject/address": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/address/-/address-5.7.0.tgz",
          "integrity": "sha512-9wYhYt7aghVGo758POM5nqcOMaE168Q6aRLJZwUmiqSrAungkG74gSSeKEIR7ukixesdRZGPgVqme6vmxs1fkA==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/rlp": "^5.7.0"
          }
        },
        "@ethersproject/base64": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/base64/-/base64-5.7.0.tgz",
          "integrity": "sha512-Dr8tcHt2mEbsZr/mwTPIQAf3Ai0Bks/7gTw9dSqk1mQvhW3XvRlmDJr/4n+wg1JmCl16NZue17CDh8xb/vZ0sQ==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0"
          }
        },
        "@ethersproject/basex": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/basex/-/basex-5.7.0.tgz",
          "integrity": "sha512-ywlh43GwZLv2Voc2gQVTKBoVQ1mti3d8HK5aMxsfu/nRDnMmNqaSJ3r3n85HBByT8OpoY96SXM1FogC533T4zw==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/properties": "^5.7.0"
          }
        },
        "@ethersproject/bignumber": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/bignumber/-/bignumber-5.7.0.tgz",
          "integrity": "sha512-n1CAdIHRWjSucQO3MC1zPSVgV/6dy/fjL9pMrPP9peL+QxEg9wOsVqwD4+818B6LUEtaXzVHQiuivzRoxPxUGw==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "bn.js": "^5.2.1"
          }
        },
        "@ethersproject/bytes": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/bytes/-/bytes-5.7.0.tgz",
          "integrity": "sha512-nsbxwgFXWh9NyYWo+U8atvmMsSdKJprTcICAkvbBffT75qDocbuggBU0SJiVK2MuTrp0q+xvLkTnGMPK1+uA9A==",
          "requires": {
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/constants": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/constants/-/constants-5.7.0.tgz",
          "integrity": "sha512-DHI+y5dBNvkpYUMiRQyxRBYBefZkJfo70VUkUAsRjcPs47muV9evftfZ0PJVCXYbAiCgght0DtcF9srFQmIgWA==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0"
          }
        },
        "@ethersproject/contracts": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/contracts/-/contracts-5.7.0.tgz",
          "integrity": "sha512-5GJbzEU3X+d33CdfPhcyS+z8MzsTrBGk/sc+G+59+tPa9yFkl6HQ9D6L0QMgNTA9q8dT0XKxxkyp883XsQvbbg==",
          "requires": {
            "@ethersproject/abi": "^5.7.0",
            "@ethersproject/abstract-provider": "^5.7.0",
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0"
          }
        },
        "@ethersproject/hash": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/hash/-/hash-5.7.0.tgz",
          "integrity": "sha512-qX5WrQfnah1EFnO5zJv1v46a8HW0+E5xuBBDTwMFZLuVTx0tbU2kkx15NqdjxecrLGatQN9FGQKpb1FKdHCt+g==",
          "requires": {
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/base64": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "@ethersproject/hdnode": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/hdnode/-/hdnode-5.7.0.tgz",
          "integrity": "sha512-OmyYo9EENBPPf4ERhR7oj6uAtUAhYGqOnIS+jE5pTXvdKBS99ikzq1E7Iv0ZQZ5V36Lqx1qZLeak0Ra16qpeOg==",
          "requires": {
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/basex": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/pbkdf2": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/sha2": "^5.7.0",
            "@ethersproject/signing-key": "^5.7.0",
            "@ethersproject/strings": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "@ethersproject/wordlists": "^5.7.0"
          }
        },
        "@ethersproject/json-wallets": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/json-wallets/-/json-wallets-5.7.0.tgz",
          "integrity": "sha512-8oee5Xgu6+RKgJTkvEMl2wDgSPSAQ9MB/3JYjFV9jlKvcYHUXZC+cQp0njgmxdHkYWn8s6/IqIZYm0YWCjO/0g==",
          "requires": {
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/hdnode": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/pbkdf2": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/random": "^5.7.0",
            "@ethersproject/strings": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "aes-js": "3.0.0",
            "scrypt-js": "3.0.1"
          }
        },
        "@ethersproject/keccak256": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/keccak256/-/keccak256-5.7.0.tgz",
          "integrity": "sha512-2UcPboeL/iW+pSg6vZ6ydF8tCnv3Iu/8tUmLLzWWGzxWKFFqOBQFLo6uLUv6BDrLgCDfN28RJ/wtByx+jZ4KBg==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "js-sha3": "0.8.0"
          }
        },
        "@ethersproject/logger": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/logger/-/logger-5.7.0.tgz",
          "integrity": "sha512-0odtFdXu/XHtjQXJYA3u9G0G8btm0ND5Cu8M7i5vhEcE8/HmF4Lbdqanwyv4uQTr2tx6b7fQRmgLrsnpQlmnig=="
        },
        "@ethersproject/networks": {
          "version": "5.7.1",
          "resolved": "https://registry.npmjs.org/@ethersproject/networks/-/networks-5.7.1.tgz",
          "integrity": "sha512-n/MufjFYv3yFcUyfhnXotyDlNdFb7onmkSy8aQERi2PjNcnWQ66xXxa3XlS8nCcA8aJKJjIIMNJTC7tu80GwpQ==",
          "requires": {
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/pbkdf2": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/pbkdf2/-/pbkdf2-5.7.0.tgz",
          "integrity": "sha512-oR/dBRZR6GTyaofd86DehG72hY6NpAjhabkhxgr3X2FpJtJuodEl2auADWBZfhDHgVCbu3/H/Ocq2uC6dpNjjw==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/sha2": "^5.7.0"
          }
        },
        "@ethersproject/properties": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/properties/-/properties-5.7.0.tgz",
          "integrity": "sha512-J87jy8suntrAkIZtecpxEPxY//szqr1mlBaYlQ0r4RCaiD2hjheqF9s1LVE8vVuJCXisjIP+JgtK/Do54ej4Sw==",
          "requires": {
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/providers": {
          "version": "5.7.2",
          "resolved": "https://registry.npmjs.org/@ethersproject/providers/-/providers-5.7.2.tgz",
          "integrity": "sha512-g34EWZ1WWAVgr4aptGlVBF8mhl3VWjv+8hoAnzStu8Ah22VHBsuGzP17eb6xDVRzw895G4W7vvx60lFFur/1Rg==",
          "requires": {
            "@ethersproject/abstract-provider": "^5.7.0",
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/base64": "^5.7.0",
            "@ethersproject/basex": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/hash": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/networks": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/random": "^5.7.0",
            "@ethersproject/rlp": "^5.7.0",
            "@ethersproject/sha2": "^5.7.0",
            "@ethersproject/strings": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "@ethersproject/web": "^5.7.0",
            "bech32": "1.1.4",
            "ws": "7.4.6"
          }
        },
        "@ethersproject/random": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/random/-/random-5.7.0.tgz",
          "integrity": "sha512-19WjScqRA8IIeWclFme75VMXSBvi4e6InrUNuaR4s5pTF2qNhcGdCUwdxUVGtDDqC00sDLCO93jPQoDUH4HVmQ==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/rlp": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/rlp/-/rlp-5.7.0.tgz",
          "integrity": "sha512-rBxzX2vK8mVF7b0Tol44t5Tb8gomOHkj5guL+HhzQ1yBh/ydjGnpw6at+X6Iw0Kp3OzzzkcKp8N9r0W4kYSs9w==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/sha2": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/sha2/-/sha2-5.7.0.tgz",
          "integrity": "sha512-gKlH42riwb3KYp0reLsFTokByAKoJdgFCwI+CCiX/k+Jm2mbNs6oOaCjYQSlI1+XBVejwH2KrmCbMAT/GnRDQw==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "hash.js": "1.1.7"
          }
        },
        "@ethersproject/signing-key": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/signing-key/-/signing-key-5.7.0.tgz",
          "integrity": "sha512-MZdy2nL3wO0u7gkB4nA/pEf8lu1TlFswPNmy8AiYkfKTdO6eXBJyUdmHO/ehm/htHw9K/qF8ujnTyUAD+Ry54Q==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "bn.js": "^5.2.1",
            "elliptic": "6.5.4",
            "hash.js": "1.1.7"
          }
        },
        "@ethersproject/solidity": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/solidity/-/solidity-5.7.0.tgz",
          "integrity": "sha512-HmabMd2Dt/raavyaGukF4XxizWKhKQ24DoLtdNbBmNKUOPqwjsKQSdV9GQtj9CBEea9DlzETlVER1gYeXXBGaA==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/sha2": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "@ethersproject/strings": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/strings/-/strings-5.7.0.tgz",
          "integrity": "sha512-/9nu+lj0YswRNSH0NXYqrh8775XNyEdUQAuf3f+SmOrnVewcJ5SBNAjF7lpgehKi4abvNNXyf+HX86czCdJ8Mg==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/transactions": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/transactions/-/transactions-5.7.0.tgz",
          "integrity": "sha512-kmcNicCp1lp8qanMTC3RIikGgoJ80ztTyvtsFvCYpSCfkjhD0jZ2LOrnbcuxuToLIUYYf+4XwD1rP+B/erDIhQ==",
          "requires": {
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/rlp": "^5.7.0",
            "@ethersproject/signing-key": "^5.7.0"
          }
        },
        "@ethersproject/units": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/units/-/units-5.7.0.tgz",
          "integrity": "sha512-pD3xLMy3SJu9kG5xDGI7+xhTEmGXlEqXU4OfNapmfnxLVY4EMSSRp7j1k7eezutBPH7RBN/7QPnwR7hzNlEFeg==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/wallet": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/wallet/-/wallet-5.7.0.tgz",
          "integrity": "sha512-MhmXlJXEJFBFVKrDLB4ZdDzxcBxQ3rLyCkhNqVu3CDYvR97E+8r01UgrI+TI99Le+aYm/in/0vp86guJuM7FCA==",
          "requires": {
            "@ethersproject/abstract-provider": "^5.7.0",
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/hash": "^5.7.0",
            "@ethersproject/hdnode": "^5.7.0",
            "@ethersproject/json-wallets": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/random": "^5.7.0",
            "@ethersproject/signing-key": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "@ethersproject/wordlists": "^5.7.0"
          }
        },
        "@ethersproject/web": {
          "version": "5.7.1",
          "resolved": "https://registry.npmjs.org/@ethersproject/web/-/web-5.7.1.tgz",
          "integrity": "sha512-Gueu8lSvyjBWL4cYsWsjh6MtMwM0+H4HvqFPZfB6dV8ctbP9zFAO73VG1cMWae0FLPCtz0peKPpZY8/ugJJX2w==",
          "requires": {
            "@ethersproject/base64": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "@ethersproject/wordlists": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/wordlists/-/wordlists-5.7.0.tgz",
          "integrity": "sha512-S2TFNJNfHWVHNE6cNDjbVlZ6MgE17MIxMbMg2zv3wn+3XSJGosL1m9ZVv3GXCf/2ymSsQ+hRI5IzoMJTG6aoVA==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/hash": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "ethers": {
          "version": "5.7.2",
          "resolved": "https://registry.npmjs.org/ethers/-/ethers-5.7.2.tgz",
          "integrity": "sha512-wswUsmWo1aOK8rR7DIKiWSw9DbLWe6x98Jrn8wcTflTVvaXhAMaB5zGAXy0GYQEQp9iO1iSHWVyARQm11zUtyg==",
          "requires": {
            "@ethersproject/abi": "5.7.0",
            "@ethersproject/abstract-provider": "5.7.0",
            "@ethersproject/abstract-signer": "5.7.0",
            "@ethersproject/address": "5.7.0",
            "@ethersproject/base64": "5.7.0",
            "@ethersproject/basex": "5.7.0",
            "@ethersproject/bignumber": "5.7.0",
            "@ethersproject/bytes": "5.7.0",
            "@ethersproject/constants": "5.7.0",
            "@ethersproject/contracts": "5.7.0",
            "@ethersproject/hash": "5.7.0",
            "@ethersproject/hdnode": "5.7.0",
            "@ethersproject/json-wallets": "5.7.0",
            "@ethersproject/keccak256": "5.7.0",
            "@ethersproject/logger": "5.7.0",
            "@ethersproject/networks": "5.7.1",
            "@ethersproject/pbkdf2": "5.7.0",
            "@ethersproject/properties": "5.7.0",
            "@ethersproject/providers": "5.7.2",
            "@ethersproject/random": "5.7.0",
            "@ethersproject/rlp": "5.7.0",
            "@ethersproject/sha2": "5.7.0",
            "@ethersproject/signing-key": "5.7.0",
            "@ethersproject/solidity": "5.7.0",
            "@ethersproject/strings": "5.7.0",
            "@ethersproject/transactions": "5.7.0",
            "@ethersproject/units": "5.7.0",
            "@ethersproject/wallet": "5.7.0",
            "@ethersproject/web": "5.7.1",
            "@ethersproject/wordlists": "5.7.0"
          }
        }
      }
    },
    "@lifi/types": {
      "version": "1.17.0",
      "resolved": "https://registry.npmjs.org/@lifi/types/-/types-1.17.0.tgz",
      "integrity": "sha512-TpDbBlFfQ09kWyuwqhQ51AfFLgyslYLB9p7Swa2PPL8r40i2SpYTmaEmHyTmenZAGRVm8XLNfGBJR3Bygn4h9A==",
      "requires": {
        "ethers": "^5.7.2"
      },
      "dependencies": {
        "@ethersproject/abi": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/abi/-/abi-5.7.0.tgz",
          "integrity": "sha512-351ktp42TiRcYB3H1OP8yajPeAQstMW/yCFokj/AthP9bLHzQFPlOrxOcwYEDkUAICmOHljvN4K39OMTMUa9RA==",
          "requires": {
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/hash": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "@ethersproject/abstract-provider": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/abstract-provider/-/abstract-provider-5.7.0.tgz",
          "integrity": "sha512-R41c9UkchKCpAqStMYUpdunjo3pkEvZC3FAwZn5S5MGbXoMQOHIdHItezTETxAO5bevtMApSyEhn9+CHcDsWBw==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/networks": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "@ethersproject/web": "^5.7.0"
          }
        },
        "@ethersproject/abstract-signer": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/abstract-signer/-/abstract-signer-5.7.0.tgz",
          "integrity": "sha512-a16V8bq1/Cz+TGCkE2OPMTOUDLS3grCpdjoJCYNnVBbdYEMSgKrU0+B90s8b6H+ByYTBZN7a3g76jdIJi7UfKQ==",
          "requires": {
            "@ethersproject/abstract-provider": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0"
          }
        },
        "@ethersproject/address": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/address/-/address-5.7.0.tgz",
          "integrity": "sha512-9wYhYt7aghVGo758POM5nqcOMaE168Q6aRLJZwUmiqSrAungkG74gSSeKEIR7ukixesdRZGPgVqme6vmxs1fkA==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/rlp": "^5.7.0"
          }
        },
        "@ethersproject/base64": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/base64/-/base64-5.7.0.tgz",
          "integrity": "sha512-Dr8tcHt2mEbsZr/mwTPIQAf3Ai0Bks/7gTw9dSqk1mQvhW3XvRlmDJr/4n+wg1JmCl16NZue17CDh8xb/vZ0sQ==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0"
          }
        },
        "@ethersproject/basex": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/basex/-/basex-5.7.0.tgz",
          "integrity": "sha512-ywlh43GwZLv2Voc2gQVTKBoVQ1mti3d8HK5aMxsfu/nRDnMmNqaSJ3r3n85HBByT8OpoY96SXM1FogC533T4zw==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/properties": "^5.7.0"
          }
        },
        "@ethersproject/bignumber": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/bignumber/-/bignumber-5.7.0.tgz",
          "integrity": "sha512-n1CAdIHRWjSucQO3MC1zPSVgV/6dy/fjL9pMrPP9peL+QxEg9wOsVqwD4+818B6LUEtaXzVHQiuivzRoxPxUGw==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "bn.js": "^5.2.1"
          }
        },
        "@ethersproject/bytes": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/bytes/-/bytes-5.7.0.tgz",
          "integrity": "sha512-nsbxwgFXWh9NyYWo+U8atvmMsSdKJprTcICAkvbBffT75qDocbuggBU0SJiVK2MuTrp0q+xvLkTnGMPK1+uA9A==",
          "requires": {
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/constants": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/constants/-/constants-5.7.0.tgz",
          "integrity": "sha512-DHI+y5dBNvkpYUMiRQyxRBYBefZkJfo70VUkUAsRjcPs47muV9evftfZ0PJVCXYbAiCgght0DtcF9srFQmIgWA==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0"
          }
        },
        "@ethersproject/contracts": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/contracts/-/contracts-5.7.0.tgz",
          "integrity": "sha512-5GJbzEU3X+d33CdfPhcyS+z8MzsTrBGk/sc+G+59+tPa9yFkl6HQ9D6L0QMgNTA9q8dT0XKxxkyp883XsQvbbg==",
          "requires": {
            "@ethersproject/abi": "^5.7.0",
            "@ethersproject/abstract-provider": "^5.7.0",
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0"
          }
        },
        "@ethersproject/hash": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/hash/-/hash-5.7.0.tgz",
          "integrity": "sha512-qX5WrQfnah1EFnO5zJv1v46a8HW0+E5xuBBDTwMFZLuVTx0tbU2kkx15NqdjxecrLGatQN9FGQKpb1FKdHCt+g==",
          "requires": {
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/base64": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "@ethersproject/hdnode": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/hdnode/-/hdnode-5.7.0.tgz",
          "integrity": "sha512-OmyYo9EENBPPf4ERhR7oj6uAtUAhYGqOnIS+jE5pTXvdKBS99ikzq1E7Iv0ZQZ5V36Lqx1qZLeak0Ra16qpeOg==",
          "requires": {
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/basex": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/pbkdf2": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/sha2": "^5.7.0",
            "@ethersproject/signing-key": "^5.7.0",
            "@ethersproject/strings": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "@ethersproject/wordlists": "^5.7.0"
          }
        },
        "@ethersproject/json-wallets": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/json-wallets/-/json-wallets-5.7.0.tgz",
          "integrity": "sha512-8oee5Xgu6+RKgJTkvEMl2wDgSPSAQ9MB/3JYjFV9jlKvcYHUXZC+cQp0njgmxdHkYWn8s6/IqIZYm0YWCjO/0g==",
          "requires": {
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/hdnode": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/pbkdf2": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/random": "^5.7.0",
            "@ethersproject/strings": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "aes-js": "3.0.0",
            "scrypt-js": "3.0.1"
          }
        },
        "@ethersproject/keccak256": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/keccak256/-/keccak256-5.7.0.tgz",
          "integrity": "sha512-2UcPboeL/iW+pSg6vZ6ydF8tCnv3Iu/8tUmLLzWWGzxWKFFqOBQFLo6uLUv6BDrLgCDfN28RJ/wtByx+jZ4KBg==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "js-sha3": "0.8.0"
          }
        },
        "@ethersproject/logger": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/logger/-/logger-5.7.0.tgz",
          "integrity": "sha512-0odtFdXu/XHtjQXJYA3u9G0G8btm0ND5Cu8M7i5vhEcE8/HmF4Lbdqanwyv4uQTr2tx6b7fQRmgLrsnpQlmnig=="
        },
        "@ethersproject/networks": {
          "version": "5.7.1",
          "resolved": "https://registry.npmjs.org/@ethersproject/networks/-/networks-5.7.1.tgz",
          "integrity": "sha512-n/MufjFYv3yFcUyfhnXotyDlNdFb7onmkSy8aQERi2PjNcnWQ66xXxa3XlS8nCcA8aJKJjIIMNJTC7tu80GwpQ==",
          "requires": {
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/pbkdf2": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/pbkdf2/-/pbkdf2-5.7.0.tgz",
          "integrity": "sha512-oR/dBRZR6GTyaofd86DehG72hY6NpAjhabkhxgr3X2FpJtJuodEl2auADWBZfhDHgVCbu3/H/Ocq2uC6dpNjjw==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/sha2": "^5.7.0"
          }
        },
        "@ethersproject/properties": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/properties/-/properties-5.7.0.tgz",
          "integrity": "sha512-J87jy8suntrAkIZtecpxEPxY//szqr1mlBaYlQ0r4RCaiD2hjheqF9s1LVE8vVuJCXisjIP+JgtK/Do54ej4Sw==",
          "requires": {
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/providers": {
          "version": "5.7.2",
          "resolved": "https://registry.npmjs.org/@ethersproject/providers/-/providers-5.7.2.tgz",
          "integrity": "sha512-g34EWZ1WWAVgr4aptGlVBF8mhl3VWjv+8hoAnzStu8Ah22VHBsuGzP17eb6xDVRzw895G4W7vvx60lFFur/1Rg==",
          "requires": {
            "@ethersproject/abstract-provider": "^5.7.0",
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/base64": "^5.7.0",
            "@ethersproject/basex": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/hash": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/networks": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/random": "^5.7.0",
            "@ethersproject/rlp": "^5.7.0",
            "@ethersproject/sha2": "^5.7.0",
            "@ethersproject/strings": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "@ethersproject/web": "^5.7.0",
            "bech32": "1.1.4",
            "ws": "7.4.6"
          }
        },
        "@ethersproject/random": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/random/-/random-5.7.0.tgz",
          "integrity": "sha512-19WjScqRA8IIeWclFme75VMXSBvi4e6InrUNuaR4s5pTF2qNhcGdCUwdxUVGtDDqC00sDLCO93jPQoDUH4HVmQ==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/rlp": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/rlp/-/rlp-5.7.0.tgz",
          "integrity": "sha512-rBxzX2vK8mVF7b0Tol44t5Tb8gomOHkj5guL+HhzQ1yBh/ydjGnpw6at+X6Iw0Kp3OzzzkcKp8N9r0W4kYSs9w==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/sha2": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/sha2/-/sha2-5.7.0.tgz",
          "integrity": "sha512-gKlH42riwb3KYp0reLsFTokByAKoJdgFCwI+CCiX/k+Jm2mbNs6oOaCjYQSlI1+XBVejwH2KrmCbMAT/GnRDQw==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "hash.js": "1.1.7"
          }
        },
        "@ethersproject/signing-key": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/signing-key/-/signing-key-5.7.0.tgz",
          "integrity": "sha512-MZdy2nL3wO0u7gkB4nA/pEf8lu1TlFswPNmy8AiYkfKTdO6eXBJyUdmHO/ehm/htHw9K/qF8ujnTyUAD+Ry54Q==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "bn.js": "^5.2.1",
            "elliptic": "6.5.4",
            "hash.js": "1.1.7"
          }
        },
        "@ethersproject/solidity": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/solidity/-/solidity-5.7.0.tgz",
          "integrity": "sha512-HmabMd2Dt/raavyaGukF4XxizWKhKQ24DoLtdNbBmNKUOPqwjsKQSdV9GQtj9CBEea9DlzETlVER1gYeXXBGaA==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/sha2": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "@ethersproject/strings": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/strings/-/strings-5.7.0.tgz",
          "integrity": "sha512-/9nu+lj0YswRNSH0NXYqrh8775XNyEdUQAuf3f+SmOrnVewcJ5SBNAjF7lpgehKi4abvNNXyf+HX86czCdJ8Mg==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/transactions": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/transactions/-/transactions-5.7.0.tgz",
          "integrity": "sha512-kmcNicCp1lp8qanMTC3RIikGgoJ80ztTyvtsFvCYpSCfkjhD0jZ2LOrnbcuxuToLIUYYf+4XwD1rP+B/erDIhQ==",
          "requires": {
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/rlp": "^5.7.0",
            "@ethersproject/signing-key": "^5.7.0"
          }
        },
        "@ethersproject/units": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/units/-/units-5.7.0.tgz",
          "integrity": "sha512-pD3xLMy3SJu9kG5xDGI7+xhTEmGXlEqXU4OfNapmfnxLVY4EMSSRp7j1k7eezutBPH7RBN/7QPnwR7hzNlEFeg==",
          "requires": {
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/constants": "^5.7.0",
            "@ethersproject/logger": "^5.7.0"
          }
        },
        "@ethersproject/wallet": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/wallet/-/wallet-5.7.0.tgz",
          "integrity": "sha512-MhmXlJXEJFBFVKrDLB4ZdDzxcBxQ3rLyCkhNqVu3CDYvR97E+8r01UgrI+TI99Le+aYm/in/0vp86guJuM7FCA==",
          "requires": {
            "@ethersproject/abstract-provider": "^5.7.0",
            "@ethersproject/abstract-signer": "^5.7.0",
            "@ethersproject/address": "^5.7.0",
            "@ethersproject/bignumber": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/hash": "^5.7.0",
            "@ethersproject/hdnode": "^5.7.0",
            "@ethersproject/json-wallets": "^5.7.0",
            "@ethersproject/keccak256": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/random": "^5.7.0",
            "@ethersproject/signing-key": "^5.7.0",
            "@ethersproject/transactions": "^5.7.0",
            "@ethersproject/wordlists": "^5.7.0"
          }
        },
        "@ethersproject/web": {
          "version": "5.7.1",
          "resolved": "https://registry.npmjs.org/@ethersproject/web/-/web-5.7.1.tgz",
          "integrity": "sha512-Gueu8lSvyjBWL4cYsWsjh6MtMwM0+H4HvqFPZfB6dV8ctbP9zFAO73VG1cMWae0FLPCtz0peKPpZY8/ugJJX2w==",
          "requires": {
            "@ethersproject/base64": "^5.7.0",
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "@ethersproject/wordlists": {
          "version": "5.7.0",
          "resolved": "https://registry.npmjs.org/@ethersproject/wordlists/-/wordlists-5.7.0.tgz",
          "integrity": "sha512-S2TFNJNfHWVHNE6cNDjbVlZ6MgE17MIxMbMg2zv3wn+3XSJGosL1m9ZVv3GXCf/2ymSsQ+hRI5IzoMJTG6aoVA==",
          "requires": {
            "@ethersproject/bytes": "^5.7.0",
            "@ethersproject/hash": "^5.7.0",
            "@ethersproject/logger": "^5.7.0",
            "@ethersproject/properties": "^5.7.0",
            "@ethersproject/strings": "^5.7.0"
          }
        },
        "ethers": {
          "version": "5.7.2",
          "resolved": "https://registry.npmjs.org/ethers/-/ethers-5.7.2.tgz",
          "integrity": "sha512-wswUsmWo1aOK8rR7DIKiWSw9DbLWe6x98Jrn8wcTflTVvaXhAMaB5zGAXy0GYQEQp9iO1iSHWVyARQm11zUtyg==",
          "requires": {
            "@ethersproject/abi": "5.7.0",
            "@ethersproject/abstract-provider": "5.7.0",
            "@ethersproject/abstract-signer": "5.7.0",
            "@ethersproject/address": "5.7.0",
            "@ethersproject/base64": "5.7.0",
            "@ethersproject/basex": "5.7.0",
            "@ethersproject/bignumber": "5.7.0",
            "@ethersproject/bytes": "5.7.0",
            "@ethersproject/constants": "5.7.0",
            "@ethersproject/contracts": "5.7.0",
            "@ethersproject/hash": "5.7.0",
            "@ethersproject/hdnode": "5.7.0",
            "@ethersproject/json-wallets": "5.7.0",
            "@ethersproject/keccak256": "5.7.0",
            "@ethersproject/logger": "5.7.0",
            "@ethersproject/networks": "5.7.1",
            "@ethersproject/pbkdf2": "5.7.0",
            "@ethersproject/properties": "5.7.0",
            "@ethersproject/providers": "5.7.2",
            "@ethersproject/random": "5.7.0",
            "@ethersproject/rlp": "5.7.0",
            "@ethersproject/sha2": "5.7.0",
            "@ethersproject/signing-key": "5.7.0",
            "@ethersproject/solidity": "5.7.0",
            "@ethersproject/strings": "5.7.0",
            "@ethersproject/transactions": "5.7.0",
            "@ethersproject/units": "5.7.0",
            "@ethersproject/wallet": "5.7.0",
            "@ethersproject/web": "5.7.1",
            "@ethersproject/wordlists": "5.7.0"
          }
        }
      }
    },
    "@nerdwallet/apollo-cache-policies": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/@nerdwallet/apollo-cache-policies/-/apollo-cache-policies-1.2.1.tgz",
      "integrity": "sha512-B9ffnsNadLJ4Ge6l92lwVDLgzSmen8MqZhZenK4ocQQ7x1vctOdVSffXtmJUCYb98/KYHNQRskj0xgnS1+dlmw==",
      "requires": {
        "@types/graphql": "^14.5.0",
        "@types/lodash": "^4.14.168",
        "@types/uuid": "^7.0.4",
        "graphql": "^15.5.0",
        "lodash": "^4.17.20",
        "typescript": "^4.3.2",
        "uuid": "^7.0.3"
      },
      "dependencies": {
        "@types/uuid": {
          "version": "7.0.4",
          "resolved": "https://registry.npmjs.org/@types/uuid/-/uuid-7.0.4.tgz",
          "integrity": "sha512-WGZCqBZZ0mXN2RxvLHL6/7RCu+OWs28jgQMP04LWfpyJlQUMTR6YU9CNJAKDgbw+EV/u687INXuLUc7FuML/4g=="
        },
        "typescript": {
          "version": "4.3.4",
          "resolved": "https://registry.npmjs.org/typescript/-/typescript-4.3.4.tgz",
          "integrity": "sha512-uauPG7XZn9F/mo+7MrsRjyvbxFpzemRjKEZXS4AK83oP2KKOJPvb+9cO/gmnv8arWZvhnjVOXz7B49m1l0e9Ew=="
        },
        "uuid": {
          "version": "7.0.3",
          "resolved": "https://registry.npmjs.org/uuid/-/uuid-7.0.3.tgz",
          "integrity": "sha512-DPSke0pXhTZgoF/d+WSt2QaKMCFSfx7QegxEWT+JOuHF5aWrKEn0G+ztjuJg/gG8/ItK+rbPCD/yNv8yyih6Cg=="
        }
      }
    },
    "@protobufjs/aspromise": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/@protobufjs/aspromise/-/aspromise-1.1.2.tgz",
      "integrity": "sha1-m4sMxmPWaafY9vXQiToU00jzD78=",
      "dev": true
    },
    "@protobufjs/base64": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/@protobufjs/base64/-/base64-1.1.2.tgz",
      "integrity": "sha512-AZkcAA5vnN/v4PDqKyMR5lx7hZttPDgClv83E//FMNhR2TMcLUhfRUBHCmSl0oi9zMgDDqRUJkSxO3wm85+XLg==",
      "dev": true
    },
    "@protobufjs/codegen": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/@protobufjs/codegen/-/codegen-2.0.4.tgz",
      "integrity": "sha512-YyFaikqM5sH0ziFZCN3xDC7zeGaB/d0IUb9CATugHWbd1FRFwWwt4ld4OYMPWu5a3Xe01mGAULCdqhMlPl29Jg==",
      "dev": true
    },
    "@protobufjs/eventemitter": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/eventemitter/-/eventemitter-1.1.0.tgz",
      "integrity": "sha1-NVy8mLr61ZePntCV85diHx0Ga3A=",
      "dev": true
    },
    "@protobufjs/fetch": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/fetch/-/fetch-1.1.0.tgz",
      "integrity": "sha1-upn7WYYUr2VwDBYZ/wbUVLDYTEU=",
      "dev": true,
      "requires": {
        "@protobufjs/aspromise": "^1.1.1",
        "@protobufjs/inquire": "^1.1.0"
      }
    },
    "@protobufjs/float": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/@protobufjs/float/-/float-1.0.2.tgz",
      "integrity": "sha1-Xp4avctz/Ap8uLKR33jIy9l7h9E=",
      "dev": true
    },
    "@protobufjs/inquire": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/inquire/-/inquire-1.1.0.tgz",
      "integrity": "sha1-/yAOPnzyQp4tyvwRQIKOjMY48Ik=",
      "dev": true
    },
    "@protobufjs/path": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/@protobufjs/path/-/path-1.1.2.tgz",
      "integrity": "sha1-bMKyDFya1q0NzP0hynZz2Nf79o0=",
      "dev": true
    },
    "@protobufjs/pool": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/pool/-/pool-1.1.0.tgz",
      "integrity": "sha1-Cf0V8tbTq/qbZbw2ZQbWrXhG/1Q=",
      "dev": true
    },
    "@protobufjs/utf8": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@protobufjs/utf8/-/utf8-1.1.0.tgz",
      "integrity": "sha1-p3c2C1s5oaLlEG+OhY8v0tBgxXA=",
      "dev": true
    },
    "@sinonjs/commons": {
      "version": "1.8.3",
      "resolved": "https://registry.npmjs.org/@sinonjs/commons/-/commons-1.8.3.tgz",
      "integrity": "sha512-xkNcLAn/wZaX14RPlwizcKicDk9G3F8m2nU3L7Ukm5zBgTwiT0wsoFAHx9Jq56fJA1z/7uKGtCRu16sOUCLIHQ==",
      "dev": true,
      "requires": {
        "type-detect": "4.0.8"
      }
    },
    "@teppeis/multimaps": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/@teppeis/multimaps/-/multimaps-1.1.0.tgz",
      "integrity": "sha512-YgANgfYU7LqgaLkGPWSTiwu2qcuhj0IOvj+kRwDFjAVbiEXT7ZQLPaFfmrAAN/Fa+tvwy1aYFd0RdT7lMO1Msw==",
      "dev": true
    },
    "@types/babel__core": {
      "version": "7.1.14",
      "resolved": "https://registry.npmjs.org/@types/babel__core/-/babel__core-7.1.14.tgz",
      "integrity": "sha512-zGZJzzBUVDo/eV6KgbE0f0ZI7dInEYvo12Rb70uNQDshC3SkRMb67ja0GgRHZgAX3Za6rhaWlvbDO8rrGyAb1g==",
      "dev": true,
      "requires": {
        "@babel/parser": "^7.1.0",
        "@babel/types": "^7.0.0",
        "@types/babel__generator": "*",
        "@types/babel__template": "*",
        "@types/babel__traverse": "*"
      }
    },
    "@types/babel__generator": {
      "version": "7.6.2",
      "resolved": "https://registry.npmjs.org/@types/babel__generator/-/babel__generator-7.6.2.tgz",
      "integrity": "sha512-MdSJnBjl+bdwkLskZ3NGFp9YcXGx5ggLpQQPqtgakVhsWK0hTtNYhjpZLlWQTviGTvF8at+Bvli3jV7faPdgeQ==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.0.0"
      }
    },
    "@types/babel__template": {
      "version": "7.4.0",
      "resolved": "https://registry.npmjs.org/@types/babel__template/-/babel__template-7.4.0.tgz",
      "integrity": "sha512-NTPErx4/FiPCGScH7foPyr+/1Dkzkni+rHiYHHoTjvwou7AQzJkNeD60A9CXRy+ZEN2B1bggmkTMCDb+Mv5k+A==",
      "dev": true,
      "requires": {
        "@babel/parser": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "@types/babel__traverse": {
      "version": "7.11.1",
      "resolved": "https://registry.npmjs.org/@types/babel__traverse/-/babel__traverse-7.11.1.tgz",
      "integrity": "sha512-Vs0hm0vPahPMYi9tDjtP66llufgO3ST16WXaSTtDGEl9cewAl3AibmxWw6TINOqHPT9z0uABKAYjT9jNSg4npw==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.3.0"
      }
    },
    "@types/eslint-visitor-keys": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/@types/eslint-visitor-keys/-/eslint-visitor-keys-1.0.0.tgz",
      "integrity": "sha512-OCutwjDZ4aFS6PB1UZ988C4YgwlBHJd6wCeQqaLdmadZ/7e+w79+hbMUFC1QXDNCmdyoRfAFdm0RypzwR+Qpag==",
      "dev": true
    },
    "@types/graceful-fs": {
      "version": "4.1.5",
      "resolved": "https://registry.npmjs.org/@types/graceful-fs/-/graceful-fs-4.1.5.tgz",
      "integrity": "sha512-anKkLmZZ+xm4p8JWBf4hElkM4XR+EZeA2M9BAkkTldmcyDY4mbdIJnRghDJH3Ov5ooY7/UAoENtmdMSkaAd7Cw==",
      "dev": true,
      "requires": {
        "@types/node": "*"
      }
    },
    "@types/graphql": {
      "version": "14.5.0",
      "resolved": "https://registry.npmjs.org/@types/graphql/-/graphql-14.5.0.tgz",
      "integrity": "sha512-MOkzsEp1Jk5bXuAsHsUi6BVv0zCO+7/2PTiZMXWDSsMXvNU6w/PLMQT2vHn8hy2i0JqojPz1Sz6rsFjHtsU0lA==",
      "requires": {
        "graphql": "*"
      }
    },
    "@types/istanbul-lib-coverage": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/@types/istanbul-lib-coverage/-/istanbul-lib-coverage-2.0.3.tgz",
      "integrity": "sha512-sz7iLqvVUg1gIedBOvlkxPlc8/uVzyS5OwGz1cKjXzkl3FpL3al0crU8YGU1WoHkxn0Wxbw5tyi6hvzJKNzFsw==",
      "dev": true
    },
    "@types/istanbul-lib-report": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/@types/istanbul-lib-report/-/istanbul-lib-report-3.0.0.tgz",
      "integrity": "sha512-plGgXAPfVKFoYfa9NpYDAkseG+g6Jr294RqeqcqDixSbU34MZVJRi/P+7Y8GDpzkEwLaGZZOpKIEmeVZNtKsrg==",
      "dev": true,
      "requires": {
        "@types/istanbul-lib-coverage": "*"
      }
    },
    "@types/istanbul-reports": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/@types/istanbul-reports/-/istanbul-reports-1.1.2.tgz",
      "integrity": "sha512-P/W9yOX/3oPZSpaYOCQzGqgCQRXn0FFO/V8bWrCQs+wLmvVVxk6CRBXALEvNs9OHIatlnlFokfhuDo2ug01ciw==",
      "dev": true,
      "requires": {
        "@types/istanbul-lib-coverage": "*",
        "@types/istanbul-lib-report": "*"
      }
    },
    "@types/jest": {
      "version": "25.2.3",
      "resolved": "https://registry.npmjs.org/@types/jest/-/jest-25.2.3.tgz",
      "integrity": "sha512-JXc1nK/tXHiDhV55dvfzqtmP4S3sy3T3ouV2tkViZgxY/zeUkcpQcQPGRlgF4KmWzWW5oiWYSZwtCB+2RsE4Fw==",
      "dev": true,
      "requires": {
        "jest-diff": "^25.2.1",
        "pretty-format": "^25.2.1"
      }
    },
    "@types/json-schema": {
      "version": "7.0.7",
      "resolved": "https://registry.npmjs.org/@types/json-schema/-/json-schema-7.0.7.tgz",
      "integrity": "sha512-cxWFQVseBm6O9Gbw1IWb8r6OS4OhSt3hPZLkFApLjM8TEXROBuQGLAH2i2gZpcXdLBIrpXuTDhH7Vbm1iXmNGA==",
      "dev": true
    },
    "@types/lodash": {
      "version": "4.14.170",
      "resolved": "https://registry.npmjs.org/@types/lodash/-/lodash-4.14.170.tgz",
      "integrity": "sha512-bpcvu/MKHHeYX+qeEN8GE7DIravODWdACVA1ctevD8CN24RhPZIKMn9ntfAsrvLfSX3cR5RrBKAbYm9bGs0A+Q=="
    },
    "@types/long": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/@types/long/-/long-4.0.1.tgz",
      "integrity": "sha512-5tXH6Bx/kNGd3MgffdmP4dy2Z+G4eaXw0SE81Tq3BNadtnMR5/ySMzX4SLEzHJzSmPNn4HIdpQsBvXMUykr58w==",
      "dev": true
    },
    "@types/node": {
      "version": "13.13.9",
      "resolved": "https://registry.npmjs.org/@types/node/-/node-13.13.9.tgz",
      "integrity": "sha512-EPZBIGed5gNnfWCiwEIwTE2Jdg4813odnG8iNPMQGrqVxrI+wL68SPtPeCX+ZxGBaA6pKAVc6jaKgP/Q0QzfdQ==",
      "dev": true
    },
    "@types/normalize-package-data": {
      "version": "2.4.0",
      "resolved": "https://registry.npmjs.org/@types/normalize-package-data/-/normalize-package-data-2.4.0.tgz",
      "integrity": "sha512-f5j5b/Gf71L+dbqxIpQ4Z2WlmI/mPJ0fOkGGmFgtb6sAu97EPczzbS3/tJKxmcYDj55OX6ssqwDAWOHIYDRDGA==",
      "dev": true
    },
    "@types/prettier": {
      "version": "1.19.1",
      "resolved": "https://registry.npmjs.org/@types/prettier/-/prettier-1.19.1.tgz",
      "integrity": "sha512-5qOlnZscTn4xxM5MeGXAMOsIOIKIbh9e85zJWfBRVPlRMEVawzoPhINYbRGkBZCI8LxvBe7tJCdWiarA99OZfQ==",
      "dev": true
    },
    "@types/stack-utils": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/@types/stack-utils/-/stack-utils-1.0.1.tgz",
      "integrity": "sha512-l42BggppR6zLmpfU6fq9HEa2oGPEI8yrSPL3GITjfRInppYFahObbIQOQK3UGxEnyQpltZLaPe75046NOZQikw==",
      "dev": true
    },
    "@types/uuid": {
      "version": "8.3.0",
      "resolved": "https://registry.npmjs.org/@types/uuid/-/uuid-8.3.0.tgz",
      "integrity": "sha512-eQ9qFW/fhfGJF8WKHGEHZEyVWfZxrT+6CLIJGBcZPfxUh/+BnEj+UCGYMlr9qZuX/2AltsvwrGqp0LhEW8D0zQ==",
      "dev": true
    },
    "@types/validator": {
      "version": "13.7.10",
      "resolved": "https://registry.npmjs.org/@types/validator/-/validator-13.7.10.tgz",
      "integrity": "sha512-t1yxFAR2n0+VO6hd/FJ9F2uezAZVWHLmpmlJzm1eX03+H7+HsuTAp7L8QJs+2pQCfWkP1+EXsGK9Z9v7o/qPVQ=="
    },
    "@types/ws": {
      "version": "7.2.4",
      "resolved": "https://registry.npmjs.org/@types/ws/-/ws-7.2.4.tgz",
      "integrity": "sha512-9S6Ask71vujkVyeEXKxjBSUV8ZUB0mjL5la4IncBoheu04bDaYyUKErh1BQcY9+WzOUOiKqz/OnpJHYckbMfNg==",
      "dev": true,
      "requires": {
        "@types/node": "*"
      }
    },
    "@types/yargs": {
      "version": "15.0.13",
      "resolved": "https://registry.npmjs.org/@types/yargs/-/yargs-15.0.13.tgz",
      "integrity": "sha512-kQ5JNTrbDv3Rp5X2n/iUu37IJBDU2gsZ5R/g1/KHOOEc5IKfUFjXT6DENPGduh08I/pamwtEq4oul7gUqKTQDQ==",
      "dev": true,
      "requires": {
        "@types/yargs-parser": "*"
      }
    },
    "@types/yargs-parser": {
      "version": "20.2.0",
      "resolved": "https://registry.npmjs.org/@types/yargs-parser/-/yargs-parser-20.2.0.tgz",
      "integrity": "sha512-37RSHht+gzzgYeobbG+KWryeAW8J33Nhr69cjTqSYymXVZEN9NbRYWoYlRtDhHKPVT1FyNKwaTPC1NynKZpzRA==",
      "dev": true
    },
    "@types/zen-observable": {
      "version": "0.8.3",
      "resolved": "https://registry.npmjs.org/@types/zen-observable/-/zen-observable-0.8.3.tgz",
      "integrity": "sha512-fbF6oTd4sGGy0xjHPKAt+eS2CrxJ3+6gQ3FGcBoIJR2TLAyCkCyI8JqZNy+FeON0AhVgNJoUumVoZQjBFUqHkw=="
    },
    "@typescript-eslint/eslint-plugin": {
      "version": "2.34.0",
      "resolved": "https://registry.npmjs.org/@typescript-eslint/eslint-plugin/-/eslint-plugin-2.34.0.tgz",
      "integrity": "sha512-4zY3Z88rEE99+CNvTbXSyovv2z9PNOVffTWD2W8QF5s2prBQtwN2zadqERcrHpcR7O/+KMI3fcTAmUUhK/iQcQ==",
      "dev": true,
      "requires": {
        "@typescript-eslint/experimental-utils": "2.34.0",
        "functional-red-black-tree": "^1.0.1",
        "regexpp": "^3.0.0",
        "tsutils": "^3.17.1"
      }
    },
    "@typescript-eslint/experimental-utils": {
      "version": "2.34.0",
      "resolved": "https://registry.npmjs.org/@typescript-eslint/experimental-utils/-/experimental-utils-2.34.0.tgz",
      "integrity": "sha512-eS6FTkq+wuMJ+sgtuNTtcqavWXqsflWcfBnlYhg/nS4aZ1leewkXGbvBhaapn1q6qf4M71bsR1tez5JTRMuqwA==",
      "dev": true,
      "requires": {
        "@types/json-schema": "^7.0.3",
        "@typescript-eslint/typescript-estree": "2.34.0",
        "eslint-scope": "^5.0.0",
        "eslint-utils": "^2.0.0"
      }
    },
    "@typescript-eslint/parser": {
      "version": "2.34.0",
      "resolved": "https://registry.npmjs.org/@typescript-eslint/parser/-/parser-2.34.0.tgz",
      "integrity": "sha512-03ilO0ucSD0EPTw2X4PntSIRFtDPWjrVq7C3/Z3VQHRC7+13YB55rcJI3Jt+YgeHbjUdJPcPa7b23rXCBokuyA==",
      "dev": true,
      "requires": {
        "@types/eslint-visitor-keys": "^1.0.0",
        "@typescript-eslint/experimental-utils": "2.34.0",
        "@typescript-eslint/typescript-estree": "2.34.0",
        "eslint-visitor-keys": "^1.1.0"
      }
    },
    "@typescript-eslint/typescript-estree": {
      "version": "2.34.0",
      "resolved": "https://registry.npmjs.org/@typescript-eslint/typescript-estree/-/typescript-estree-2.34.0.tgz",
      "integrity": "sha512-OMAr+nJWKdlVM9LOqCqh3pQQPwxHAN7Du8DR6dmwCrAmxtiXQnhHJ6tBNtf+cggqfo51SG/FCwnKhXCIM7hnVg==",
      "dev": true,
      "requires": {
        "debug": "^4.1.1",
        "eslint-visitor-keys": "^1.1.0",
        "glob": "^7.1.6",
        "is-glob": "^4.0.1",
        "lodash": "^4.17.15",
        "semver": "^7.3.2",
        "tsutils": "^3.17.1"
      }
    },
    "@wry/context": {
      "version": "0.6.1",
      "resolved": "https://registry.npmjs.org/@wry/context/-/context-0.6.1.tgz",
      "integrity": "sha512-LOmVnY1iTU2D8tv4Xf6MVMZZ+juIJ87Kt/plMijjN20NMAXGmH4u8bS1t0uT74cZ5gwpocYueV58YwyI8y+GKw==",
      "requires": {
        "tslib": "^2.3.0"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.1",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
          "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
        }
      }
    },
    "@wry/equality": {
      "version": "0.5.2",
      "resolved": "https://registry.npmjs.org/@wry/equality/-/equality-0.5.2.tgz",
      "integrity": "sha512-oVMxbUXL48EV/C0/M7gLVsoK6qRHPS85x8zECofEZOVvxGmIPLA9o5Z27cc2PoAyZz1S2VoM2A7FLAnpfGlneA==",
      "requires": {
        "tslib": "^2.3.0"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.1",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
          "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
        }
      }
    },
    "@wry/trie": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/@wry/trie/-/trie-0.3.1.tgz",
      "integrity": "sha512-WwB53ikYudh9pIorgxrkHKrQZcCqNM/Q/bDzZBffEaGUKGuHrRb3zZUT9Sh2qw9yogC7SsdRmQ1ER0pqvd3bfw==",
      "requires": {
        "tslib": "^2.3.0"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.1",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
          "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
        }
      }
    },
    "@zeit/schemas": {
      "version": "2.21.0",
      "resolved": "https://registry.npmjs.org/@zeit/schemas/-/schemas-2.21.0.tgz",
      "integrity": "sha512-/J4WBTpWtQ4itN1rb3ao8LfClmVcmz2pO6oYb7Qd4h7VSqUhIbJIvrykz9Ew1WMg6eFWsKdsMHc5uPbFxqlCpg==",
      "dev": true
    },
    "abab": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/abab/-/abab-2.0.5.tgz",
      "integrity": "sha512-9IK9EadsbHo6jLWIpxpR6pL0sazTXV6+SQv25ZB+F7Bj9mJNaOc4nCRabwd5M/JwmUa8idz6Eci6eKfJryPs6Q==",
      "dev": true
    },
    "accepts": {
      "version": "1.3.8",
      "resolved": "https://registry.npmjs.org/accepts/-/accepts-1.3.8.tgz",
      "integrity": "sha512-PYAthTa2m2VKxuvSD3DPC/Gy+U+sOA1LAuT8mkmRuvw+NACSaeXEQ+NHcVF7rONl6qcaxV3Uuemwawk+7+SJLw==",
      "dev": true,
      "requires": {
        "mime-types": "~2.1.34",
        "negotiator": "0.6.3"
      },
      "dependencies": {
        "mime-db": {
          "version": "1.52.0",
          "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
          "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
          "dev": true
        },
        "mime-types": {
          "version": "2.1.35",
          "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
          "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
          "dev": true,
          "requires": {
            "mime-db": "1.52.0"
          }
        }
      }
    },
    "acorn": {
      "version": "7.4.1",
      "resolved": "https://registry.npmjs.org/acorn/-/acorn-7.4.1.tgz",
      "integrity": "sha512-nQyp0o1/mNdbTO1PO6kHkwSrmgZ0MT/jCCpNiwbUjGoRN4dlBhqJtoQuCnEOKzgTVwg0ZWiCoQy6SxMebQVh8A==",
      "dev": true
    },
    "acorn-globals": {
      "version": "4.3.4",
      "resolved": "https://registry.npmjs.org/acorn-globals/-/acorn-globals-4.3.4.tgz",
      "integrity": "sha512-clfQEh21R+D0leSbUdWf3OcfqyaCSAQ8Ryq00bofSekfr9W8u1jyYZo6ir0xu9Gtcf7BjcHJpnbZH7JOCpP60A==",
      "dev": true,
      "requires": {
        "acorn": "^6.0.1",
        "acorn-walk": "^6.0.1"
      },
      "dependencies": {
        "acorn": {
          "version": "6.4.2",
          "resolved": "https://registry.npmjs.org/acorn/-/acorn-6.4.2.tgz",
          "integrity": "sha512-XtGIhXwF8YM8bJhGxG5kXgjkEuNGLTkoYqVE+KMR+aspr4KGYmKYg7yUe3KghyQ9yheNwLnjmzh/7+gfDBmHCQ==",
          "dev": true
        }
      }
    },
    "acorn-jsx": {
      "version": "5.3.1",
      "resolved": "https://registry.npmjs.org/acorn-jsx/-/acorn-jsx-5.3.1.tgz",
      "integrity": "sha512-K0Ptm/47OKfQRpNQ2J/oIN/3QYiK6FwW+eJbILhsdxh2WTLdl+30o8aGdTbm5JbffpFFAg/g+zi1E+jvJha5ng==",
      "dev": true,
      "requires": {}
    },
    "acorn-walk": {
      "version": "6.2.0",
      "resolved": "https://registry.npmjs.org/acorn-walk/-/acorn-walk-6.2.0.tgz",
      "integrity": "sha512-7evsyfH1cLOCdAzZAd43Cic04yKydNx0cF+7tiA19p1XnLLPU4dpCQOqpjqwokFe//vS0QqfqqjCS2JkiIs0cA==",
      "dev": true
    },
    "aes-js": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/aes-js/-/aes-js-3.0.0.tgz",
      "integrity": "sha1-4h3xCtbCBTKVvLuNq0Cwnb6ofk0="
    },
    "ajv": {
      "version": "6.12.6",
      "resolved": "https://registry.npmjs.org/ajv/-/ajv-6.12.6.tgz",
      "integrity": "sha512-j3fVLgvTo527anyYyJOGTYJbG+vnnQYvE0m5mmkc1TK+nxAppkCLMIL0aZ4dblVCNoGShhm+kzE4ZUykBoMg4g==",
      "dev": true,
      "requires": {
        "fast-deep-equal": "^3.1.1",
        "fast-json-stable-stringify": "^2.0.0",
        "json-schema-traverse": "^0.4.1",
        "uri-js": "^4.2.2"
      }
    },
    "ansi-align": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/ansi-align/-/ansi-align-3.0.1.tgz",
      "integrity": "sha512-IOfwwBF5iczOjp/WeY4YxyjqAFMQoZufdQWDd19SEExbVLNXqvpzSJ/M7Za4/sCPmQ0+GRquoA7bGcINcxew6w==",
      "dev": true,
      "requires": {
        "string-width": "^4.1.0"
      }
    },
    "ansi-escapes": {
      "version": "4.3.2",
      "resolved": "https://registry.npmjs.org/ansi-escapes/-/ansi-escapes-4.3.2.tgz",
      "integrity": "sha512-gKXj5ALrKWQLsYG9jlTRmR/xKluxHV+Z9QEwNIgCfM1/uwPMCuzVVnh5mwTd+OuBZcwSIMbqssNWRm1lE51QaQ==",
      "dev": true,
      "requires": {
        "type-fest": "^0.21.3"
      },
      "dependencies": {
        "type-fest": {
          "version": "0.21.3",
          "resolved": "https://registry.npmjs.org/type-fest/-/type-fest-0.21.3.tgz",
          "integrity": "sha512-t0rzBq87m3fVcduHDUFhKmyyX+9eo6WQjZvf51Ea/M0Q7+T374Jp1aUiyUl0GKxp8M/OETVHSDvmkyPgvX+X2w==",
          "dev": true
        }
      }
    },
    "ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true
    },
    "ansi-styles": {
      "version": "3.2.1",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-3.2.1.tgz",
      "integrity": "sha512-VT0ZI6kZRdTh8YyJw3SMbYm/u+NqfsAxEpWO0Pf9sq8/e94WxxOpPKx9FR1FlyCtOVDNOQ+8ntlqFxiRc+r5qA==",
      "dev": true,
      "requires": {
        "color-convert": "^1.9.0"
      }
    },
    "any-promise": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/any-promise/-/any-promise-1.3.0.tgz",
      "integrity": "sha1-q8av7tzqUugJzcA3au0845Y10X8=",
      "dev": true
    },
    "anymatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/anymatch/-/anymatch-3.1.2.tgz",
      "integrity": "sha512-P43ePfOAIupkguHUycrc4qJ9kz8ZiuOUijaETwX7THt0Y/GNK7v0aa8rY816xWjZ7rJdA5XdMcpVFTKMq+RvWg==",
      "dev": true,
      "requires": {
        "normalize-path": "^3.0.0",
        "picomatch": "^2.0.4"
      }
    },
    "arch": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/arch/-/arch-2.2.0.tgz",
      "integrity": "sha512-Of/R0wqp83cgHozfIYLbBMnej79U/SVGOOyuB3VVFv1NRM/PSFMK12x9KVtiYzJqmnU5WR2qp0Z5rHb7sWGnFQ==",
      "dev": true
    },
    "arg": {
      "version": "5.0.2",
      "resolved": "https://registry.npmjs.org/arg/-/arg-5.0.2.tgz",
      "integrity": "sha512-PYjyFOLKQ9y57JvQ6QLo8dAgNqswh8M1RMJYdQduT6xbWSgK36P/Z/v+p888pM69jMMfS8Xd8F6I1kQ/I9HUGg==",
      "dev": true
    },
    "argparse": {
      "version": "1.0.10",
      "resolved": "https://registry.npmjs.org/argparse/-/argparse-1.0.10.tgz",
      "integrity": "sha512-o5Roy6tNG4SL/FOkCAN6RzjiakZS25RLYFrcMttJqbdd8BWrnA+fGz57iN5Pb06pvBGvl5gQ0B48dJlslXvoTg==",
      "dev": true,
      "requires": {
        "sprintf-js": "~1.0.2"
      }
    },
    "arr-diff": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/arr-diff/-/arr-diff-4.0.0.tgz",
      "integrity": "sha1-1kYQdP6/7HHn4VI1dhoyml3HxSA=",
      "dev": true
    },
    "arr-flatten": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/arr-flatten/-/arr-flatten-1.1.0.tgz",
      "integrity": "sha512-L3hKV5R/p5o81R7O02IGnwpDmkp6E982XhtbuwSe3O4qOtMMMtodicASA1Cny2U+aCXcNpml+m4dPsvsJ3jatg==",
      "dev": true
    },
    "arr-union": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/arr-union/-/arr-union-3.1.0.tgz",
      "integrity": "sha1-45sJrqne+Gao8gbiiK9jkZuuOcQ=",
      "dev": true
    },
    "array-equal": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/array-equal/-/array-equal-1.0.0.tgz",
      "integrity": "sha1-jCpe8kcv2ep0KwTHenUJO6J1fJM=",
      "dev": true
    },
    "array-includes": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/array-includes/-/array-includes-3.1.3.tgz",
      "integrity": "sha512-gcem1KlBU7c9rB+Rq8/3PPKsK2kjqeEBa3bD5kkQo4nYlOHQCJqIJFqBXDEfwaRuYTT4E+FxA9xez7Gf/e3Q7A==",
      "dev": true,
      "requires": {
        "call-bind": "^1.0.2",
        "define-properties": "^1.1.3",
        "es-abstract": "^1.18.0-next.2",
        "get-intrinsic": "^1.1.1",
        "is-string": "^1.0.5"
      }
    },
    "array-union": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/array-union/-/array-union-1.0.2.tgz",
      "integrity": "sha1-mjRBDk9OPaI96jdb5b5w8kd47Dk=",
      "dev": true,
      "requires": {
        "array-uniq": "^1.0.1"
      }
    },
    "array-uniq": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/array-uniq/-/array-uniq-1.0.3.tgz",
      "integrity": "sha1-r2rId6Jcx/dOBYiUdThY39sk/bY=",
      "dev": true
    },
    "array-unique": {
      "version": "0.3.2",
      "resolved": "https://registry.npmjs.org/array-unique/-/array-unique-0.3.2.tgz",
      "integrity": "sha1-qJS3XUvE9s1nnvMkSp/Y9Gri1Cg=",
      "dev": true
    },
    "array.prototype.flat": {
      "version": "1.2.4",
      "resolved": "https://registry.npmjs.org/array.prototype.flat/-/array.prototype.flat-1.2.4.tgz",
      "integrity": "sha512-4470Xi3GAPAjZqFcljX2xzckv1qeKPizoNkiS0+O4IoPR2ZNpcjE0pkhdihlDouK+x6QOast26B4Q/O9DJnwSg==",
      "dev": true,
      "requires": {
        "call-bind": "^1.0.0",
        "define-properties": "^1.1.3",
        "es-abstract": "^1.18.0-next.1"
      }
    },
    "asn1": {
      "version": "0.2.4",
      "resolved": "https://registry.npmjs.org/asn1/-/asn1-0.2.4.tgz",
      "integrity": "sha512-jxwzQpLQjSmWXgwaCZE9Nz+glAG01yF1QnWgbhGwHI5A6FRIEY6IVqtHhIepHqI7/kyEyQEagBC5mBEFlIYvdg==",
      "dev": true,
      "requires": {
        "safer-buffer": "~2.1.0"
      }
    },
    "assert-plus": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/assert-plus/-/assert-plus-1.0.0.tgz",
      "integrity": "sha1-8S4PPF13sLHN2RRpQuTpbB5N1SU=",
      "dev": true
    },
    "assertion-error-formatter": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/assertion-error-formatter/-/assertion-error-formatter-3.0.0.tgz",
      "integrity": "sha512-6YyAVLrEze0kQ7CmJfUgrLHb+Y7XghmL2Ie7ijVa2Y9ynP3LV+VDiwFk62Dn0qtqbmY0BT0ss6p1xxpiF2PYbQ==",
      "dev": true,
      "requires": {
        "diff": "^4.0.1",
        "pad-right": "^0.2.2",
        "repeat-string": "^1.6.1"
      }
    },
    "assign-symbols": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/assign-symbols/-/assign-symbols-1.0.0.tgz",
      "integrity": "sha1-WWZ/QfrdTyDMvCu5a41Pf3jsA2c=",
      "dev": true
    },
    "astral-regex": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/astral-regex/-/astral-regex-1.0.0.tgz",
      "integrity": "sha512-+Ryf6g3BKoRc7jfp7ad8tM4TtMiaWvbF/1/sQcZPkkS7ag3D5nMBCe2UfOTONtAkaG0tO0ij3C5Lwmf1EiyjHg==",
      "dev": true
    },
    "async": {
      "version": "2.6.4",
      "resolved": "https://registry.npmjs.org/async/-/async-2.6.4.tgz",
      "integrity": "sha512-mzo5dfJYwAn29PeiJ0zvwTo04zj8HDJj0Mn8TD7sno7q12prdbnasKJHhkm2c1LgrhlJ0teaea8860oxi51mGA==",
      "dev": true,
      "requires": {
        "lodash": "^4.17.14"
      }
    },
    "async-limiter": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/async-limiter/-/async-limiter-1.0.1.tgz",
      "integrity": "sha512-csOlWGAcRFJaI6m+F2WKdnMKr4HhdhFVBk0H/QbJFMCr+uO2kwohwXQPxw/9OCxp05r5ghVBFSyioixx3gfkNQ=="
    },
    "asynckit": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/asynckit/-/asynckit-0.4.0.tgz",
      "integrity": "sha1-x57Zf380y48robyXkLzDZkdLS3k="
    },
    "atob": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/atob/-/atob-2.1.2.tgz",
      "integrity": "sha512-Wm6ukoaOGJi/73p/cl2GvLjTI5JM1k/O14isD73YML8StrH/7/lRFgmg8nICZgD3bZZvjwCGxtMOD3wWNAu8cg==",
      "dev": true
    },
    "aws-sign2": {
      "version": "0.7.0",
      "resolved": "https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.7.0.tgz",
      "integrity": "sha1-tG6JCTSpWR8tL2+G1+ap8bP+dqg=",
      "dev": true
    },
    "aws4": {
      "version": "1.11.0",
      "resolved": "https://registry.npmjs.org/aws4/-/aws4-1.11.0.tgz",
      "integrity": "sha512-xh1Rl34h6Fi1DC2WWKfxUTVqRsNnr6LsKz2+hfwDxQJWmrx8+c7ylaqBMcHfl1U1r2dsifOvKX3LQuLNZ+XSvA==",
      "dev": true
    },
    "axios": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/axios/-/axios-1.1.3.tgz",
      "integrity": "sha512-00tXVRwKx/FZr/IDVFt4C+f9FYairX517WoGCL6dpOntqLkZofjhu43F/Xl44UOpqa+9sLFDrG/XAnFsUYgkDA==",
      "requires": {
        "follow-redirects": "^1.15.0",
        "form-data": "^4.0.0",
        "proxy-from-env": "^1.1.0"
      },
      "dependencies": {
        "form-data": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/form-data/-/form-data-4.0.0.tgz",
          "integrity": "sha512-ETEklSGi5t0QMZuiXoA/Q6vcnxcLQP5vdugSpuAyi6SVGi2clPPp+xgEhuMaHC+zGgn31Kd235W35f7Hykkaww==",
          "requires": {
            "asynckit": "^0.4.0",
            "combined-stream": "^1.0.8",
            "mime-types": "^2.1.12"
          }
        }
      }
    },
    "babel-jest": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/babel-jest/-/babel-jest-25.5.1.tgz",
      "integrity": "sha512-9dA9+GmMjIzgPnYtkhBg73gOo/RHqPmLruP3BaGL4KEX3Dwz6pI8auSN8G8+iuEG90+GSswyKvslN+JYSaacaQ==",
      "dev": true,
      "requires": {
        "@jest/transform": "^25.5.1",
        "@jest/types": "^25.5.0",
        "@types/babel__core": "^7.1.7",
        "babel-plugin-istanbul": "^6.0.0",
        "babel-preset-jest": "^25.5.0",
        "chalk": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "slash": "^3.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "babel-plugin-istanbul": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-istanbul/-/babel-plugin-istanbul-6.0.0.tgz",
      "integrity": "sha512-AF55rZXpe7trmEylbaE1Gv54wn6rwU03aptvRoVIGP8YykoSxqdVLV1TfwflBCE/QtHmqtP8SWlTENqbK8GCSQ==",
      "dev": true,
      "requires": {
        "@babel/helper-plugin-utils": "^7.0.0",
        "@istanbuljs/load-nyc-config": "^1.0.0",
        "@istanbuljs/schema": "^0.1.2",
        "istanbul-lib-instrument": "^4.0.0",
        "test-exclude": "^6.0.0"
      }
    },
    "babel-plugin-jest-hoist": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/babel-plugin-jest-hoist/-/babel-plugin-jest-hoist-25.5.0.tgz",
      "integrity": "sha512-u+/W+WAjMlvoocYGTwthAiQSxDcJAyHpQ6oWlHdFZaaN+Rlk8Q7iiwDPg2lN/FyJtAYnKjFxbn7xus4HCFkg5g==",
      "dev": true,
      "requires": {
        "@babel/template": "^7.3.3",
        "@babel/types": "^7.3.3",
        "@types/babel__traverse": "^7.0.6"
      }
    },
    "babel-preset-current-node-syntax": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/babel-preset-current-node-syntax/-/babel-preset-current-node-syntax-0.1.4.tgz",
      "integrity": "sha512-5/INNCYhUGqw7VbVjT/hb3ucjgkVHKXY7lX3ZjlN4gm565VyFmJUrJ/h+h16ECVB38R/9SF6aACydpKMLZ/c9w==",
      "dev": true,
      "requires": {
        "@babel/plugin-syntax-async-generators": "^7.8.4",
        "@babel/plugin-syntax-bigint": "^7.8.3",
        "@babel/plugin-syntax-class-properties": "^7.8.3",
        "@babel/plugin-syntax-import-meta": "^7.8.3",
        "@babel/plugin-syntax-json-strings": "^7.8.3",
        "@babel/plugin-syntax-logical-assignment-operators": "^7.8.3",
        "@babel/plugin-syntax-nullish-coalescing-operator": "^7.8.3",
        "@babel/plugin-syntax-numeric-separator": "^7.8.3",
        "@babel/plugin-syntax-object-rest-spread": "^7.8.3",
        "@babel/plugin-syntax-optional-catch-binding": "^7.8.3",
        "@babel/plugin-syntax-optional-chaining": "^7.8.3"
      }
    },
    "babel-preset-jest": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/babel-preset-jest/-/babel-preset-jest-25.5.0.tgz",
      "integrity": "sha512-8ZczygctQkBU+63DtSOKGh7tFL0CeCuz+1ieud9lJ1WPQ9O6A1a/r+LGn6Y705PA6whHQ3T1XuB/PmpfNYf8Fw==",
      "dev": true,
      "requires": {
        "babel-plugin-jest-hoist": "^25.5.0",
        "babel-preset-current-node-syntax": "^0.1.2"
      }
    },
    "backo2": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz",
      "integrity": "sha1-MasayLEpNjRj41s+u2n038+6eUc="
    },
    "balanced-match": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/balanced-match/-/balanced-match-1.0.2.tgz",
      "integrity": "sha512-3oSeUO0TMV67hN1AmbXsK4yaqU7tjiHlbxRDZOpH0KW9+CeX4bRAaX0Anxt0tx2MrpRpWwQaPwIlISEJhYU5Pw==",
      "dev": true
    },
    "base": {
      "version": "0.11.2",
      "resolved": "https://registry.npmjs.org/base/-/base-0.11.2.tgz",
      "integrity": "sha512-5T6P4xPgpp0YDFvSWwEZ4NoE3aM4QBQXDzmVbraCkFj8zHM+mba8SyqB5DbZWyR7mYHo6Y7BdQo3MoA4m0TeQg==",
      "dev": true,
      "requires": {
        "cache-base": "^1.0.1",
        "class-utils": "^0.3.5",
        "component-emitter": "^1.2.1",
        "define-property": "^1.0.0",
        "isobject": "^3.0.1",
        "mixin-deep": "^1.2.0",
        "pascalcase": "^0.1.1"
      },
      "dependencies": {
        "define-property": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
          "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
          "dev": true,
          "requires": {
            "is-descriptor": "^1.0.0"
          }
        }
      }
    },
    "bcrypt-pbkdf": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/bcrypt-pbkdf/-/bcrypt-pbkdf-1.0.2.tgz",
      "integrity": "sha1-pDAdOJtqQ/m2f/PKEaP2Y342Dp4=",
      "dev": true,
      "requires": {
        "tweetnacl": "^0.14.3"
      }
    },
    "bech32": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/bech32/-/bech32-1.1.4.tgz",
      "integrity": "sha512-s0IrSOzLlbvX7yp4WBfPITzpAU8sqQcpsmwXDiKwrG4r491vwCO/XpejasRNl0piBMe/DvP4Tz0mIS/X1DPJBQ=="
    },
    "becke-ch--regex--s0-0-v1--base--pl--lib": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/becke-ch--regex--s0-0-v1--base--pl--lib/-/becke-ch--regex--s0-0-v1--base--pl--lib-1.4.0.tgz",
      "integrity": "sha1-Qpzuu/pffpNueNc/vcfacWKyDiA=",
      "dev": true
    },
    "bignumber.js": {
      "version": "9.1.0",
      "resolved": "https://registry.npmjs.org/bignumber.js/-/bignumber.js-9.1.0.tgz",
      "integrity": "sha512-4LwHK4nfDOraBCtst+wOWIHbu1vhvAPJK8g8nROd4iuc3PSEjWif/qwbkh8jwCJz6yDBvtU4KPynETgrfh7y3A=="
    },
    "bluebird": {
      "version": "3.7.2",
      "resolved": "https://registry.npmjs.org/bluebird/-/bluebird-3.7.2.tgz",
      "integrity": "sha512-XpNj6GDQzdfW+r2Wnn7xiSAd7TM3jzkxGXBGTtWKuSXv1xUV+azxAm8jdWZN06QTQk+2N2XB9jRDkvbmQmcRtg==",
      "dev": true
    },
    "bn.js": {
      "version": "5.2.1",
      "resolved": "https://registry.npmjs.org/bn.js/-/bn.js-5.2.1.tgz",
      "integrity": "sha512-eXRvHzWyYPBuB4NBy0cmYQjGitUrtqwbvlzP3G6VFnNRbsZQIxQ10PbKKHt8gZ/HW/D/747aDl+QkDqg3KQLMQ=="
    },
    "boxen": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/boxen/-/boxen-7.0.0.tgz",
      "integrity": "sha512-j//dBVuyacJbvW+tvZ9HuH03fZ46QcaKvvhZickZqtB271DxJ7SNRSNxrV/dZX0085m7hISRZWbzWlJvx/rHSg==",
      "dev": true,
      "requires": {
        "ansi-align": "^3.0.1",
        "camelcase": "^7.0.0",
        "chalk": "^5.0.1",
        "cli-boxes": "^3.0.0",
        "string-width": "^5.1.2",
        "type-fest": "^2.13.0",
        "widest-line": "^4.0.1",
        "wrap-ansi": "^8.0.1"
      },
      "dependencies": {
        "ansi-regex": {
          "version": "6.0.1",
          "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-6.0.1.tgz",
          "integrity": "sha512-n5M855fKb2SsfMIiFFoVrABHJC8QtHwVx+mHWP3QcEqBHYienj5dHSgjbxtC0WEZXYt4wcD6zrQElDPhFuZgfA==",
          "dev": true
        },
        "ansi-styles": {
          "version": "6.2.1",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-6.2.1.tgz",
          "integrity": "sha512-bN798gFfQX+viw3R7yrGWRqnrN2oRkEkUjjl4JNn4E8GxxbjtG3FbrEIIY3l8/hrwUwIeCZvi4QuOTP4MErVug==",
          "dev": true
        },
        "camelcase": {
          "version": "7.0.1",
          "resolved": "https://registry.npmjs.org/camelcase/-/camelcase-7.0.1.tgz",
          "integrity": "sha512-xlx1yCK2Oc1APsPXDL2LdlNP6+uu8OCDdhOBSVT279M/S+y75O30C2VuD8T2ogdePBBl7PfPF4504tnLgX3zfw==",
          "dev": true
        },
        "chalk": {
          "version": "5.2.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-5.2.0.tgz",
          "integrity": "sha512-ree3Gqw/nazQAPuJJEy+avdl7QfZMcUvmHIKgEZkGL+xOBzRvup5Hxo6LHuMceSxOabuJLJm5Yp/92R9eMmMvA==",
          "dev": true
        },
        "emoji-regex": {
          "version": "9.2.2",
          "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-9.2.2.tgz",
          "integrity": "sha512-L18DaJsXSUk2+42pv8mLs5jJT2hqFkFE4j21wOmgbUqsZ2hL72NsUU785g9RXgo3s0ZNgVl42TiHp3ZtOv/Vyg==",
          "dev": true
        },
        "string-width": {
          "version": "5.1.2",
          "resolved": "https://registry.npmjs.org/string-width/-/string-width-5.1.2.tgz",
          "integrity": "sha512-HnLOCR3vjcY8beoNLtcjZ5/nxn2afmME6lhrDrebokqMap+XbeW8n9TXpPDOqdGK5qcI3oT0GKTW6wC7EMiVqA==",
          "dev": true,
          "requires": {
            "eastasianwidth": "^0.2.0",
            "emoji-regex": "^9.2.2",
            "strip-ansi": "^7.0.1"
          }
        },
        "strip-ansi": {
          "version": "7.0.1",
          "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-7.0.1.tgz",
          "integrity": "sha512-cXNxvT8dFNRVfhVME3JAe98mkXDYN2O1l7jmcwMnOslDeESg1rF/OZMtK0nRAhiari1unG5cD4jG3rapUAkLbw==",
          "dev": true,
          "requires": {
            "ansi-regex": "^6.0.1"
          }
        },
        "type-fest": {
          "version": "2.19.0",
          "resolved": "https://registry.npmjs.org/type-fest/-/type-fest-2.19.0.tgz",
          "integrity": "sha512-RAH822pAdBgcNMAfWnCBU3CFZcfZ/i1eZjwFU/dsLKumyuuP3niueg2UAukXYF0E2AAoc82ZSSf9J0WQBinzHA==",
          "dev": true
        },
        "wrap-ansi": {
          "version": "8.0.1",
          "resolved": "https://registry.npmjs.org/wrap-ansi/-/wrap-ansi-8.0.1.tgz",
          "integrity": "sha512-QFF+ufAqhoYHvoHdajT/Po7KoXVBPXS2bgjIam5isfWJPfIOnQZ50JtUiVvCv/sjgacf3yRrt2ZKUZ/V4itN4g==",
          "dev": true,
          "requires": {
            "ansi-styles": "^6.1.0",
            "string-width": "^5.0.1",
            "strip-ansi": "^7.0.1"
          }
        }
      }
    },
    "brace-expansion": {
      "version": "1.1.11",
      "resolved": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.11.tgz",
      "integrity": "sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==",
      "dev": true,
      "requires": {
        "balanced-match": "^1.0.0",
        "concat-map": "0.0.1"
      }
    },
    "braces": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/braces/-/braces-3.0.2.tgz",
      "integrity": "sha512-b8um+L1RzM3WDSzvhm6gIz1yfTbBt6YTlcEKAvsmqCZZFw46z626lVj9j1yEPW33H5H+lBQpZMP1k8l+78Ha0A==",
      "dev": true,
      "requires": {
        "fill-range": "^7.0.1"
      }
    },
    "brorand": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/brorand/-/brorand-1.1.0.tgz",
      "integrity": "sha1-EsJe/kCkXjwyPrhnWgoM5XsiNx8="
    },
    "browser-process-hrtime": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/browser-process-hrtime/-/browser-process-hrtime-1.0.0.tgz",
      "integrity": "sha512-9o5UecI3GhkpM6DrXr69PblIuWxPKk9Y0jHBRhdocZ2y7YECBFCsHm79Pr3OyR2AvjhDkabFJaDJMYRazHgsow==",
      "dev": true
    },
    "browser-resolve": {
      "version": "1.11.3",
      "resolved": "https://registry.npmjs.org/browser-resolve/-/browser-resolve-1.11.3.tgz",
      "integrity": "sha512-exDi1BYWB/6raKHmDTCicQfTkqwN5fioMFV4j8BsfMU4R2DK/QfZfK7kOVkmWCNANf0snkBzqGqAJBao9gZMdQ==",
      "dev": true,
      "requires": {
        "resolve": "1.1.7"
      },
      "dependencies": {
        "resolve": {
          "version": "1.1.7",
          "resolved": "https://registry.npmjs.org/resolve/-/resolve-1.1.7.tgz",
          "integrity": "sha1-IDEU2CrSxe2ejgQRs5ModeiJ6Xs=",
          "dev": true
        }
      }
    },
    "browserslist": {
      "version": "4.16.6",
      "resolved": "https://registry.npmjs.org/browserslist/-/browserslist-4.16.6.tgz",
      "integrity": "sha512-Wspk/PqO+4W9qp5iUTJsa1B/QrYn1keNCcEP5OvP7WBwT4KaDly0uONYmC6Xa3Z5IqnUgS0KcgLYu1l74x0ZXQ==",
      "dev": true,
      "requires": {
        "caniuse-lite": "^1.0.30001219",
        "colorette": "^1.2.2",
        "electron-to-chromium": "^1.3.723",
        "escalade": "^3.1.1",
        "node-releases": "^1.1.71"
      }
    },
    "bs-logger": {
      "version": "0.2.6",
      "resolved": "https://registry.npmjs.org/bs-logger/-/bs-logger-0.2.6.tgz",
      "integrity": "sha512-pd8DCoxmbgc7hyPKOvxtqNcjYoOsABPQdcCUjGp3d42VR2CX1ORhk2A87oqqu5R1kk+76nsxZupkmyd+MVtCog==",
      "dev": true,
      "requires": {
        "fast-json-stable-stringify": "2.x"
      }
    },
    "bser": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/bser/-/bser-2.1.1.tgz",
      "integrity": "sha512-gQxTNE/GAfIIrmHLUE3oJyp5FO6HRBfhjnw4/wMmA63ZGDJnWBmgY/lyQBpnDUkGmAhbSe39tx2d/iTOAfglwQ==",
      "dev": true,
      "requires": {
        "node-int64": "^0.4.0"
      }
    },
    "buffer-from": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/buffer-from/-/buffer-from-1.1.1.tgz",
      "integrity": "sha512-MQcXEUbCKtEo7bhqEs6560Hyd4XaovZlO/k9V3hjVUF/zwW7KBVdSK4gIt/bzwS9MbR5qob+F5jusZsb0YQK2A==",
      "dev": true
    },
    "bytes": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/bytes/-/bytes-3.0.0.tgz",
      "integrity": "sha512-pMhOfFDPiv9t5jjIXkHosWmkSyQbvsgEVNkz0ERHbuLh2T/7j4Mqqpz523Fe8MVY89KC6Sh/QfS2sM+SjgFDcw==",
      "dev": true
    },
    "cache-base": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/cache-base/-/cache-base-1.0.1.tgz",
      "integrity": "sha512-AKcdTnFSWATd5/GCPRxr2ChwIJ85CeyrEyjRHlKxQ56d4XJMGym0uAiKn0xbLOGOl3+yRpOTi484dVCEc5AUzQ==",
      "dev": true,
      "requires": {
        "collection-visit": "^1.0.0",
        "component-emitter": "^1.2.1",
        "get-value": "^2.0.6",
        "has-value": "^1.0.0",
        "isobject": "^3.0.1",
        "set-value": "^2.0.0",
        "to-object-path": "^0.3.0",
        "union-value": "^1.0.0",
        "unset-value": "^1.0.0"
      }
    },
    "call-bind": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/call-bind/-/call-bind-1.0.2.tgz",
      "integrity": "sha512-7O+FbCihrB5WGbFYesctwmTKae6rOiIzmz1icreWJ+0aA7LJfuqhEso2T9ncpcFtzMQtzXf2QGGueWJGTYsqrA==",
      "dev": true,
      "requires": {
        "function-bind": "^1.1.1",
        "get-intrinsic": "^1.0.2"
      }
    },
    "callsites": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/callsites/-/callsites-3.1.0.tgz",
      "integrity": "sha512-P8BjAsXvZS+VIDUI11hHCQEv74YT67YUi5JJFNWIqL235sBmjX4+qx9Muvls5ivyNENctx46xQLQ3aTuE7ssaQ==",
      "dev": true
    },
    "camelcase": {
      "version": "5.3.1",
      "resolved": "https://registry.npmjs.org/camelcase/-/camelcase-5.3.1.tgz",
      "integrity": "sha512-L28STB170nwWS63UjtlEOE3dldQApaJXZkOI1uMFfzf3rRuPegHaHesyee+YxQ+W6SvRDQV6UrdOdRiR153wJg==",
      "dev": true
    },
    "caniuse-lite": {
      "version": "1.0.30001237",
      "resolved": "https://registry.npmjs.org/caniuse-lite/-/caniuse-lite-1.0.30001237.tgz",
      "integrity": "sha512-pDHgRndit6p1NR2GhzMbQ6CkRrp4VKuSsqbcLeOQppYPKOYkKT/6ZvZDvKJUqcmtyWIAHuZq3SVS2vc1egCZzw==",
      "dev": true
    },
    "capital-case": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/capital-case/-/capital-case-1.0.4.tgz",
      "integrity": "sha512-ds37W8CytHgwnhGGTi88pcPyR15qoNkOpYwmMMfnWqqWgESapLqvDx6huFjQ5vqWSn2Z06173XNA7LtMOeUh1A==",
      "dev": true,
      "requires": {
        "no-case": "^3.0.4",
        "tslib": "^2.0.3",
        "upper-case-first": "^2.0.2"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.0",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
          "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg==",
          "dev": true
        }
      }
    },
    "capture-exit": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/capture-exit/-/capture-exit-2.0.0.tgz",
      "integrity": "sha512-PiT/hQmTonHhl/HFGN+Lx3JJUznrVYJ3+AQsnthneZbvW7x+f08Tk7yLJTLEOUvBTbduLeeBkxEaYXUOUrRq6g==",
      "dev": true,
      "requires": {
        "rsvp": "^4.8.4"
      }
    },
    "caseless": {
      "version": "0.12.0",
      "resolved": "https://registry.npmjs.org/caseless/-/caseless-0.12.0.tgz",
      "integrity": "sha1-G2gcIf+EAzyCZUMJBolCDRhxUdw=",
      "dev": true
    },
    "chalk": {
      "version": "2.4.2",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-2.4.2.tgz",
      "integrity": "sha512-Mti+f9lpJNcwF4tWV8/OrTTtF1gZi+f8FqlyAdouralcFWFQWF2+NgCHShjkCb+IFBLq9buZwE1xckQU4peSuQ==",
      "dev": true,
      "requires": {
        "ansi-styles": "^3.2.1",
        "escape-string-regexp": "^1.0.5",
        "supports-color": "^5.3.0"
      }
    },
    "chalk-template": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/chalk-template/-/chalk-template-0.4.0.tgz",
      "integrity": "sha512-/ghrgmhfY8RaSdeo43hNXxpoHAtxdbskUHjPpfqUWGttFgycUhYPGx3YZBCnUCvOa7Doivn1IZec3DEGFoMgLg==",
      "dev": true,
      "requires": {
        "chalk": "^4.1.2"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "4.1.2",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-4.1.2.tgz",
          "integrity": "sha512-oKnbhFyRIXpUuez8iBMmyEa4nbj4IOQyuhc/wy9kY7/WVPcwIO9VA668Pu8RkO7+0G76SLROeyw9CpQ061i4mA==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "chardet": {
      "version": "0.7.0",
      "resolved": "https://registry.npmjs.org/chardet/-/chardet-0.7.0.tgz",
      "integrity": "sha512-mT8iDcrh03qDGRRmoA2hmBJnxpllMR+0/0qlzjqZES6NdiWDcZkCNAk4rPFZ9Q85r27unkiNNg8ZOiwZXBHwcA==",
      "dev": true
    },
    "ci-info": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ci-info/-/ci-info-2.0.0.tgz",
      "integrity": "sha512-5tK7EtrZ0N+OLFMthtqOj4fI2Jeb88C4CAZPu25LDVUgXJ0A3Js4PMGqrn0JU1W0Mh1/Z8wZzYPxqUrXeBboCQ==",
      "dev": true
    },
    "class-transformer": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/class-transformer/-/class-transformer-0.4.0.tgz",
      "integrity": "sha512-ETWD/H2TbWbKEi7m9N4Km5+cw1hNcqJSxlSYhsLsNjQzWWiZIYA1zafxpK9PwVfaZ6AqR5rrjPVUBGESm5tQUA=="
    },
    "class-utils": {
      "version": "0.3.6",
      "resolved": "https://registry.npmjs.org/class-utils/-/class-utils-0.3.6.tgz",
      "integrity": "sha512-qOhPa/Fj7s6TY8H8esGu5QNpMMQxz79h+urzrNYN6mn+9BnxlDGf5QZ+XeCDsxSjPqsSR56XOZOJmpeurnLMeg==",
      "dev": true,
      "requires": {
        "arr-union": "^3.1.0",
        "define-property": "^0.2.5",
        "isobject": "^3.0.0",
        "static-extend": "^0.1.1"
      },
      "dependencies": {
        "define-property": {
          "version": "0.2.5",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
          "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
          "dev": true,
          "requires": {
            "is-descriptor": "^0.1.0"
          }
        },
        "is-accessor-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
          "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "is-data-descriptor": {
          "version": "0.1.4",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
          "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "is-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
          "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
          "dev": true,
          "requires": {
            "is-accessor-descriptor": "^0.1.6",
            "is-data-descriptor": "^0.1.4",
            "kind-of": "^5.0.0"
          }
        },
        "kind-of": {
          "version": "5.1.0",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
          "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
          "dev": true
        }
      }
    },
    "class-validator": {
      "version": "0.14.0",
      "resolved": "https://registry.npmjs.org/class-validator/-/class-validator-0.14.0.tgz",
      "integrity": "sha512-ct3ltplN8I9fOwUd8GrP8UQixwff129BkEtuWDKL5W45cQuLd19xqmTLu5ge78YDm/fdje6FMt0hGOhl0lii3A==",
      "requires": {
        "@types/validator": "^13.7.10",
        "libphonenumber-js": "^1.10.14",
        "validator": "^13.7.0"
      }
    },
    "cli-boxes": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/cli-boxes/-/cli-boxes-3.0.0.tgz",
      "integrity": "sha512-/lzGpEWL/8PfI0BmBOPRwp0c/wFNX1RdUML3jK/RcSBA9T8mZDdQpqYBKtCFTOfQbwPqWEOpjqW+Fnayc0969g==",
      "dev": true
    },
    "cli-cursor": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/cli-cursor/-/cli-cursor-3.1.0.tgz",
      "integrity": "sha512-I/zHAwsKf9FqGoXM4WWRACob9+SNukZTd94DWF57E4toouRulbCxcUh6RKUEOQlYTHJnzkPMySvPNaaSLNfLZw==",
      "dev": true,
      "requires": {
        "restore-cursor": "^3.1.0"
      }
    },
    "cli-table3": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/cli-table3/-/cli-table3-0.6.0.tgz",
      "integrity": "sha512-gnB85c3MGC7Nm9I/FkiasNBOKjOiO1RNuXXarQms37q4QMpWdlbBgD/VnOStA2faG1dpXMv31RFApjX1/QdgWQ==",
      "dev": true,
      "requires": {
        "colors": "^1.1.2",
        "object-assign": "^4.1.0",
        "string-width": "^4.2.0"
      }
    },
    "cli-width": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/cli-width/-/cli-width-3.0.0.tgz",
      "integrity": "sha512-FxqpkPPwu1HjuN93Omfm4h8uIanXofW0RxVEW3k5RKx+mJJYSthzNhp32Kzxxy3YAEZ/Dc/EWN1vZRY0+kOhbw==",
      "dev": true
    },
    "clipboardy": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/clipboardy/-/clipboardy-3.0.0.tgz",
      "integrity": "sha512-Su+uU5sr1jkUy1sGRpLKjKrvEOVXgSgiSInwa/qeID6aJ07yh+5NWc3h2QfjHjBnfX4LhtFcuAWKUsJ3r+fjbg==",
      "dev": true,
      "requires": {
        "arch": "^2.2.0",
        "execa": "^5.1.1",
        "is-wsl": "^2.2.0"
      },
      "dependencies": {
        "cross-spawn": {
          "version": "7.0.3",
          "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-7.0.3.tgz",
          "integrity": "sha512-iRDPJKUPVEND7dHPO8rkbOnPpyDygcDFtWjpeWNCgy8WP2rXcxXL8TskReQl6OrB2G7+UJrags1q15Fudc7G6w==",
          "dev": true,
          "requires": {
            "path-key": "^3.1.0",
            "shebang-command": "^2.0.0",
            "which": "^2.0.1"
          }
        },
        "execa": {
          "version": "5.1.1",
          "resolved": "https://registry.npmjs.org/execa/-/execa-5.1.1.tgz",
          "integrity": "sha512-8uSpZZocAZRBAPIEINJj3Lo9HyGitllczc27Eh5YYojjMFMn8yHMDMaUHE2Jqfq05D/wucwI4JGURyXt1vchyg==",
          "dev": true,
          "requires": {
            "cross-spawn": "^7.0.3",
            "get-stream": "^6.0.0",
            "human-signals": "^2.1.0",
            "is-stream": "^2.0.0",
            "merge-stream": "^2.0.0",
            "npm-run-path": "^4.0.1",
            "onetime": "^5.1.2",
            "signal-exit": "^3.0.3",
            "strip-final-newline": "^2.0.0"
          }
        },
        "get-stream": {
          "version": "6.0.1",
          "resolved": "https://registry.npmjs.org/get-stream/-/get-stream-6.0.1.tgz",
          "integrity": "sha512-ts6Wi+2j3jQjqi70w5AlN8DFnkSwC+MqmxEzdEALB2qXZYV3X/b1CTfgPLGJNMeAWxdPfU8FO1ms3NUfaHCPYg==",
          "dev": true
        },
        "human-signals": {
          "version": "2.1.0",
          "resolved": "https://registry.npmjs.org/human-signals/-/human-signals-2.1.0.tgz",
          "integrity": "sha512-B4FFZ6q/T2jhhksgkbEW3HBvWIfDW85snkQgawt07S7J5QXTk6BkNV+0yAeZrM5QpMAdYlocGoljn0sJ/WQkFw==",
          "dev": true
        },
        "path-key": {
          "version": "3.1.1",
          "resolved": "https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz",
          "integrity": "sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==",
          "dev": true
        },
        "shebang-command": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/shebang-command/-/shebang-command-2.0.0.tgz",
          "integrity": "sha512-kHxr2zZpYtdmrN1qDjrrX/Z1rR1kG8Dx+gkpK1G4eXmvXswmcE1hTWBWYUzlraYw1/yZp6YuDY77YtvbN0dmDA==",
          "dev": true,
          "requires": {
            "shebang-regex": "^3.0.0"
          }
        },
        "shebang-regex": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/shebang-regex/-/shebang-regex-3.0.0.tgz",
          "integrity": "sha512-7++dFhtcx3353uBaq8DDR4NuxBetBzC7ZQOhmTQInHEd6bSrXdiEyzCvG07Z44UYdLShWUyXt5M/yhz8ekcb1A==",
          "dev": true
        },
        "which": {
          "version": "2.0.2",
          "resolved": "https://registry.npmjs.org/which/-/which-2.0.2.tgz",
          "integrity": "sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==",
          "dev": true,
          "requires": {
            "isexe": "^2.0.0"
          }
        }
      }
    },
    "cliui": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/cliui/-/cliui-6.0.0.tgz",
      "integrity": "sha512-t6wbgtoCXvAzst7QgXxJYqPt0usEfbgQdftEPbLL/cvv6HPE5VgvqCuAIDR0NgU52ds6rFwqrgakNLrHEjCbrQ==",
      "dev": true,
      "requires": {
        "string-width": "^4.2.0",
        "strip-ansi": "^6.0.0",
        "wrap-ansi": "^6.2.0"
      },
      "dependencies": {
        "strip-ansi": {
          "version": "6.0.0",
          "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
          "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
          "dev": true,
          "requires": {
            "ansi-regex": "^5.0.0"
          }
        }
      }
    },
    "co": {
      "version": "4.6.0",
      "resolved": "https://registry.npmjs.org/co/-/co-4.6.0.tgz",
      "integrity": "sha1-bqa989hTrlTMuOR7+gvz+QMfsYQ=",
      "dev": true
    },
    "collect-v8-coverage": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/collect-v8-coverage/-/collect-v8-coverage-1.0.1.tgz",
      "integrity": "sha512-iBPtljfCNcTKNAto0KEtDfZ3qzjJvqE3aTGZsbhjSBlorqpXJlaWWtPO35D+ZImoC3KWejX64o+yPGxhWSTzfg==",
      "dev": true
    },
    "collection-visit": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/collection-visit/-/collection-visit-1.0.0.tgz",
      "integrity": "sha1-S8A3PBZLwykbTTaMgpzxqApZ3KA=",
      "dev": true,
      "requires": {
        "map-visit": "^1.0.0",
        "object-visit": "^1.0.0"
      }
    },
    "color-convert": {
      "version": "1.9.3",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-1.9.3.tgz",
      "integrity": "sha512-QfAUtd+vFdAtFQcC8CCyYt1fYWxSqAiK2cSD6zDB8N3cpsEBAvRxp9zOGg6G/SHHJYAT88/az/IuDGALsNVbGg==",
      "dev": true,
      "requires": {
        "color-name": "1.1.3"
      }
    },
    "color-name": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.3.tgz",
      "integrity": "sha1-p9BVi9icQveV3UIyj3QIMcpTvCU=",
      "dev": true
    },
    "colorette": {
      "version": "1.2.2",
      "resolved": "https://registry.npmjs.org/colorette/-/colorette-1.2.2.tgz",
      "integrity": "sha512-MKGMzyfeuutC/ZJ1cba9NqcNpfeqMUcYmyF1ZFY6/Cn7CNSAKx6a+s48sqLqyAiZuaP2TcqMhoo+dlwFnVxT9w==",
      "dev": true
    },
    "colors": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/colors/-/colors-1.4.0.tgz",
      "integrity": "sha512-a+UqTh4kgZg/SlGvfbzDHpgRu7AAQOmmqRHJnxhRZICKFUT91brVhNNt58CMWU9PsBbv3PDCZUHbVxuDiH2mtA==",
      "dev": true
    },
    "combined-stream": {
      "version": "1.0.8",
      "resolved": "https://registry.npmjs.org/combined-stream/-/combined-stream-1.0.8.tgz",
      "integrity": "sha512-FQN4MRfuJeHf7cBbBMJFXhKSDq+2kAArBlmRBvcvFE5BB1HZKXtSFASDhdlz9zOYwxh8lDdnvmMOe/+5cdoEdg==",
      "requires": {
        "delayed-stream": "~1.0.0"
      }
    },
    "commander": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/commander/-/commander-5.1.0.tgz",
      "integrity": "sha512-P0CysNDQ7rtVw4QIQtm+MRxV66vKFSvlsQvGYXZWR3qFU0jlMKHZZZgw8e+8DSah4UDKMqnknRDQz+xuQXQ/Zg==",
      "dev": true
    },
    "commondir": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/commondir/-/commondir-1.0.1.tgz",
      "integrity": "sha1-3dgA2gxmEnOTzKWVDqloo6rxJTs=",
      "dev": true
    },
    "component-emitter": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/component-emitter/-/component-emitter-1.3.0.tgz",
      "integrity": "sha512-Rd3se6QB+sO1TwqZjscQrurpEPIfO0/yYnSin6Q/rD3mOutHvUrCAhJub3r90uNb+SESBuE0QYoB90YdfatsRg==",
      "dev": true
    },
    "compressible": {
      "version": "2.0.18",
      "resolved": "https://registry.npmjs.org/compressible/-/compressible-2.0.18.tgz",
      "integrity": "sha512-AF3r7P5dWxL8MxyITRMlORQNaOA2IkAFaTr4k7BUumjPtRpGDTZpl0Pb1XCO6JeDCBdp126Cgs9sMxqSjgYyRg==",
      "dev": true,
      "requires": {
        "mime-db": ">= 1.43.0 < 2"
      }
    },
    "compression": {
      "version": "1.7.4",
      "resolved": "https://registry.npmjs.org/compression/-/compression-1.7.4.tgz",
      "integrity": "sha512-jaSIDzP9pZVS4ZfQ+TzvtiWhdpFhE2RDHz8QJkpX9SIpLq88VueF5jJw6t+6CUQcAoA6t+x89MLrWAqpfDE8iQ==",
      "dev": true,
      "requires": {
        "accepts": "~1.3.5",
        "bytes": "3.0.0",
        "compressible": "~2.0.16",
        "debug": "2.6.9",
        "on-headers": "~1.0.2",
        "safe-buffer": "5.1.2",
        "vary": "~1.1.2"
      },
      "dependencies": {
        "debug": {
          "version": "2.6.9",
          "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
          "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
          "dev": true,
          "requires": {
            "ms": "2.0.0"
          }
        },
        "ms": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
          "integrity": "sha512-Tpp60P6IUJDTuOq/5Z8cdskzJujfwqfOTkrwIwj7IRISpnkJnT6SyJ4PCPnGMoFjC9ddhal5KVIYtAt97ix05A==",
          "dev": true
        }
      }
    },
    "concat-map": {
      "version": "0.0.1",
      "resolved": "https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz",
      "integrity": "sha1-2Klr13/Wjfd5OnMDajug1UBdR3s=",
      "dev": true
    },
    "contains-path": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/contains-path/-/contains-path-0.1.0.tgz",
      "integrity": "sha1-/ozxhP9mcLa67wGp1IYaXL7EEgo=",
      "dev": true
    },
    "content-disposition": {
      "version": "0.5.2",
      "resolved": "https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.2.tgz",
      "integrity": "sha512-kRGRZw3bLlFISDBgwTSA1TMBFN6J6GWDeubmDE3AF+3+yXL8hTWv8r5rkLbqYXY4RjPk/EzHnClI3zQf1cFmHA==",
      "dev": true
    },
    "convert-source-map": {
      "version": "1.7.0",
      "resolved": "https://registry.npmjs.org/convert-source-map/-/convert-source-map-1.7.0.tgz",
      "integrity": "sha512-4FJkXzKXEDB1snCFZlLP4gpC3JILicCpGbzG9f9G7tGqGCzETQ2hWPrcinA9oU4wtf2biUaEH5065UnMeR33oA==",
      "dev": true,
      "requires": {
        "safe-buffer": "~5.1.1"
      }
    },
    "copy-descriptor": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/copy-descriptor/-/copy-descriptor-0.1.1.tgz",
      "integrity": "sha1-Z29us8OZl8LuGsOpJP1hJHSPV40=",
      "dev": true
    },
    "core-util-is": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz",
      "integrity": "sha1-tf1UIgqivFq1eqtxQMlAdUUDwac=",
      "dev": true
    },
    "create-require": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/create-require/-/create-require-1.1.1.tgz",
      "integrity": "sha512-dcKFX3jn0MpIaXjisoRvexIJVEKzaq7z2rZKxf+MSr9TkdmHmsU4m2lcLojrj/FHl8mk5VxMmYA+ftRkP/3oKQ==",
      "dev": true
    },
    "cross-fetch": {
      "version": "3.1.5",
      "resolved": "https://registry.npmjs.org/cross-fetch/-/cross-fetch-3.1.5.tgz",
      "integrity": "sha512-lvb1SBsI0Z7GDwmuid+mU3kWVBwTVUbe7S0H52yaaAdQOXq2YktTCZdlAcNKFzE6QtRz0snpw9bNiPeOIkkQvw==",
      "requires": {
        "node-fetch": "2.6.7"
      }
    },
    "cross-spawn": {
      "version": "6.0.5",
      "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-6.0.5.tgz",
      "integrity": "sha512-eTVLrBSt7fjbDygz805pMnstIs2VTBNkRm0qxZd+M7A5XDdxVRWO5MxGBXZhjY4cqLYLdtrGqRf8mBPmzwSpWQ==",
      "dev": true,
      "requires": {
        "nice-try": "^1.0.4",
        "path-key": "^2.0.1",
        "semver": "^5.5.0",
        "shebang-command": "^1.2.0",
        "which": "^1.2.9"
      },
      "dependencies": {
        "semver": {
          "version": "5.7.1",
          "resolved": "https://registry.npmjs.org/semver/-/semver-5.7.1.tgz",
          "integrity": "sha512-sauaDf/PZdVgrLTNYHRtpXa1iRiKcaebiKQ1BJdpQlWH2lCvexQdX55snPFyK7QzpudqbCI0qXFfOasHdyNDGQ==",
          "dev": true
        }
      }
    },
    "cssom": {
      "version": "0.4.4",
      "resolved": "https://registry.npmjs.org/cssom/-/cssom-0.4.4.tgz",
      "integrity": "sha512-p3pvU7r1MyyqbTk+WbNJIgJjG2VmTIaB10rI93LzVPrmDJKkzKYMtxxyAvQXR/NS6otuzveI7+7BBq3SjBS2mw==",
      "dev": true
    },
    "cssstyle": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/cssstyle/-/cssstyle-2.3.0.tgz",
      "integrity": "sha512-AZL67abkUzIuvcHqk7c09cezpGNcxUxU4Ioi/05xHk4DQeTkWmGYftIE6ctU6AEt+Gn4n1lDStOtj7FKycP71A==",
      "dev": true,
      "requires": {
        "cssom": "~0.3.6"
      },
      "dependencies": {
        "cssom": {
          "version": "0.3.8",
          "resolved": "https://registry.npmjs.org/cssom/-/cssom-0.3.8.tgz",
          "integrity": "sha512-b0tGHbfegbhPJpxpiBPU2sCkigAqtM9O121le6bbOlgyV+NyGyCmVfJ6QW9eRjz8CpNfWEOYBIMIGRYkLwsIYg==",
          "dev": true
        }
      }
    },
    "d": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/d/-/d-1.0.1.tgz",
      "integrity": "sha512-m62ShEObQ39CfralilEQRjH6oAMtNCV1xJyEx5LpRYUVN+EviphDgUc/F3hnYbADmkiNs67Y+3ylmlG7Lnu+FA==",
      "dev": true,
      "requires": {
        "es5-ext": "^0.10.50",
        "type": "^1.0.1"
      }
    },
    "dashdash": {
      "version": "1.14.1",
      "resolved": "https://registry.npmjs.org/dashdash/-/dashdash-1.14.1.tgz",
      "integrity": "sha1-hTz6D3y+L+1d4gMmuN1YEDX24vA=",
      "dev": true,
      "requires": {
        "assert-plus": "^1.0.0"
      }
    },
    "data-urls": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/data-urls/-/data-urls-1.1.0.tgz",
      "integrity": "sha512-YTWYI9se1P55u58gL5GkQHW4P6VJBJ5iBT+B5a7i2Tjadhv52paJG0qHX4A0OR6/t52odI64KP2YvFpkDOi3eQ==",
      "dev": true,
      "requires": {
        "abab": "^2.0.0",
        "whatwg-mimetype": "^2.2.0",
        "whatwg-url": "^7.0.0"
      }
    },
    "debug": {
      "version": "4.3.1",
      "resolved": "https://registry.npmjs.org/debug/-/debug-4.3.1.tgz",
      "integrity": "sha512-doEwdvm4PCeK4K3RQN2ZC2BYUBaxwLARCqZmMjtF8a51J2Rb0xpVloFRnCODwqjpwnAoao4pelN8l3RJdv3gRQ==",
      "dev": true,
      "requires": {
        "ms": "2.1.2"
      }
    },
    "decamelize": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/decamelize/-/decamelize-1.2.0.tgz",
      "integrity": "sha1-9lNNFRSCabIDUue+4m9QH5oZEpA=",
      "dev": true
    },
    "decode-uri-component": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/decode-uri-component/-/decode-uri-component-0.2.0.tgz",
      "integrity": "sha1-6zkTMzRYd1y4TNGh+uBiEGu4dUU=",
      "dev": true
    },
    "deep-extend": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/deep-extend/-/deep-extend-0.6.0.tgz",
      "integrity": "sha512-LOHxIOaPYdHlJRtCQfDIVZtfw/ufM8+rVj649RIHzcm/vGwQRXFt6OPqIFWsm2XEMrNIEtWR64sY1LEKD2vAOA==",
      "dev": true
    },
    "deep-is": {
      "version": "0.1.3",
      "resolved": "https://registry.npmjs.org/deep-is/-/deep-is-0.1.3.tgz",
      "integrity": "sha1-s2nW+128E+7PUk+RsHD+7cNXzzQ=",
      "dev": true
    },
    "deepmerge": {
      "version": "4.2.2",
      "resolved": "https://registry.npmjs.org/deepmerge/-/deepmerge-4.2.2.tgz",
      "integrity": "sha512-FJ3UgI4gIl+PHZm53knsuSFpE+nESMr7M4v9QcgB7S63Kj/6WqMiFQJpBBYz1Pt+66bZpP3Q7Lye0Oo9MPKEdg==",
      "dev": true
    },
    "define-properties": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/define-properties/-/define-properties-1.1.3.tgz",
      "integrity": "sha512-3MqfYKj2lLzdMSf8ZIZE/V+Zuy+BgD6f164e8K2w7dgnpKArBDerGYpM46IYYcjnkdPNMjPk9A6VFB8+3SKlXQ==",
      "dev": true,
      "requires": {
        "object-keys": "^1.0.12"
      }
    },
    "define-property": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/define-property/-/define-property-2.0.2.tgz",
      "integrity": "sha512-jwK2UV4cnPpbcG7+VRARKTZPUWowwXA8bzH5NP6ud0oeAxyYPuGZUAC7hMugpCdz4BeSZl2Dl9k66CHJ/46ZYQ==",
      "dev": true,
      "requires": {
        "is-descriptor": "^1.0.2",
        "isobject": "^3.0.1"
      }
    },
    "delayed-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delayed-stream/-/delayed-stream-1.0.0.tgz",
      "integrity": "sha1-3zrhmayt+31ECqrgsp4icrJOxhk="
    },
    "detect-newline": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/detect-newline/-/detect-newline-3.1.0.tgz",
      "integrity": "sha512-TLz+x/vEXm/Y7P7wn1EJFNLxYpUD4TgMosxY6fAVJUnJMbupHBOncxyWUG9OpTaH9EBD7uFI5LfEgmMOc54DsA==",
      "dev": true
    },
    "diff": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/diff/-/diff-4.0.2.tgz",
      "integrity": "sha512-58lmxKSA4BNyLz+HHMUzlOEpg09FV+ev6ZMe3vJihgdxzgcwZ8VoEEPmALCZG9LmqfVoNMMKpttIYTVG6uDY7A==",
      "dev": true
    },
    "diff-sequences": {
      "version": "25.2.6",
      "resolved": "https://registry.npmjs.org/diff-sequences/-/diff-sequences-25.2.6.tgz",
      "integrity": "sha512-Hq8o7+6GaZeoFjtpgvRBUknSXNeJiCx7V9Fr94ZMljNiCr9n9L8H8aJqgWOQiDDGdyn29fRNcDdRVJ5fdyihfg==",
      "dev": true
    },
    "doctrine": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/doctrine/-/doctrine-3.0.0.tgz",
      "integrity": "sha512-yS+Q5i3hBf7GBkd4KG8a7eBNNWNGLTaEwwYWUijIYM7zrlYDM0BFXHjjPWlWZ1Rg7UaddZeIDmi9jF3HmqiQ2w==",
      "dev": true,
      "requires": {
        "esutils": "^2.0.2"
      }
    },
    "domexception": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/domexception/-/domexception-1.0.1.tgz",
      "integrity": "sha512-raigMkn7CJNNo6Ihro1fzG7wr3fHuYVytzquZKX5n0yizGsTcYgzdIUwj1X9pK0VvjeihV+XiclP+DjwbsSKug==",
      "dev": true,
      "requires": {
        "webidl-conversions": "^4.0.2"
      }
    },
    "duration": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/duration/-/duration-0.2.2.tgz",
      "integrity": "sha512-06kgtea+bGreF5eKYgI/36A6pLXggY7oR4p1pq4SmdFBn1ReOL5D8RhG64VrqfTTKNucqqtBAwEj8aB88mcqrg==",
      "dev": true,
      "requires": {
        "d": "1",
        "es5-ext": "~0.10.46"
      }
    },
    "durations": {
      "version": "3.4.2",
      "resolved": "https://registry.npmjs.org/durations/-/durations-3.4.2.tgz",
      "integrity": "sha512-V/lf7y33dGaypZZetVI1eu7BmvkbC4dItq12OElLRpKuaU5JxQstV2zHwLv8P7cNbQ+KL1WD80zMCTx5dNC4dg==",
      "dev": true
    },
    "eastasianwidth": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/eastasianwidth/-/eastasianwidth-0.2.0.tgz",
      "integrity": "sha512-I88TYZWc9XiYHRQ4/3c5rjjfgkjhLyW2luGIheGERbNQ6OY7yTybanSpDXZa8y7VUP9YmDcYa+eyq4ca7iLqWA==",
      "dev": true
    },
    "ecc-jsbn": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.2.tgz",
      "integrity": "sha1-OoOpBOVDUyh4dMVkt1SThoSamMk=",
      "dev": true,
      "requires": {
        "jsbn": "~0.1.0",
        "safer-buffer": "^2.1.0"
      }
    },
    "electron-to-chromium": {
      "version": "1.3.752",
      "resolved": "https://registry.npmjs.org/electron-to-chromium/-/electron-to-chromium-1.3.752.tgz",
      "integrity": "sha512-2Tg+7jSl3oPxgsBsWKh5H83QazTkmWG/cnNwJplmyZc7KcN61+I10oUgaXSVk/NwfvN3BdkKDR4FYuRBQQ2v0A==",
      "dev": true
    },
    "elliptic": {
      "version": "6.5.4",
      "resolved": "https://registry.npmjs.org/elliptic/-/elliptic-6.5.4.tgz",
      "integrity": "sha512-iLhC6ULemrljPZb+QutR5TQGB+pdW6KGD5RSegS+8sorOZT+rdQFbsQFJgvN3eRqNALqJer4oQ16YvJHlU8hzQ==",
      "requires": {
        "bn.js": "^4.11.9",
        "brorand": "^1.1.0",
        "hash.js": "^1.0.0",
        "hmac-drbg": "^1.0.1",
        "inherits": "^2.0.4",
        "minimalistic-assert": "^1.0.1",
        "minimalistic-crypto-utils": "^1.0.1"
      },
      "dependencies": {
        "bn.js": {
          "version": "4.12.0",
          "resolved": "https://registry.npmjs.org/bn.js/-/bn.js-4.12.0.tgz",
          "integrity": "sha512-c98Bf3tPniI+scsdk237ku1Dc3ujXQTSgyiPUDEOe7tRkhrqridvh8klBv0HCEso1OLOYcHuCv/cS6DNxKH+ZA=="
        }
      }
    },
    "email-addresses": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/email-addresses/-/email-addresses-3.1.0.tgz",
      "integrity": "sha512-k0/r7GrWVL32kZlGwfPNgB2Y/mMXVTq/decgLczm/j34whdaspNrZO8CnXPf1laaHxI6ptUlsnAxN+UAPw+fzg==",
      "dev": true
    },
    "emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "dev": true
    },
    "end-of-stream": {
      "version": "1.4.4",
      "resolved": "https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.4.4.tgz",
      "integrity": "sha512-+uw1inIHVPQoaVuHzRyXd21icM+cnt4CzD5rW+NC1wjOUSTOs+Te7FOv7AhN7vS9x/oIyhLP5PR1H+phQAHu5Q==",
      "dev": true,
      "requires": {
        "once": "^1.4.0"
      }
    },
    "error-ex": {
      "version": "1.3.2",
      "resolved": "https://registry.npmjs.org/error-ex/-/error-ex-1.3.2.tgz",
      "integrity": "sha512-7dFHNmqeFSEt2ZBsCriorKnn3Z2pj+fd9kmI6QoWw4//DL+icEBfc0U7qJCisqrTsKTjw4fNFy2pW9OqStD84g==",
      "dev": true,
      "requires": {
        "is-arrayish": "^0.2.1"
      }
    },
    "error-stack-parser": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/error-stack-parser/-/error-stack-parser-2.0.6.tgz",
      "integrity": "sha512-d51brTeqC+BHlwF0BhPtcYgF5nlzf9ZZ0ZIUQNZpc9ZB9qw5IJ2diTrBY9jlCJkTLITYPjmiX6OWCwH+fuyNgQ==",
      "dev": true,
      "requires": {
        "stackframe": "^1.1.1"
      }
    },
    "es-abstract": {
      "version": "1.18.3",
      "resolved": "https://registry.npmjs.org/es-abstract/-/es-abstract-1.18.3.tgz",
      "integrity": "sha512-nQIr12dxV7SSxE6r6f1l3DtAeEYdsGpps13dR0TwJg1S8gyp4ZPgy3FZcHBgbiQqnoqSTb+oC+kO4UQ0C/J8vw==",
      "dev": true,
      "requires": {
        "call-bind": "^1.0.2",
        "es-to-primitive": "^1.2.1",
        "function-bind": "^1.1.1",
        "get-intrinsic": "^1.1.1",
        "has": "^1.0.3",
        "has-symbols": "^1.0.2",
        "is-callable": "^1.2.3",
        "is-negative-zero": "^2.0.1",
        "is-regex": "^1.1.3",
        "is-string": "^1.0.6",
        "object-inspect": "^1.10.3",
        "object-keys": "^1.1.1",
        "object.assign": "^4.1.2",
        "string.prototype.trimend": "^1.0.4",
        "string.prototype.trimstart": "^1.0.4",
        "unbox-primitive": "^1.0.1"
      }
    },
    "es-to-primitive": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/es-to-primitive/-/es-to-primitive-1.2.1.tgz",
      "integrity": "sha512-QCOllgZJtaUo9miYBcLChTUaHNjJF3PYs1VidD7AwiEj1kYxKeQTctLAezAOH5ZKRH0g2IgPn6KwB4IT8iRpvA==",
      "dev": true,
      "requires": {
        "is-callable": "^1.1.4",
        "is-date-object": "^1.0.1",
        "is-symbol": "^1.0.2"
      }
    },
    "es5-ext": {
      "version": "0.10.53",
      "resolved": "https://registry.npmjs.org/es5-ext/-/es5-ext-0.10.53.tgz",
      "integrity": "sha512-Xs2Stw6NiNHWypzRTY1MtaG/uJlwCk8kH81920ma8mvN8Xq1gsfhZvpkImLQArw8AHnv8MT2I45J3c0R8slE+Q==",
      "dev": true,
      "requires": {
        "es6-iterator": "~2.0.3",
        "es6-symbol": "~3.1.3",
        "next-tick": "~1.0.0"
      }
    },
    "es6-iterator": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/es6-iterator/-/es6-iterator-2.0.3.tgz",
      "integrity": "sha1-p96IkUGgWpSwhUQDstCg+/qY87c=",
      "dev": true,
      "requires": {
        "d": "1",
        "es5-ext": "^0.10.35",
        "es6-symbol": "^3.1.1"
      }
    },
    "es6-symbol": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/es6-symbol/-/es6-symbol-3.1.3.tgz",
      "integrity": "sha512-NJ6Yn3FuDinBaBRWl/q5X/s4koRHBrgKAu+yGI6JCBeiu3qrcbJhwT2GeR/EXVfylRk8dpQVJoLEFhK+Mu31NA==",
      "dev": true,
      "requires": {
        "d": "^1.0.1",
        "ext": "^1.1.2"
      }
    },
    "escalade": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/escalade/-/escalade-3.1.1.tgz",
      "integrity": "sha512-k0er2gUkLf8O0zKJiAhmkTnJlTvINGv7ygDNPbeIsX/TJjGJZHuh9B2UxbsaEkmlEo9MfhrSzmhIlhRlI2GXnw==",
      "dev": true
    },
    "escape-string-regexp": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz",
      "integrity": "sha1-G2HAViGQqN/2rjuyzwIAyhMLhtQ=",
      "dev": true
    },
    "escodegen": {
      "version": "1.14.3",
      "resolved": "https://registry.npmjs.org/escodegen/-/escodegen-1.14.3.tgz",
      "integrity": "sha512-qFcX0XJkdg+PB3xjZZG/wKSuT1PnQWx57+TVSjIMmILd2yC/6ByYElPwJnslDsuWuSAp4AwJGumarAAmJch5Kw==",
      "dev": true,
      "requires": {
        "esprima": "^4.0.1",
        "estraverse": "^4.2.0",
        "esutils": "^2.0.2",
        "optionator": "^0.8.1",
        "source-map": "~0.6.1"
      }
    },
    "eslint": {
      "version": "6.8.0",
      "resolved": "https://registry.npmjs.org/eslint/-/eslint-6.8.0.tgz",
      "integrity": "sha512-K+Iayyo2LtyYhDSYwz5D5QdWw0hCacNzyq1Y821Xna2xSJj7cijoLLYmLxTQgcgZ9mC61nryMy9S7GRbYpI5Ig==",
      "dev": true,
      "requires": {
        "@babel/code-frame": "^7.0.0",
        "ajv": "^6.10.0",
        "chalk": "^2.1.0",
        "cross-spawn": "^6.0.5",
        "debug": "^4.0.1",
        "doctrine": "^3.0.0",
        "eslint-scope": "^5.0.0",
        "eslint-utils": "^1.4.3",
        "eslint-visitor-keys": "^1.1.0",
        "espree": "^6.1.2",
        "esquery": "^1.0.1",
        "esutils": "^2.0.2",
        "file-entry-cache": "^5.0.1",
        "functional-red-black-tree": "^1.0.1",
        "glob-parent": "^5.0.0",
        "globals": "^12.1.0",
        "ignore": "^4.0.6",
        "import-fresh": "^3.0.0",
        "imurmurhash": "^0.1.4",
        "inquirer": "^7.0.0",
        "is-glob": "^4.0.0",
        "js-yaml": "^3.13.1",
        "json-stable-stringify-without-jsonify": "^1.0.1",
        "levn": "^0.3.0",
        "lodash": "^4.17.14",
        "minimatch": "^3.0.4",
        "mkdirp": "^0.5.1",
        "natural-compare": "^1.4.0",
        "optionator": "^0.8.3",
        "progress": "^2.0.0",
        "regexpp": "^2.0.1",
        "semver": "^6.1.2",
        "strip-ansi": "^5.2.0",
        "strip-json-comments": "^3.0.1",
        "table": "^5.2.3",
        "text-table": "^0.2.0",
        "v8-compile-cache": "^2.0.3"
      },
      "dependencies": {
        "eslint-utils": {
          "version": "1.4.3",
          "resolved": "https://registry.npmjs.org/eslint-utils/-/eslint-utils-1.4.3.tgz",
          "integrity": "sha512-fbBN5W2xdY45KulGXmLHZ3c3FHfVYmKg0IrAKGOkT/464PQsx2UeIzfz1RmEci+KLm1bBaAzZAh8+/E+XAeZ8Q==",
          "dev": true,
          "requires": {
            "eslint-visitor-keys": "^1.1.0"
          }
        },
        "regexpp": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/regexpp/-/regexpp-2.0.1.tgz",
          "integrity": "sha512-lv0M6+TkDVniA3aD1Eg0DVpfU/booSu7Eev3TDO/mZKHBfVjgCGTV4t4buppESEYDtkArYFOxTJWv6S5C+iaNw==",
          "dev": true
        },
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
          "dev": true
        }
      }
    },
    "eslint-config-prettier": {
      "version": "6.11.0",
      "resolved": "https://registry.npmjs.org/eslint-config-prettier/-/eslint-config-prettier-6.11.0.tgz",
      "integrity": "sha512-oB8cpLWSAjOVFEJhhyMZh6NOEOtBVziaqdDQ86+qhDHFbZXoRTM7pNSvFRfW/W/L/LrQ38C99J5CGuRBBzBsdA==",
      "dev": true,
      "requires": {
        "get-stdin": "^6.0.0"
      }
    },
    "eslint-import-resolver-node": {
      "version": "0.3.4",
      "resolved": "https://registry.npmjs.org/eslint-import-resolver-node/-/eslint-import-resolver-node-0.3.4.tgz",
      "integrity": "sha512-ogtf+5AB/O+nM6DIeBUNr2fuT7ot9Qg/1harBfBtaP13ekEWFQEEMP94BCB7zaNW3gyY+8SHYF00rnqYwXKWOA==",
      "dev": true,
      "requires": {
        "debug": "^2.6.9",
        "resolve": "^1.13.1"
      },
      "dependencies": {
        "debug": {
          "version": "2.6.9",
          "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
          "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
          "dev": true,
          "requires": {
            "ms": "2.0.0"
          }
        },
        "ms": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
          "integrity": "sha1-VgiurfwAvmwpAd9fmGF4jeDVl8g=",
          "dev": true
        }
      }
    },
    "eslint-module-utils": {
      "version": "2.6.1",
      "resolved": "https://registry.npmjs.org/eslint-module-utils/-/eslint-module-utils-2.6.1.tgz",
      "integrity": "sha512-ZXI9B8cxAJIH4nfkhTwcRTEAnrVfobYqwjWy/QMCZ8rHkZHFjf9yO4BzpiF9kCSfNlMG54eKigISHpX0+AaT4A==",
      "dev": true,
      "requires": {
        "debug": "^3.2.7",
        "pkg-dir": "^2.0.0"
      },
      "dependencies": {
        "debug": {
          "version": "3.2.7",
          "resolved": "https://registry.npmjs.org/debug/-/debug-3.2.7.tgz",
          "integrity": "sha512-CFjzYYAi4ThfiQvizrFQevTTXHtnCqWfe7x1AhgEscTz6ZbLbfoLRLPugTQyBth6f8ZERVUSyWHFD/7Wu4t1XQ==",
          "dev": true,
          "requires": {
            "ms": "^2.1.1"
          }
        }
      }
    },
    "eslint-plugin-import": {
      "version": "2.20.2",
      "resolved": "https://registry.npmjs.org/eslint-plugin-import/-/eslint-plugin-import-2.20.2.tgz",
      "integrity": "sha512-FObidqpXrR8OnCh4iNsxy+WACztJLXAHBO5hK79T1Hc77PgQZkyDGA5Ag9xAvRpglvLNxhH/zSmZ70/pZ31dHg==",
      "dev": true,
      "requires": {
        "array-includes": "^3.0.3",
        "array.prototype.flat": "^1.2.1",
        "contains-path": "^0.1.0",
        "debug": "^2.6.9",
        "doctrine": "1.5.0",
        "eslint-import-resolver-node": "^0.3.2",
        "eslint-module-utils": "^2.4.1",
        "has": "^1.0.3",
        "minimatch": "^3.0.4",
        "object.values": "^1.1.0",
        "read-pkg-up": "^2.0.0",
        "resolve": "^1.12.0"
      },
      "dependencies": {
        "debug": {
          "version": "2.6.9",
          "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
          "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
          "dev": true,
          "requires": {
            "ms": "2.0.0"
          }
        },
        "doctrine": {
          "version": "1.5.0",
          "resolved": "https://registry.npmjs.org/doctrine/-/doctrine-1.5.0.tgz",
          "integrity": "sha1-N53Ocw9hZvds76TmcHoVmwLFpvo=",
          "dev": true,
          "requires": {
            "esutils": "^2.0.2",
            "isarray": "^1.0.0"
          }
        },
        "find-up": {
          "version": "2.1.0",
          "resolved": "https://registry.npmjs.org/find-up/-/find-up-2.1.0.tgz",
          "integrity": "sha1-RdG35QbHF93UgndaK3eSCjwMV6c=",
          "dev": true,
          "requires": {
            "locate-path": "^2.0.0"
          }
        },
        "locate-path": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/locate-path/-/locate-path-2.0.0.tgz",
          "integrity": "sha1-K1aLJl7slExtnA3pw9u7ygNUzY4=",
          "dev": true,
          "requires": {
            "p-locate": "^2.0.0",
            "path-exists": "^3.0.0"
          }
        },
        "ms": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
          "integrity": "sha1-VgiurfwAvmwpAd9fmGF4jeDVl8g=",
          "dev": true
        },
        "p-limit": {
          "version": "1.3.0",
          "resolved": "https://registry.npmjs.org/p-limit/-/p-limit-1.3.0.tgz",
          "integrity": "sha512-vvcXsLAJ9Dr5rQOPk7toZQZJApBl2K4J6dANSsEuh6QI41JYcsS/qhTGa9ErIUUgK3WNQoJYvylxvjqmiqEA9Q==",
          "dev": true,
          "requires": {
            "p-try": "^1.0.0"
          }
        },
        "p-locate": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/p-locate/-/p-locate-2.0.0.tgz",
          "integrity": "sha1-IKAQOyIqcMj9OcwuWAaA893l7EM=",
          "dev": true,
          "requires": {
            "p-limit": "^1.1.0"
          }
        },
        "p-try": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/p-try/-/p-try-1.0.0.tgz",
          "integrity": "sha1-y8ec26+P1CKOE/Yh8rGiN8GyB7M=",
          "dev": true
        },
        "path-exists": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/path-exists/-/path-exists-3.0.0.tgz",
          "integrity": "sha1-zg6+ql94yxiSXqfYENe1mwEP1RU=",
          "dev": true
        },
        "read-pkg": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/read-pkg/-/read-pkg-2.0.0.tgz",
          "integrity": "sha1-jvHAYjxqbbDcZxPEv6xGMysjaPg=",
          "dev": true,
          "requires": {
            "load-json-file": "^2.0.0",
            "normalize-package-data": "^2.3.2",
            "path-type": "^2.0.0"
          }
        },
        "read-pkg-up": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/read-pkg-up/-/read-pkg-up-2.0.0.tgz",
          "integrity": "sha1-a3KoBImE4MQeeVEP1en6mbO1Sb4=",
          "dev": true,
          "requires": {
            "find-up": "^2.0.0",
            "read-pkg": "^2.0.0"
          }
        }
      }
    },
    "eslint-scope": {
      "version": "5.1.1",
      "resolved": "https://registry.npmjs.org/eslint-scope/-/eslint-scope-5.1.1.tgz",
      "integrity": "sha512-2NxwbF/hZ0KpepYN0cNbo+FN6XoK7GaHlQhgx/hIZl6Va0bF45RQOOwhLIy8lQDbuCiadSLCBnH2CFYquit5bw==",
      "dev": true,
      "requires": {
        "esrecurse": "^4.3.0",
        "estraverse": "^4.1.1"
      }
    },
    "eslint-utils": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/eslint-utils/-/eslint-utils-2.1.0.tgz",
      "integrity": "sha512-w94dQYoauyvlDc43XnGB8lU3Zt713vNChgt4EWwhXAP2XkBvndfxF0AgIqKOOasjPIPzj9JqgwkwbCYD0/V3Zg==",
      "dev": true,
      "requires": {
        "eslint-visitor-keys": "^1.1.0"
      }
    },
    "eslint-visitor-keys": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/eslint-visitor-keys/-/eslint-visitor-keys-1.3.0.tgz",
      "integrity": "sha512-6J72N8UNa462wa/KFODt/PJ3IU60SDpC3QXC1Hjc1BXXpfL2C9R5+AU7jhe0F6GREqVMh4Juu+NY7xn+6dipUQ==",
      "dev": true
    },
    "espree": {
      "version": "6.2.1",
      "resolved": "https://registry.npmjs.org/espree/-/espree-6.2.1.tgz",
      "integrity": "sha512-ysCxRQY3WaXJz9tdbWOwuWr5Y/XrPTGX9Kiz3yoUXwW0VZ4w30HTkQLaGx/+ttFjF8i+ACbArnB4ce68a9m5hw==",
      "dev": true,
      "requires": {
        "acorn": "^7.1.1",
        "acorn-jsx": "^5.2.0",
        "eslint-visitor-keys": "^1.1.0"
      }
    },
    "esprima": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/esprima/-/esprima-4.0.1.tgz",
      "integrity": "sha512-eGuFFw7Upda+g4p+QHvnW0RyTX/SVeJBDM/gCtMARO0cLuT2HcEKnTPvhjV6aGeqrCB/sbNop0Kszm0jsaWU4A==",
      "dev": true
    },
    "esquery": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/esquery/-/esquery-1.4.0.tgz",
      "integrity": "sha512-cCDispWt5vHHtwMY2YrAQ4ibFkAL8RbH5YGBnZBc90MolvvfkkQcJro/aZiAQUlQ3qgrYS6D6v8Gc5G5CQsc9w==",
      "dev": true,
      "requires": {
        "estraverse": "^5.1.0"
      },
      "dependencies": {
        "estraverse": {
          "version": "5.2.0",
          "resolved": "https://registry.npmjs.org/estraverse/-/estraverse-5.2.0.tgz",
          "integrity": "sha512-BxbNGGNm0RyRYvUdHpIwv9IWzeM9XClbOxwoATuFdOE7ZE6wHL+HQ5T8hoPM+zHvmKzzsEqhgy0GrQ5X13afiQ==",
          "dev": true
        }
      }
    },
    "esrecurse": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/esrecurse/-/esrecurse-4.3.0.tgz",
      "integrity": "sha512-KmfKL3b6G+RXvP8N1vr3Tq1kL/oCFgn2NYXEtqP8/L3pKapUA4G8cFVaoF3SU323CD4XypR/ffioHmkti6/Tag==",
      "dev": true,
      "requires": {
        "estraverse": "^5.2.0"
      },
      "dependencies": {
        "estraverse": {
          "version": "5.2.0",
          "resolved": "https://registry.npmjs.org/estraverse/-/estraverse-5.2.0.tgz",
          "integrity": "sha512-BxbNGGNm0RyRYvUdHpIwv9IWzeM9XClbOxwoATuFdOE7ZE6wHL+HQ5T8hoPM+zHvmKzzsEqhgy0GrQ5X13afiQ==",
          "dev": true
        }
      }
    },
    "estraverse": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/estraverse/-/estraverse-4.3.0.tgz",
      "integrity": "sha512-39nnKffWz8xN1BU/2c79n9nB9HDzo0niYUqx6xyqUnyoAnQyyWpOTdZEeiCch8BBu515t4wp9ZmgVfVhn9EBpw==",
      "dev": true
    },
    "esutils": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/esutils/-/esutils-2.0.3.tgz",
      "integrity": "sha512-kVscqXk4OCp68SZ0dkgEKVi6/8ij300KBWTJq32P/dYeWTSwK41WyTxalN1eRmA5Z9UU/LX9D7FWSmV9SAYx6g==",
      "dev": true
    },
    "eth-rpc-errors": {
      "version": "4.0.3",
      "resolved": "https://registry.npmjs.org/eth-rpc-errors/-/eth-rpc-errors-4.0.3.tgz",
      "integrity": "sha512-Z3ymjopaoft7JDoxZcEb3pwdGh7yiYMhOwm2doUt6ASXlMavpNlK6Cre0+IMl2VSGyEU9rkiperQhp5iRxn5Pg==",
      "requires": {
        "fast-safe-stringify": "^2.0.6"
      }
    },
    "ethers": {
      "version": "5.6.8",
      "resolved": "https://registry.npmjs.org/ethers/-/ethers-5.6.8.tgz",
      "integrity": "sha512-YxIGaltAOdvBFPZwIkyHnXbW40f1r8mHUgapW6dxkO+6t7H6wY8POUn0Kbxrd/N7I4hHxyi7YCddMAH/wmho2w==",
      "dev": true,
      "requires": {
        "@ethersproject/abi": "5.6.3",
        "@ethersproject/abstract-provider": "5.6.1",
        "@ethersproject/abstract-signer": "5.6.2",
        "@ethersproject/address": "5.6.1",
        "@ethersproject/base64": "5.6.1",
        "@ethersproject/basex": "5.6.1",
        "@ethersproject/bignumber": "5.6.2",
        "@ethersproject/bytes": "5.6.1",
        "@ethersproject/constants": "5.6.1",
        "@ethersproject/contracts": "5.6.2",
        "@ethersproject/hash": "5.6.1",
        "@ethersproject/hdnode": "5.6.2",
        "@ethersproject/json-wallets": "5.6.1",
        "@ethersproject/keccak256": "5.6.1",
        "@ethersproject/logger": "5.6.0",
        "@ethersproject/networks": "5.6.3",
        "@ethersproject/pbkdf2": "5.6.1",
        "@ethersproject/properties": "5.6.0",
        "@ethersproject/providers": "5.6.8",
        "@ethersproject/random": "5.6.1",
        "@ethersproject/rlp": "5.6.1",
        "@ethersproject/sha2": "5.6.1",
        "@ethersproject/signing-key": "5.6.2",
        "@ethersproject/solidity": "5.6.1",
        "@ethersproject/strings": "5.6.1",
        "@ethersproject/transactions": "5.6.2",
        "@ethersproject/units": "5.6.1",
        "@ethersproject/wallet": "5.6.2",
        "@ethersproject/web": "5.6.1",
        "@ethersproject/wordlists": "5.6.1"
      }
    },
    "eventemitter3": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/eventemitter3/-/eventemitter3-3.1.2.tgz",
      "integrity": "sha512-tvtQIeLVHjDkJYnzf2dgVMxfuSGJeM/7UCG17TT4EumTfNtF+0nebF/4zWOIkCreAbtNqhGEboB6BWrwqNaw4Q=="
    },
    "exec-sh": {
      "version": "0.3.6",
      "resolved": "https://registry.npmjs.org/exec-sh/-/exec-sh-0.3.6.tgz",
      "integrity": "sha512-nQn+hI3yp+oD0huYhKwvYI32+JFeq+XkNcD1GAo3Y/MjxsfVGmrrzrnzjWiNY6f+pUCP440fThsFh5gZrRAU/w==",
      "dev": true
    },
    "execa": {
      "version": "3.4.0",
      "resolved": "https://registry.npmjs.org/execa/-/execa-3.4.0.tgz",
      "integrity": "sha512-r9vdGQk4bmCuK1yKQu1KTwcT2zwfWdbdaXfCtAh+5nU/4fSX+JAb7vZGvI5naJrQlvONrEB20jeruESI69530g==",
      "dev": true,
      "requires": {
        "cross-spawn": "^7.0.0",
        "get-stream": "^5.0.0",
        "human-signals": "^1.1.1",
        "is-stream": "^2.0.0",
        "merge-stream": "^2.0.0",
        "npm-run-path": "^4.0.0",
        "onetime": "^5.1.0",
        "p-finally": "^2.0.0",
        "signal-exit": "^3.0.2",
        "strip-final-newline": "^2.0.0"
      },
      "dependencies": {
        "cross-spawn": {
          "version": "7.0.3",
          "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-7.0.3.tgz",
          "integrity": "sha512-iRDPJKUPVEND7dHPO8rkbOnPpyDygcDFtWjpeWNCgy8WP2rXcxXL8TskReQl6OrB2G7+UJrags1q15Fudc7G6w==",
          "dev": true,
          "requires": {
            "path-key": "^3.1.0",
            "shebang-command": "^2.0.0",
            "which": "^2.0.1"
          }
        },
        "path-key": {
          "version": "3.1.1",
          "resolved": "https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz",
          "integrity": "sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==",
          "dev": true
        },
        "shebang-command": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/shebang-command/-/shebang-command-2.0.0.tgz",
          "integrity": "sha512-kHxr2zZpYtdmrN1qDjrrX/Z1rR1kG8Dx+gkpK1G4eXmvXswmcE1hTWBWYUzlraYw1/yZp6YuDY77YtvbN0dmDA==",
          "dev": true,
          "requires": {
            "shebang-regex": "^3.0.0"
          }
        },
        "shebang-regex": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/shebang-regex/-/shebang-regex-3.0.0.tgz",
          "integrity": "sha512-7++dFhtcx3353uBaq8DDR4NuxBetBzC7ZQOhmTQInHEd6bSrXdiEyzCvG07Z44UYdLShWUyXt5M/yhz8ekcb1A==",
          "dev": true
        },
        "which": {
          "version": "2.0.2",
          "resolved": "https://registry.npmjs.org/which/-/which-2.0.2.tgz",
          "integrity": "sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==",
          "dev": true,
          "requires": {
            "isexe": "^2.0.0"
          }
        }
      }
    },
    "exit": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/exit/-/exit-0.1.2.tgz",
      "integrity": "sha1-BjJjj42HfMghB9MKD/8aF8uhzQw=",
      "dev": true
    },
    "expand-brackets": {
      "version": "2.1.4",
      "resolved": "https://registry.npmjs.org/expand-brackets/-/expand-brackets-2.1.4.tgz",
      "integrity": "sha1-t3c14xXOMPa27/D4OwQVGiJEliI=",
      "dev": true,
      "requires": {
        "debug": "^2.3.3",
        "define-property": "^0.2.5",
        "extend-shallow": "^2.0.1",
        "posix-character-classes": "^0.1.0",
        "regex-not": "^1.0.0",
        "snapdragon": "^0.8.1",
        "to-regex": "^3.0.1"
      },
      "dependencies": {
        "debug": {
          "version": "2.6.9",
          "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
          "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
          "dev": true,
          "requires": {
            "ms": "2.0.0"
          }
        },
        "define-property": {
          "version": "0.2.5",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
          "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
          "dev": true,
          "requires": {
            "is-descriptor": "^0.1.0"
          }
        },
        "extend-shallow": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
          "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
          "dev": true,
          "requires": {
            "is-extendable": "^0.1.0"
          }
        },
        "is-accessor-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
          "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "is-data-descriptor": {
          "version": "0.1.4",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
          "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "is-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
          "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
          "dev": true,
          "requires": {
            "is-accessor-descriptor": "^0.1.6",
            "is-data-descriptor": "^0.1.4",
            "kind-of": "^5.0.0"
          }
        },
        "is-extendable": {
          "version": "0.1.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
          "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
          "dev": true
        },
        "kind-of": {
          "version": "5.1.0",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
          "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
          "dev": true
        },
        "ms": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
          "integrity": "sha1-VgiurfwAvmwpAd9fmGF4jeDVl8g=",
          "dev": true
        }
      }
    },
    "expect": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/expect/-/expect-25.5.0.tgz",
      "integrity": "sha512-w7KAXo0+6qqZZhovCaBVPSIqQp7/UTcx4M9uKt2m6pd2VB1voyC8JizLRqeEqud3AAVP02g+hbErDu5gu64tlA==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "ansi-styles": "^4.0.0",
        "jest-get-type": "^25.2.6",
        "jest-matcher-utils": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-regex-util": "^25.2.6"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        }
      }
    },
    "ext": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/ext/-/ext-1.4.0.tgz",
      "integrity": "sha512-Key5NIsUxdqKg3vIsdw9dSuXpPCQ297y6wBjL30edxwPgt2E44WcWBZey/ZvUc6sERLTxKdyCu4gZFmUbk1Q7A==",
      "dev": true,
      "requires": {
        "type": "^2.0.0"
      },
      "dependencies": {
        "type": {
          "version": "2.5.0",
          "resolved": "https://registry.npmjs.org/type/-/type-2.5.0.tgz",
          "integrity": "sha512-180WMDQaIMm3+7hGXWf12GtdniDEy7nYcyFMKJn/eZz/6tSLXrUN9V0wKSbMjej0I1WHWbpREDEKHtqPQa9NNw==",
          "dev": true
        }
      }
    },
    "extend": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/extend/-/extend-3.0.2.tgz",
      "integrity": "sha512-fjquC59cD7CyW6urNXK0FBufkZcoiGG80wTuPujX590cB5Ttln20E2UB4S/WARVqhXffZl2LNgS+gQdPIIim/g==",
      "dev": true
    },
    "extend-shallow": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-3.0.2.tgz",
      "integrity": "sha1-Jqcarwc7OfshJxcnRhMcJwQCjbg=",
      "dev": true,
      "requires": {
        "assign-symbols": "^1.0.0",
        "is-extendable": "^1.0.1"
      }
    },
    "external-editor": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/external-editor/-/external-editor-3.1.0.tgz",
      "integrity": "sha512-hMQ4CX1p1izmuLYyZqLMO/qGNw10wSv9QDCPfzXfyFrOaCSSoRfqE1Kf1s5an66J5JZC62NewG+mK49jOCtQew==",
      "dev": true,
      "requires": {
        "chardet": "^0.7.0",
        "iconv-lite": "^0.4.24",
        "tmp": "^0.0.33"
      },
      "dependencies": {
        "tmp": {
          "version": "0.0.33",
          "resolved": "https://registry.npmjs.org/tmp/-/tmp-0.0.33.tgz",
          "integrity": "sha512-jRCJlojKnZ3addtTOjdIqoRuPEKBvNXcGYqzO6zWZX8KfKEpnGY5jfggJQ3EjKuu8D4bJRr0y+cYJFmYbImXGw==",
          "dev": true,
          "requires": {
            "os-tmpdir": "~1.0.2"
          }
        }
      }
    },
    "extglob": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/extglob/-/extglob-2.0.4.tgz",
      "integrity": "sha512-Nmb6QXkELsuBr24CJSkilo6UHHgbekK5UiZgfE6UHD3Eb27YC6oD+bhcT+tJ6cl8dmsgdQxnWlcry8ksBIBLpw==",
      "dev": true,
      "requires": {
        "array-unique": "^0.3.2",
        "define-property": "^1.0.0",
        "expand-brackets": "^2.1.4",
        "extend-shallow": "^2.0.1",
        "fragment-cache": "^0.2.1",
        "regex-not": "^1.0.0",
        "snapdragon": "^0.8.1",
        "to-regex": "^3.0.1"
      },
      "dependencies": {
        "define-property": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
          "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
          "dev": true,
          "requires": {
            "is-descriptor": "^1.0.0"
          }
        },
        "extend-shallow": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
          "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
          "dev": true,
          "requires": {
            "is-extendable": "^0.1.0"
          }
        },
        "is-extendable": {
          "version": "0.1.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
          "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
          "dev": true
        }
      }
    },
    "extsprintf": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/extsprintf/-/extsprintf-1.3.0.tgz",
      "integrity": "sha1-lpGEQOMEGnpBT4xS48V06zw+HgU=",
      "dev": true
    },
    "fast-deep-equal": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/fast-deep-equal/-/fast-deep-equal-3.1.3.tgz",
      "integrity": "sha512-f3qQ9oQy9j2AhBe/H9VC91wLmKBCCU/gDOnKNAYG5hswO7BLKj09Hc5HYNz9cGI++xlpDCIgDaitVs03ATR84Q==",
      "dev": true
    },
    "fast-json-stable-stringify": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/fast-json-stable-stringify/-/fast-json-stable-stringify-2.1.0.tgz",
      "integrity": "sha512-lhd/wF+Lk98HZoTCtlVraHtfh5XYijIjalXck7saUtuanSDyLMxnHhSXEDJqHxD7msR8D0uCmqlkwjCV8xvwHw==",
      "dev": true
    },
    "fast-levenshtein": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz",
      "integrity": "sha1-PYpcZog6FqMMqGQ+hR8Zuqd5eRc=",
      "dev": true
    },
    "fast-safe-stringify": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/fast-safe-stringify/-/fast-safe-stringify-2.1.1.tgz",
      "integrity": "sha512-W+KJc2dmILlPplD/H4K9l9LcAHAfPtP6BY84uVLXQ6Evcz9Lcg33Y2z1IVblT6xdY54PXYVHEv+0Wpq8Io6zkA=="
    },
    "fast-url-parser": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/fast-url-parser/-/fast-url-parser-1.1.3.tgz",
      "integrity": "sha512-5jOCVXADYNuRkKFzNJ0dCCewsZiYo0dz8QNYljkOpFC6r2U4OBmKtvm/Tsuh4w1YYdDqDb31a8TVhBJ2OJKdqQ==",
      "dev": true,
      "requires": {
        "punycode": "^1.3.2"
      }
    },
    "fb-watchman": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/fb-watchman/-/fb-watchman-2.0.1.tgz",
      "integrity": "sha512-DkPJKQeY6kKwmuMretBhr7G6Vodr7bFwDYTXIkfG1gjvNpaxBTQV3PbXg6bR1c1UP4jPOX0jHUbbHANL9vRjVg==",
      "dev": true,
      "requires": {
        "bser": "2.1.1"
      }
    },
    "figures": {
      "version": "3.2.0",
      "resolved": "https://registry.npmjs.org/figures/-/figures-3.2.0.tgz",
      "integrity": "sha512-yaduQFRKLXYOGgEn6AZau90j3ggSOyiqXU0F9JZfeXYhNa+Jk4X+s45A2zg5jns87GAFa34BBm2kXw4XpNcbdg==",
      "dev": true,
      "requires": {
        "escape-string-regexp": "^1.0.5"
      }
    },
    "file-entry-cache": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/file-entry-cache/-/file-entry-cache-5.0.1.tgz",
      "integrity": "sha512-bCg29ictuBaKUwwArK4ouCaqDgLZcysCFLmM/Yn/FDoqndh/9vNuQfXRDvTuXKLxfD/JtZQGKFT8MGcJBK644g==",
      "dev": true,
      "requires": {
        "flat-cache": "^2.0.1"
      }
    },
    "filename-reserved-regex": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/filename-reserved-regex/-/filename-reserved-regex-2.0.0.tgz",
      "integrity": "sha1-q/c9+rc10EVECr/qLZHzieu/oik=",
      "dev": true
    },
    "filenamify": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/filenamify/-/filenamify-4.3.0.tgz",
      "integrity": "sha512-hcFKyUG57yWGAzu1CMt/dPzYZuv+jAJUT85bL8mrXvNe6hWj6yEHEc4EdcgiA6Z3oi1/9wXJdZPXF2dZNgwgOg==",
      "dev": true,
      "requires": {
        "filename-reserved-regex": "^2.0.0",
        "strip-outer": "^1.0.1",
        "trim-repeated": "^1.0.0"
      }
    },
    "fill-range": {
      "version": "7.0.1",
      "resolved": "https://registry.npmjs.org/fill-range/-/fill-range-7.0.1.tgz",
      "integrity": "sha512-qOo9F+dMUmC2Lcb4BbVvnKJxTPjCm+RRpe4gDuGrzkL7mEVl/djYSu2OdQ2Pa302N4oqkSg9ir6jaLWJ2USVpQ==",
      "dev": true,
      "requires": {
        "to-regex-range": "^5.0.1"
      }
    },
    "find-cache-dir": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/find-cache-dir/-/find-cache-dir-3.3.1.tgz",
      "integrity": "sha512-t2GDMt3oGC/v+BMwzmllWDuJF/xcDtE5j/fCGbqDD7OLuJkj0cfh1YSA5VKPvwMeLFLNDBkwOKZ2X85jGLVftQ==",
      "dev": true,
      "requires": {
        "commondir": "^1.0.1",
        "make-dir": "^3.0.2",
        "pkg-dir": "^4.1.0"
      },
      "dependencies": {
        "pkg-dir": {
          "version": "4.2.0",
          "resolved": "https://registry.npmjs.org/pkg-dir/-/pkg-dir-4.2.0.tgz",
          "integrity": "sha512-HRDzbaKjC+AOWVXxAU/x54COGeIv9eb+6CkDSQoNTt4XyWoIJvuPsXizxu/Fr23EiekbtZwmh1IcIG/l/a10GQ==",
          "dev": true,
          "requires": {
            "find-up": "^4.0.0"
          }
        }
      }
    },
    "find-up": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/find-up/-/find-up-4.1.0.tgz",
      "integrity": "sha512-PpOwAdQ/YlXQ2vj8a3h8IipDuYRi3wceVQQGYWxNINccq40Anw7BlsEXCMbt1Zt+OLA6Fq9suIpIWD0OsnISlw==",
      "dev": true,
      "requires": {
        "locate-path": "^5.0.0",
        "path-exists": "^4.0.0"
      }
    },
    "flat-cache": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/flat-cache/-/flat-cache-2.0.1.tgz",
      "integrity": "sha512-LoQe6yDuUMDzQAEH8sgmh4Md6oZnc/7PjtwjNFSzveXqSHt6ka9fPBuso7IGf9Rz4uqnSnWiFH2B/zj24a5ReA==",
      "dev": true,
      "requires": {
        "flatted": "^2.0.0",
        "rimraf": "2.6.3",
        "write": "1.0.3"
      },
      "dependencies": {
        "rimraf": {
          "version": "2.6.3",
          "resolved": "https://registry.npmjs.org/rimraf/-/rimraf-2.6.3.tgz",
          "integrity": "sha512-mwqeW5XsA2qAejG46gYdENaxXjx9onRNCfn7L0duuP4hCuTIi/QO7PDK07KJfp1d+izWPrzEJDcSqBa0OZQriA==",
          "dev": true,
          "requires": {
            "glob": "^7.1.3"
          }
        }
      }
    },
    "flatted": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/flatted/-/flatted-2.0.2.tgz",
      "integrity": "sha512-r5wGx7YeOwNWNlCA0wQ86zKyDLMQr+/RB8xy74M4hTphfmjlijTSSXGuH8rnvKZnfT9i+75zmd8jcKdMR4O6jA==",
      "dev": true
    },
    "follow-redirects": {
      "version": "1.15.2",
      "resolved": "https://registry.npmjs.org/follow-redirects/-/follow-redirects-1.15.2.tgz",
      "integrity": "sha512-VQLG33o04KaQ8uYi2tVNbdrWp1QWxNNea+nmIB4EVM28v0hmP17z7aG1+wAkNzVq4KeXTq3221ye5qTJP91JwA=="
    },
    "for-in": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/for-in/-/for-in-1.0.2.tgz",
      "integrity": "sha1-gQaNKVqBQuwKxybG4iAMMPttXoA=",
      "dev": true
    },
    "forever-agent": {
      "version": "0.6.1",
      "resolved": "https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz",
      "integrity": "sha1-+8cfDEGt6zf5bFd60e1C2P2sypE=",
      "dev": true
    },
    "form-data": {
      "version": "2.3.3",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-2.3.3.tgz",
      "integrity": "sha512-1lLKB2Mu3aGP1Q/2eCOx0fNbRMe7XdwktwOruhfqqd0rIJWwN4Dh+E3hrPSlDCXnSR7UtZ1N38rVXm+6+MEhJQ==",
      "dev": true,
      "requires": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.6",
        "mime-types": "^2.1.12"
      }
    },
    "fragment-cache": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/fragment-cache/-/fragment-cache-0.2.1.tgz",
      "integrity": "sha1-QpD60n8T6Jvn8zeZxrxaCr//DRk=",
      "dev": true,
      "requires": {
        "map-cache": "^0.2.2"
      }
    },
    "fs-extra": {
      "version": "8.1.0",
      "resolved": "https://registry.npmjs.org/fs-extra/-/fs-extra-8.1.0.tgz",
      "integrity": "sha512-yhlQgA6mnOJUKOsRUFsgJdQCvkKhcz8tlZG5HBQfReYZy46OwLcY+Zia0mtdHsOo9y/hP+CxMN0TU9QxoOtG4g==",
      "dev": true,
      "requires": {
        "graceful-fs": "^4.2.0",
        "jsonfile": "^4.0.0",
        "universalify": "^0.1.0"
      }
    },
    "fs.realpath": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz",
      "integrity": "sha1-FQStJSMVjKpA20onh8sBQRmU6k8=",
      "dev": true
    },
    "fsevents": {
      "version": "2.3.2",
      "resolved": "https://registry.npmjs.org/fsevents/-/fsevents-2.3.2.tgz",
      "integrity": "sha512-xiqMQR4xAeHTuB9uWm+fFRcIOgKBMiOBP+eXiyT7jsgVCq1bkVygt00oASowB7EdtpOHaaPgKt812P9ab+DDKA==",
      "dev": true,
      "optional": true
    },
    "function-bind": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/function-bind/-/function-bind-1.1.1.tgz",
      "integrity": "sha512-yIovAzMX49sF8Yl58fSCWJ5svSLuaibPxXQJFLmBObTuCr0Mf1KiPopGM9NiFjiYBCbfaa2Fh6breQ6ANVTI0A==",
      "dev": true
    },
    "functional-red-black-tree": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/functional-red-black-tree/-/functional-red-black-tree-1.0.1.tgz",
      "integrity": "sha1-GwqzvVU7Kg1jmdKcDj6gslIHgyc=",
      "dev": true
    },
    "gensync": {
      "version": "1.0.0-beta.2",
      "resolved": "https://registry.npmjs.org/gensync/-/gensync-1.0.0-beta.2.tgz",
      "integrity": "sha512-3hN7NaskYvMDLQY55gnW3NQ+mesEAepTqlg+VEbj7zzqEMBVNhzcGYYeqFo/TlYz6eQiFcp1HcsCZO+nGgS8zg==",
      "dev": true
    },
    "get-caller-file": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/get-caller-file/-/get-caller-file-2.0.5.tgz",
      "integrity": "sha512-DyFP3BM/3YHTQOCUL/w0OZHR0lpKeGrxotcHWcqNEdnltqFwXVfhEBQ94eIo34AfQpo0rGki4cyIiftY06h2Fg==",
      "dev": true
    },
    "get-intrinsic": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/get-intrinsic/-/get-intrinsic-1.1.1.tgz",
      "integrity": "sha512-kWZrnVM42QCiEA2Ig1bG8zjoIMOgxWwYCEeNdwY6Tv/cOSeGpcoX4pXHfKUxNKVoArnrEr2e9srnAxxGIraS9Q==",
      "dev": true,
      "requires": {
        "function-bind": "^1.1.1",
        "has": "^1.0.3",
        "has-symbols": "^1.0.1"
      }
    },
    "get-package-type": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/get-package-type/-/get-package-type-0.1.0.tgz",
      "integrity": "sha512-pjzuKtY64GYfWizNAJ0fr9VqttZkNiK2iS430LtIHzjBEr6bX8Am2zm4sW4Ro5wjWW5cAlRL1qAMTcXbjNAO2Q==",
      "dev": true
    },
    "get-stdin": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/get-stdin/-/get-stdin-6.0.0.tgz",
      "integrity": "sha512-jp4tHawyV7+fkkSKyvjuLZswblUtz+SQKzSWnBbii16BuZksJlU1wuBYXY75r+duh/llF1ur6oNwi+2ZzjKZ7g==",
      "dev": true
    },
    "get-stream": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/get-stream/-/get-stream-5.2.0.tgz",
      "integrity": "sha512-nBF+F1rAZVCu/p7rjzgA+Yb4lfYXrpl7a6VmJrU8wF9I1CKvP/QwPNZHnOlwbTkY6dvtFIzFMSyQXbLoTQPRpA==",
      "dev": true,
      "requires": {
        "pump": "^3.0.0"
      }
    },
    "get-value": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/get-value/-/get-value-2.0.6.tgz",
      "integrity": "sha1-3BXKHGcjh8p2vTesCjlbogQqLCg=",
      "dev": true
    },
    "getpass": {
      "version": "0.1.7",
      "resolved": "https://registry.npmjs.org/getpass/-/getpass-0.1.7.tgz",
      "integrity": "sha1-Xv+OPmhNVprkyysSgmBOi6YhSfo=",
      "dev": true,
      "requires": {
        "assert-plus": "^1.0.0"
      }
    },
    "gh-pages": {
      "version": "3.2.3",
      "resolved": "https://registry.npmjs.org/gh-pages/-/gh-pages-3.2.3.tgz",
      "integrity": "sha512-jA1PbapQ1jqzacECfjUaO9gV8uBgU6XNMV0oXLtfCX3haGLe5Atq8BxlrADhbD6/UdG9j6tZLWAkAybndOXTJg==",
      "dev": true,
      "requires": {
        "async": "^2.6.1",
        "commander": "^2.18.0",
        "email-addresses": "^3.0.1",
        "filenamify": "^4.3.0",
        "find-cache-dir": "^3.3.1",
        "fs-extra": "^8.1.0",
        "globby": "^6.1.0"
      },
      "dependencies": {
        "commander": {
          "version": "2.20.3",
          "resolved": "https://registry.npmjs.org/commander/-/commander-2.20.3.tgz",
          "integrity": "sha512-GpVkmM8vF2vQUkj2LvZmD35JxeJOLCwJ9cUkugyk2nuhbv3+mJvpLYYt+0+USMxE+oj+ey/lJEnhZw75x/OMcQ==",
          "dev": true
        }
      }
    },
    "glob": {
      "version": "7.1.7",
      "resolved": "https://registry.npmjs.org/glob/-/glob-7.1.7.tgz",
      "integrity": "sha512-OvD9ENzPLbegENnYP5UUfJIirTg4+XwMWGaQfQTY0JenxNvvIKP3U3/tAQSPIu/lHxXYSZmpXlUHeqAIdKzBLQ==",
      "dev": true,
      "requires": {
        "fs.realpath": "^1.0.0",
        "inflight": "^1.0.4",
        "inherits": "2",
        "minimatch": "^3.0.4",
        "once": "^1.3.0",
        "path-is-absolute": "^1.0.0"
      }
    },
    "glob-parent": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/glob-parent/-/glob-parent-5.1.2.tgz",
      "integrity": "sha512-AOIgSQCepiJYwP3ARnGx+5VnTu2HBYdzbGP45eLw1vr3zB3vZLeyed1sC9hnbcOc9/SrMyM5RPQrkGz4aS9Zow==",
      "dev": true,
      "requires": {
        "is-glob": "^4.0.1"
      }
    },
    "globals": {
      "version": "12.4.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-12.4.0.tgz",
      "integrity": "sha512-BWICuzzDvDoH54NHKCseDanAhE3CeDorgDL5MT6LMXXj2WCnd9UC2szdk4AWLfjdgNBCXLUanXYcpBBKOSWGwg==",
      "dev": true,
      "requires": {
        "type-fest": "^0.8.1"
      }
    },
    "globby": {
      "version": "6.1.0",
      "resolved": "https://registry.npmjs.org/globby/-/globby-6.1.0.tgz",
      "integrity": "sha1-9abXDoOV4hyFj7BInWTfAkJNUGw=",
      "dev": true,
      "requires": {
        "array-union": "^1.0.1",
        "glob": "^7.0.3",
        "object-assign": "^4.0.1",
        "pify": "^2.0.0",
        "pinkie-promise": "^2.0.0"
      }
    },
    "graceful-fs": {
      "version": "4.2.6",
      "resolved": "https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.2.6.tgz",
      "integrity": "sha512-nTnJ528pbqxYanhpDYsi4Rd8MAeaBA67+RZ10CM1m3bTAVFEDcd5AuA4a6W5YkGZ1iNXHzZz8T6TBKLeBuNriQ==",
      "dev": true
    },
    "graphql": {
      "version": "15.5.3",
      "resolved": "https://registry.npmjs.org/graphql/-/graphql-15.5.3.tgz",
      "integrity": "sha512-sM+jXaO5KinTui6lbK/7b7H/Knj9BpjGxZ+Ki35v7YbUJxxdBCUqNM0h3CRVU1ZF9t5lNiBzvBCSYPvIwxPOQA=="
    },
    "graphql-tag": {
      "version": "2.12.4",
      "resolved": "https://registry.npmjs.org/graphql-tag/-/graphql-tag-2.12.4.tgz",
      "integrity": "sha512-VV1U4O+9x99EkNpNmCUV5RZwq6MnK4+pGbRYWG+lA/m3uo7TSqJF81OkcOP148gFP6fzdl7JWYBrwWVTS9jXww==",
      "requires": {
        "tslib": "^2.1.0"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.0",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
          "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg=="
        }
      }
    },
    "growly": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/growly/-/growly-1.3.0.tgz",
      "integrity": "sha1-8QdIy+dq+WS3yWyTxrzCivEgwIE=",
      "dev": true,
      "optional": true
    },
    "handlebars": {
      "version": "4.7.7",
      "resolved": "https://registry.npmjs.org/handlebars/-/handlebars-4.7.7.tgz",
      "integrity": "sha512-aAcXm5OAfE/8IXkcZvCepKU3VzW1/39Fb5ZuqMtgI/hT8X2YgoMvBY5dLhq/cpOvw7Lk1nK/UF71aLG/ZnVYRA==",
      "dev": true,
      "requires": {
        "minimist": "^1.2.5",
        "neo-async": "^2.6.0",
        "source-map": "^0.6.1",
        "uglify-js": "^3.1.4",
        "wordwrap": "^1.0.0"
      }
    },
    "har-schema": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/har-schema/-/har-schema-2.0.0.tgz",
      "integrity": "sha1-qUwiJOvKwEeCoNkDVSHyRzW37JI=",
      "dev": true
    },
    "har-validator": {
      "version": "5.1.5",
      "resolved": "https://registry.npmjs.org/har-validator/-/har-validator-5.1.5.tgz",
      "integrity": "sha512-nmT2T0lljbxdQZfspsno9hgrG3Uir6Ks5afism62poxqBM6sDnMEuPmzTq8XN0OEwqKLLdh1jQI3qyE66Nzb3w==",
      "dev": true,
      "requires": {
        "ajv": "^6.12.3",
        "har-schema": "^2.0.0"
      }
    },
    "has": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/has/-/has-1.0.3.tgz",
      "integrity": "sha512-f2dvO0VU6Oej7RkWJGrehjbzMAjFp5/VKPp5tTpWIV4JHHZK1/BxbFRtf/siA2SWTe09caDmVtYYzWEIbBS4zw==",
      "dev": true,
      "requires": {
        "function-bind": "^1.1.1"
      }
    },
    "has-bigints": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/has-bigints/-/has-bigints-1.0.1.tgz",
      "integrity": "sha512-LSBS2LjbNBTf6287JEbEzvJgftkF5qFkmCo9hDRpAzKhUOlJ+hx8dd4USs00SgsUNwc4617J9ki5YtEClM2ffA==",
      "dev": true
    },
    "has-flag": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-3.0.0.tgz",
      "integrity": "sha1-tdRU3CGZriJWmfNGfloH87lVuv0=",
      "dev": true
    },
    "has-symbols": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/has-symbols/-/has-symbols-1.0.2.tgz",
      "integrity": "sha512-chXa79rL/UC2KlX17jo3vRGz0azaWEx5tGqZg5pO3NUyEJVB17dMruQlzCCOfUvElghKcm5194+BCRvi2Rv/Gw==",
      "dev": true
    },
    "has-value": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/has-value/-/has-value-1.0.0.tgz",
      "integrity": "sha1-GLKB2lhbHFxR3vJMkw7SmgvmsXc=",
      "dev": true,
      "requires": {
        "get-value": "^2.0.6",
        "has-values": "^1.0.0",
        "isobject": "^3.0.0"
      }
    },
    "has-values": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/has-values/-/has-values-1.0.0.tgz",
      "integrity": "sha1-lbC2P+whRmGab+V/51Yo1aOe/k8=",
      "dev": true,
      "requires": {
        "is-number": "^3.0.0",
        "kind-of": "^4.0.0"
      },
      "dependencies": {
        "is-number": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/is-number/-/is-number-3.0.0.tgz",
          "integrity": "sha1-JP1iAaR4LPUFYcgQJ2r8fRLXEZU=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "kind-of": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-4.0.0.tgz",
          "integrity": "sha1-IIE989cSkosgc3hpGkUGb65y3Vc=",
          "dev": true,
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "hash.js": {
      "version": "1.1.7",
      "resolved": "https://registry.npmjs.org/hash.js/-/hash.js-1.1.7.tgz",
      "integrity": "sha512-taOaskGt4z4SOANNseOviYDvjEJinIkRgmp7LbKP2YTTmVxWBl87s/uzK9r+44BclBSp2X7K1hqeNfz9JbBeXA==",
      "requires": {
        "inherits": "^2.0.3",
        "minimalistic-assert": "^1.0.1"
      }
    },
    "highlight.js": {
      "version": "10.7.3",
      "resolved": "https://registry.npmjs.org/highlight.js/-/highlight.js-10.7.3.tgz",
      "integrity": "sha512-tzcUFauisWKNHaRkN4Wjl/ZA07gENAjFl3J/c480dprkGTg5EQstgaNFqBfUqCq54kZRIEcreTsAgF/m2quD7A==",
      "dev": true
    },
    "hmac-drbg": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/hmac-drbg/-/hmac-drbg-1.0.1.tgz",
      "integrity": "sha1-0nRXAQJabHdabFRXk+1QL8DGSaE=",
      "requires": {
        "hash.js": "^1.0.3",
        "minimalistic-assert": "^1.0.0",
        "minimalistic-crypto-utils": "^1.0.1"
      }
    },
    "hoist-non-react-statics": {
      "version": "3.3.2",
      "resolved": "https://registry.npmjs.org/hoist-non-react-statics/-/hoist-non-react-statics-3.3.2.tgz",
      "integrity": "sha512-/gGivxi8JPKWNm/W0jSmzcMPpfpPLc3dY/6GxhX2hQ9iGj3aDfklV4ET7NjKpSinLpJ5vafa9iiGIEZg10SfBw==",
      "requires": {
        "react-is": "^16.7.0"
      }
    },
    "hosted-git-info": {
      "version": "2.8.9",
      "resolved": "https://registry.npmjs.org/hosted-git-info/-/hosted-git-info-2.8.9.tgz",
      "integrity": "sha512-mxIDAb9Lsm6DoOJ7xH+5+X4y1LU/4Hi50L9C5sIswK3JzULS4bwk1FvjdBgvYR4bzT4tuUQiC15FE2f5HbLvYw==",
      "dev": true
    },
    "html-encoding-sniffer": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/html-encoding-sniffer/-/html-encoding-sniffer-1.0.2.tgz",
      "integrity": "sha512-71lZziiDnsuabfdYiUeWdCVyKuqwWi23L8YeIgV9jSSZHCtb6wB1BKWooH7L3tn4/FuZJMVWyNaIDr4RGmaSYw==",
      "dev": true,
      "requires": {
        "whatwg-encoding": "^1.0.1"
      }
    },
    "html-escaper": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/html-escaper/-/html-escaper-2.0.2.tgz",
      "integrity": "sha512-H2iMtd0I4Mt5eYiapRdIDjp+XzelXQ0tFE4JS7YFwFevXXMmOp9myNrUvCg0D6ws8iqkRPBfKHgbwig1SmlLfg==",
      "dev": true
    },
    "http-signature": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/http-signature/-/http-signature-1.2.0.tgz",
      "integrity": "sha1-muzZJRFHcvPZW2WmCruPfBj7rOE=",
      "dev": true,
      "requires": {
        "assert-plus": "^1.0.0",
        "jsprim": "^1.2.2",
        "sshpk": "^1.7.0"
      }
    },
    "human-signals": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/human-signals/-/human-signals-1.1.1.tgz",
      "integrity": "sha512-SEQu7vl8KjNL2eoGBLF3+wAjpsNfA9XMlXAYj/3EdaNfAlxKthD1xjEQfGOUhllCGGJVNY34bRr6lPINhNjyZw==",
      "dev": true
    },
    "husky": {
      "version": "8.0.2",
      "resolved": "https://registry.npmjs.org/husky/-/husky-8.0.2.tgz",
      "integrity": "sha512-Tkv80jtvbnkK3mYWxPZePGFpQ/tT3HNSs/sasF9P2YfkMezDl3ON37YN6jUUI4eTg5LcyVynlb6r4eyvOmspvg==",
      "dev": true
    },
    "iconv-lite": {
      "version": "0.4.24",
      "resolved": "https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.24.tgz",
      "integrity": "sha512-v3MXnZAcvnywkTUEZomIActle7RXXeedOR31wwl7VlyoXO4Qi9arvSenNQWne1TcRwhCL1HwLI21bEqdpj8/rA==",
      "dev": true,
      "requires": {
        "safer-buffer": ">= 2.1.2 < 3"
      }
    },
    "ignore": {
      "version": "4.0.6",
      "resolved": "https://registry.npmjs.org/ignore/-/ignore-4.0.6.tgz",
      "integrity": "sha512-cyFDKrqc/YdcWFniJhzI42+AzS+gNwmUzOSFcRCQYwySuBBBy/KjuxWLZ/FHEH6Moq1NizMOBWyTcv8O4OZIMg==",
      "dev": true
    },
    "import-fresh": {
      "version": "3.3.0",
      "resolved": "https://registry.npmjs.org/import-fresh/-/import-fresh-3.3.0.tgz",
      "integrity": "sha512-veYYhQa+D1QBKznvhUHxb8faxlrwUnxseDAbAp457E0wLNio2bOSKnjYDhMj+YiAq61xrMGhQk9iXVk5FzgQMw==",
      "dev": true,
      "requires": {
        "parent-module": "^1.0.0",
        "resolve-from": "^4.0.0"
      }
    },
    "import-local": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/import-local/-/import-local-3.0.2.tgz",
      "integrity": "sha512-vjL3+w0oulAVZ0hBHnxa/Nm5TAurf9YLQJDhqRZyqb+VKGOB6LU8t9H1Nr5CIo16vh9XfJTOoHwU0B71S557gA==",
      "dev": true,
      "requires": {
        "pkg-dir": "^4.2.0",
        "resolve-cwd": "^3.0.0"
      },
      "dependencies": {
        "pkg-dir": {
          "version": "4.2.0",
          "resolved": "https://registry.npmjs.org/pkg-dir/-/pkg-dir-4.2.0.tgz",
          "integrity": "sha512-HRDzbaKjC+AOWVXxAU/x54COGeIv9eb+6CkDSQoNTt4XyWoIJvuPsXizxu/Fr23EiekbtZwmh1IcIG/l/a10GQ==",
          "dev": true,
          "requires": {
            "find-up": "^4.0.0"
          }
        }
      }
    },
    "imurmurhash": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz",
      "integrity": "sha1-khi5srkoojixPcT7a21XbyMUU+o=",
      "dev": true
    },
    "indent-string": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/indent-string/-/indent-string-4.0.0.tgz",
      "integrity": "sha512-EdDDZu4A2OyIK7Lr/2zG+w5jmbuk1DVBnEwREQvBzspBJkCEbRa8GxU1lghYcaGJCnRWibjDXlq779X1/y5xwg==",
      "dev": true
    },
    "inflight": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/inflight/-/inflight-1.0.6.tgz",
      "integrity": "sha1-Sb1jMdfQLQwJvJEKEHW6gWW1bfk=",
      "dev": true,
      "requires": {
        "once": "^1.3.0",
        "wrappy": "1"
      }
    },
    "inherits": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/inherits/-/inherits-2.0.4.tgz",
      "integrity": "sha512-k/vGaX4/Yla3WzyMCvTQOXYeIHvqOKtnqBduzTHpzpQZzAskKMhZ2K+EnBiSM9zGSoIFeMpXKxa4dYeZIQqewQ=="
    },
    "ini": {
      "version": "1.3.8",
      "resolved": "https://registry.npmjs.org/ini/-/ini-1.3.8.tgz",
      "integrity": "sha512-JV/yugV2uzW5iMRSiZAyDtQd+nxtUnjeLt0acNdw98kKLrvuRVyB80tsREOE7yvGVgalhZ6RNXCmEHkUKBKxew==",
      "dev": true
    },
    "inquirer": {
      "version": "7.3.3",
      "resolved": "https://registry.npmjs.org/inquirer/-/inquirer-7.3.3.tgz",
      "integrity": "sha512-JG3eIAj5V9CwcGvuOmoo6LB9kbAYT8HXffUl6memuszlwDC/qvFAJw49XJ5NROSFNPxp3iQg1GqkFhaY/CR0IA==",
      "dev": true,
      "requires": {
        "ansi-escapes": "^4.2.1",
        "chalk": "^4.1.0",
        "cli-cursor": "^3.1.0",
        "cli-width": "^3.0.0",
        "external-editor": "^3.0.3",
        "figures": "^3.0.0",
        "lodash": "^4.17.19",
        "mute-stream": "0.0.8",
        "run-async": "^2.4.0",
        "rxjs": "^6.6.0",
        "string-width": "^4.1.0",
        "strip-ansi": "^6.0.0",
        "through": "^2.3.6"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "4.1.1",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-4.1.1.tgz",
          "integrity": "sha512-diHzdDKxcU+bAsUboHLPEDQiw0qEe0qd7SYUn3HgcFlWgbDcfLGswOHYeGrHKzG9z6UYf01d9VFMfZxPM1xZSg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "strip-ansi": {
          "version": "6.0.0",
          "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
          "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
          "dev": true,
          "requires": {
            "ansi-regex": "^5.0.0"
          }
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "interpret": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/interpret/-/interpret-1.4.0.tgz",
      "integrity": "sha512-agE4QfB2Lkp9uICn7BAqoscw4SZP9kTE2hxiFI3jBPmXJfdqiahTbUuKGsMoN2GtqL9AxhYioAcVvgsb1HvRbA==",
      "dev": true
    },
    "ip-regex": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/ip-regex/-/ip-regex-2.1.0.tgz",
      "integrity": "sha1-+ni/XS5pE8kRzp+BnuUUa7bYROk=",
      "dev": true
    },
    "is-accessor-descriptor": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-1.0.0.tgz",
      "integrity": "sha512-m5hnHTkcVsPfqx3AKlyttIPb7J+XykHvJP2B9bZDjlhLIoEq4XoK64Vg7boZlVWYK6LUY94dYPEE7Lh0ZkZKcQ==",
      "dev": true,
      "requires": {
        "kind-of": "^6.0.0"
      }
    },
    "is-arrayish": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/is-arrayish/-/is-arrayish-0.2.1.tgz",
      "integrity": "sha1-d8mYQFJ6qOyxqLppe4BkWnqSap0=",
      "dev": true
    },
    "is-bigint": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/is-bigint/-/is-bigint-1.0.2.tgz",
      "integrity": "sha512-0JV5+SOCQkIdzjBK9buARcV804Ddu7A0Qet6sHi3FimE9ne6m4BGQZfRn+NZiXbBk4F4XmHfDZIipLj9pX8dSA==",
      "dev": true
    },
    "is-boolean-object": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/is-boolean-object/-/is-boolean-object-1.1.1.tgz",
      "integrity": "sha512-bXdQWkECBUIAcCkeH1unwJLIpZYaa5VvuygSyS/c2lf719mTKZDU5UdDRlpd01UjADgmW8RfqaP+mRaVPdr/Ng==",
      "dev": true,
      "requires": {
        "call-bind": "^1.0.2"
      }
    },
    "is-buffer": {
      "version": "1.1.6",
      "resolved": "https://registry.npmjs.org/is-buffer/-/is-buffer-1.1.6.tgz",
      "integrity": "sha512-NcdALwpXkTm5Zvvbk7owOUSvVvBKDgKP5/ewfXEznmQFfs4ZRmanOeKBTjRVjka3QFoN6XJ+9F3USqfHqTaU5w==",
      "dev": true
    },
    "is-callable": {
      "version": "1.2.3",
      "resolved": "https://registry.npmjs.org/is-callable/-/is-callable-1.2.3.tgz",
      "integrity": "sha512-J1DcMe8UYTBSrKezuIUTUwjXsho29693unXM2YhJUTR2txK/eG47bvNa/wipPFmZFgr/N6f1GA66dv0mEyTIyQ==",
      "dev": true
    },
    "is-ci": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/is-ci/-/is-ci-2.0.0.tgz",
      "integrity": "sha512-YfJT7rkpQB0updsdHLGWrvhBJfcfzNNawYDNIyQXJz0IViGf75O8EBPKSdvw2rF+LGCsX4FZ8tcr3b19LcZq4w==",
      "dev": true,
      "requires": {
        "ci-info": "^2.0.0"
      }
    },
    "is-core-module": {
      "version": "2.4.0",
      "resolved": "https://registry.npmjs.org/is-core-module/-/is-core-module-2.4.0.tgz",
      "integrity": "sha512-6A2fkfq1rfeQZjxrZJGerpLCTHRNEBiSgnu0+obeJpEPZRUooHgsizvzv0ZjJwOz3iWIHdJtVWJ/tmPr3D21/A==",
      "dev": true,
      "requires": {
        "has": "^1.0.3"
      }
    },
    "is-data-descriptor": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-1.0.0.tgz",
      "integrity": "sha512-jbRXy1FmtAoCjQkVmIVYwuuqDFUbaOeDjmed1tOGPrsMhtJA4rD9tkgA0F1qJ3gRFRXcHYVkdeaP50Q5rE/jLQ==",
      "dev": true,
      "requires": {
        "kind-of": "^6.0.0"
      }
    },
    "is-date-object": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/is-date-object/-/is-date-object-1.0.4.tgz",
      "integrity": "sha512-/b4ZVsG7Z5XVtIxs/h9W8nvfLgSAyKYdtGWQLbqy6jA1icmgjf8WCoTKgeS4wy5tYaPePouzFMANbnj94c2Z+A==",
      "dev": true
    },
    "is-descriptor": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-1.0.2.tgz",
      "integrity": "sha512-2eis5WqQGV7peooDyLmNEPUrps9+SXX5c9pL3xEB+4e9HnGuDa7mB7kHxHw4CbqS9k1T2hOH3miL8n8WtiYVtg==",
      "dev": true,
      "requires": {
        "is-accessor-descriptor": "^1.0.0",
        "is-data-descriptor": "^1.0.0",
        "kind-of": "^6.0.2"
      }
    },
    "is-docker": {
      "version": "2.2.1",
      "resolved": "https://registry.npmjs.org/is-docker/-/is-docker-2.2.1.tgz",
      "integrity": "sha512-F+i2BKsFrH66iaUFc0woD8sLy8getkwTwtOBjvs56Cx4CgJDeKQeqfz8wAYiSb8JOprWhHH5p77PbmYCvvUuXQ==",
      "dev": true
    },
    "is-extendable": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-1.0.1.tgz",
      "integrity": "sha512-arnXMxT1hhoKo9k1LZdmlNyJdDDfy2v0fXjFlmok4+i8ul/6WlbVge9bhM74OpNPQPMGUToDtz+KXa1PneJxOA==",
      "dev": true,
      "requires": {
        "is-plain-object": "^2.0.4"
      }
    },
    "is-extglob": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/is-extglob/-/is-extglob-2.1.1.tgz",
      "integrity": "sha1-qIwCU1eR8C7TfHahueqXc8gz+MI=",
      "dev": true
    },
    "is-fullwidth-code-point": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-3.0.0.tgz",
      "integrity": "sha512-zymm5+u+sCsSWyD9qNaejV3DFvhCKclKdizYaJUuHA83RLjb7nSuGnddCHGv0hk+KY7BMAlsWeK4Ueg6EV6XQg==",
      "dev": true
    },
    "is-generator": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/is-generator/-/is-generator-1.0.3.tgz",
      "integrity": "sha1-wUwhBX7TbjKNuANHlmxpP4hjifM=",
      "dev": true
    },
    "is-generator-fn": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/is-generator-fn/-/is-generator-fn-2.1.0.tgz",
      "integrity": "sha512-cTIB4yPYL/Grw0EaSzASzg6bBy9gqCofvWN8okThAYIxKJZC+udlRAmGbM0XLeniEJSs8uEgHPGuHSe1XsOLSQ==",
      "dev": true
    },
    "is-glob": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/is-glob/-/is-glob-4.0.1.tgz",
      "integrity": "sha512-5G0tKtBTFImOqDnLB2hG6Bp2qcKEFduo4tZu9MT/H6NQv/ghhy30o55ufafxJ/LdH79LLs2Kfrn85TLKyA7BUg==",
      "dev": true,
      "requires": {
        "is-extglob": "^2.1.1"
      }
    },
    "is-negative-zero": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/is-negative-zero/-/is-negative-zero-2.0.1.tgz",
      "integrity": "sha512-2z6JzQvZRa9A2Y7xC6dQQm4FSTSTNWjKIYYTt4246eMTJmIo0Q+ZyOsU66X8lxK1AbB92dFeglPLrhwpeRKO6w==",
      "dev": true
    },
    "is-number": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/is-number/-/is-number-7.0.0.tgz",
      "integrity": "sha512-41Cifkg6e8TylSpdtTpeLVMqvSBEVzTttHvERD741+pnZ8ANv0004MRL43QKPDlK9cGvNp6NZWZUBlbGXYxxng==",
      "dev": true
    },
    "is-number-object": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/is-number-object/-/is-number-object-1.0.5.tgz",
      "integrity": "sha512-RU0lI/n95pMoUKu9v1BZP5MBcZuNSVJkMkAG2dJqC4z2GlkGUNeH68SuHuBKBD/XFe+LHZ+f9BKkLET60Niedw==",
      "dev": true
    },
    "is-plain-object": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/is-plain-object/-/is-plain-object-2.0.4.tgz",
      "integrity": "sha512-h5PpgXkWitc38BBMYawTYMWJHFZJVnBquFE57xFpjB8pJFiF6gZ+bU+WyI/yqXiFR5mdLsgYNaPe8uao6Uv9Og==",
      "dev": true,
      "requires": {
        "isobject": "^3.0.1"
      }
    },
    "is-port-reachable": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/is-port-reachable/-/is-port-reachable-4.0.0.tgz",
      "integrity": "sha512-9UoipoxYmSk6Xy7QFgRv2HDyaysmgSG75TFQs6S+3pDM7ZhKTF/bskZV+0UlABHzKjNVhPjYCLfeZUEg1wXxig==",
      "dev": true
    },
    "is-regex": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/is-regex/-/is-regex-1.1.3.tgz",
      "integrity": "sha512-qSVXFz28HM7y+IWX6vLCsexdlvzT1PJNFSBuaQLQ5o0IEw8UDYW6/2+eCMVyIsbM8CNLX2a/QWmSpyxYEHY7CQ==",
      "dev": true,
      "requires": {
        "call-bind": "^1.0.2",
        "has-symbols": "^1.0.2"
      }
    },
    "is-stream": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/is-stream/-/is-stream-2.0.0.tgz",
      "integrity": "sha512-XCoy+WlUr7d1+Z8GgSuXmpuUFC9fOhRXglJMx+dwLKTkL44Cjd4W1Z5P+BQZpr+cR93aGP4S/s7Ftw6Nd/kiEw==",
      "dev": true
    },
    "is-string": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/is-string/-/is-string-1.0.6.tgz",
      "integrity": "sha512-2gdzbKUuqtQ3lYNrUTQYoClPhm7oQu4UdpSZMp1/DGgkHBT8E2Z1l0yMdb6D4zNAxwDiMv8MdulKROJGNl0Q0w==",
      "dev": true
    },
    "is-symbol": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/is-symbol/-/is-symbol-1.0.4.tgz",
      "integrity": "sha512-C/CPBqKWnvdcxqIARxyOh4v1UUEOCHpgDa0WYgpKDFMszcrPcffg5uhwSgPCLD2WWxmq6isisz87tzT01tuGhg==",
      "dev": true,
      "requires": {
        "has-symbols": "^1.0.2"
      }
    },
    "is-typedarray": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz",
      "integrity": "sha1-5HnICFjfDBsR3dppQPlgEfzaSpo=",
      "dev": true
    },
    "is-windows": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/is-windows/-/is-windows-1.0.2.tgz",
      "integrity": "sha512-eXK1UInq2bPmjyX6e3VHIzMLobc4J94i4AWn+Hpq3OU5KkrRC96OAcR3PRJ/pGu6m8TRnBHP9dkXQVsT/COVIA==",
      "dev": true
    },
    "is-wsl": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/is-wsl/-/is-wsl-2.2.0.tgz",
      "integrity": "sha512-fKzAra0rGJUUBwGBgNkHZuToZcn+TtXHpeCgmkMJMMYx1sQDYaCSyjJBSCa2nH1DGm7s3n1oBnohoVTBaN7Lww==",
      "dev": true,
      "requires": {
        "is-docker": "^2.0.0"
      }
    },
    "isarray": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/isarray/-/isarray-1.0.0.tgz",
      "integrity": "sha1-u5NdSFgsuhaMBoNJV6VKPgcSTxE=",
      "dev": true
    },
    "isexe": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/isexe/-/isexe-2.0.0.tgz",
      "integrity": "sha1-6PvzdNxVb/iUehDcsFctYz8s+hA=",
      "dev": true
    },
    "isobject": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/isobject/-/isobject-3.0.1.tgz",
      "integrity": "sha1-TkMekrEalzFjaqH5yNHMvP2reN8=",
      "dev": true
    },
    "isstream": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz",
      "integrity": "sha1-R+Y/evVa+m+S4VAOaQ64uFKcCZo=",
      "dev": true
    },
    "istanbul-lib-coverage": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/istanbul-lib-coverage/-/istanbul-lib-coverage-3.0.0.tgz",
      "integrity": "sha512-UiUIqxMgRDET6eR+o5HbfRYP1l0hqkWOs7vNxC/mggutCMUIhWMm8gAHb8tHlyfD3/l6rlgNA5cKdDzEAf6hEg==",
      "dev": true
    },
    "istanbul-lib-instrument": {
      "version": "4.0.3",
      "resolved": "https://registry.npmjs.org/istanbul-lib-instrument/-/istanbul-lib-instrument-4.0.3.tgz",
      "integrity": "sha512-BXgQl9kf4WTCPCCpmFGoJkz/+uhvm7h7PFKUYxh7qarQd3ER33vHG//qaE8eN25l07YqZPpHXU9I09l/RD5aGQ==",
      "dev": true,
      "requires": {
        "@babel/core": "^7.7.5",
        "@istanbuljs/schema": "^0.1.2",
        "istanbul-lib-coverage": "^3.0.0",
        "semver": "^6.3.0"
      },
      "dependencies": {
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
          "dev": true
        }
      }
    },
    "istanbul-lib-report": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/istanbul-lib-report/-/istanbul-lib-report-3.0.0.tgz",
      "integrity": "sha512-wcdi+uAKzfiGT2abPpKZ0hSU1rGQjUQnLvtY5MpQ7QCTahD3VODhcu4wcfY1YtkGaDD5yuydOLINXsfbus9ROw==",
      "dev": true,
      "requires": {
        "istanbul-lib-coverage": "^3.0.0",
        "make-dir": "^3.0.0",
        "supports-color": "^7.1.0"
      },
      "dependencies": {
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "istanbul-lib-source-maps": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/istanbul-lib-source-maps/-/istanbul-lib-source-maps-4.0.0.tgz",
      "integrity": "sha512-c16LpFRkR8vQXyHZ5nLpY35JZtzj1PQY1iZmesUbf1FZHbIupcWfjgOXBY9YHkLEQ6puz1u4Dgj6qmU/DisrZg==",
      "dev": true,
      "requires": {
        "debug": "^4.1.1",
        "istanbul-lib-coverage": "^3.0.0",
        "source-map": "^0.6.1"
      }
    },
    "istanbul-reports": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/istanbul-reports/-/istanbul-reports-3.0.2.tgz",
      "integrity": "sha512-9tZvz7AiR3PEDNGiV9vIouQ/EAcqMXFmkcA1CDFTwOB98OZVDL0PH9glHotf5Ugp6GCOTypfzGWI/OqjWNCRUw==",
      "dev": true,
      "requires": {
        "html-escaper": "^2.0.0",
        "istanbul-lib-report": "^3.0.0"
      }
    },
    "iterall": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/iterall/-/iterall-1.3.0.tgz",
      "integrity": "sha512-QZ9qOMdF+QLHxy1QIpUHUU1D5pS2CG2P69LF6L6CPjPYA/XMOmKV3PZpawHoAjHNyB0swdVTRxdYT4tbBbxqwg=="
    },
    "jest": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest/-/jest-25.5.4.tgz",
      "integrity": "sha512-hHFJROBTqZahnO+X+PMtT6G2/ztqAZJveGqz//FnWWHurizkD05PQGzRZOhF3XP6z7SJmL+5tCfW8qV06JypwQ==",
      "dev": true,
      "requires": {
        "@jest/core": "^25.5.4",
        "import-local": "^3.0.2",
        "jest-cli": "^25.5.4"
      }
    },
    "jest-changed-files": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-changed-files/-/jest-changed-files-25.5.0.tgz",
      "integrity": "sha512-EOw9QEqapsDT7mKF162m8HFzRPbmP8qJQny6ldVOdOVBz3ACgPm/1nAn5fPQ/NDaYhX/AHkrGwwkCncpAVSXcw==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "execa": "^3.2.0",
        "throat": "^5.0.0"
      }
    },
    "jest-cli": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-cli/-/jest-cli-25.5.4.tgz",
      "integrity": "sha512-rG8uJkIiOUpnREh1768/N3n27Cm+xPFkSNFO91tgg+8o2rXeVLStz+vkXkGr4UtzH6t1SNbjwoiswd7p4AhHTw==",
      "dev": true,
      "requires": {
        "@jest/core": "^25.5.4",
        "@jest/test-result": "^25.5.0",
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "exit": "^0.1.2",
        "graceful-fs": "^4.2.4",
        "import-local": "^3.0.2",
        "is-ci": "^2.0.0",
        "jest-config": "^25.5.4",
        "jest-util": "^25.5.0",
        "jest-validate": "^25.5.0",
        "prompts": "^2.0.1",
        "realpath-native": "^2.0.0",
        "yargs": "^15.3.1"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-config": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-config/-/jest-config-25.5.4.tgz",
      "integrity": "sha512-SZwR91SwcdK6bz7Gco8qL7YY2sx8tFJYzvg216DLihTWf+LKY/DoJXpM9nTzYakSyfblbqeU48p/p7Jzy05Atg==",
      "dev": true,
      "requires": {
        "@babel/core": "^7.1.0",
        "@jest/test-sequencer": "^25.5.4",
        "@jest/types": "^25.5.0",
        "babel-jest": "^25.5.1",
        "chalk": "^3.0.0",
        "deepmerge": "^4.2.2",
        "glob": "^7.1.1",
        "graceful-fs": "^4.2.4",
        "jest-environment-jsdom": "^25.5.0",
        "jest-environment-node": "^25.5.0",
        "jest-get-type": "^25.2.6",
        "jest-jasmine2": "^25.5.4",
        "jest-regex-util": "^25.2.6",
        "jest-resolve": "^25.5.1",
        "jest-util": "^25.5.0",
        "jest-validate": "^25.5.0",
        "micromatch": "^4.0.2",
        "pretty-format": "^25.5.0",
        "realpath-native": "^2.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-diff": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-diff/-/jest-diff-25.5.0.tgz",
      "integrity": "sha512-z1kygetuPiREYdNIumRpAHY6RXiGmp70YHptjdaxTWGmA085W3iCnXNx0DhflK3vwrKmrRWyY1wUpkPMVxMK7A==",
      "dev": true,
      "requires": {
        "chalk": "^3.0.0",
        "diff-sequences": "^25.2.6",
        "jest-get-type": "^25.2.6",
        "pretty-format": "^25.5.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-docblock": {
      "version": "25.3.0",
      "resolved": "https://registry.npmjs.org/jest-docblock/-/jest-docblock-25.3.0.tgz",
      "integrity": "sha512-aktF0kCar8+zxRHxQZwxMy70stc9R1mOmrLsT5VO3pIT0uzGRSDAXxSlz4NqQWpuLjPpuMhPRl7H+5FRsvIQAg==",
      "dev": true,
      "requires": {
        "detect-newline": "^3.0.0"
      }
    },
    "jest-each": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-each/-/jest-each-25.5.0.tgz",
      "integrity": "sha512-QBogUxna3D8vtiItvn54xXde7+vuzqRrEeaw8r1s+1TG9eZLVJE5ZkKoSUlqFwRjnlaA4hyKGiu9OlkFIuKnjA==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "jest-get-type": "^25.2.6",
        "jest-util": "^25.5.0",
        "pretty-format": "^25.5.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-environment-jsdom": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-environment-jsdom/-/jest-environment-jsdom-25.5.0.tgz",
      "integrity": "sha512-7Jr02ydaq4jaWMZLY+Skn8wL5nVIYpWvmeatOHL3tOcV3Zw8sjnPpx+ZdeBfc457p8jCR9J6YCc+Lga0oIy62A==",
      "dev": true,
      "requires": {
        "@jest/environment": "^25.5.0",
        "@jest/fake-timers": "^25.5.0",
        "@jest/types": "^25.5.0",
        "jest-mock": "^25.5.0",
        "jest-util": "^25.5.0",
        "jsdom": "^15.2.1"
      }
    },
    "jest-environment-node": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-environment-node/-/jest-environment-node-25.5.0.tgz",
      "integrity": "sha512-iuxK6rQR2En9EID+2k+IBs5fCFd919gVVK5BeND82fYeLWPqvRcFNPKu9+gxTwfB5XwBGBvZ0HFQa+cHtIoslA==",
      "dev": true,
      "requires": {
        "@jest/environment": "^25.5.0",
        "@jest/fake-timers": "^25.5.0",
        "@jest/types": "^25.5.0",
        "jest-mock": "^25.5.0",
        "jest-util": "^25.5.0",
        "semver": "^6.3.0"
      },
      "dependencies": {
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
          "dev": true
        }
      }
    },
    "jest-get-type": {
      "version": "25.2.6",
      "resolved": "https://registry.npmjs.org/jest-get-type/-/jest-get-type-25.2.6.tgz",
      "integrity": "sha512-DxjtyzOHjObRM+sM1knti6or+eOgcGU4xVSb2HNP1TqO4ahsT+rqZg+nyqHWJSvWgKC5cG3QjGFBqxLghiF/Ig==",
      "dev": true
    },
    "jest-haste-map": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/jest-haste-map/-/jest-haste-map-25.5.1.tgz",
      "integrity": "sha512-dddgh9UZjV7SCDQUrQ+5t9yy8iEgKc1AKqZR9YDww8xsVOtzPQSMVLDChc21+g29oTRexb9/B0bIlZL+sWmvAQ==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "@types/graceful-fs": "^4.1.2",
        "anymatch": "^3.0.3",
        "fb-watchman": "^2.0.0",
        "fsevents": "^2.1.2",
        "graceful-fs": "^4.2.4",
        "jest-serializer": "^25.5.0",
        "jest-util": "^25.5.0",
        "jest-worker": "^25.5.0",
        "micromatch": "^4.0.2",
        "sane": "^4.0.3",
        "walker": "^1.0.7",
        "which": "^2.0.2"
      },
      "dependencies": {
        "which": {
          "version": "2.0.2",
          "resolved": "https://registry.npmjs.org/which/-/which-2.0.2.tgz",
          "integrity": "sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==",
          "dev": true,
          "requires": {
            "isexe": "^2.0.0"
          }
        }
      }
    },
    "jest-jasmine2": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-jasmine2/-/jest-jasmine2-25.5.4.tgz",
      "integrity": "sha512-9acbWEfbmS8UpdcfqnDO+uBUgKa/9hcRh983IHdM+pKmJPL77G0sWAAK0V0kr5LK3a8cSBfkFSoncXwQlRZfkQ==",
      "dev": true,
      "requires": {
        "@babel/traverse": "^7.1.0",
        "@jest/environment": "^25.5.0",
        "@jest/source-map": "^25.5.0",
        "@jest/test-result": "^25.5.0",
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "co": "^4.6.0",
        "expect": "^25.5.0",
        "is-generator-fn": "^2.0.0",
        "jest-each": "^25.5.0",
        "jest-matcher-utils": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-runtime": "^25.5.4",
        "jest-snapshot": "^25.5.1",
        "jest-util": "^25.5.0",
        "pretty-format": "^25.5.0",
        "throat": "^5.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-leak-detector": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-leak-detector/-/jest-leak-detector-25.5.0.tgz",
      "integrity": "sha512-rV7JdLsanS8OkdDpZtgBf61L5xZ4NnYLBq72r6ldxahJWWczZjXawRsoHyXzibM5ed7C2QRjpp6ypgwGdKyoVA==",
      "dev": true,
      "requires": {
        "jest-get-type": "^25.2.6",
        "pretty-format": "^25.5.0"
      }
    },
    "jest-matcher-utils": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-matcher-utils/-/jest-matcher-utils-25.5.0.tgz",
      "integrity": "sha512-VWI269+9JS5cpndnpCwm7dy7JtGQT30UHfrnM3mXl22gHGt/b7NkjBqXfbhZ8V4B7ANUsjK18PlSBmG0YH7gjw==",
      "dev": true,
      "requires": {
        "chalk": "^3.0.0",
        "jest-diff": "^25.5.0",
        "jest-get-type": "^25.2.6",
        "pretty-format": "^25.5.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-message-util": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-message-util/-/jest-message-util-25.5.0.tgz",
      "integrity": "sha512-ezddz3YCT/LT0SKAmylVyWWIGYoKHOFOFXx3/nA4m794lfVUskMcwhip6vTgdVrOtYdjeQeis2ypzes9mZb4EA==",
      "dev": true,
      "requires": {
        "@babel/code-frame": "^7.0.0",
        "@jest/types": "^25.5.0",
        "@types/stack-utils": "^1.0.1",
        "chalk": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "micromatch": "^4.0.2",
        "slash": "^3.0.0",
        "stack-utils": "^1.0.1"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-mock": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-mock/-/jest-mock-25.5.0.tgz",
      "integrity": "sha512-eXWuTV8mKzp/ovHc5+3USJMYsTBhyQ+5A1Mak35dey/RG8GlM4YWVylZuGgVXinaW6tpvk/RSecmF37FKUlpXA==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0"
      }
    },
    "jest-pnp-resolver": {
      "version": "1.2.2",
      "resolved": "https://registry.npmjs.org/jest-pnp-resolver/-/jest-pnp-resolver-1.2.2.tgz",
      "integrity": "sha512-olV41bKSMm8BdnuMsewT4jqlZ8+3TCARAXjZGT9jcoSnrfUnRCqnMoF9XEeoWjbzObpqF9dRhHQj0Xb9QdF6/w==",
      "dev": true,
      "requires": {}
    },
    "jest-regex-util": {
      "version": "25.2.6",
      "resolved": "https://registry.npmjs.org/jest-regex-util/-/jest-regex-util-25.2.6.tgz",
      "integrity": "sha512-KQqf7a0NrtCkYmZZzodPftn7fL1cq3GQAFVMn5Hg8uKx/fIenLEobNanUxb7abQ1sjADHBseG/2FGpsv/wr+Qw==",
      "dev": true
    },
    "jest-resolve": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/jest-resolve/-/jest-resolve-25.5.1.tgz",
      "integrity": "sha512-Hc09hYch5aWdtejsUZhA+vSzcotf7fajSlPA6EZPE1RmPBAD39XtJhvHWFStid58iit4IPDLI/Da4cwdDmAHiQ==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "browser-resolve": "^1.11.3",
        "chalk": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "jest-pnp-resolver": "^1.2.1",
        "read-pkg-up": "^7.0.1",
        "realpath-native": "^2.0.0",
        "resolve": "^1.17.0",
        "slash": "^3.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-resolve-dependencies": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-resolve-dependencies/-/jest-resolve-dependencies-25.5.4.tgz",
      "integrity": "sha512-yFmbPd+DAQjJQg88HveObcGBA32nqNZ02fjYmtL16t1xw9bAttSn5UGRRhzMHIQbsep7znWvAvnD4kDqOFM0Uw==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "jest-regex-util": "^25.2.6",
        "jest-snapshot": "^25.5.1"
      }
    },
    "jest-runner": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-runner/-/jest-runner-25.5.4.tgz",
      "integrity": "sha512-V/2R7fKZo6blP8E9BL9vJ8aTU4TH2beuqGNxHbxi6t14XzTb+x90B3FRgdvuHm41GY8ch4xxvf0ATH4hdpjTqg==",
      "dev": true,
      "requires": {
        "@jest/console": "^25.5.0",
        "@jest/environment": "^25.5.0",
        "@jest/test-result": "^25.5.0",
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "exit": "^0.1.2",
        "graceful-fs": "^4.2.4",
        "jest-config": "^25.5.4",
        "jest-docblock": "^25.3.0",
        "jest-haste-map": "^25.5.1",
        "jest-jasmine2": "^25.5.4",
        "jest-leak-detector": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-resolve": "^25.5.1",
        "jest-runtime": "^25.5.4",
        "jest-util": "^25.5.0",
        "jest-worker": "^25.5.0",
        "source-map-support": "^0.5.6",
        "throat": "^5.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-runtime": {
      "version": "25.5.4",
      "resolved": "https://registry.npmjs.org/jest-runtime/-/jest-runtime-25.5.4.tgz",
      "integrity": "sha512-RWTt8LeWh3GvjYtASH2eezkc8AehVoWKK20udV6n3/gC87wlTbE1kIA+opCvNWyyPeBs6ptYsc6nyHUb1GlUVQ==",
      "dev": true,
      "requires": {
        "@jest/console": "^25.5.0",
        "@jest/environment": "^25.5.0",
        "@jest/globals": "^25.5.2",
        "@jest/source-map": "^25.5.0",
        "@jest/test-result": "^25.5.0",
        "@jest/transform": "^25.5.1",
        "@jest/types": "^25.5.0",
        "@types/yargs": "^15.0.0",
        "chalk": "^3.0.0",
        "collect-v8-coverage": "^1.0.0",
        "exit": "^0.1.2",
        "glob": "^7.1.3",
        "graceful-fs": "^4.2.4",
        "jest-config": "^25.5.4",
        "jest-haste-map": "^25.5.1",
        "jest-message-util": "^25.5.0",
        "jest-mock": "^25.5.0",
        "jest-regex-util": "^25.2.6",
        "jest-resolve": "^25.5.1",
        "jest-snapshot": "^25.5.1",
        "jest-util": "^25.5.0",
        "jest-validate": "^25.5.0",
        "realpath-native": "^2.0.0",
        "slash": "^3.0.0",
        "strip-bom": "^4.0.0",
        "yargs": "^15.3.1"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-serializer": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-serializer/-/jest-serializer-25.5.0.tgz",
      "integrity": "sha512-LxD8fY1lByomEPflwur9o4e2a5twSQ7TaVNLlFUuToIdoJuBt8tzHfCsZ42Ok6LkKXWzFWf3AGmheuLAA7LcCA==",
      "dev": true,
      "requires": {
        "graceful-fs": "^4.2.4"
      }
    },
    "jest-snapshot": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/jest-snapshot/-/jest-snapshot-25.5.1.tgz",
      "integrity": "sha512-C02JE1TUe64p2v1auUJ2ze5vcuv32tkv9PyhEb318e8XOKF7MOyXdJ7kdjbvrp3ChPLU2usI7Rjxs97Dj5P0uQ==",
      "dev": true,
      "requires": {
        "@babel/types": "^7.0.0",
        "@jest/types": "^25.5.0",
        "@types/prettier": "^1.19.0",
        "chalk": "^3.0.0",
        "expect": "^25.5.0",
        "graceful-fs": "^4.2.4",
        "jest-diff": "^25.5.0",
        "jest-get-type": "^25.2.6",
        "jest-matcher-utils": "^25.5.0",
        "jest-message-util": "^25.5.0",
        "jest-resolve": "^25.5.1",
        "make-dir": "^3.0.0",
        "natural-compare": "^1.4.0",
        "pretty-format": "^25.5.0",
        "semver": "^6.3.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-util": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-util/-/jest-util-25.5.0.tgz",
      "integrity": "sha512-KVlX+WWg1zUTB9ktvhsg2PXZVdkI1NBevOJSkTKYAyXyH4QSvh+Lay/e/v+bmaFfrkfx43xD8QTfgobzlEXdIA==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "chalk": "^3.0.0",
        "graceful-fs": "^4.2.4",
        "is-ci": "^2.0.0",
        "make-dir": "^3.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-validate": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-validate/-/jest-validate-25.5.0.tgz",
      "integrity": "sha512-okUFKqhZIpo3jDdtUXUZ2LxGUZJIlfdYBvZb1aczzxrlyMlqdnnws9MOxezoLGhSaFc2XYaHNReNQfj5zPIWyQ==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "camelcase": "^5.3.1",
        "chalk": "^3.0.0",
        "jest-get-type": "^25.2.6",
        "leven": "^3.1.0",
        "pretty-format": "^25.5.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-watcher": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-watcher/-/jest-watcher-25.5.0.tgz",
      "integrity": "sha512-XrSfJnVASEl+5+bb51V0Q7WQx65dTSk7NL4yDdVjPnRNpM0hG+ncFmDYJo9O8jaSRcAitVbuVawyXCRoxGrT5Q==",
      "dev": true,
      "requires": {
        "@jest/test-result": "^25.5.0",
        "@jest/types": "^25.5.0",
        "ansi-escapes": "^4.2.1",
        "chalk": "^3.0.0",
        "jest-util": "^25.5.0",
        "string-length": "^3.1.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "chalk": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-3.0.0.tgz",
          "integrity": "sha512-4D3B6Wf41KOYRFdszmDqMCGq5VV/uMAB273JILmO+3jAlh8X4qDtdtgCR3fxtbLEMzSx22QdhnDcJvu2u1fVwg==",
          "dev": true,
          "requires": {
            "ansi-styles": "^4.1.0",
            "supports-color": "^7.1.0"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "jest-worker": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/jest-worker/-/jest-worker-25.5.0.tgz",
      "integrity": "sha512-/dsSmUkIy5EBGfv/IjjqmFxrNAUpBERfGs1oHROyD7yxjG/w+t0GOJDX8O1k32ySmd7+a5IhnJU2qQFcJ4n1vw==",
      "dev": true,
      "requires": {
        "merge-stream": "^2.0.0",
        "supports-color": "^7.0.0"
      },
      "dependencies": {
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "js-sha3": {
      "version": "0.8.0",
      "resolved": "https://registry.npmjs.org/js-sha3/-/js-sha3-0.8.0.tgz",
      "integrity": "sha512-gF1cRrHhIzNfToc802P800N8PpXS+evLLXfsVpowqmAFR9uwbi89WvXg2QspOmXL8QL86J4T1EpFu+yUkwJY3Q=="
    },
    "js-tokens": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/js-tokens/-/js-tokens-4.0.0.tgz",
      "integrity": "sha512-RdJUflcE3cUzKiMqQgsCu06FPu9UdIJO0beYbPhHN4k6apgJtifcoCtT9bcxOpYBtpD2kCM6Sbzg4CausW/PKQ=="
    },
    "js-yaml": {
      "version": "3.14.1",
      "resolved": "https://registry.npmjs.org/js-yaml/-/js-yaml-3.14.1.tgz",
      "integrity": "sha512-okMH7OXXJ7YrN9Ok3/SXrnu4iX9yOk+25nqX4imS2npuvTYDmo/QEZoqwZkYaIDk3jVvBOTOIEgEhaLOynBS9g==",
      "dev": true,
      "requires": {
        "argparse": "^1.0.7",
        "esprima": "^4.0.0"
      }
    },
    "jsbn": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/jsbn/-/jsbn-0.1.1.tgz",
      "integrity": "sha1-peZUwuWi3rXyAdls77yoDA7y9RM=",
      "dev": true
    },
    "jsdom": {
      "version": "15.2.1",
      "resolved": "https://registry.npmjs.org/jsdom/-/jsdom-15.2.1.tgz",
      "integrity": "sha512-fAl1W0/7T2G5vURSyxBzrJ1LSdQn6Tr5UX/xD4PXDx/PDgwygedfW6El/KIj3xJ7FU61TTYnc/l/B7P49Eqt6g==",
      "dev": true,
      "requires": {
        "abab": "^2.0.0",
        "acorn": "^7.1.0",
        "acorn-globals": "^4.3.2",
        "array-equal": "^1.0.0",
        "cssom": "^0.4.1",
        "cssstyle": "^2.0.0",
        "data-urls": "^1.1.0",
        "domexception": "^1.0.1",
        "escodegen": "^1.11.1",
        "html-encoding-sniffer": "^1.0.2",
        "nwsapi": "^2.2.0",
        "parse5": "5.1.0",
        "pn": "^1.1.0",
        "request": "^2.88.0",
        "request-promise-native": "^1.0.7",
        "saxes": "^3.1.9",
        "symbol-tree": "^3.2.2",
        "tough-cookie": "^3.0.1",
        "w3c-hr-time": "^1.0.1",
        "w3c-xmlserializer": "^1.1.2",
        "webidl-conversions": "^4.0.2",
        "whatwg-encoding": "^1.0.5",
        "whatwg-mimetype": "^2.3.0",
        "whatwg-url": "^7.0.0",
        "ws": "^7.0.0",
        "xml-name-validator": "^3.0.0"
      }
    },
    "jsesc": {
      "version": "2.5.2",
      "resolved": "https://registry.npmjs.org/jsesc/-/jsesc-2.5.2.tgz",
      "integrity": "sha512-OYu7XEzjkCQ3C5Ps3QIZsQfNpqoJyZZA99wd9aWd05NCtC5pWOkShK2mkL6HXQR6/Cy2lbNdPlZBpuQHXE63gA==",
      "dev": true
    },
    "json-parse-even-better-errors": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/json-parse-even-better-errors/-/json-parse-even-better-errors-2.3.1.tgz",
      "integrity": "sha512-xyFwyhro/JEof6Ghe2iz2NcXoj2sloNsWr/XsERDK/oiPCfaNhl5ONfp+jQdAZRQQ0IJWNzH9zIZF7li91kh2w==",
      "dev": true
    },
    "json-schema": {
      "version": "0.2.3",
      "resolved": "https://registry.npmjs.org/json-schema/-/json-schema-0.2.3.tgz",
      "integrity": "sha1-tIDIkuWaLwWVTOcnvT8qTogvnhM=",
      "dev": true
    },
    "json-schema-traverse": {
      "version": "0.4.1",
      "resolved": "https://registry.npmjs.org/json-schema-traverse/-/json-schema-traverse-0.4.1.tgz",
      "integrity": "sha512-xbbCH5dCYU5T8LcEhhuh7HJ88HXuW3qsI3Y0zOZFKfZEHcpWiHU/Jxzk629Brsab/mMiHQti9wMP+845RPe3Vg==",
      "dev": true
    },
    "json-stable-stringify-without-jsonify": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/json-stable-stringify-without-jsonify/-/json-stable-stringify-without-jsonify-1.0.1.tgz",
      "integrity": "sha1-nbe1lJatPzz+8wp1FC0tkwrXJlE=",
      "dev": true
    },
    "json-stringify-safe": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/json-stringify-safe/-/json-stringify-safe-5.0.1.tgz",
      "integrity": "sha1-Epai1Y/UXxmg9s4B1lcB4sc1tus=",
      "dev": true
    },
    "json5": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/json5/-/json5-2.2.0.tgz",
      "integrity": "sha512-f+8cldu7X/y7RAJurMEJmdoKXGB/X550w2Nr3tTbezL6RwEE/iMcm+tZnXeoZtKuOq6ft8+CqzEkrIgx1fPoQA==",
      "dev": true,
      "requires": {
        "minimist": "^1.2.5"
      }
    },
    "jsonfile": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/jsonfile/-/jsonfile-4.0.0.tgz",
      "integrity": "sha1-h3Gq4HmbZAdrdmQPygWPnBDjPss=",
      "dev": true,
      "requires": {
        "graceful-fs": "^4.1.6"
      }
    },
    "jsprim": {
      "version": "1.4.1",
      "resolved": "https://registry.npmjs.org/jsprim/-/jsprim-1.4.1.tgz",
      "integrity": "sha1-MT5mvB5cwG5Di8G3SZwuXFastqI=",
      "dev": true,
      "requires": {
        "assert-plus": "1.0.0",
        "extsprintf": "1.3.0",
        "json-schema": "0.2.3",
        "verror": "1.10.0"
      }
    },
    "kind-of": {
      "version": "6.0.3",
      "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-6.0.3.tgz",
      "integrity": "sha512-dcS1ul+9tmeD95T+x28/ehLgd9mENa3LsvDTtzm3vyBEO7RPptvAD+t44WVXaUjTBRcrpFeFlC8WCruUR456hw==",
      "dev": true
    },
    "kleur": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/kleur/-/kleur-3.0.3.tgz",
      "integrity": "sha512-eTIzlVOSUR+JxdDFepEYcBMtZ9Qqdef+rnzWdRZuMbOywu5tO2w2N7rqjoANZ5k9vywhL6Br1VRjUIgTQx4E8w==",
      "dev": true
    },
    "knuth-shuffle-seeded": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/knuth-shuffle-seeded/-/knuth-shuffle-seeded-1.0.6.tgz",
      "integrity": "sha1-AfG2VzOqdUDuCNiwF0Fk0iCB5OE=",
      "dev": true,
      "requires": {
        "seed-random": "~2.2.0"
      }
    },
    "leven": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/leven/-/leven-3.1.0.tgz",
      "integrity": "sha512-qsda+H8jTaUaN/x5vzW2rzc+8Rw4TAQ/4KjB46IwK5VH+IlVeeeje/EoZRpiXvIqjFgK84QffqPztGI3VBLG1A==",
      "dev": true
    },
    "levn": {
      "version": "0.3.0",
      "resolved": "https://registry.npmjs.org/levn/-/levn-0.3.0.tgz",
      "integrity": "sha1-OwmSTt+fCDwEkP3UwLxEIeBHZO4=",
      "dev": true,
      "requires": {
        "prelude-ls": "~1.1.2",
        "type-check": "~0.3.2"
      }
    },
    "libphonenumber-js": {
      "version": "1.10.18",
      "resolved": "https://registry.npmjs.org/libphonenumber-js/-/libphonenumber-js-1.10.18.tgz",
      "integrity": "sha512-NS4ZEgNhwbcPz1gfSXCGFnQm0xEiyTSPRthIuWytDzOiEG9xnZ2FbLyfJC4tI2BMAAXpoWbNxHYH75pa3Dq9og=="
    },
    "lines-and-columns": {
      "version": "1.1.6",
      "resolved": "https://registry.npmjs.org/lines-and-columns/-/lines-and-columns-1.1.6.tgz",
      "integrity": "sha1-HADHQ7QzzQpOgHWPe2SldEDZ/wA=",
      "dev": true
    },
    "load-json-file": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/load-json-file/-/load-json-file-2.0.0.tgz",
      "integrity": "sha1-eUfkIUmvgNaWy/eXvKq8/h/inKg=",
      "dev": true,
      "requires": {
        "graceful-fs": "^4.1.2",
        "parse-json": "^2.2.0",
        "pify": "^2.0.0",
        "strip-bom": "^3.0.0"
      },
      "dependencies": {
        "parse-json": {
          "version": "2.2.0",
          "resolved": "https://registry.npmjs.org/parse-json/-/parse-json-2.2.0.tgz",
          "integrity": "sha1-9ID0BDTvgHQfhGkJn43qGPVaTck=",
          "dev": true,
          "requires": {
            "error-ex": "^1.2.0"
          }
        },
        "strip-bom": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/strip-bom/-/strip-bom-3.0.0.tgz",
          "integrity": "sha1-IzTBjpx1n3vdVv3vfprj1YjmjtM=",
          "dev": true
        }
      }
    },
    "locate-path": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/locate-path/-/locate-path-5.0.0.tgz",
      "integrity": "sha512-t7hw9pI+WvuwNJXwk5zVHpyhIqzg2qTlklJOf0mVxGSbe3Fp2VieZcduNYjaLDoy6p9uGpQEGWG87WpMKlNq8g==",
      "dev": true,
      "requires": {
        "p-locate": "^4.1.0"
      }
    },
    "lodash": {
      "version": "4.17.21",
      "resolved": "https://registry.npmjs.org/lodash/-/lodash-4.17.21.tgz",
      "integrity": "sha512-v2kDEe57lecTulaDIuNTPy3Ry4gLGJ6Z1O3vE1krgXZNrsQ+LFTGHVxVjcXPs17LhbZVGedAJv8XZ1tvj5FvSg=="
    },
    "lodash.memoize": {
      "version": "4.1.2",
      "resolved": "https://registry.npmjs.org/lodash.memoize/-/lodash.memoize-4.1.2.tgz",
      "integrity": "sha1-vMbEmkKihA7Zl/Mj6tpezRguC/4=",
      "dev": true
    },
    "lodash.sortby": {
      "version": "4.7.0",
      "resolved": "https://registry.npmjs.org/lodash.sortby/-/lodash.sortby-4.7.0.tgz",
      "integrity": "sha1-7dFMgk4sycHgsKG0K7UhBRakJDg=",
      "dev": true
    },
    "lolex": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/lolex/-/lolex-5.1.2.tgz",
      "integrity": "sha512-h4hmjAvHTmd+25JSwrtTIuwbKdwg5NzZVRMLn9saij4SZaepCrTCxPr35H/3bjwfMJtN+t3CX8672UIkglz28A==",
      "dev": true,
      "requires": {
        "@sinonjs/commons": "^1.7.0"
      }
    },
    "long": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/long/-/long-4.0.0.tgz",
      "integrity": "sha512-XsP+KhQif4bjX1kbuSiySJFNAehNxgLb6hPRGJ9QsUr8ajHkuXGdrHmFUTUUXhDwVX2R5bY4JNZEwbUiMhV+MA==",
      "dev": true
    },
    "loose-envify": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/loose-envify/-/loose-envify-1.4.0.tgz",
      "integrity": "sha512-lyuxPGr/Wfhrlem2CL/UcnUc1zcqKAImBDzukY7Y5F/yQiNdko6+fRLevlw1HgMySw7f611UIY408EtxRSoK3Q==",
      "requires": {
        "js-tokens": "^3.0.0 || ^4.0.0"
      }
    },
    "lower-case": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/lower-case/-/lower-case-2.0.2.tgz",
      "integrity": "sha512-7fm3l3NAF9WfN6W3JOmf5drwpVqX78JtoGJ3A6W0a6ZnldM41w2fV5D490psKFTpMds8TJse/eHLFFsNHHjHgg==",
      "dev": true,
      "requires": {
        "tslib": "^2.0.3"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.0",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
          "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg==",
          "dev": true
        }
      }
    },
    "lru-cache": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/lru-cache/-/lru-cache-6.0.0.tgz",
      "integrity": "sha512-Jo6dJ04CmSjuznwJSS3pUeWmd/H0ffTlkXXgwZi+eq1UCmqQwCh+eLsYOYCwY991i2Fah4h1BEMCx4qThGbsiA==",
      "dev": true,
      "requires": {
        "yallist": "^4.0.0"
      }
    },
    "lunr": {
      "version": "2.3.9",
      "resolved": "https://registry.npmjs.org/lunr/-/lunr-2.3.9.tgz",
      "integrity": "sha512-zTU3DaZaF3Rt9rhN3uBMGQD3dD2/vFQqnvZCDv4dl5iOzq2IZQqTxu90r4E5J+nP70J3ilqVCrbho2eWaeW8Ow==",
      "dev": true
    },
    "make-dir": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/make-dir/-/make-dir-3.1.0.tgz",
      "integrity": "sha512-g3FeP20LNwhALb/6Cz6Dd4F2ngze0jz7tbzrD2wAV+o9FeNHe4rL+yK2md0J/fiSf1sa1ADhXqi5+oVwOM/eGw==",
      "dev": true,
      "requires": {
        "semver": "^6.0.0"
      },
      "dependencies": {
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
          "dev": true
        }
      }
    },
    "make-error": {
      "version": "1.3.6",
      "resolved": "https://registry.npmjs.org/make-error/-/make-error-1.3.6.tgz",
      "integrity": "sha512-s8UhlNe7vPKomQhC1qFelMokr/Sc3AgNbso3n74mVPA5LTZwkB9NlXf4XPamLxJE8h0gh73rM94xvwRT2CVInw==",
      "dev": true
    },
    "makeerror": {
      "version": "1.0.11",
      "resolved": "https://registry.npmjs.org/makeerror/-/makeerror-1.0.11.tgz",
      "integrity": "sha1-4BpckQnyr3lmDk6LlYd5AYT1qWw=",
      "dev": true,
      "requires": {
        "tmpl": "1.0.x"
      }
    },
    "map-cache": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/map-cache/-/map-cache-0.2.2.tgz",
      "integrity": "sha1-wyq9C9ZSXZsFFkW7TyasXcmKDb8=",
      "dev": true
    },
    "map-visit": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/map-visit/-/map-visit-1.0.0.tgz",
      "integrity": "sha1-7Nyo8TFE5mDxtb1B8S80edmN+48=",
      "dev": true,
      "requires": {
        "object-visit": "^1.0.0"
      }
    },
    "marked": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/marked/-/marked-1.0.0.tgz",
      "integrity": "sha512-Wo+L1pWTVibfrSr+TTtMuiMfNzmZWiOPeO7rZsQUY5bgsxpHesBEcIWJloWVTFnrMXnf/TL30eTFSGJddmQAng==",
      "dev": true
    },
    "merge-stream": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/merge-stream/-/merge-stream-2.0.0.tgz",
      "integrity": "sha512-abv/qOcuPfk3URPfDzmZU1LKmuw8kT+0nIHvKrKgFrwifol/doWcdA4ZqsWQ8ENrFKkd67Mfpo/LovbIUsbt3w==",
      "dev": true
    },
    "micromatch": {
      "version": "4.0.4",
      "resolved": "https://registry.npmjs.org/micromatch/-/micromatch-4.0.4.tgz",
      "integrity": "sha512-pRmzw/XUcwXGpD9aI9q/0XOwLNygjETJ8y0ao0wdqprrzDa4YnxLcz7fQRZr8voh8V10kGhABbNcHVk5wHgWwg==",
      "dev": true,
      "requires": {
        "braces": "^3.0.1",
        "picomatch": "^2.2.3"
      }
    },
    "mime-db": {
      "version": "1.48.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.48.0.tgz",
      "integrity": "sha512-FM3QwxV+TnZYQ2aRqhlKBMHxk10lTbMt3bBkMAp54ddrNeVSfcQYOOKuGuy3Ddrm38I04If834fOUSq1yzslJQ=="
    },
    "mime-types": {
      "version": "2.1.31",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.31.tgz",
      "integrity": "sha512-XGZnNzm3QvgKxa8dpzyhFTHmpP3l5YNusmne07VUOXxou9CqUqYa/HBy124RqtVh/O2pECas/MOcsDgpilPOPg==",
      "requires": {
        "mime-db": "1.48.0"
      }
    },
    "mimic-fn": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/mimic-fn/-/mimic-fn-2.1.0.tgz",
      "integrity": "sha512-OqbOk5oEQeAZ8WXWydlu9HJjz9WVdEIvamMCcXmuqUYjTknH/sqsWvhQ3vgwKFRR1HpjvNBKQ37nbJgYzGqGcg==",
      "dev": true
    },
    "minimalistic-assert": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/minimalistic-assert/-/minimalistic-assert-1.0.1.tgz",
      "integrity": "sha512-UtJcAD4yEaGtjPezWuO9wC4nwUnVH/8/Im3yEHQP4b67cXlD/Qr9hdITCU1xDbSEXg2XKNaP8jsReV7vQd00/A=="
    },
    "minimalistic-crypto-utils": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/minimalistic-crypto-utils/-/minimalistic-crypto-utils-1.0.1.tgz",
      "integrity": "sha1-9sAMHAsIIkblxNmd+4x8CDsrWCo="
    },
    "minimatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/minimatch/-/minimatch-3.1.2.tgz",
      "integrity": "sha512-J7p63hRiAjw1NDEww1W7i37+ByIrOWO5XQQAzZ3VOcL0PNybwpfmV/N05zFAzwQ9USyEcX6t3UO+K5aqBQOIHw==",
      "dev": true,
      "requires": {
        "brace-expansion": "^1.1.7"
      }
    },
    "minimist": {
      "version": "1.2.6",
      "resolved": "https://registry.npmjs.org/minimist/-/minimist-1.2.6.tgz",
      "integrity": "sha512-Jsjnk4bw3YJqYzbdyBiNsPWHPfO++UGG749Cxs6peCu5Xg4nrena6OVxOYxrQTqww0Jmwt+Ref8rggumkTLz9Q==",
      "dev": true
    },
    "mixin-deep": {
      "version": "1.3.2",
      "resolved": "https://registry.npmjs.org/mixin-deep/-/mixin-deep-1.3.2.tgz",
      "integrity": "sha512-WRoDn//mXBiJ1H40rqa3vH0toePwSsGb45iInWlTySa+Uu4k3tYUSxa2v1KqAiLtvlrSzaExqS1gtk96A9zvEA==",
      "dev": true,
      "requires": {
        "for-in": "^1.0.2",
        "is-extendable": "^1.0.1"
      }
    },
    "mkdirp": {
      "version": "0.5.5",
      "resolved": "https://registry.npmjs.org/mkdirp/-/mkdirp-0.5.5.tgz",
      "integrity": "sha512-NKmAlESf6jMGym1++R0Ra7wvhV+wFW63FaSOFPwRahvea0gMUcGUhVeAg/0BC0wiv9ih5NYPB1Wn1UEI1/L+xQ==",
      "dev": true,
      "requires": {
        "minimist": "^1.2.5"
      }
    },
    "ms": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.1.2.tgz",
      "integrity": "sha512-sGkPx+VjMtmA6MX27oA4FBFELFCZZ4S4XqeGOXCv68tT+jb3vk/RyaKWP0PTKyWtmLSM0b+adUTEvbs1PEaH2w==",
      "dev": true
    },
    "mute-stream": {
      "version": "0.0.8",
      "resolved": "https://registry.npmjs.org/mute-stream/-/mute-stream-0.0.8.tgz",
      "integrity": "sha512-nnbWWOkoWyUsTjKrhgD0dcz22mdkSnpYqbEjIm2nhwhuxlSkpywJmBo8h0ZqJdkp73mb90SssHkN4rsRaBAfAA==",
      "dev": true
    },
    "mz": {
      "version": "2.7.0",
      "resolved": "https://registry.npmjs.org/mz/-/mz-2.7.0.tgz",
      "integrity": "sha512-z81GNO7nnYMEhrGh9LeymoE4+Yr0Wn5McHIZMK5cfQCl+NDX08sCZgUc9/6MHni9IWuFLm1Z3HTCXu2z9fN62Q==",
      "dev": true,
      "requires": {
        "any-promise": "^1.0.0",
        "object-assign": "^4.0.1",
        "thenify-all": "^1.0.0"
      }
    },
    "nanomatch": {
      "version": "1.2.13",
      "resolved": "https://registry.npmjs.org/nanomatch/-/nanomatch-1.2.13.tgz",
      "integrity": "sha512-fpoe2T0RbHwBTBUOftAfBPaDEi06ufaUai0mE6Yn1kacc3SnTErfb/h+X94VXzI64rKFHYImXSvdwGGCmwOqCA==",
      "dev": true,
      "requires": {
        "arr-diff": "^4.0.0",
        "array-unique": "^0.3.2",
        "define-property": "^2.0.2",
        "extend-shallow": "^3.0.2",
        "fragment-cache": "^0.2.1",
        "is-windows": "^1.0.2",
        "kind-of": "^6.0.2",
        "object.pick": "^1.3.0",
        "regex-not": "^1.0.0",
        "snapdragon": "^0.8.1",
        "to-regex": "^3.0.1"
      }
    },
    "natural-compare": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/natural-compare/-/natural-compare-1.4.0.tgz",
      "integrity": "sha1-Sr6/7tdUHywnrPspvbvRXI1bpPc=",
      "dev": true
    },
    "negotiator": {
      "version": "0.6.3",
      "resolved": "https://registry.npmjs.org/negotiator/-/negotiator-0.6.3.tgz",
      "integrity": "sha512-+EUsqGPLsM+j/zdChZjsnX51g4XrHFOIXwfnCVPGlQk/k5giakcKsuxCObBRu6DSm9opw/O6slWbJdghQM4bBg==",
      "dev": true
    },
    "neo-async": {
      "version": "2.6.2",
      "resolved": "https://registry.npmjs.org/neo-async/-/neo-async-2.6.2.tgz",
      "integrity": "sha512-Yd3UES5mWCSqR+qNT93S3UoYUkqAZ9lLg8a7g9rimsWmYGK8cVToA4/sF3RrshdyV3sAGMXVUmpMYOw+dLpOuw==",
      "dev": true
    },
    "next-tick": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/next-tick/-/next-tick-1.0.0.tgz",
      "integrity": "sha1-yobR/ogoFpsBICCOPchCS524NCw=",
      "dev": true
    },
    "nice-try": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/nice-try/-/nice-try-1.0.5.tgz",
      "integrity": "sha512-1nh45deeb5olNY7eX82BkPO7SSxR5SSYJiPTrTdFUVYwAl8CKMA5N9PjTYkHiRjisVcxcQ1HXdLhx2qxxJzLNQ==",
      "dev": true
    },
    "no-case": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/no-case/-/no-case-3.0.4.tgz",
      "integrity": "sha512-fgAN3jGAh+RoxUGZHTSOLJIqUc2wmoBwGR4tbpNAKmmovFoWq0OdRkb0VkldReO2a2iBT/OEulG9XSUc10r3zg==",
      "dev": true,
      "requires": {
        "lower-case": "^2.0.2",
        "tslib": "^2.0.3"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.0",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
          "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg==",
          "dev": true
        }
      }
    },
    "node-fetch": {
      "version": "2.6.7",
      "resolved": "https://registry.npmjs.org/node-fetch/-/node-fetch-2.6.7.tgz",
      "integrity": "sha512-ZjMPFEfVx5j+y2yF35Kzx5sF7kDzxuDj6ziH4FFbOp87zKDZNx8yExJIb05OGF4Nlt9IHFIMBkRl41VdvcNdbQ==",
      "requires": {
        "whatwg-url": "^5.0.0"
      },
      "dependencies": {
        "tr46": {
          "version": "0.0.3",
          "resolved": "https://registry.npmjs.org/tr46/-/tr46-0.0.3.tgz",
          "integrity": "sha512-N3WMsuqV66lT30CrXNbEjx4GEwlow3v6rr4mCcv6prnfwhS01rkgyFdjPNBYd9br7LpXV1+Emh01fHnq2Gdgrw=="
        },
        "webidl-conversions": {
          "version": "3.0.1",
          "resolved": "https://registry.npmjs.org/webidl-conversions/-/webidl-conversions-3.0.1.tgz",
          "integrity": "sha512-2JAn3z8AR6rjK8Sm8orRC0h/bcl/DqL7tRPdGZ4I1CjdF+EaMLmYxBHyXuKL849eucPFhvBoxMsflfOb8kxaeQ=="
        },
        "whatwg-url": {
          "version": "5.0.0",
          "resolved": "https://registry.npmjs.org/whatwg-url/-/whatwg-url-5.0.0.tgz",
          "integrity": "sha512-saE57nupxk6v3HY35+jzBwYa0rKSy0XR8JSxZPwgLr7ys0IBzhGviA1/TUGJLmSVqs8pb9AnvICXEuOHLprYTw==",
          "requires": {
            "tr46": "~0.0.3",
            "webidl-conversions": "^3.0.0"
          }
        }
      }
    },
    "node-int64": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/node-int64/-/node-int64-0.4.0.tgz",
      "integrity": "sha1-h6kGXNs1XTGC2PlM4RGIuCXGijs=",
      "dev": true
    },
    "node-modules-regexp": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/node-modules-regexp/-/node-modules-regexp-1.0.0.tgz",
      "integrity": "sha1-jZ2+KJZKSsVxLpExZCEHxx6Q7EA=",
      "dev": true
    },
    "node-notifier": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/node-notifier/-/node-notifier-6.0.0.tgz",
      "integrity": "sha512-SVfQ/wMw+DesunOm5cKqr6yDcvUTDl/yc97ybGHMrteNEY6oekXpNpS3lZwgLlwz0FLgHoiW28ZpmBHUDg37cw==",
      "dev": true,
      "optional": true,
      "requires": {
        "growly": "^1.3.0",
        "is-wsl": "^2.1.1",
        "semver": "^6.3.0",
        "shellwords": "^0.1.1",
        "which": "^1.3.1"
      },
      "dependencies": {
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
          "dev": true,
          "optional": true
        }
      }
    },
    "node-releases": {
      "version": "1.1.73",
      "resolved": "https://registry.npmjs.org/node-releases/-/node-releases-1.1.73.tgz",
      "integrity": "sha512-uW7fodD6pyW2FZNZnp/Z3hvWKeEW1Y8R1+1CnErE8cXFXzl5blBOoVB41CvMer6P6Q0S5FXDwcHgFd1Wj0U9zg==",
      "dev": true
    },
    "normalize-package-data": {
      "version": "2.5.0",
      "resolved": "https://registry.npmjs.org/normalize-package-data/-/normalize-package-data-2.5.0.tgz",
      "integrity": "sha512-/5CMN3T0R4XTj4DcGaexo+roZSdSFW/0AOOTROrjxzCG1wrWXEsGbRKevjlIL+ZDE4sZlJr5ED4YW0yqmkK+eA==",
      "dev": true,
      "requires": {
        "hosted-git-info": "^2.1.4",
        "resolve": "^1.10.0",
        "semver": "2 || 3 || 4 || 5",
        "validate-npm-package-license": "^3.0.1"
      },
      "dependencies": {
        "semver": {
          "version": "5.7.1",
          "resolved": "https://registry.npmjs.org/semver/-/semver-5.7.1.tgz",
          "integrity": "sha512-sauaDf/PZdVgrLTNYHRtpXa1iRiKcaebiKQ1BJdpQlWH2lCvexQdX55snPFyK7QzpudqbCI0qXFfOasHdyNDGQ==",
          "dev": true
        }
      }
    },
    "normalize-path": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/normalize-path/-/normalize-path-3.0.0.tgz",
      "integrity": "sha512-6eZs5Ls3WtCisHWp9S2GUy8dqkpGi4BVSz3GaqiE6ezub0512ESztXUwUB6C6IKbQkY2Pnb/mD4WYojCRwcwLA==",
      "dev": true
    },
    "npm-run-path": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/npm-run-path/-/npm-run-path-4.0.1.tgz",
      "integrity": "sha512-S48WzZW777zhNIrn7gxOlISNAqi9ZC/uQFnRdbeIHhZhCA6UqpkOT8T1G7BvfdgP4Er8gF4sUbaS0i7QvIfCWw==",
      "dev": true,
      "requires": {
        "path-key": "^3.0.0"
      },
      "dependencies": {
        "path-key": {
          "version": "3.1.1",
          "resolved": "https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz",
          "integrity": "sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==",
          "dev": true
        }
      }
    },
    "nwsapi": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/nwsapi/-/nwsapi-2.2.0.tgz",
      "integrity": "sha512-h2AatdwYH+JHiZpv7pt/gSX1XoRGb7L/qSIeuqA6GwYoF9w1vP1cw42TO0aI2pNyshRK5893hNSl+1//vHK7hQ==",
      "dev": true
    },
    "oauth-sign": {
      "version": "0.9.0",
      "resolved": "https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.9.0.tgz",
      "integrity": "sha512-fexhUFFPTGV8ybAtSIGbV6gOkSv8UtRbDBnAyLQw4QPKkgNlsH2ByPGtMUqdWkos6YCRmAqViwgZrJc/mRDzZQ==",
      "dev": true
    },
    "object-assign": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/object-assign/-/object-assign-4.1.1.tgz",
      "integrity": "sha1-IQmtx5ZYh8/AXLvUQsrIv7s2CGM="
    },
    "object-copy": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/object-copy/-/object-copy-0.1.0.tgz",
      "integrity": "sha1-fn2Fi3gb18mRpBupde04EnVOmYw=",
      "dev": true,
      "requires": {
        "copy-descriptor": "^0.1.0",
        "define-property": "^0.2.5",
        "kind-of": "^3.0.3"
      },
      "dependencies": {
        "define-property": {
          "version": "0.2.5",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
          "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
          "dev": true,
          "requires": {
            "is-descriptor": "^0.1.0"
          }
        },
        "is-accessor-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
          "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          }
        },
        "is-data-descriptor": {
          "version": "0.1.4",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
          "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          }
        },
        "is-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
          "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
          "dev": true,
          "requires": {
            "is-accessor-descriptor": "^0.1.6",
            "is-data-descriptor": "^0.1.4",
            "kind-of": "^5.0.0"
          },
          "dependencies": {
            "kind-of": {
              "version": "5.1.0",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
              "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
              "dev": true
            }
          }
        },
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "dev": true,
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "object-inspect": {
      "version": "1.10.3",
      "resolved": "https://registry.npmjs.org/object-inspect/-/object-inspect-1.10.3.tgz",
      "integrity": "sha512-e5mCJlSH7poANfC8z8S9s9S2IN5/4Zb3aZ33f5s8YqoazCFzNLloLU8r5VCG+G7WoqLvAAZoVMcy3tp/3X0Plw==",
      "dev": true
    },
    "object-keys": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/object-keys/-/object-keys-1.1.1.tgz",
      "integrity": "sha512-NuAESUOUMrlIXOfHKzD6bpPu3tYt3xvjNdRIQ+FeT0lNb4K8WR70CaDxhuNguS2XG+GjkyMwOzsN5ZktImfhLA==",
      "dev": true
    },
    "object-visit": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/object-visit/-/object-visit-1.0.1.tgz",
      "integrity": "sha1-95xEk68MU3e1n+OdOV5BBC3QRbs=",
      "dev": true,
      "requires": {
        "isobject": "^3.0.0"
      }
    },
    "object.assign": {
      "version": "4.1.2",
      "resolved": "https://registry.npmjs.org/object.assign/-/object.assign-4.1.2.tgz",
      "integrity": "sha512-ixT2L5THXsApyiUPYKmW+2EHpXXe5Ii3M+f4e+aJFAHao5amFRW6J0OO6c/LU8Be47utCx2GL89hxGB6XSmKuQ==",
      "dev": true,
      "requires": {
        "call-bind": "^1.0.0",
        "define-properties": "^1.1.3",
        "has-symbols": "^1.0.1",
        "object-keys": "^1.1.1"
      }
    },
    "object.pick": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/object.pick/-/object.pick-1.3.0.tgz",
      "integrity": "sha1-h6EKxMFpS9Lhy/U1kaZhQftd10c=",
      "dev": true,
      "requires": {
        "isobject": "^3.0.1"
      }
    },
    "object.values": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/object.values/-/object.values-1.1.4.tgz",
      "integrity": "sha512-TnGo7j4XSnKQoK3MfvkzqKCi0nVe/D9I9IjwTNYdb/fxYHpjrluHVOgw0AF6jrRFGMPHdfuidR09tIDiIvnaSg==",
      "dev": true,
      "requires": {
        "call-bind": "^1.0.2",
        "define-properties": "^1.1.3",
        "es-abstract": "^1.18.2"
      }
    },
    "on-headers": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/on-headers/-/on-headers-1.0.2.tgz",
      "integrity": "sha512-pZAE+FJLoyITytdqK0U5s+FIpjN0JP3OzFi/u8Rx+EV5/W+JTWGXG8xFzevE7AjBfDqHv/8vL8qQsIhHnqRkrA==",
      "dev": true
    },
    "once": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/once/-/once-1.4.0.tgz",
      "integrity": "sha1-WDsap3WWHUsROsF9nFC6753Xa9E=",
      "dev": true,
      "requires": {
        "wrappy": "1"
      }
    },
    "onetime": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/onetime/-/onetime-5.1.2.tgz",
      "integrity": "sha512-kbpaSSGJTWdAY5KPVeMOKXSrPtr8C8C7wodJbcsd51jRnmD+GZu8Y0VoU6Dm5Z4vWr0Ig/1NKuWRKf7j5aaYSg==",
      "dev": true,
      "requires": {
        "mimic-fn": "^2.1.0"
      }
    },
    "optimism": {
      "version": "0.16.1",
      "resolved": "https://registry.npmjs.org/optimism/-/optimism-0.16.1.tgz",
      "integrity": "sha512-64i+Uw3otrndfq5kaoGNoY7pvOhSsjFEN4bdEFh80MWVk/dbgJfMv7VFDeCT8LxNAlEVhQmdVEbfE7X2nWNIIg==",
      "requires": {
        "@wry/context": "^0.6.0",
        "@wry/trie": "^0.3.0"
      }
    },
    "optionator": {
      "version": "0.8.3",
      "resolved": "https://registry.npmjs.org/optionator/-/optionator-0.8.3.tgz",
      "integrity": "sha512-+IW9pACdk3XWmmTXG8m3upGUJst5XRGzxMRjXzAuJ1XnIFNvfhjjIuYkDvysnPQ7qzqVzLt78BCruntqRhWQbA==",
      "dev": true,
      "requires": {
        "deep-is": "~0.1.3",
        "fast-levenshtein": "~2.0.6",
        "levn": "~0.3.0",
        "prelude-ls": "~1.1.2",
        "type-check": "~0.3.2",
        "word-wrap": "~1.2.3"
      }
    },
    "os-tmpdir": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/os-tmpdir/-/os-tmpdir-1.0.2.tgz",
      "integrity": "sha1-u+Z0BseaqFxc/sdm/lc0VV36EnQ=",
      "dev": true
    },
    "p-each-series": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/p-each-series/-/p-each-series-2.2.0.tgz",
      "integrity": "sha512-ycIL2+1V32th+8scbpTvyHNaHe02z0sjgh91XXjAk+ZeXoPN4Z46DVUnzdso0aX4KckKw0FNNFHdjZ2UsZvxiA==",
      "dev": true
    },
    "p-finally": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/p-finally/-/p-finally-2.0.1.tgz",
      "integrity": "sha512-vpm09aKwq6H9phqRQzecoDpD8TmVyGw70qmWlyq5onxY7tqyTTFVvxMykxQSQKILBSFlbXpypIw2T1Ml7+DDtw==",
      "dev": true
    },
    "p-limit": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/p-limit/-/p-limit-2.3.0.tgz",
      "integrity": "sha512-//88mFWSJx8lxCzwdAABTJL2MyWB12+eIY7MDL2SqLmAkeKU9qxRvWuSyTjm3FUmpBEMuFfckAIqEaVGUDxb6w==",
      "dev": true,
      "requires": {
        "p-try": "^2.0.0"
      }
    },
    "p-locate": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/p-locate/-/p-locate-4.1.0.tgz",
      "integrity": "sha512-R79ZZ/0wAxKGu3oYMlz8jy/kbhsNrS7SKZ7PxEHBgJ5+F2mtFW2fK2cOtBh1cHYkQsbzFV7I+EoRKe6Yt0oK7A==",
      "dev": true,
      "requires": {
        "p-limit": "^2.2.0"
      }
    },
    "p-try": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/p-try/-/p-try-2.2.0.tgz",
      "integrity": "sha512-R4nPAVTAU0B9D35/Gk3uJf/7XYbQcyohSKdvAxIRSNghFl4e71hVoGnBNQz9cWaXxO2I10KTC+3jMdvvoKw6dQ==",
      "dev": true
    },
    "pad-right": {
      "version": "0.2.2",
      "resolved": "https://registry.npmjs.org/pad-right/-/pad-right-0.2.2.tgz",
      "integrity": "sha1-b7ySQEXSRPKiokRQMGDTv8YAl3Q=",
      "dev": true,
      "requires": {
        "repeat-string": "^1.5.2"
      }
    },
    "parent-module": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/parent-module/-/parent-module-1.0.1.tgz",
      "integrity": "sha512-GQ2EWRpQV8/o+Aw8YqtfZZPfNRWZYkbidE9k5rpl/hC3vtHHBfGm2Ifi6qWV+coDGkrUKZAxE3Lot5kcsRlh+g==",
      "dev": true,
      "requires": {
        "callsites": "^3.0.0"
      }
    },
    "parse-json": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/parse-json/-/parse-json-5.2.0.tgz",
      "integrity": "sha512-ayCKvm/phCGxOkYRSCM82iDwct8/EonSEgCSxWxD7ve6jHggsFl4fZVQBPRNgQoKiuV/odhFrGzQXZwbifC8Rg==",
      "dev": true,
      "requires": {
        "@babel/code-frame": "^7.0.0",
        "error-ex": "^1.3.1",
        "json-parse-even-better-errors": "^2.3.0",
        "lines-and-columns": "^1.1.6"
      }
    },
    "parse5": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/parse5/-/parse5-5.1.0.tgz",
      "integrity": "sha512-fxNG2sQjHvlVAYmzBZS9YlDp6PTSSDwa98vkD4QgVDDCAo84z5X1t5XyJQ62ImdLXx5NdIIfihey6xpum9/gRQ==",
      "dev": true
    },
    "pascalcase": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/pascalcase/-/pascalcase-0.1.1.tgz",
      "integrity": "sha1-s2PlXoAGym/iF4TS2yK9FdeRfxQ=",
      "dev": true
    },
    "path-exists": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/path-exists/-/path-exists-4.0.0.tgz",
      "integrity": "sha512-ak9Qy5Q7jYb2Wwcey5Fpvg2KoAc/ZIhLSLOSBmRmygPsGwkVVt0fZa0qrtMz+m6tJTAHfZQ8FnmB4MG4LWy7/w==",
      "dev": true
    },
    "path-is-absolute": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/path-is-absolute/-/path-is-absolute-1.0.1.tgz",
      "integrity": "sha1-F0uSaHNVNP+8es5r9TpanhtcX18=",
      "dev": true
    },
    "path-is-inside": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/path-is-inside/-/path-is-inside-1.0.2.tgz",
      "integrity": "sha512-DUWJr3+ULp4zXmol/SZkFf3JGsS9/SIv+Y3Rt93/UjPpDpklB5f1er4O3POIbUuUJ3FXgqte2Q7SrU6zAqwk8w==",
      "dev": true
    },
    "path-key": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/path-key/-/path-key-2.0.1.tgz",
      "integrity": "sha1-QRyttXTFoUDTpLGRDUDYDMn0C0A=",
      "dev": true
    },
    "path-parse": {
      "version": "1.0.7",
      "resolved": "https://registry.npmjs.org/path-parse/-/path-parse-1.0.7.tgz",
      "integrity": "sha512-LDJzPVEEEPR+y48z93A0Ed0yXb8pAByGWo/k5YYdYgpY2/2EsOsksJrq7lOHxryrVOn1ejG6oAp8ahvOIQD8sw==",
      "dev": true
    },
    "path-to-regexp": {
      "version": "2.2.1",
      "resolved": "https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-2.2.1.tgz",
      "integrity": "sha512-gu9bD6Ta5bwGrrU8muHzVOBFFREpp2iRkVfhBJahwJ6p6Xw20SjT0MxLnwkjOibQmGSYhiUnf2FLe7k+jcFmGQ==",
      "dev": true
    },
    "path-type": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/path-type/-/path-type-2.0.0.tgz",
      "integrity": "sha1-8BLMuEFbcJb8LaoQVMPXI4lZTHM=",
      "dev": true,
      "requires": {
        "pify": "^2.0.0"
      }
    },
    "performance-now": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/performance-now/-/performance-now-2.1.0.tgz",
      "integrity": "sha1-Ywn04OX6kT7BxpMHrjZLSzd8nns=",
      "dev": true
    },
    "picomatch": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/picomatch/-/picomatch-2.3.0.tgz",
      "integrity": "sha512-lY1Q/PiJGC2zOv/z391WOTD+Z02bCgsFfvxoXXf6h7kv9o+WmsmzYqrAwY63sNgOxE4xEdq0WyUnXfKeBrSvYw==",
      "dev": true
    },
    "pify": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/pify/-/pify-2.3.0.tgz",
      "integrity": "sha1-7RQaasBDqEnqWISY59yosVMw6Qw=",
      "dev": true
    },
    "pinkie": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz",
      "integrity": "sha1-clVrgM+g1IqXToDnckjoDtT3+HA=",
      "dev": true
    },
    "pinkie-promise": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.1.tgz",
      "integrity": "sha1-ITXW36ejWMBprJsXh3YogihFD/o=",
      "dev": true,
      "requires": {
        "pinkie": "^2.0.0"
      }
    },
    "pirates": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/pirates/-/pirates-4.0.1.tgz",
      "integrity": "sha512-WuNqLTbMI3tmfef2TKxlQmAiLHKtFhlsCZnPIpuv2Ow0RDVO8lfy1Opf4NUzlMXLjPl+Men7AuVdX6TA+s+uGA==",
      "dev": true,
      "requires": {
        "node-modules-regexp": "^1.0.0"
      }
    },
    "pkg-dir": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/pkg-dir/-/pkg-dir-2.0.0.tgz",
      "integrity": "sha1-9tXREJ4Z1j7fQo4L1X4Sd3YVM0s=",
      "dev": true,
      "requires": {
        "find-up": "^2.1.0"
      },
      "dependencies": {
        "find-up": {
          "version": "2.1.0",
          "resolved": "https://registry.npmjs.org/find-up/-/find-up-2.1.0.tgz",
          "integrity": "sha1-RdG35QbHF93UgndaK3eSCjwMV6c=",
          "dev": true,
          "requires": {
            "locate-path": "^2.0.0"
          }
        },
        "locate-path": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/locate-path/-/locate-path-2.0.0.tgz",
          "integrity": "sha1-K1aLJl7slExtnA3pw9u7ygNUzY4=",
          "dev": true,
          "requires": {
            "p-locate": "^2.0.0",
            "path-exists": "^3.0.0"
          }
        },
        "p-limit": {
          "version": "1.3.0",
          "resolved": "https://registry.npmjs.org/p-limit/-/p-limit-1.3.0.tgz",
          "integrity": "sha512-vvcXsLAJ9Dr5rQOPk7toZQZJApBl2K4J6dANSsEuh6QI41JYcsS/qhTGa9ErIUUgK3WNQoJYvylxvjqmiqEA9Q==",
          "dev": true,
          "requires": {
            "p-try": "^1.0.0"
          }
        },
        "p-locate": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/p-locate/-/p-locate-2.0.0.tgz",
          "integrity": "sha1-IKAQOyIqcMj9OcwuWAaA893l7EM=",
          "dev": true,
          "requires": {
            "p-limit": "^1.1.0"
          }
        },
        "p-try": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/p-try/-/p-try-1.0.0.tgz",
          "integrity": "sha1-y8ec26+P1CKOE/Yh8rGiN8GyB7M=",
          "dev": true
        },
        "path-exists": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/path-exists/-/path-exists-3.0.0.tgz",
          "integrity": "sha1-zg6+ql94yxiSXqfYENe1mwEP1RU=",
          "dev": true
        }
      }
    },
    "pn": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/pn/-/pn-1.1.0.tgz",
      "integrity": "sha512-2qHaIQr2VLRFoxe2nASzsV6ef4yOOH+Fi9FBOVH6cqeSgUnoyySPZkxzLuzd+RYOQTRpROA0ztTMqxROKSb/nA==",
      "dev": true
    },
    "posix-character-classes": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/posix-character-classes/-/posix-character-classes-0.1.1.tgz",
      "integrity": "sha1-AerA/jta9xoqbAL+q7jB/vfgDqs=",
      "dev": true
    },
    "prelude-ls": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/prelude-ls/-/prelude-ls-1.1.2.tgz",
      "integrity": "sha1-IZMqVJ9eUv/ZqCf1cOBL5iqX2lQ=",
      "dev": true
    },
    "prettier": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/prettier/-/prettier-2.0.5.tgz",
      "integrity": "sha512-7PtVymN48hGcO4fGjybyBSIWDsLU4H4XlvOHfq91pz9kkGlonzwTfYkaIEwiRg/dAJF9YlbsduBAgtYLi+8cFg==",
      "dev": true
    },
    "pretty-format": {
      "version": "25.5.0",
      "resolved": "https://registry.npmjs.org/pretty-format/-/pretty-format-25.5.0.tgz",
      "integrity": "sha512-kbo/kq2LQ/A/is0PQwsEHM7Ca6//bGPPvU6UnsdDRSKTWxT/ru/xb88v4BJf6a69H+uTytOEsTusT9ksd/1iWQ==",
      "dev": true,
      "requires": {
        "@jest/types": "^25.5.0",
        "ansi-regex": "^5.0.0",
        "ansi-styles": "^4.0.0",
        "react-is": "^16.12.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        }
      }
    },
    "progress": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/progress/-/progress-2.0.3.tgz",
      "integrity": "sha512-7PiHtLll5LdnKIMw100I+8xJXR5gW2QwWYkT6iJva0bXitZKa/XMrSbdmg3r2Xnaidz9Qumd0VPaMrZlF9V9sA==",
      "dev": true
    },
    "prompts": {
      "version": "2.4.1",
      "resolved": "https://registry.npmjs.org/prompts/-/prompts-2.4.1.tgz",
      "integrity": "sha512-EQyfIuO2hPDsX1L/blblV+H7I0knhgAd82cVneCwcdND9B8AuCDuRcBH6yIcG4dFzlOUqbazQqwGjx5xmsNLuQ==",
      "dev": true,
      "requires": {
        "kleur": "^3.0.3",
        "sisteransi": "^1.0.5"
      }
    },
    "prop-types": {
      "version": "15.7.2",
      "resolved": "https://registry.npmjs.org/prop-types/-/prop-types-15.7.2.tgz",
      "integrity": "sha512-8QQikdH7//R2vurIJSutZ1smHYTcLpRWEOlHnzcWHmBYrOGUysKwSsrC89BCiFj3CbrfJ/nXFdJepOVrY1GCHQ==",
      "requires": {
        "loose-envify": "^1.4.0",
        "object-assign": "^4.1.1",
        "react-is": "^16.8.1"
      }
    },
    "protobufjs": {
      "version": "6.11.2",
      "resolved": "https://registry.npmjs.org/protobufjs/-/protobufjs-6.11.2.tgz",
      "integrity": "sha512-4BQJoPooKJl2G9j3XftkIXjoC9C0Av2NOrWmbLWT1vH32GcSUHjM0Arra6UfTsVyfMAuFzaLucXn1sadxJydAw==",
      "dev": true,
      "requires": {
        "@protobufjs/aspromise": "^1.1.2",
        "@protobufjs/base64": "^1.1.2",
        "@protobufjs/codegen": "^2.0.4",
        "@protobufjs/eventemitter": "^1.1.0",
        "@protobufjs/fetch": "^1.1.0",
        "@protobufjs/float": "^1.0.2",
        "@protobufjs/inquire": "^1.1.0",
        "@protobufjs/path": "^1.1.2",
        "@protobufjs/pool": "^1.1.0",
        "@protobufjs/utf8": "^1.1.0",
        "@types/long": "^4.0.1",
        "@types/node": ">=13.7.0",
        "long": "^4.0.0"
      }
    },
    "proxy-from-env": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/proxy-from-env/-/proxy-from-env-1.1.0.tgz",
      "integrity": "sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg=="
    },
    "psl": {
      "version": "1.8.0",
      "resolved": "https://registry.npmjs.org/psl/-/psl-1.8.0.tgz",
      "integrity": "sha512-RIdOzyoavK+hA18OGGWDqUTsCLhtA7IcZ/6NCs4fFJaHBDab+pDDmDIByWFRQJq2Cd7r1OoQxBGKOaztq+hjIQ==",
      "dev": true
    },
    "pump": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/pump/-/pump-3.0.0.tgz",
      "integrity": "sha512-LwZy+p3SFs1Pytd/jYct4wpv49HiYCqd9Rlc5ZVdk0V+8Yzv6jR5Blk3TRmPL1ft69TxP0IMZGJ+WPFU2BFhww==",
      "dev": true,
      "requires": {
        "end-of-stream": "^1.1.0",
        "once": "^1.3.1"
      }
    },
    "punycode": {
      "version": "1.4.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-1.4.1.tgz",
      "integrity": "sha512-jmYNElW7yvO7TV33CjSmvSiE2yco3bV2czu/OzDKdMNVZQWfxCblURLhf+47syQRBntjfLdd/H0egrzIG+oaFQ==",
      "dev": true
    },
    "qs": {
      "version": "6.5.2",
      "resolved": "https://registry.npmjs.org/qs/-/qs-6.5.2.tgz",
      "integrity": "sha512-N5ZAX4/LxJmF+7wN74pUD6qAh9/wnvdQcjq9TZjevvXzSUo7bfmw91saqMjzGS2xq91/odN2dW/WOl7qQHNDGA==",
      "dev": true
    },
    "range-parser": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/range-parser/-/range-parser-1.2.0.tgz",
      "integrity": "sha512-kA5WQoNVo4t9lNx2kQNFCxKeBl5IbbSNBl1M/tLkw9WCn+hxNBAW5Qh8gdhs63CJnhjJ2zQWFoqPJP2sK1AV5A==",
      "dev": true
    },
    "rc": {
      "version": "1.2.8",
      "resolved": "https://registry.npmjs.org/rc/-/rc-1.2.8.tgz",
      "integrity": "sha512-y3bGgqKj3QBdxLbLkomlohkvsA8gdAiUQlSBJnBhfn+BPxg4bc62d8TcBW15wavDfgexCgccckhcZvywyQYPOw==",
      "dev": true,
      "requires": {
        "deep-extend": "^0.6.0",
        "ini": "~1.3.0",
        "minimist": "^1.2.0",
        "strip-json-comments": "~2.0.1"
      },
      "dependencies": {
        "strip-json-comments": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-2.0.1.tgz",
          "integrity": "sha512-4gB8na07fecVVkOI6Rs4e7T6NOTki5EmL7TUduTs6bu3EdnSycntVJ4re8kgZA+wx9IueI2Y11bfbgwtzuE0KQ==",
          "dev": true
        }
      }
    },
    "react-is": {
      "version": "16.13.1",
      "resolved": "https://registry.npmjs.org/react-is/-/react-is-16.13.1.tgz",
      "integrity": "sha512-24e6ynE2H+OKt4kqsOvNd8kBpV65zoxbA4BVsEOB3ARVWQki/DHzaUoC5KuON/BiccDaCCTZBuOcfZs70kR8bQ=="
    },
    "read-pkg": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/read-pkg/-/read-pkg-5.2.0.tgz",
      "integrity": "sha512-Ug69mNOpfvKDAc2Q8DRpMjjzdtrnv9HcSMX+4VsZxD1aZ6ZzrIE7rlzXBtWTyhULSMKg076AW6WR5iZpD0JiOg==",
      "dev": true,
      "requires": {
        "@types/normalize-package-data": "^2.4.0",
        "normalize-package-data": "^2.5.0",
        "parse-json": "^5.0.0",
        "type-fest": "^0.6.0"
      },
      "dependencies": {
        "type-fest": {
          "version": "0.6.0",
          "resolved": "https://registry.npmjs.org/type-fest/-/type-fest-0.6.0.tgz",
          "integrity": "sha512-q+MB8nYR1KDLrgr4G5yemftpMC7/QLqVndBmEEdqzmNj5dcFOO4Oo8qlwZE3ULT3+Zim1F8Kq4cBnikNhlCMlg==",
          "dev": true
        }
      }
    },
    "read-pkg-up": {
      "version": "7.0.1",
      "resolved": "https://registry.npmjs.org/read-pkg-up/-/read-pkg-up-7.0.1.tgz",
      "integrity": "sha512-zK0TB7Xd6JpCLmlLmufqykGE+/TlOePD6qKClNW7hHDKFh/J7/7gCWGR7joEQEW1bKq3a3yUZSObOoWLFQ4ohg==",
      "dev": true,
      "requires": {
        "find-up": "^4.1.0",
        "read-pkg": "^5.2.0",
        "type-fest": "^0.8.1"
      }
    },
    "realpath-native": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/realpath-native/-/realpath-native-2.0.0.tgz",
      "integrity": "sha512-v1SEYUOXXdbBZK8ZuNgO4TBjamPsiSgcFr0aP+tEKpQZK8vooEUqV6nm6Cv502mX4NF2EfsnVqtNAHG+/6Ur1Q==",
      "dev": true
    },
    "rechoir": {
      "version": "0.6.2",
      "resolved": "https://registry.npmjs.org/rechoir/-/rechoir-0.6.2.tgz",
      "integrity": "sha1-hSBLVNuoLVdC4oyWdW70OvUOM4Q=",
      "dev": true,
      "requires": {
        "resolve": "^1.1.6"
      }
    },
    "reflect-metadata": {
      "version": "0.1.13",
      "resolved": "https://registry.npmjs.org/reflect-metadata/-/reflect-metadata-0.1.13.tgz",
      "integrity": "sha512-Ts1Y/anZELhSsjMcU605fU9RE4Oi3p5ORujwbIKXfWa+0Zxs510Qrmrce5/Jowq3cHSZSJqBjypxmHarc+vEWg==",
      "dev": true
    },
    "regex-not": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/regex-not/-/regex-not-1.0.2.tgz",
      "integrity": "sha512-J6SDjUgDxQj5NusnOtdFxDwN/+HWykR8GELwctJ7mdqhcyy1xEc4SRFHUXvxTp661YaVKAjfRLZ9cCqS6tn32A==",
      "dev": true,
      "requires": {
        "extend-shallow": "^3.0.2",
        "safe-regex": "^1.1.0"
      }
    },
    "regexpp": {
      "version": "3.2.0",
      "resolved": "https://registry.npmjs.org/regexpp/-/regexpp-3.2.0.tgz",
      "integrity": "sha512-pq2bWo9mVD43nbts2wGv17XLiNLya+GklZ8kaDLV2Z08gDCsGpnKn9BFMepvWuHCbyVvY7J5o5+BVvoQbmlJLg==",
      "dev": true
    },
    "registry-auth-token": {
      "version": "3.3.2",
      "resolved": "https://registry.npmjs.org/registry-auth-token/-/registry-auth-token-3.3.2.tgz",
      "integrity": "sha512-JL39c60XlzCVgNrO+qq68FoNb56w/m7JYvGR2jT5iR1xBrUA3Mfx5Twk5rqTThPmQKMWydGmq8oFtDlxfrmxnQ==",
      "dev": true,
      "requires": {
        "rc": "^1.1.6",
        "safe-buffer": "^5.0.1"
      }
    },
    "registry-url": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/registry-url/-/registry-url-3.1.0.tgz",
      "integrity": "sha512-ZbgR5aZEdf4UKZVBPYIgaglBmSF2Hi94s2PcIHhRGFjKYu+chjJdYfHn4rt3hB6eCKLJ8giVIIfgMa1ehDfZKA==",
      "dev": true,
      "requires": {
        "rc": "^1.0.1"
      }
    },
    "remove-trailing-separator": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/remove-trailing-separator/-/remove-trailing-separator-1.1.0.tgz",
      "integrity": "sha1-wkvOKig62tW8P1jg1IJJuSN52O8=",
      "dev": true
    },
    "repeat-element": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/repeat-element/-/repeat-element-1.1.4.tgz",
      "integrity": "sha512-LFiNfRcSu7KK3evMyYOuCzv3L10TW7yC1G2/+StMjK8Y6Vqd2MG7r/Qjw4ghtuCOjFvlnms/iMmLqpvW/ES/WQ==",
      "dev": true
    },
    "repeat-string": {
      "version": "1.6.1",
      "resolved": "https://registry.npmjs.org/repeat-string/-/repeat-string-1.6.1.tgz",
      "integrity": "sha1-jcrkcOHIirwtYA//Sndihtp15jc=",
      "dev": true
    },
    "request": {
      "version": "2.88.2",
      "resolved": "https://registry.npmjs.org/request/-/request-2.88.2.tgz",
      "integrity": "sha512-MsvtOrfG9ZcrOwAW+Qi+F6HbD0CWXEh9ou77uOb7FM2WPhwT7smM833PzanhJLsgXjN89Ir6V2PczXNnMpwKhw==",
      "dev": true,
      "requires": {
        "aws-sign2": "~0.7.0",
        "aws4": "^1.8.0",
        "caseless": "~0.12.0",
        "combined-stream": "~1.0.6",
        "extend": "~3.0.2",
        "forever-agent": "~0.6.1",
        "form-data": "~2.3.2",
        "har-validator": "~5.1.3",
        "http-signature": "~1.2.0",
        "is-typedarray": "~1.0.0",
        "isstream": "~0.1.2",
        "json-stringify-safe": "~5.0.1",
        "mime-types": "~2.1.19",
        "oauth-sign": "~0.9.0",
        "performance-now": "^2.1.0",
        "qs": "~6.5.2",
        "safe-buffer": "^5.1.2",
        "tough-cookie": "~2.5.0",
        "tunnel-agent": "^0.6.0",
        "uuid": "^3.3.2"
      },
      "dependencies": {
        "punycode": {
          "version": "2.1.1",
          "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
          "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
          "dev": true
        },
        "tough-cookie": {
          "version": "2.5.0",
          "resolved": "https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.5.0.tgz",
          "integrity": "sha512-nlLsUzgm1kfLXSXfRZMc1KLAugd4hqJHDTvc2hDIwS3mZAfMEuMbc03SujMF+GEcpaX/qboeycw6iO8JwVv2+g==",
          "dev": true,
          "requires": {
            "psl": "^1.1.28",
            "punycode": "^2.1.1"
          }
        },
        "uuid": {
          "version": "3.4.0",
          "resolved": "https://registry.npmjs.org/uuid/-/uuid-3.4.0.tgz",
          "integrity": "sha512-HjSDRw6gZE5JMggctHBcjVak08+KEVhSIiDzFnT9S9aegmp85S/bReBVTb4QTFaRNptJ9kuYaNhnbNEOkbKb/A==",
          "dev": true
        }
      }
    },
    "request-promise-core": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/request-promise-core/-/request-promise-core-1.1.4.tgz",
      "integrity": "sha512-TTbAfBBRdWD7aNNOoVOBH4pN/KigV6LyapYNNlAPA8JwbovRti1E88m3sYAwsLi5ryhPKsE9APwnjFTgdUjTpw==",
      "dev": true,
      "requires": {
        "lodash": "^4.17.19"
      }
    },
    "request-promise-native": {
      "version": "1.0.9",
      "resolved": "https://registry.npmjs.org/request-promise-native/-/request-promise-native-1.0.9.tgz",
      "integrity": "sha512-wcW+sIUiWnKgNY0dqCpOZkUbF/I+YPi+f09JZIDa39Ec+q82CpSYniDp+ISgTTbKmnpJWASeJBPZmoxH84wt3g==",
      "dev": true,
      "requires": {
        "request-promise-core": "1.1.4",
        "stealthy-require": "^1.1.1",
        "tough-cookie": "^2.3.3"
      },
      "dependencies": {
        "punycode": {
          "version": "2.1.1",
          "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
          "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
          "dev": true
        },
        "tough-cookie": {
          "version": "2.5.0",
          "resolved": "https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.5.0.tgz",
          "integrity": "sha512-nlLsUzgm1kfLXSXfRZMc1KLAugd4hqJHDTvc2hDIwS3mZAfMEuMbc03SujMF+GEcpaX/qboeycw6iO8JwVv2+g==",
          "dev": true,
          "requires": {
            "psl": "^1.1.28",
            "punycode": "^2.1.1"
          }
        }
      }
    },
    "require-directory": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/require-directory/-/require-directory-2.1.1.tgz",
      "integrity": "sha1-jGStX9MNqxyXbiNE/+f3kqam30I=",
      "dev": true
    },
    "require-from-string": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/require-from-string/-/require-from-string-2.0.2.tgz",
      "integrity": "sha512-Xf0nWe6RseziFMu+Ap9biiUbmplq6S9/p+7w7YXP/JBHhrUDDUhwa+vANyubuqfZWTveU//DYVGsDG7RKL/vEw==",
      "dev": true
    },
    "require-main-filename": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/require-main-filename/-/require-main-filename-2.0.0.tgz",
      "integrity": "sha512-NKN5kMDylKuldxYLSUfrbo5Tuzh4hd+2E8NPPX02mZtn1VuREQToYe/ZdlJy+J3uCpfaiGF05e7B8W0iXbQHmg==",
      "dev": true
    },
    "resolve": {
      "version": "1.20.0",
      "resolved": "https://registry.npmjs.org/resolve/-/resolve-1.20.0.tgz",
      "integrity": "sha512-wENBPt4ySzg4ybFQW2TT1zMQucPK95HSh/nq2CFTZVOGut2+pQvSsgtda4d26YrYcr067wjbmzOG8byDPBX63A==",
      "dev": true,
      "requires": {
        "is-core-module": "^2.2.0",
        "path-parse": "^1.0.6"
      }
    },
    "resolve-cwd": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/resolve-cwd/-/resolve-cwd-3.0.0.tgz",
      "integrity": "sha512-OrZaX2Mb+rJCpH/6CpSqt9xFVpN++x01XnN2ie9g6P5/3xelLAkXWVADpdz1IHD/KFfEXyE6V0U01OQ3UO2rEg==",
      "dev": true,
      "requires": {
        "resolve-from": "^5.0.0"
      },
      "dependencies": {
        "resolve-from": {
          "version": "5.0.0",
          "resolved": "https://registry.npmjs.org/resolve-from/-/resolve-from-5.0.0.tgz",
          "integrity": "sha512-qYg9KP24dD5qka9J47d0aVky0N+b4fTU89LN9iDnjB5waksiC49rvMB0PrUJQGoTmH50XPiqOvAjDfaijGxYZw==",
          "dev": true
        }
      }
    },
    "resolve-from": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/resolve-from/-/resolve-from-4.0.0.tgz",
      "integrity": "sha512-pb/MYmXstAkysRFx8piNI1tGFNQIFA3vkE3Gq4EuA1dF6gHp/+vgZqsCGJapvy8N3Q+4o7FwvquPJcnZ7RYy4g==",
      "dev": true
    },
    "resolve-url": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/resolve-url/-/resolve-url-0.2.1.tgz",
      "integrity": "sha1-LGN/53yJOv0qZj/iGqkIAGjiBSo=",
      "dev": true
    },
    "restore-cursor": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/restore-cursor/-/restore-cursor-3.1.0.tgz",
      "integrity": "sha512-l+sSefzHpj5qimhFSE5a8nufZYAM3sBSVMAPtYkmC+4EH2anSGaEMXSD0izRQbu9nfyQ9y5JrVmp7E8oZrUjvA==",
      "dev": true,
      "requires": {
        "onetime": "^5.1.0",
        "signal-exit": "^3.0.2"
      }
    },
    "ret": {
      "version": "0.1.15",
      "resolved": "https://registry.npmjs.org/ret/-/ret-0.1.15.tgz",
      "integrity": "sha512-TTlYpa+OL+vMMNG24xSlQGEJ3B/RzEfUlLct7b5G/ytav+wPrplCpVMFuwzXbkecJrb6IYo1iFb0S9v37754mg==",
      "dev": true
    },
    "rimraf": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/rimraf/-/rimraf-3.0.2.tgz",
      "integrity": "sha512-JZkJMZkAGFFPP2YqXZXPbMlMBgsxzE8ILs4lMIX/2o0L9UBw9O/Y3o6wFw/i9YLapcUJWwqbi3kdxIPdC62TIA==",
      "dev": true,
      "requires": {
        "glob": "^7.1.3"
      }
    },
    "rsvp": {
      "version": "4.8.5",
      "resolved": "https://registry.npmjs.org/rsvp/-/rsvp-4.8.5.tgz",
      "integrity": "sha512-nfMOlASu9OnRJo1mbEk2cz0D56a1MBNrJ7orjRZQG10XDyuvwksKbuXNp6qa+kbn839HwjwhBzhFmdsaEAfauA==",
      "dev": true
    },
    "run-async": {
      "version": "2.4.1",
      "resolved": "https://registry.npmjs.org/run-async/-/run-async-2.4.1.tgz",
      "integrity": "sha512-tvVnVv01b8c1RrA6Ep7JkStj85Guv/YrMcwqYQnwjsAS2cTmmPGBBjAjpCW7RrSodNSoE2/qg9O4bceNvUuDgQ==",
      "dev": true
    },
    "rxjs": {
      "version": "6.6.7",
      "resolved": "https://registry.npmjs.org/rxjs/-/rxjs-6.6.7.tgz",
      "integrity": "sha512-hTdwr+7yYNIT5n4AMYp85KA6yw2Va0FLa3Rguvbpa4W3I5xynaBZo41cM3XM+4Q6fRMj3sBYIR1VAmZMXYJvRQ==",
      "dev": true,
      "requires": {
        "tslib": "^1.9.0"
      }
    },
    "safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g==",
      "dev": true
    },
    "safe-regex": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/safe-regex/-/safe-regex-1.1.0.tgz",
      "integrity": "sha1-QKNmnzsHfR6UPURinhV91IAjvy4=",
      "dev": true,
      "requires": {
        "ret": "~0.1.10"
      }
    },
    "safer-buffer": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/safer-buffer/-/safer-buffer-2.1.2.tgz",
      "integrity": "sha512-YZo3K82SD7Riyi0E1EQPojLz7kpepnSQI9IyPbHHg1XXXevb5dJI7tpyN2ADxGcQbHG7vcyRHk0cbwqcQriUtg==",
      "dev": true
    },
    "sane": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/sane/-/sane-4.1.0.tgz",
      "integrity": "sha512-hhbzAgTIX8O7SHfp2c8/kREfEn4qO/9q8C9beyY6+tvZ87EpoZ3i1RIEvp27YBswnNbY9mWd6paKVmKbAgLfZA==",
      "dev": true,
      "requires": {
        "@cnakazawa/watch": "^1.0.3",
        "anymatch": "^2.0.0",
        "capture-exit": "^2.0.0",
        "exec-sh": "^0.3.2",
        "execa": "^1.0.0",
        "fb-watchman": "^2.0.0",
        "micromatch": "^3.1.4",
        "minimist": "^1.1.1",
        "walker": "~1.0.5"
      },
      "dependencies": {
        "anymatch": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/anymatch/-/anymatch-2.0.0.tgz",
          "integrity": "sha512-5teOsQWABXHHBFP9y3skS5P3d/WfWXpv3FUpy+LorMrNYaT9pI4oLMQX7jzQ2KklNpGpWHzdCXTDT2Y3XGlZBw==",
          "dev": true,
          "requires": {
            "micromatch": "^3.1.4",
            "normalize-path": "^2.1.1"
          }
        },
        "braces": {
          "version": "2.3.2",
          "resolved": "https://registry.npmjs.org/braces/-/braces-2.3.2.tgz",
          "integrity": "sha512-aNdbnj9P8PjdXU4ybaWLK2IF3jc/EoDYbC7AazW6to3TRsfXxscC9UXOB5iDiEQrkyIbWp2SLQda4+QAa7nc3w==",
          "dev": true,
          "requires": {
            "arr-flatten": "^1.1.0",
            "array-unique": "^0.3.2",
            "extend-shallow": "^2.0.1",
            "fill-range": "^4.0.0",
            "isobject": "^3.0.1",
            "repeat-element": "^1.1.2",
            "snapdragon": "^0.8.1",
            "snapdragon-node": "^2.0.1",
            "split-string": "^3.0.2",
            "to-regex": "^3.0.1"
          },
          "dependencies": {
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "dev": true,
              "requires": {
                "is-extendable": "^0.1.0"
              }
            }
          }
        },
        "execa": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/execa/-/execa-1.0.0.tgz",
          "integrity": "sha512-adbxcyWV46qiHyvSp50TKt05tB4tK3HcmF7/nxfAdhnox83seTDbwnaqKO4sXRy7roHAIFqJP/Rw/AuEbX61LA==",
          "dev": true,
          "requires": {
            "cross-spawn": "^6.0.0",
            "get-stream": "^4.0.0",
            "is-stream": "^1.1.0",
            "npm-run-path": "^2.0.0",
            "p-finally": "^1.0.0",
            "signal-exit": "^3.0.0",
            "strip-eof": "^1.0.0"
          }
        },
        "fill-range": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/fill-range/-/fill-range-4.0.0.tgz",
          "integrity": "sha1-1USBHUKPmOsGpj3EAtJAPDKMOPc=",
          "dev": true,
          "requires": {
            "extend-shallow": "^2.0.1",
            "is-number": "^3.0.0",
            "repeat-string": "^1.6.1",
            "to-regex-range": "^2.1.0"
          },
          "dependencies": {
            "extend-shallow": {
              "version": "2.0.1",
              "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
              "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
              "dev": true,
              "requires": {
                "is-extendable": "^0.1.0"
              }
            }
          }
        },
        "get-stream": {
          "version": "4.1.0",
          "resolved": "https://registry.npmjs.org/get-stream/-/get-stream-4.1.0.tgz",
          "integrity": "sha512-GMat4EJ5161kIy2HevLlr4luNjBgvmj413KaQA7jt4V8B4RDsfpHk7WQ9GVqfYyyx8OS/L66Kox+rJRNklLK7w==",
          "dev": true,
          "requires": {
            "pump": "^3.0.0"
          }
        },
        "is-extendable": {
          "version": "0.1.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
          "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
          "dev": true
        },
        "is-number": {
          "version": "3.0.0",
          "resolved": "https://registry.npmjs.org/is-number/-/is-number-3.0.0.tgz",
          "integrity": "sha1-JP1iAaR4LPUFYcgQJ2r8fRLXEZU=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "is-stream": {
          "version": "1.1.0",
          "resolved": "https://registry.npmjs.org/is-stream/-/is-stream-1.1.0.tgz",
          "integrity": "sha1-EtSj3U5o4Lec6428hBc66A2RykQ=",
          "dev": true
        },
        "micromatch": {
          "version": "3.1.10",
          "resolved": "https://registry.npmjs.org/micromatch/-/micromatch-3.1.10.tgz",
          "integrity": "sha512-MWikgl9n9M3w+bpsY3He8L+w9eF9338xRl8IAO5viDizwSzziFEyUzo2xrrloB64ADbTf8uA8vRqqttDTOmccg==",
          "dev": true,
          "requires": {
            "arr-diff": "^4.0.0",
            "array-unique": "^0.3.2",
            "braces": "^2.3.1",
            "define-property": "^2.0.2",
            "extend-shallow": "^3.0.2",
            "extglob": "^2.0.4",
            "fragment-cache": "^0.2.1",
            "kind-of": "^6.0.2",
            "nanomatch": "^1.2.9",
            "object.pick": "^1.3.0",
            "regex-not": "^1.0.0",
            "snapdragon": "^0.8.1",
            "to-regex": "^3.0.2"
          }
        },
        "normalize-path": {
          "version": "2.1.1",
          "resolved": "https://registry.npmjs.org/normalize-path/-/normalize-path-2.1.1.tgz",
          "integrity": "sha1-GrKLVW4Zg2Oowab35vogE3/mrtk=",
          "dev": true,
          "requires": {
            "remove-trailing-separator": "^1.0.1"
          }
        },
        "npm-run-path": {
          "version": "2.0.2",
          "resolved": "https://registry.npmjs.org/npm-run-path/-/npm-run-path-2.0.2.tgz",
          "integrity": "sha1-NakjLfo11wZ7TLLd8jV7GHFTbF8=",
          "dev": true,
          "requires": {
            "path-key": "^2.0.0"
          }
        },
        "p-finally": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/p-finally/-/p-finally-1.0.0.tgz",
          "integrity": "sha1-P7z7FbiZpEEjs0ttzBi3JDNqLK4=",
          "dev": true
        },
        "to-regex-range": {
          "version": "2.1.1",
          "resolved": "https://registry.npmjs.org/to-regex-range/-/to-regex-range-2.1.1.tgz",
          "integrity": "sha1-fIDBe53+vlmeJzZ+DU3VWQFB2zg=",
          "dev": true,
          "requires": {
            "is-number": "^3.0.0",
            "repeat-string": "^1.6.1"
          }
        }
      }
    },
    "saxes": {
      "version": "3.1.11",
      "resolved": "https://registry.npmjs.org/saxes/-/saxes-3.1.11.tgz",
      "integrity": "sha512-Ydydq3zC+WYDJK1+gRxRapLIED9PWeSuuS41wqyoRmzvhhh9nc+QQrVMKJYzJFULazeGhzSV0QleN2wD3boh2g==",
      "dev": true,
      "requires": {
        "xmlchars": "^2.1.1"
      }
    },
    "scrypt-js": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/scrypt-js/-/scrypt-js-3.0.1.tgz",
      "integrity": "sha512-cdwTTnqPu0Hyvf5in5asVdZocVDTNRmR7XEcJuIzMjJeSHybHl7vpB66AzwTaIg6CLSbtjcxc8fqcySfnTkccA=="
    },
    "seed-random": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/seed-random/-/seed-random-2.2.0.tgz",
      "integrity": "sha1-KpsZ4lCoFwmSMaW5mk2vgLf77VQ=",
      "dev": true
    },
    "semver": {
      "version": "7.3.5",
      "resolved": "https://registry.npmjs.org/semver/-/semver-7.3.5.tgz",
      "integrity": "sha512-PoeGJYh8HK4BTO/a9Tf6ZG3veo/A7ZVsYrSA6J8ny9nb3B1VrpkuN+z9OE5wfE5p6H4LchYZsegiQgbJD94ZFQ==",
      "dev": true,
      "requires": {
        "lru-cache": "^6.0.0"
      }
    },
    "serve": {
      "version": "14.1.2",
      "resolved": "https://registry.npmjs.org/serve/-/serve-14.1.2.tgz",
      "integrity": "sha512-luwVfJwbeE7dhCKeRU0vIBpt4bXdbAfzwsWJIQ5eqrIW2e+4nLWXbSlZ0WzelSFHQq+FlueOW6dr90jEewS9zw==",
      "dev": true,
      "requires": {
        "@zeit/schemas": "2.21.0",
        "ajv": "8.11.0",
        "arg": "5.0.2",
        "boxen": "7.0.0",
        "chalk": "5.0.1",
        "chalk-template": "0.4.0",
        "clipboardy": "3.0.0",
        "compression": "1.7.4",
        "is-port-reachable": "4.0.0",
        "serve-handler": "6.1.5",
        "update-check": "1.5.4"
      },
      "dependencies": {
        "ajv": {
          "version": "8.11.0",
          "resolved": "https://registry.npmjs.org/ajv/-/ajv-8.11.0.tgz",
          "integrity": "sha512-wGgprdCvMalC0BztXvitD2hC04YffAvtsUn93JbGXYLAtCUO4xd17mCCZQxUOItiBwZvJScWo8NIvQMQ71rdpg==",
          "dev": true,
          "requires": {
            "fast-deep-equal": "^3.1.1",
            "json-schema-traverse": "^1.0.0",
            "require-from-string": "^2.0.2",
            "uri-js": "^4.2.2"
          }
        },
        "chalk": {
          "version": "5.0.1",
          "resolved": "https://registry.npmjs.org/chalk/-/chalk-5.0.1.tgz",
          "integrity": "sha512-Fo07WOYGqMfCWHOzSXOt2CxDbC6skS/jO9ynEcmpANMoPrD+W1r1K6Vx7iNm+AQmETU1Xr2t+n8nzkV9t6xh3w==",
          "dev": true
        },
        "json-schema-traverse": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/json-schema-traverse/-/json-schema-traverse-1.0.0.tgz",
          "integrity": "sha512-NM8/P9n3XjXhIZn1lLhkFaACTOURQXjWhV4BA/RnOv8xvgqtqpAX9IO4mRQxSx1Rlo4tqzeqb0sOlruaOy3dug==",
          "dev": true
        }
      }
    },
    "serve-handler": {
      "version": "6.1.5",
      "resolved": "https://registry.npmjs.org/serve-handler/-/serve-handler-6.1.5.tgz",
      "integrity": "sha512-ijPFle6Hwe8zfmBxJdE+5fta53fdIY0lHISJvuikXB3VYFafRjMRpOffSPvCYsbKyBA7pvy9oYr/BT1O3EArlg==",
      "dev": true,
      "requires": {
        "bytes": "3.0.0",
        "content-disposition": "0.5.2",
        "fast-url-parser": "1.1.3",
        "mime-types": "2.1.18",
        "minimatch": "3.1.2",
        "path-is-inside": "1.0.2",
        "path-to-regexp": "2.2.1",
        "range-parser": "1.2.0"
      },
      "dependencies": {
        "mime-db": {
          "version": "1.33.0",
          "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.33.0.tgz",
          "integrity": "sha512-BHJ/EKruNIqJf/QahvxwQZXKygOQ256myeN/Ew+THcAa5q+PjyTTMMeNQC4DZw5AwfvelsUrA6B67NKMqXDbzQ==",
          "dev": true
        },
        "mime-types": {
          "version": "2.1.18",
          "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.18.tgz",
          "integrity": "sha512-lc/aahn+t4/SWV/qcmumYjymLsWfN3ELhpmVuUFjgsORruuZPVSwAQryq+HHGvO/SI2KVX26bx+En+zhM8g8hQ==",
          "dev": true,
          "requires": {
            "mime-db": "~1.33.0"
          }
        }
      }
    },
    "set-blocking": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/set-blocking/-/set-blocking-2.0.0.tgz",
      "integrity": "sha1-BF+XgtARrppoA93TgrJDkrPYkPc=",
      "dev": true
    },
    "set-value": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/set-value/-/set-value-2.0.1.tgz",
      "integrity": "sha512-JxHc1weCN68wRY0fhCoXpyK55m/XPHafOmK4UWD7m2CI14GMcFypt4w/0+NV5f/ZMby2F6S2wwA7fgynh9gWSw==",
      "dev": true,
      "requires": {
        "extend-shallow": "^2.0.1",
        "is-extendable": "^0.1.1",
        "is-plain-object": "^2.0.3",
        "split-string": "^3.0.1"
      },
      "dependencies": {
        "extend-shallow": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
          "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
          "dev": true,
          "requires": {
            "is-extendable": "^0.1.0"
          }
        },
        "is-extendable": {
          "version": "0.1.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
          "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
          "dev": true
        }
      }
    },
    "shebang-command": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/shebang-command/-/shebang-command-1.2.0.tgz",
      "integrity": "sha1-RKrGW2lbAzmJaMOfNj/uXer98eo=",
      "dev": true,
      "requires": {
        "shebang-regex": "^1.0.0"
      }
    },
    "shebang-regex": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/shebang-regex/-/shebang-regex-1.0.0.tgz",
      "integrity": "sha1-2kL0l0DAtC2yypcoVxyxkMmO/qM=",
      "dev": true
    },
    "shelljs": {
      "version": "0.8.5",
      "resolved": "https://registry.npmjs.org/shelljs/-/shelljs-0.8.5.tgz",
      "integrity": "sha512-TiwcRcrkhHvbrZbnRcFYMLl30Dfov3HKqzp5tO5b4pt6G/SezKcYhmDg15zXVBswHmctSAQKznqNW2LO5tTDow==",
      "dev": true,
      "requires": {
        "glob": "^7.0.0",
        "interpret": "^1.0.0",
        "rechoir": "^0.6.2"
      }
    },
    "shellwords": {
      "version": "0.1.1",
      "resolved": "https://registry.npmjs.org/shellwords/-/shellwords-0.1.1.tgz",
      "integrity": "sha512-vFwSUfQvqybiICwZY5+DAWIPLKsWO31Q91JSKl3UYv+K5c2QRPzn0qzec6QPu1Qc9eHYItiP3NdJqNVqetYAww==",
      "dev": true,
      "optional": true
    },
    "signal-exit": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/signal-exit/-/signal-exit-3.0.3.tgz",
      "integrity": "sha512-VUJ49FC8U1OxwZLxIbTTrDvLnf/6TDgxZcK8wxR8zs13xpx7xbG60ndBlhNrFi2EMuFRoeDoJO7wthSLq42EjA==",
      "dev": true
    },
    "sisteransi": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/sisteransi/-/sisteransi-1.0.5.tgz",
      "integrity": "sha512-bLGGlR1QxBcynn2d5YmDX4MGjlZvy2MRBDRNHLJ8VI6l6+9FUiyTFNJ0IveOSP0bcXgVDPRcfGqA0pjaqUpfVg==",
      "dev": true
    },
    "slash": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/slash/-/slash-3.0.0.tgz",
      "integrity": "sha512-g9Q1haeby36OSStwb4ntCGGGaKsaVSjQ68fBxoQcutl5fS1vuY18H3wSt3jFyFtrkx+Kz0V1G85A4MyAdDMi2Q==",
      "dev": true
    },
    "slice-ansi": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/slice-ansi/-/slice-ansi-2.1.0.tgz",
      "integrity": "sha512-Qu+VC3EwYLldKa1fCxuuvULvSJOKEgk9pi8dZeCVK7TqBfUNTH4sFkk4joj8afVSfAYgJoSOetjx9QWOJ5mYoQ==",
      "dev": true,
      "requires": {
        "ansi-styles": "^3.2.0",
        "astral-regex": "^1.0.0",
        "is-fullwidth-code-point": "^2.0.0"
      },
      "dependencies": {
        "is-fullwidth-code-point": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz",
          "integrity": "sha1-o7MKXE8ZkYMWeqq5O+764937ZU8=",
          "dev": true
        }
      }
    },
    "snapdragon": {
      "version": "0.8.2",
      "resolved": "https://registry.npmjs.org/snapdragon/-/snapdragon-0.8.2.tgz",
      "integrity": "sha512-FtyOnWN/wCHTVXOMwvSv26d+ko5vWlIDD6zoUJ7LW8vh+ZBC8QdljveRP+crNrtBwioEUWy/4dMtbBjA4ioNlg==",
      "dev": true,
      "requires": {
        "base": "^0.11.1",
        "debug": "^2.2.0",
        "define-property": "^0.2.5",
        "extend-shallow": "^2.0.1",
        "map-cache": "^0.2.2",
        "source-map": "^0.5.6",
        "source-map-resolve": "^0.5.0",
        "use": "^3.1.0"
      },
      "dependencies": {
        "debug": {
          "version": "2.6.9",
          "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
          "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
          "dev": true,
          "requires": {
            "ms": "2.0.0"
          }
        },
        "define-property": {
          "version": "0.2.5",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
          "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
          "dev": true,
          "requires": {
            "is-descriptor": "^0.1.0"
          }
        },
        "extend-shallow": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/extend-shallow/-/extend-shallow-2.0.1.tgz",
          "integrity": "sha1-Ua99YUrZqfYQ6huvu5idaxxWiQ8=",
          "dev": true,
          "requires": {
            "is-extendable": "^0.1.0"
          }
        },
        "is-accessor-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
          "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "is-data-descriptor": {
          "version": "0.1.4",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
          "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "is-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
          "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
          "dev": true,
          "requires": {
            "is-accessor-descriptor": "^0.1.6",
            "is-data-descriptor": "^0.1.4",
            "kind-of": "^5.0.0"
          }
        },
        "is-extendable": {
          "version": "0.1.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
          "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
          "dev": true
        },
        "kind-of": {
          "version": "5.1.0",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
          "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
          "dev": true
        },
        "ms": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
          "integrity": "sha1-VgiurfwAvmwpAd9fmGF4jeDVl8g=",
          "dev": true
        },
        "source-map": {
          "version": "0.5.7",
          "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.5.7.tgz",
          "integrity": "sha1-igOdLRAh0i0eoUyA2OpGi6LvP8w=",
          "dev": true
        }
      }
    },
    "snapdragon-node": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/snapdragon-node/-/snapdragon-node-2.1.1.tgz",
      "integrity": "sha512-O27l4xaMYt/RSQ5TR3vpWCAB5Kb/czIcqUFOM/C4fYcLnbZUc1PkjTAMjof2pBWaSTwOUd6qUHcFGVGj7aIwnw==",
      "dev": true,
      "requires": {
        "define-property": "^1.0.0",
        "isobject": "^3.0.0",
        "snapdragon-util": "^3.0.1"
      },
      "dependencies": {
        "define-property": {
          "version": "1.0.0",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-1.0.0.tgz",
          "integrity": "sha1-dp66rz9KY6rTr56NMEybvnm/sOY=",
          "dev": true,
          "requires": {
            "is-descriptor": "^1.0.0"
          }
        }
      }
    },
    "snapdragon-util": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/snapdragon-util/-/snapdragon-util-3.0.1.tgz",
      "integrity": "sha512-mbKkMdQKsjX4BAL4bRYTj21edOf8cN7XHdYUJEe+Zn99hVEYcMvKPct1IqNe7+AZPirn8BCDOQBHQZknqmKlZQ==",
      "dev": true,
      "requires": {
        "kind-of": "^3.2.0"
      },
      "dependencies": {
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "dev": true,
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "source-map": {
      "version": "0.6.1",
      "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.6.1.tgz",
      "integrity": "sha512-UjgapumWlbMhkBgzT7Ykc5YXUT46F0iKu8SGXq0bcwP5dz/h0Plj6enJqjz1Zbq2l5WaqYnrVbwWOWMyF3F47g==",
      "dev": true
    },
    "source-map-resolve": {
      "version": "0.5.3",
      "resolved": "https://registry.npmjs.org/source-map-resolve/-/source-map-resolve-0.5.3.tgz",
      "integrity": "sha512-Htz+RnsXWk5+P2slx5Jh3Q66vhQj1Cllm0zvnaY98+NFx+Dv2CF/f5O/t8x+KaNdrdIAsruNzoh/KpialbqAnw==",
      "dev": true,
      "requires": {
        "atob": "^2.1.2",
        "decode-uri-component": "^0.2.0",
        "resolve-url": "^0.2.1",
        "source-map-url": "^0.4.0",
        "urix": "^0.1.0"
      }
    },
    "source-map-support": {
      "version": "0.5.19",
      "resolved": "https://registry.npmjs.org/source-map-support/-/source-map-support-0.5.19.tgz",
      "integrity": "sha512-Wonm7zOCIJzBGQdB+thsPar0kYuCIzYvxZwlBa87yi/Mdjv7Tip2cyVbLj5o0cFPN4EVkuTwb3GDDyUx2DGnGw==",
      "dev": true,
      "requires": {
        "buffer-from": "^1.0.0",
        "source-map": "^0.6.0"
      }
    },
    "source-map-url": {
      "version": "0.4.1",
      "resolved": "https://registry.npmjs.org/source-map-url/-/source-map-url-0.4.1.tgz",
      "integrity": "sha512-cPiFOTLUKvJFIg4SKVScy4ilPPW6rFgMgfuZJPNoDuMs3nC1HbMUycBoJw77xFIp6z1UJQJOfx6C9GMH80DiTw==",
      "dev": true
    },
    "spdx-correct": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/spdx-correct/-/spdx-correct-3.1.1.tgz",
      "integrity": "sha512-cOYcUWwhCuHCXi49RhFRCyJEK3iPj1Ziz9DpViV3tbZOwXD49QzIN3MpOLJNxh2qwq2lJJZaKMVw9qNi4jTC0w==",
      "dev": true,
      "requires": {
        "spdx-expression-parse": "^3.0.0",
        "spdx-license-ids": "^3.0.0"
      }
    },
    "spdx-exceptions": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/spdx-exceptions/-/spdx-exceptions-2.3.0.tgz",
      "integrity": "sha512-/tTrYOC7PPI1nUAgx34hUpqXuyJG+DTHJTnIULG4rDygi4xu/tfgmq1e1cIRwRzwZgo4NLySi+ricLkZkw4i5A==",
      "dev": true
    },
    "spdx-expression-parse": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/spdx-expression-parse/-/spdx-expression-parse-3.0.1.tgz",
      "integrity": "sha512-cbqHunsQWnJNE6KhVSMsMeH5H/L9EpymbzqTQ3uLwNCLZ1Q481oWaofqH7nO6V07xlXwY6PhQdQ2IedWx/ZK4Q==",
      "dev": true,
      "requires": {
        "spdx-exceptions": "^2.1.0",
        "spdx-license-ids": "^3.0.0"
      }
    },
    "spdx-license-ids": {
      "version": "3.0.9",
      "resolved": "https://registry.npmjs.org/spdx-license-ids/-/spdx-license-ids-3.0.9.tgz",
      "integrity": "sha512-Ki212dKK4ogX+xDo4CtOZBVIwhsKBEfsEEcwmJfLQzirgc2jIWdzg40Unxz/HzEUqM1WFzVlQSMF9kZZ2HboLQ==",
      "dev": true
    },
    "split-string": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/split-string/-/split-string-3.1.0.tgz",
      "integrity": "sha512-NzNVhJDYpwceVVii8/Hu6DKfD2G+NrQHlS/V/qgv763EYudVwEcMQNxd2lh+0VrUByXN/oJkl5grOhYWvQUYiw==",
      "dev": true,
      "requires": {
        "extend-shallow": "^3.0.0"
      }
    },
    "sprintf-js": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/sprintf-js/-/sprintf-js-1.0.3.tgz",
      "integrity": "sha1-BOaSb2YolTVPPdAVIDYzuFcpfiw=",
      "dev": true
    },
    "sshpk": {
      "version": "1.16.1",
      "resolved": "https://registry.npmjs.org/sshpk/-/sshpk-1.16.1.tgz",
      "integrity": "sha512-HXXqVUq7+pcKeLqqZj6mHFUMvXtOJt1uoUx09pFW6011inTMxqI8BA8PM95myrIyyKwdnzjdFjLiE6KBPVtJIg==",
      "dev": true,
      "requires": {
        "asn1": "~0.2.3",
        "assert-plus": "^1.0.0",
        "bcrypt-pbkdf": "^1.0.0",
        "dashdash": "^1.12.0",
        "ecc-jsbn": "~0.1.1",
        "getpass": "^0.1.1",
        "jsbn": "~0.1.0",
        "safer-buffer": "^2.0.2",
        "tweetnacl": "~0.14.0"
      }
    },
    "stack-chain": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/stack-chain/-/stack-chain-2.0.0.tgz",
      "integrity": "sha512-GGrHXePi305aW7XQweYZZwiRwR7Js3MWoK/EHzzB9ROdc75nCnjSJVi21rdAGxFl+yCx2L2qdfl5y7NO4lTyqg==",
      "dev": true
    },
    "stack-generator": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/stack-generator/-/stack-generator-2.0.5.tgz",
      "integrity": "sha512-/t1ebrbHkrLrDuNMdeAcsvynWgoH/i4o8EGGfX7dEYDoTXOYVAkEpFdtshlvabzc6JlJ8Kf9YdFEoz7JkzGN9Q==",
      "dev": true,
      "requires": {
        "stackframe": "^1.1.1"
      }
    },
    "stack-utils": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/stack-utils/-/stack-utils-1.0.5.tgz",
      "integrity": "sha512-KZiTzuV3CnSnSvgMRrARVCj+Ht7rMbauGDK0LdVFRGyenwdylpajAp4Q0i6SX8rEmbTpMMf6ryq2gb8pPq2WgQ==",
      "dev": true,
      "requires": {
        "escape-string-regexp": "^2.0.0"
      },
      "dependencies": {
        "escape-string-regexp": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-2.0.0.tgz",
          "integrity": "sha512-UpzcLCXolUWcNu5HtVMHYdXJjArjsF9C0aNnquZYY4uW/Vu0miy5YoWvbV345HauVvcAUnpRuhMMcqTcGOY2+w==",
          "dev": true
        }
      }
    },
    "stackframe": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/stackframe/-/stackframe-1.2.0.tgz",
      "integrity": "sha512-GrdeshiRmS1YLMYgzF16olf2jJ/IzxXY9lhKOskuVziubpTYcYqyOwYeJKzQkwy7uN0fYSsbsC4RQaXf9LCrYA==",
      "dev": true
    },
    "stacktrace-gps": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/stacktrace-gps/-/stacktrace-gps-3.0.4.tgz",
      "integrity": "sha512-qIr8x41yZVSldqdqe6jciXEaSCKw1U8XTXpjDuy0ki/apyTn/r3w9hDAAQOhZdxvsC93H+WwwEu5cq5VemzYeg==",
      "dev": true,
      "requires": {
        "source-map": "0.5.6",
        "stackframe": "^1.1.1"
      },
      "dependencies": {
        "source-map": {
          "version": "0.5.6",
          "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz",
          "integrity": "sha1-dc449SvwczxafwwRjYEzSiu19BI=",
          "dev": true
        }
      }
    },
    "stacktrace-js": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/stacktrace-js/-/stacktrace-js-2.0.2.tgz",
      "integrity": "sha512-Je5vBeY4S1r/RnLydLl0TBTi3F2qdfWmYsGvtfZgEI+SCprPppaIhQf5nGcal4gI4cGpCV/duLcAzT1np6sQqg==",
      "dev": true,
      "requires": {
        "error-stack-parser": "^2.0.6",
        "stack-generator": "^2.0.5",
        "stacktrace-gps": "^3.0.4"
      }
    },
    "static-extend": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/static-extend/-/static-extend-0.1.2.tgz",
      "integrity": "sha1-YICcOcv/VTNyJv1eC1IPNB8ftcY=",
      "dev": true,
      "requires": {
        "define-property": "^0.2.5",
        "object-copy": "^0.1.0"
      },
      "dependencies": {
        "define-property": {
          "version": "0.2.5",
          "resolved": "https://registry.npmjs.org/define-property/-/define-property-0.2.5.tgz",
          "integrity": "sha1-w1se+RjsPJkPmlvFe+BKrOxcgRY=",
          "dev": true,
          "requires": {
            "is-descriptor": "^0.1.0"
          }
        },
        "is-accessor-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-accessor-descriptor/-/is-accessor-descriptor-0.1.6.tgz",
          "integrity": "sha1-qeEss66Nh2cn7u84Q/igiXtcmNY=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "is-data-descriptor": {
          "version": "0.1.4",
          "resolved": "https://registry.npmjs.org/is-data-descriptor/-/is-data-descriptor-0.1.4.tgz",
          "integrity": "sha1-C17mSDiOLIYCgueT8YVv7D8wG1Y=",
          "dev": true,
          "requires": {
            "kind-of": "^3.0.2"
          },
          "dependencies": {
            "kind-of": {
              "version": "3.2.2",
              "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
              "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
              "dev": true,
              "requires": {
                "is-buffer": "^1.1.5"
              }
            }
          }
        },
        "is-descriptor": {
          "version": "0.1.6",
          "resolved": "https://registry.npmjs.org/is-descriptor/-/is-descriptor-0.1.6.tgz",
          "integrity": "sha512-avDYr0SB3DwO9zsMov0gKCESFYqCnE4hq/4z3TdUlukEy5t9C0YRq7HLrsN52NAcqXKaepeCD0n+B0arnVG3Hg==",
          "dev": true,
          "requires": {
            "is-accessor-descriptor": "^0.1.6",
            "is-data-descriptor": "^0.1.4",
            "kind-of": "^5.0.0"
          }
        },
        "kind-of": {
          "version": "5.1.0",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-5.1.0.tgz",
          "integrity": "sha512-NGEErnH6F2vUuXDh+OlbcKW7/wOcfdRHaZ7VWtqCztfHri/++YKmP51OdWeGPuqCOba6kk2OTe5d02VmTB80Pw==",
          "dev": true
        }
      }
    },
    "stealthy-require": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/stealthy-require/-/stealthy-require-1.1.1.tgz",
      "integrity": "sha1-NbCYdbT/SfJqd35QmzCQoyJr8ks=",
      "dev": true
    },
    "string-argv": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/string-argv/-/string-argv-0.3.1.tgz",
      "integrity": "sha512-a1uQGz7IyVy9YwhqjZIZu1c8JO8dNIe20xBmSS6qu9kv++k3JGzCVmprbNN5Kn+BgzD5E7YYwg1CcjuJMRNsvg==",
      "dev": true
    },
    "string-length": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/string-length/-/string-length-3.1.0.tgz",
      "integrity": "sha512-Ttp5YvkGm5v9Ijagtaz1BnN+k9ObpvS0eIBblPMp2YWL8FBmi9qblQ9fexc2k/CXFgrTIteU3jAw3payCnwSTA==",
      "dev": true,
      "requires": {
        "astral-regex": "^1.0.0",
        "strip-ansi": "^5.2.0"
      }
    },
    "string-width": {
      "version": "4.2.2",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-4.2.2.tgz",
      "integrity": "sha512-XBJbT3N4JhVumXE0eoLU9DCjcaF92KLNqTmFCnG1pf8duUxFGwtP6AD6nkjw9a3IdiRtL3E2w3JDiE/xi3vOeA==",
      "dev": true,
      "requires": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.0"
      },
      "dependencies": {
        "strip-ansi": {
          "version": "6.0.0",
          "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
          "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
          "dev": true,
          "requires": {
            "ansi-regex": "^5.0.0"
          }
        }
      }
    },
    "string.prototype.trimend": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/string.prototype.trimend/-/string.prototype.trimend-1.0.4.tgz",
      "integrity": "sha512-y9xCjw1P23Awk8EvTpcyL2NIr1j7wJ39f+k6lvRnSMz+mz9CGz9NYPelDk42kOz6+ql8xjfK8oYzy3jAP5QU5A==",
      "dev": true,
      "requires": {
        "call-bind": "^1.0.2",
        "define-properties": "^1.1.3"
      }
    },
    "string.prototype.trimstart": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/string.prototype.trimstart/-/string.prototype.trimstart-1.0.4.tgz",
      "integrity": "sha512-jh6e984OBfvxS50tdY2nRZnoC5/mLFKOREQfw8t5yytkoUsJRNxvI/E39qu1sD0OtWI3OC0XgKSmcWwziwYuZw==",
      "dev": true,
      "requires": {
        "call-bind": "^1.0.2",
        "define-properties": "^1.1.3"
      }
    },
    "strip-ansi": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-5.2.0.tgz",
      "integrity": "sha512-DuRs1gKbBqsMKIZlrffwlug8MHkcnpjs5VPmL1PAh+mA30U0DTotfDZ0d2UUsXpPmPmMMJ6W773MaA3J+lbiWA==",
      "dev": true,
      "requires": {
        "ansi-regex": "^4.1.0"
      },
      "dependencies": {
        "ansi-regex": {
          "version": "4.1.1",
          "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-4.1.1.tgz",
          "integrity": "sha512-ILlv4k/3f6vfQ4OoP2AGvirOktlQ98ZEL1k9FaQjxa3L1abBgbuTDAdPOpvbGncC0BTVQrl+OM8xZGK6tWXt7g==",
          "dev": true
        }
      }
    },
    "strip-bom": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/strip-bom/-/strip-bom-4.0.0.tgz",
      "integrity": "sha512-3xurFv5tEgii33Zi8Jtp55wEIILR9eh34FAW00PZf+JnSsTmV/ioewSgQl97JHvgjoRGwPShsWm+IdrxB35d0w==",
      "dev": true
    },
    "strip-eof": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/strip-eof/-/strip-eof-1.0.0.tgz",
      "integrity": "sha1-u0P/VZim6wXYm1n80SnJgzE2Br8=",
      "dev": true
    },
    "strip-final-newline": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/strip-final-newline/-/strip-final-newline-2.0.0.tgz",
      "integrity": "sha512-BrpvfNAE3dcvq7ll3xVumzjKjZQ5tI1sEUIKr3Uoks0XUl45St3FlatVqef9prk4jRDzhW6WZg+3bk93y6pLjA==",
      "dev": true
    },
    "strip-json-comments": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-3.1.1.tgz",
      "integrity": "sha512-6fPc+R4ihwqP6N/aIv2f1gMH8lOVtWQHoqC4yK6oSDVVocumAsfCqjkXnqiYMhmMwS/mEHLp7Vehlt3ql6lEig==",
      "dev": true
    },
    "strip-outer": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/strip-outer/-/strip-outer-1.0.1.tgz",
      "integrity": "sha512-k55yxKHwaXnpYGsOzg4Vl8+tDrWylxDEpknGjhTiZB8dFRU5rTo9CAzeycivxV3s+zlTKwrs6WxMxR95n26kwg==",
      "dev": true,
      "requires": {
        "escape-string-regexp": "^1.0.2"
      }
    },
    "subscriptions-transport-ws": {
      "version": "0.9.18",
      "resolved": "https://registry.npmjs.org/subscriptions-transport-ws/-/subscriptions-transport-ws-0.9.18.tgz",
      "integrity": "sha512-tztzcBTNoEbuErsVQpTN2xUNN/efAZXyCyL5m3x4t6SKrEiTL2N8SaKWBFWM4u56pL79ULif3zjyeq+oV+nOaA==",
      "requires": {
        "backo2": "^1.0.2",
        "eventemitter3": "^3.1.0",
        "iterall": "^1.2.1",
        "symbol-observable": "^1.0.4",
        "ws": "^5.2.0"
      },
      "dependencies": {
        "symbol-observable": {
          "version": "1.2.0",
          "resolved": "https://registry.npmjs.org/symbol-observable/-/symbol-observable-1.2.0.tgz",
          "integrity": "sha512-e900nM8RRtGhlV36KGEU9k65K3mPb1WV70OdjfxlG2EAuM1noi/E/BaW/uMhL7bPEssK8QV57vN3esixjUvcXQ=="
        },
        "ws": {
          "version": "5.2.3",
          "resolved": "https://registry.npmjs.org/ws/-/ws-5.2.3.tgz",
          "integrity": "sha512-jZArVERrMsKUatIdnLzqvcfydI85dvd/Fp1u/VOpfdDWQ4c9qWXe+VIeAbQ5FrDwciAkr+lzofXLz3Kuf26AOA==",
          "requires": {
            "async-limiter": "~1.0.0"
          }
        }
      }
    },
    "supports-color": {
      "version": "5.5.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-5.5.0.tgz",
      "integrity": "sha512-QjVjwdXIt408MIiAqCX4oUKsgU2EqAGzs2Ppkm4aQYbjm+ZEWEcW4SfFNTr4uMNZma0ey4f5lgLrkB0aX0QMow==",
      "dev": true,
      "requires": {
        "has-flag": "^3.0.0"
      }
    },
    "supports-hyperlinks": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/supports-hyperlinks/-/supports-hyperlinks-2.2.0.tgz",
      "integrity": "sha512-6sXEzV5+I5j8Bmq9/vUphGRM/RJNT9SCURJLjwfOg51heRtguGWDzcaBlgAzKhQa0EVNpPEKzQuBwZ8S8WaCeQ==",
      "dev": true,
      "requires": {
        "has-flag": "^4.0.0",
        "supports-color": "^7.0.0"
      },
      "dependencies": {
        "has-flag": {
          "version": "4.0.0",
          "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
          "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
          "dev": true
        },
        "supports-color": {
          "version": "7.2.0",
          "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
          "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
          "dev": true,
          "requires": {
            "has-flag": "^4.0.0"
          }
        }
      }
    },
    "symbol-observable": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/symbol-observable/-/symbol-observable-4.0.0.tgz",
      "integrity": "sha512-b19dMThMV4HVFynSAM1++gBHAbk2Tc/osgLIBZMKsyqh34jb2e8Os7T6ZW/Bt3pJFdBTd2JwAnAAEQV7rSNvcQ=="
    },
    "symbol-tree": {
      "version": "3.2.4",
      "resolved": "https://registry.npmjs.org/symbol-tree/-/symbol-tree-3.2.4.tgz",
      "integrity": "sha512-9QNk5KwDF+Bvz+PyObkmSYjI5ksVUYtjW7AU22r2NKcfLJcXp96hkDWU3+XndOsUb+AQ9QhfzfCT2O+CNWT5Tw==",
      "dev": true
    },
    "table": {
      "version": "5.4.6",
      "resolved": "https://registry.npmjs.org/table/-/table-5.4.6.tgz",
      "integrity": "sha512-wmEc8m4fjnob4gt5riFRtTu/6+4rSe12TpAELNSqHMfF3IqnA+CH37USM6/YR3qRZv7e56kAEAtd6nKZaxe0Ug==",
      "dev": true,
      "requires": {
        "ajv": "^6.10.2",
        "lodash": "^4.17.14",
        "slice-ansi": "^2.1.0",
        "string-width": "^3.0.0"
      },
      "dependencies": {
        "emoji-regex": {
          "version": "7.0.3",
          "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-7.0.3.tgz",
          "integrity": "sha512-CwBLREIQ7LvYFB0WyRvwhq5N5qPhc6PMjD6bYggFlI5YyDgl+0vxq5VHbMOFqLg7hfWzmu8T5Z1QofhmTIhItA==",
          "dev": true
        },
        "is-fullwidth-code-point": {
          "version": "2.0.0",
          "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-2.0.0.tgz",
          "integrity": "sha1-o7MKXE8ZkYMWeqq5O+764937ZU8=",
          "dev": true
        },
        "string-width": {
          "version": "3.1.0",
          "resolved": "https://registry.npmjs.org/string-width/-/string-width-3.1.0.tgz",
          "integrity": "sha512-vafcv6KjVZKSgz06oM/H6GDBrAtz8vdhQakGjFIvNrHA6y3HCF1CInLy+QLq8dTJPQ1b+KDUqDFctkdRW44e1w==",
          "dev": true,
          "requires": {
            "emoji-regex": "^7.0.1",
            "is-fullwidth-code-point": "^2.0.0",
            "strip-ansi": "^5.1.0"
          }
        }
      }
    },
    "terminal-link": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/terminal-link/-/terminal-link-2.1.1.tgz",
      "integrity": "sha512-un0FmiRUQNr5PJqy9kP7c40F5BOfpGlYTrxonDChEZB7pzZxRNp/bt+ymiy9/npwXya9KH99nJ/GXFIiUkYGFQ==",
      "dev": true,
      "requires": {
        "ansi-escapes": "^4.2.1",
        "supports-hyperlinks": "^2.0.0"
      }
    },
    "test-exclude": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/test-exclude/-/test-exclude-6.0.0.tgz",
      "integrity": "sha512-cAGWPIyOHU6zlmg88jwm7VRyXnMN7iV68OGAbYDk/Mh/xC/pzVPlQtY6ngoIH/5/tciuhGfvESU8GrHrcxD56w==",
      "dev": true,
      "requires": {
        "@istanbuljs/schema": "^0.1.2",
        "glob": "^7.1.4",
        "minimatch": "^3.0.4"
      }
    },
    "text-table": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/text-table/-/text-table-0.2.0.tgz",
      "integrity": "sha1-f17oI66AUgfACvLfSoTsP8+lcLQ=",
      "dev": true
    },
    "thenify": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/thenify/-/thenify-3.3.1.tgz",
      "integrity": "sha512-RVZSIV5IG10Hk3enotrhvz0T9em6cyHBLkH/YAZuKqd8hRkKhSfCGIcP2KUY0EPxndzANBmNllzWPwak+bheSw==",
      "dev": true,
      "requires": {
        "any-promise": "^1.0.0"
      }
    },
    "thenify-all": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/thenify-all/-/thenify-all-1.6.0.tgz",
      "integrity": "sha1-GhkY1ALY/D+Y+/I02wvMjMEOlyY=",
      "dev": true,
      "requires": {
        "thenify": ">= 3.1.0 < 4"
      }
    },
    "throat": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/throat/-/throat-5.0.0.tgz",
      "integrity": "sha512-fcwX4mndzpLQKBS1DVYhGAcYaYt7vsHNIvQV+WXMvnow5cgjPphq5CaayLaGsjRdSCKZFNGt7/GYAuXaNOiYCA==",
      "dev": true
    },
    "through": {
      "version": "2.3.8",
      "resolved": "https://registry.npmjs.org/through/-/through-2.3.8.tgz",
      "integrity": "sha1-DdTJ/6q8NXlgsbckEV1+Doai4fU=",
      "dev": true
    },
    "tmp": {
      "version": "0.2.1",
      "resolved": "https://registry.npmjs.org/tmp/-/tmp-0.2.1.tgz",
      "integrity": "sha512-76SUhtfqR2Ijn+xllcI5P1oyannHNHByD80W1q447gU3mp9G9PSpGdWmjUOHRDPiHYacIk66W7ubDTuPF3BEtQ==",
      "dev": true,
      "requires": {
        "rimraf": "^3.0.0"
      }
    },
    "tmpl": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/tmpl/-/tmpl-1.0.5.tgz",
      "integrity": "sha512-3f0uOEAQwIqGuWW2MVzYg8fV/QNnc/IpuJNG837rLuczAaLVHslWHZQj4IGiEl5Hs3kkbhwL9Ab7Hrsmuj+Smw==",
      "dev": true
    },
    "to-fast-properties": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/to-fast-properties/-/to-fast-properties-2.0.0.tgz",
      "integrity": "sha1-3F5pjL0HkmW8c+A3doGk5Og/YW4=",
      "dev": true
    },
    "to-object-path": {
      "version": "0.3.0",
      "resolved": "https://registry.npmjs.org/to-object-path/-/to-object-path-0.3.0.tgz",
      "integrity": "sha1-KXWIt7Dn4KwI4E5nL4XB9JmeF68=",
      "dev": true,
      "requires": {
        "kind-of": "^3.0.2"
      },
      "dependencies": {
        "kind-of": {
          "version": "3.2.2",
          "resolved": "https://registry.npmjs.org/kind-of/-/kind-of-3.2.2.tgz",
          "integrity": "sha1-MeohpzS6ubuw8yRm2JOupR5KPGQ=",
          "dev": true,
          "requires": {
            "is-buffer": "^1.1.5"
          }
        }
      }
    },
    "to-regex": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/to-regex/-/to-regex-3.0.2.tgz",
      "integrity": "sha512-FWtleNAtZ/Ki2qtqej2CXTOayOH9bHDQF+Q48VpWyDXjbYxA4Yz8iDB31zXOBUlOHHKidDbqGVrTUvQMPmBGBw==",
      "dev": true,
      "requires": {
        "define-property": "^2.0.2",
        "extend-shallow": "^3.0.2",
        "regex-not": "^1.0.2",
        "safe-regex": "^1.1.0"
      }
    },
    "to-regex-range": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/to-regex-range/-/to-regex-range-5.0.1.tgz",
      "integrity": "sha512-65P7iz6X5yEr1cwcgvQxbbIw7Uk3gOy5dIdtZ4rDveLqhrdJP+Li/Hx6tyK0NEb+2GCyneCMJiGqrADCSNk8sQ==",
      "dev": true,
      "requires": {
        "is-number": "^7.0.0"
      }
    },
    "tough-cookie": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/tough-cookie/-/tough-cookie-3.0.1.tgz",
      "integrity": "sha512-yQyJ0u4pZsv9D4clxO69OEjLWYw+jbgspjTue4lTQZLfV0c5l1VmK2y1JK8E9ahdpltPOaAThPcp5nKPUgSnsg==",
      "dev": true,
      "requires": {
        "ip-regex": "^2.1.0",
        "psl": "^1.1.28",
        "punycode": "^2.1.1"
      },
      "dependencies": {
        "punycode": {
          "version": "2.1.1",
          "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
          "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
          "dev": true
        }
      }
    },
    "tr46": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/tr46/-/tr46-1.0.1.tgz",
      "integrity": "sha1-qLE/1r/SSJUZZ0zN5VujaTtwbQk=",
      "dev": true,
      "requires": {
        "punycode": "^2.1.0"
      },
      "dependencies": {
        "punycode": {
          "version": "2.1.1",
          "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
          "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
          "dev": true
        }
      }
    },
    "trim-repeated": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/trim-repeated/-/trim-repeated-1.0.0.tgz",
      "integrity": "sha1-42RqLqTokTEr9+rObPsFOAvAHCE=",
      "dev": true,
      "requires": {
        "escape-string-regexp": "^1.0.2"
      }
    },
    "ts-invariant": {
      "version": "0.9.3",
      "resolved": "https://registry.npmjs.org/ts-invariant/-/ts-invariant-0.9.3.tgz",
      "integrity": "sha512-HinBlTbFslQI0OHP07JLsSXPibSegec6r9ai5xxq/qHYCsIQbzpymLpDhAUsnXcSrDEcd0L62L8vsOEdzM0qlA==",
      "requires": {
        "tslib": "^2.1.0"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.1",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.1.tgz",
          "integrity": "sha512-77EbyPPpMz+FRFRuAFlWMtmgUWGe9UOG2Z25NqCwiIjRhOf5iKGuzSe5P2w1laq+FkRy4p+PCuVkJSGkzTEKVw=="
        }
      }
    },
    "ts-jest": {
      "version": "25.5.1",
      "resolved": "https://registry.npmjs.org/ts-jest/-/ts-jest-25.5.1.tgz",
      "integrity": "sha512-kHEUlZMK8fn8vkxDjwbHlxXRB9dHYpyzqKIGDNxbzs+Rz+ssNDSDNusEK8Fk/sDd4xE6iKoQLfFkFVaskmTJyw==",
      "dev": true,
      "requires": {
        "bs-logger": "0.x",
        "buffer-from": "1.x",
        "fast-json-stable-stringify": "2.x",
        "json5": "2.x",
        "lodash.memoize": "4.x",
        "make-error": "1.x",
        "micromatch": "4.x",
        "mkdirp": "0.x",
        "semver": "6.x",
        "yargs-parser": "18.x"
      },
      "dependencies": {
        "semver": {
          "version": "6.3.0",
          "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.0.tgz",
          "integrity": "sha512-b39TBaTSfV6yBrapU89p5fKekE2m/NwnDocOVruQFS1/veMgdzuPcnOM34M6CwxW8jH/lxEa5rBoDeUwu5HHTw==",
          "dev": true
        }
      }
    },
    "ts-node": {
      "version": "8.10.2",
      "resolved": "https://registry.npmjs.org/ts-node/-/ts-node-8.10.2.tgz",
      "integrity": "sha512-ISJJGgkIpDdBhWVu3jufsWpK3Rzo7bdiIXJjQc0ynKxVOVcg2oIrf2H2cejminGrptVc6q6/uynAHNCuWGbpVA==",
      "dev": true,
      "requires": {
        "arg": "^4.1.0",
        "diff": "^4.0.1",
        "make-error": "^1.1.1",
        "source-map-support": "^0.5.17",
        "yn": "3.1.1"
      },
      "dependencies": {
        "arg": {
          "version": "4.1.3",
          "resolved": "https://registry.npmjs.org/arg/-/arg-4.1.3.tgz",
          "integrity": "sha512-58S9QDqG0Xx27YwPSt9fJxivjYl432YCwfDMfZ+71RAqUrZef7LrKQZ3LHLOwCS4FLNBplP533Zx895SeOCHvA==",
          "dev": true
        }
      }
    },
    "tslib": {
      "version": "1.14.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-1.14.1.tgz",
      "integrity": "sha512-Xni35NKzjgMrwevysHTCArtLDpPvye8zV/0E4EyYn43P7/7qvQwPh9BGkHewbMulVntbigmcT7rdX3BNo9wRJg==",
      "dev": true
    },
    "tsutils": {
      "version": "3.21.0",
      "resolved": "https://registry.npmjs.org/tsutils/-/tsutils-3.21.0.tgz",
      "integrity": "sha512-mHKK3iUXL+3UF6xL5k0PEhKRUBKPBCv/+RkEOpjRWxxx27KKRBmmA60A9pgOUvMi8GKhRMPEmjBRPzs2W7O1OA==",
      "dev": true,
      "requires": {
        "tslib": "^1.8.1"
      }
    },
    "tunnel-agent": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.6.0.tgz",
      "integrity": "sha1-J6XeoGs2sEoKmWZ3SykIaPD8QP0=",
      "dev": true,
      "requires": {
        "safe-buffer": "^5.0.1"
      }
    },
    "tweetnacl": {
      "version": "0.14.5",
      "resolved": "https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.5.tgz",
      "integrity": "sha1-WuaBd/GS1EViadEIr6k/+HQ/T2Q=",
      "dev": true
    },
    "type": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/type/-/type-1.2.0.tgz",
      "integrity": "sha512-+5nt5AAniqsCnu2cEQQdpzCAh33kVx8n0VoFidKpB1dVVLAN/F+bgVOqOJqOnEnrhp222clB5p3vUlD+1QAnfg==",
      "dev": true
    },
    "type-check": {
      "version": "0.3.2",
      "resolved": "https://registry.npmjs.org/type-check/-/type-check-0.3.2.tgz",
      "integrity": "sha1-WITKtRLPHTVeP7eE8wgEsrUg23I=",
      "dev": true,
      "requires": {
        "prelude-ls": "~1.1.2"
      }
    },
    "type-detect": {
      "version": "4.0.8",
      "resolved": "https://registry.npmjs.org/type-detect/-/type-detect-4.0.8.tgz",
      "integrity": "sha512-0fr/mIH1dlO+x7TlcMy+bIDqKPsw/70tVyeHW787goQjhmqaZe10uwLujubK9q9Lg6Fiho1KUKDYz0Z7k7g5/g==",
      "dev": true
    },
    "type-fest": {
      "version": "0.8.1",
      "resolved": "https://registry.npmjs.org/type-fest/-/type-fest-0.8.1.tgz",
      "integrity": "sha512-4dbzIzqvjtgiM5rw1k5rEHtBANKmdudhGyBEajN01fEyhaAIhsoKNy6y7+IN93IfpFtwY9iqi7kD+xwKhQsNJA==",
      "dev": true
    },
    "typedarray-to-buffer": {
      "version": "3.1.5",
      "resolved": "https://registry.npmjs.org/typedarray-to-buffer/-/typedarray-to-buffer-3.1.5.tgz",
      "integrity": "sha512-zdu8XMNEDepKKR+XYOXAVPtWui0ly0NtohUscw+UmaHiAWT8hrV1rr//H6V+0DvJ3OQ19S979M0laLfX8rm82Q==",
      "dev": true,
      "requires": {
        "is-typedarray": "^1.0.0"
      }
    },
    "typedoc": {
      "version": "0.17.8",
      "resolved": "https://registry.npmjs.org/typedoc/-/typedoc-0.17.8.tgz",
      "integrity": "sha512-/OyrHCJ8jtzu+QZ+771YaxQ9s4g5Z3XsQE3Ma7q+BL392xxBn4UMvvCdVnqKC2T/dz03/VXSLVKOP3lHmDdc/w==",
      "dev": true,
      "requires": {
        "fs-extra": "^8.1.0",
        "handlebars": "^4.7.6",
        "highlight.js": "^10.0.0",
        "lodash": "^4.17.15",
        "lunr": "^2.3.8",
        "marked": "1.0.0",
        "minimatch": "^3.0.0",
        "progress": "^2.0.3",
        "shelljs": "^0.8.4",
        "typedoc-default-themes": "^0.10.2"
      }
    },
    "typedoc-default-themes": {
      "version": "0.10.2",
      "resolved": "https://registry.npmjs.org/typedoc-default-themes/-/typedoc-default-themes-0.10.2.tgz",
      "integrity": "sha512-zo09yRj+xwLFE3hyhJeVHWRSPuKEIAsFK5r2u47KL/HBKqpwdUSanoaz5L34IKiSATFrjG5ywmIu98hPVMfxZg==",
      "dev": true,
      "requires": {
        "lunr": "^2.3.8"
      }
    },
    "typescript": {
      "version": "3.9.3",
      "resolved": "https://registry.npmjs.org/typescript/-/typescript-3.9.3.tgz",
      "integrity": "sha512-D/wqnB2xzNFIcoBG9FG8cXRDjiqSTbG2wd8DMZeQyJlP1vfTkIxH4GKveWaEBYySKIg+USu+E+EDIR47SqnaMQ==",
      "dev": true
    },
    "uglify-js": {
      "version": "3.13.9",
      "resolved": "https://registry.npmjs.org/uglify-js/-/uglify-js-3.13.9.tgz",
      "integrity": "sha512-wZbyTQ1w6Y7fHdt8sJnHfSIuWeDgk6B5rCb4E/AM6QNNPbOMIZph21PW5dRB3h7Df0GszN+t7RuUH6sWK5bF0g==",
      "dev": true,
      "optional": true
    },
    "unbox-primitive": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/unbox-primitive/-/unbox-primitive-1.0.1.tgz",
      "integrity": "sha512-tZU/3NqK3dA5gpE1KtyiJUrEB0lxnGkMFHptJ7q6ewdZ8s12QrODwNbhIJStmJkd1QDXa1NRA8aF2A1zk/Ypyw==",
      "dev": true,
      "requires": {
        "function-bind": "^1.1.1",
        "has-bigints": "^1.0.1",
        "has-symbols": "^1.0.2",
        "which-boxed-primitive": "^1.0.2"
      }
    },
    "union-value": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/union-value/-/union-value-1.0.1.tgz",
      "integrity": "sha512-tJfXmxMeWYnczCVs7XAEvIV7ieppALdyepWMkHkwciRpZraG/xwT+s2JN8+pr1+8jCRf80FFzvr+MpQeeoF4Xg==",
      "dev": true,
      "requires": {
        "arr-union": "^3.1.0",
        "get-value": "^2.0.6",
        "is-extendable": "^0.1.1",
        "set-value": "^2.0.1"
      },
      "dependencies": {
        "is-extendable": {
          "version": "0.1.1",
          "resolved": "https://registry.npmjs.org/is-extendable/-/is-extendable-0.1.1.tgz",
          "integrity": "sha1-YrEQ4omkcUGOPsNqYX1HLjAd/Ik=",
          "dev": true
        }
      }
    },
    "universalify": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/universalify/-/universalify-0.1.2.tgz",
      "integrity": "sha512-rBJeI5CXAlmy1pV+617WB9J63U6XcazHHF2f2dbJix4XzpUF0RS3Zbj0FGIOCAva5P/d/GBOYaACQ1w+0azUkg==",
      "dev": true
    },
    "unset-value": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/unset-value/-/unset-value-1.0.0.tgz",
      "integrity": "sha1-g3aHP30jNRef+x5vw6jtDfyKtVk=",
      "dev": true,
      "requires": {
        "has-value": "^0.3.1",
        "isobject": "^3.0.0"
      },
      "dependencies": {
        "has-value": {
          "version": "0.3.1",
          "resolved": "https://registry.npmjs.org/has-value/-/has-value-0.3.1.tgz",
          "integrity": "sha1-ex9YutpiyoJ+wKIHgCVlSEWZXh8=",
          "dev": true,
          "requires": {
            "get-value": "^2.0.3",
            "has-values": "^0.1.4",
            "isobject": "^2.0.0"
          },
          "dependencies": {
            "isobject": {
              "version": "2.1.0",
              "resolved": "https://registry.npmjs.org/isobject/-/isobject-2.1.0.tgz",
              "integrity": "sha1-8GVWEJaj8dou9GJy+BXIQNh+DIk=",
              "dev": true,
              "requires": {
                "isarray": "1.0.0"
              }
            }
          }
        },
        "has-values": {
          "version": "0.1.4",
          "resolved": "https://registry.npmjs.org/has-values/-/has-values-0.1.4.tgz",
          "integrity": "sha1-bWHeldkd/Km5oCCJrThL/49it3E=",
          "dev": true
        }
      }
    },
    "update-check": {
      "version": "1.5.4",
      "resolved": "https://registry.npmjs.org/update-check/-/update-check-1.5.4.tgz",
      "integrity": "sha512-5YHsflzHP4t1G+8WGPlvKbJEbAJGCgw+Em+dGR1KmBUbr1J36SJBqlHLjR7oob7sco5hWHGQVcr9B2poIVDDTQ==",
      "dev": true,
      "requires": {
        "registry-auth-token": "3.3.2",
        "registry-url": "3.1.0"
      }
    },
    "upper-case-first": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/upper-case-first/-/upper-case-first-2.0.2.tgz",
      "integrity": "sha512-514ppYHBaKwfJRK/pNC6c/OxfGa0obSnAl106u97Ed0I625Nin96KAjttZF6ZL3e1XLtphxnqrOi9iWgm+u+bg==",
      "dev": true,
      "requires": {
        "tslib": "^2.0.3"
      },
      "dependencies": {
        "tslib": {
          "version": "2.3.0",
          "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.3.0.tgz",
          "integrity": "sha512-N82ooyxVNm6h1riLCoyS9e3fuJ3AMG2zIZs2Gd1ATcSFjSA23Q0fzjjZeh0jbJvWVDZ0cJT8yaNNaaXHzueNjg==",
          "dev": true
        }
      }
    },
    "uri-js": {
      "version": "4.4.1",
      "resolved": "https://registry.npmjs.org/uri-js/-/uri-js-4.4.1.tgz",
      "integrity": "sha512-7rKUyy33Q1yc98pQ1DAmLtwX109F7TIfWlW1Ydo8Wl1ii1SeHieeh0HHfPeL2fMXK6z0s8ecKs9frCuLJvndBg==",
      "dev": true,
      "requires": {
        "punycode": "^2.1.0"
      },
      "dependencies": {
        "punycode": {
          "version": "2.1.1",
          "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.1.1.tgz",
          "integrity": "sha512-XRsRjdf+j5ml+y/6GKHPZbrF/8p2Yga0JPtdqTIY2Xe5ohJPD9saDJJLPvp9+NSBprVvevdXZybnj2cv8OEd0A==",
          "dev": true
        }
      }
    },
    "urix": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/urix/-/urix-0.1.0.tgz",
      "integrity": "sha1-2pN/emLiH+wf0Y1Js1wpNQZ6bHI=",
      "dev": true
    },
    "use": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/use/-/use-3.1.1.tgz",
      "integrity": "sha512-cwESVXlO3url9YWlFW/TA9cshCEhtu7IKJ/p5soJ/gGpj7vbvFrAY/eIioQ6Dw23KjZhYgiIo8HOs1nQ2vr/oQ==",
      "dev": true
    },
    "util-arity": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/util-arity/-/util-arity-1.1.0.tgz",
      "integrity": "sha1-WdAa8f2z/t4KxOYysKtfbOl8kzA=",
      "dev": true
    },
    "uuid": {
      "version": "8.3.2",
      "resolved": "https://registry.npmjs.org/uuid/-/uuid-8.3.2.tgz",
      "integrity": "sha512-+NYs2QeMWy+GWFOEm9xnn6HCDp0l7QBD7ml8zLUmJ+93Q5NF0NocErnwkTkXVFNiX3/fpC6afS8Dhb/gz7R7eg==",
      "dev": true
    },
    "v8-compile-cache": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/v8-compile-cache/-/v8-compile-cache-2.3.0.tgz",
      "integrity": "sha512-l8lCEmLcLYZh4nbunNZvQCJc5pv7+RCwa8q/LdUx8u7lsWvPDKmpodJAJNwkAhJC//dFY48KuIEmjtd4RViDrA==",
      "dev": true
    },
    "v8-to-istanbul": {
      "version": "4.1.4",
      "resolved": "https://registry.npmjs.org/v8-to-istanbul/-/v8-to-istanbul-4.1.4.tgz",
      "integrity": "sha512-Rw6vJHj1mbdK8edjR7+zuJrpDtKIgNdAvTSAcpYfgMIw+u2dPDntD3dgN4XQFLU2/fvFQdzj+EeSGfd/jnY5fQ==",
      "dev": true,
      "requires": {
        "@types/istanbul-lib-coverage": "^2.0.1",
        "convert-source-map": "^1.6.0",
        "source-map": "^0.7.3"
      },
      "dependencies": {
        "source-map": {
          "version": "0.7.3",
          "resolved": "https://registry.npmjs.org/source-map/-/source-map-0.7.3.tgz",
          "integrity": "sha512-CkCj6giN3S+n9qrYiBTX5gystlENnRW5jZeNLHpe6aue+SrHcG5VYwujhW9s4dY31mEGsxBDrHR6oI69fTXsaQ==",
          "dev": true
        }
      }
    },
    "validate-npm-package-license": {
      "version": "3.0.4",
      "resolved": "https://registry.npmjs.org/validate-npm-package-license/-/validate-npm-package-license-3.0.4.tgz",
      "integrity": "sha512-DpKm2Ui/xN7/HQKCtpZxoRWBhZ9Z0kqtygG8XCgNQ8ZlDnxuQmWhj566j8fN4Cu3/JmbhsDo7fcAJq4s9h27Ew==",
      "dev": true,
      "requires": {
        "spdx-correct": "^3.0.0",
        "spdx-expression-parse": "^3.0.0"
      }
    },
    "validator": {
      "version": "13.7.0",
      "resolved": "https://registry.npmjs.org/validator/-/validator-13.7.0.tgz",
      "integrity": "sha512-nYXQLCBkpJ8X6ltALua9dRrZDHVYxjJ1wgskNt1lH9fzGjs3tgojGSCBjmEPwkWS1y29+DrizMTW19Pr9uB2nw=="
    },
    "vary": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/vary/-/vary-1.1.2.tgz",
      "integrity": "sha512-BNGbWLfd0eUPabhkXUVm0j8uuvREyTh5ovRa/dyow/BqAbZJyC+5fU+IzQOzmAKzYqYRAISoRhdQr3eIZ/PXqg==",
      "dev": true
    },
    "verror": {
      "version": "1.10.0",
      "resolved": "https://registry.npmjs.org/verror/-/verror-1.10.0.tgz",
      "integrity": "sha1-OhBcoXBTr1XW4nDB+CiGguGNpAA=",
      "dev": true,
      "requires": {
        "assert-plus": "^1.0.0",
        "core-util-is": "1.0.2",
        "extsprintf": "^1.2.0"
      }
    },
    "w3c-hr-time": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/w3c-hr-time/-/w3c-hr-time-1.0.2.tgz",
      "integrity": "sha512-z8P5DvDNjKDoFIHK7q8r8lackT6l+jo/Ye3HOle7l9nICP9lf1Ci25fy9vHd0JOWewkIFzXIEig3TdKT7JQ5fQ==",
      "dev": true,
      "requires": {
        "browser-process-hrtime": "^1.0.0"
      }
    },
    "w3c-xmlserializer": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/w3c-xmlserializer/-/w3c-xmlserializer-1.1.2.tgz",
      "integrity": "sha512-p10l/ayESzrBMYWRID6xbuCKh2Fp77+sA0doRuGn4tTIMrrZVeqfpKjXHY+oDh3K4nLdPgNwMTVP6Vp4pvqbNg==",
      "dev": true,
      "requires": {
        "domexception": "^1.0.1",
        "webidl-conversions": "^4.0.2",
        "xml-name-validator": "^3.0.0"
      }
    },
    "walker": {
      "version": "1.0.7",
      "resolved": "https://registry.npmjs.org/walker/-/walker-1.0.7.tgz",
      "integrity": "sha1-L3+bj9ENZ3JisYqITijRlhjgKPs=",
      "dev": true,
      "requires": {
        "makeerror": "1.0.x"
      }
    },
    "webidl-conversions": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/webidl-conversions/-/webidl-conversions-4.0.2.tgz",
      "integrity": "sha512-YQ+BmxuTgd6UXZW3+ICGfyqRyHXVlD5GtQr5+qjiNW7bF0cqrzX500HVXPBOvgXb5YnzDd+h0zqyv61KUD7+Sg==",
      "dev": true
    },
    "whatwg-encoding": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/whatwg-encoding/-/whatwg-encoding-1.0.5.tgz",
      "integrity": "sha512-b5lim54JOPN9HtzvK9HFXvBma/rnfFeqsic0hSpjtDbVxR3dJKLc+KB4V6GgiGOvl7CY/KNh8rxSo9DKQrnUEw==",
      "dev": true,
      "requires": {
        "iconv-lite": "0.4.24"
      }
    },
    "whatwg-mimetype": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/whatwg-mimetype/-/whatwg-mimetype-2.3.0.tgz",
      "integrity": "sha512-M4yMwr6mAnQz76TbJm914+gPpB/nCwvZbJU28cUD6dR004SAxDLOOSUaB1JDRqLtaOV/vi0IC5lEAGFgrjGv/g==",
      "dev": true
    },
    "whatwg-url": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/whatwg-url/-/whatwg-url-7.1.0.tgz",
      "integrity": "sha512-WUu7Rg1DroM7oQvGWfOiAK21n74Gg+T4elXEQYkOhtyLeWiJFoOGLXPKI/9gzIie9CtwVLm8wtw6YJdKyxSjeg==",
      "dev": true,
      "requires": {
        "lodash.sortby": "^4.7.0",
        "tr46": "^1.0.1",
        "webidl-conversions": "^4.0.2"
      }
    },
    "which": {
      "version": "1.3.1",
      "resolved": "https://registry.npmjs.org/which/-/which-1.3.1.tgz",
      "integrity": "sha512-HxJdYWq1MTIQbJ3nw0cqssHoTNU267KlrDuGZ1WYlxDStUtKUhOaJmh112/TZmHxxUfuJqPXSOm7tDyas0OSIQ==",
      "dev": true,
      "requires": {
        "isexe": "^2.0.0"
      }
    },
    "which-boxed-primitive": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/which-boxed-primitive/-/which-boxed-primitive-1.0.2.tgz",
      "integrity": "sha512-bwZdv0AKLpplFY2KZRX6TvyuN7ojjr7lwkg6ml0roIy9YeuSr7JS372qlNW18UQYzgYK9ziGcerWqZOmEn9VNg==",
      "dev": true,
      "requires": {
        "is-bigint": "^1.0.1",
        "is-boolean-object": "^1.1.0",
        "is-number-object": "^1.0.4",
        "is-string": "^1.0.5",
        "is-symbol": "^1.0.3"
      }
    },
    "which-module": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/which-module/-/which-module-2.0.0.tgz",
      "integrity": "sha1-2e8H3Od7mQK4o6j6SzHD4/fm6Ho=",
      "dev": true
    },
    "widest-line": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/widest-line/-/widest-line-4.0.1.tgz",
      "integrity": "sha512-o0cyEG0e8GPzT4iGHphIOh0cJOV8fivsXxddQasHPHfoZf1ZexrfeA21w2NaEN1RHE+fXlfISmOE8R9N3u3Qig==",
      "dev": true,
      "requires": {
        "string-width": "^5.0.1"
      },
      "dependencies": {
        "ansi-regex": {
          "version": "6.0.1",
          "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-6.0.1.tgz",
          "integrity": "sha512-n5M855fKb2SsfMIiFFoVrABHJC8QtHwVx+mHWP3QcEqBHYienj5dHSgjbxtC0WEZXYt4wcD6zrQElDPhFuZgfA==",
          "dev": true
        },
        "emoji-regex": {
          "version": "9.2.2",
          "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-9.2.2.tgz",
          "integrity": "sha512-L18DaJsXSUk2+42pv8mLs5jJT2hqFkFE4j21wOmgbUqsZ2hL72NsUU785g9RXgo3s0ZNgVl42TiHp3ZtOv/Vyg==",
          "dev": true
        },
        "string-width": {
          "version": "5.1.2",
          "resolved": "https://registry.npmjs.org/string-width/-/string-width-5.1.2.tgz",
          "integrity": "sha512-HnLOCR3vjcY8beoNLtcjZ5/nxn2afmME6lhrDrebokqMap+XbeW8n9TXpPDOqdGK5qcI3oT0GKTW6wC7EMiVqA==",
          "dev": true,
          "requires": {
            "eastasianwidth": "^0.2.0",
            "emoji-regex": "^9.2.2",
            "strip-ansi": "^7.0.1"
          }
        },
        "strip-ansi": {
          "version": "7.0.1",
          "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-7.0.1.tgz",
          "integrity": "sha512-cXNxvT8dFNRVfhVME3JAe98mkXDYN2O1l7jmcwMnOslDeESg1rF/OZMtK0nRAhiari1unG5cD4jG3rapUAkLbw==",
          "dev": true,
          "requires": {
            "ansi-regex": "^6.0.1"
          }
        }
      }
    },
    "word-wrap": {
      "version": "1.2.3",
      "resolved": "https://registry.npmjs.org/word-wrap/-/word-wrap-1.2.3.tgz",
      "integrity": "sha512-Hz/mrNwitNRh/HUAtM/VT/5VH+ygD6DV7mYKZAtHOrbs8U7lvPS6xf7EJKMF0uW1KJCl0H701g3ZGus+muE5vQ==",
      "dev": true
    },
    "wordwrap": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/wordwrap/-/wordwrap-1.0.0.tgz",
      "integrity": "sha1-J1hIEIkUVqQXHI0CJkQa3pDLyus=",
      "dev": true
    },
    "wrap-ansi": {
      "version": "6.2.0",
      "resolved": "https://registry.npmjs.org/wrap-ansi/-/wrap-ansi-6.2.0.tgz",
      "integrity": "sha512-r6lPcBGxZXlIcymEu7InxDMhdW0KDxpLgoFLcguasxCaJ/SOIZwINatK9KY/tf+ZrlywOKU0UDj3ATXUBfxJXA==",
      "dev": true,
      "requires": {
        "ansi-styles": "^4.0.0",
        "string-width": "^4.1.0",
        "strip-ansi": "^6.0.0"
      },
      "dependencies": {
        "ansi-styles": {
          "version": "4.3.0",
          "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
          "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
          "dev": true,
          "requires": {
            "color-convert": "^2.0.1"
          }
        },
        "color-convert": {
          "version": "2.0.1",
          "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
          "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
          "dev": true,
          "requires": {
            "color-name": "~1.1.4"
          }
        },
        "color-name": {
          "version": "1.1.4",
          "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
          "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
          "dev": true
        },
        "strip-ansi": {
          "version": "6.0.0",
          "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.0.tgz",
          "integrity": "sha512-AuvKTrTfQNYNIctbR1K/YGTR1756GycPsg7b9bdV9Duqur4gv6aKqHXah67Z8ImS7WEz5QVcOtlfW2rZEugt6w==",
          "dev": true,
          "requires": {
            "ansi-regex": "^5.0.0"
          }
        }
      }
    },
    "wrappy": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz",
      "integrity": "sha1-tSQ9jz7BqjXxNkYFvA0QNuMKtp8=",
      "dev": true
    },
    "write": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/write/-/write-1.0.3.tgz",
      "integrity": "sha512-/lg70HAjtkUgWPVZhZcm+T4hkL8Zbtp1nFNOn3lRrxnlv50SRBv7cR7RqR+GMsd3hUXy9hWBo4CHTbFTcOYwig==",
      "dev": true,
      "requires": {
        "mkdirp": "^0.5.1"
      }
    },
    "write-file-atomic": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/write-file-atomic/-/write-file-atomic-3.0.3.tgz",
      "integrity": "sha512-AvHcyZ5JnSfq3ioSyjrBkH9yW4m7Ayk8/9My/DD9onKeu/94fwrMocemO2QAJFAlnnDN+ZDS+ZjAR5ua1/PV/Q==",
      "dev": true,
      "requires": {
        "imurmurhash": "^0.1.4",
        "is-typedarray": "^1.0.0",
        "signal-exit": "^3.0.2",
        "typedarray-to-buffer": "^3.1.5"
      }
    },
    "ws": {
      "version": "7.4.6",
      "resolved": "https://registry.npmjs.org/ws/-/ws-7.4.6.tgz",
      "integrity": "sha512-YmhHDO4MzaDLB+M9ym/mDA5z0naX8j7SIlT8f8z+I0VtzsRbekxEutHSme7NPS2qE8StCYQNUnfWdXta/Yu85A==",
      "requires": {}
    },
    "xml-name-validator": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/xml-name-validator/-/xml-name-validator-3.0.0.tgz",
      "integrity": "sha512-A5CUptxDsvxKJEU3yO6DuWBSJz/qizqzJKOMIfUJHETbBw/sFaDxgd6fxm1ewUaM0jZ444Fc5vC5ROYurg/4Pw==",
      "dev": true
    },
    "xmlchars": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/xmlchars/-/xmlchars-2.2.0.tgz",
      "integrity": "sha512-JZnDKK8B0RCDw84FNdDAIpZK+JuJw+s7Lz8nksI7SIuU3UXJJslUthsi+uWBUYOwPFwW7W7PRLRfUKpxjtjFCw==",
      "dev": true
    },
    "y18n": {
      "version": "4.0.3",
      "resolved": "https://registry.npmjs.org/y18n/-/y18n-4.0.3.tgz",
      "integrity": "sha512-JKhqTOwSrqNA1NY5lSztJ1GrBiUodLMmIZuLiDaMRJ+itFd+ABVE8XBjOvIWL+rSqNDC74LCSFmlb/U4UZ4hJQ==",
      "dev": true
    },
    "yallist": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/yallist/-/yallist-4.0.0.tgz",
      "integrity": "sha512-3wdGidZyq5PB084XLES5TpOSRA3wjXAlIWMhum2kRcv/41Sn2emQ0dycQW4uZXLejwKvg6EsvbdlVL+FYEct7A==",
      "dev": true
    },
    "yargs": {
      "version": "15.4.1",
      "resolved": "https://registry.npmjs.org/yargs/-/yargs-15.4.1.tgz",
      "integrity": "sha512-aePbxDmcYW++PaqBsJ+HYUFwCdv4LVvdnhBy78E57PIor8/OVvhMrADFFEDh8DHDFRv/O9i3lPhsENjO7QX0+A==",
      "dev": true,
      "requires": {
        "cliui": "^6.0.0",
        "decamelize": "^1.2.0",
        "find-up": "^4.1.0",
        "get-caller-file": "^2.0.1",
        "require-directory": "^2.1.1",
        "require-main-filename": "^2.0.0",
        "set-blocking": "^2.0.0",
        "string-width": "^4.2.0",
        "which-module": "^2.0.0",
        "y18n": "^4.0.0",
        "yargs-parser": "^18.1.2"
      }
    },
    "yargs-parser": {
      "version": "18.1.3",
      "resolved": "https://registry.npmjs.org/yargs-parser/-/yargs-parser-18.1.3.tgz",
      "integrity": "sha512-o50j0JeToy/4K6OZcaQmW6lyXXKhq7csREXcDwk2omFPJEwUNOVtJKvmDr9EI1fAJZUyZcRF7kxGBWmRXudrCQ==",
      "dev": true,
      "requires": {
        "camelcase": "^5.0.0",
        "decamelize": "^1.2.0"
      }
    },
    "yn": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/yn/-/yn-3.1.1.tgz",
      "integrity": "sha512-Ux4ygGWsu2c7isFWe8Yu1YluJmqVhxqK2cLXNQA5AcC3QfbGNpM7fu0Y8b/z16pXLnFxZYvWhd3fhBY9DLmC6Q==",
      "dev": true
    },
    "zen-observable": {
      "version": "0.8.15",
      "resolved": "https://registry.npmjs.org/zen-observable/-/zen-observable-0.8.15.tgz",
      "integrity": "sha512-PQ2PC7R9rslx84ndNBZB/Dkv8V8fZEpk83RLgXtYd0fwUgEjseMn1Dgajh2x6S8QbZAFa9p2qVCEuYZNgve0dQ=="
    },
    "zen-observable-ts": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/zen-observable-ts/-/zen-observable-ts-1.1.0.tgz",
      "integrity": "sha512-1h4zlLSqI2cRLPJUHJFL8bCWHhkpuXkF+dbGkRaWjgDIG26DmzyshUMrdV/rL3UnR+mhaX4fRq8LPouq0MYYIA==",
      "requires": {
        "@types/zen-observable": "0.8.3",
        "zen-observable": "0.8.15"
      }
    }
  }
}
