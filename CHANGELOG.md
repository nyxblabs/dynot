# Changelog


## v0.1.8

[compare changes](https://github.com/nyxblabs/dynot/compare/v0.1.7...v0.1.8)


### 🩹 Fixes

  - **eslintrc): update no-html-link-for-pages rule to use @next/next/no-html-link-for-pages 🔧 chore(eslintrc:** Add react version to settings The no-html-link-for-pages rule was updated to use the @next/next/no-html-link-for-pages package to ensure that the rule is being used correctly. Additionally, the react version was added to the settings to ensure that the correct version of react is being used. ([1e45ece](https://github.com/nyxblabs/dynot/commit/1e45ece))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>

## v0.1.7

[compare changes](https://github.com/nyxblabs/dynot/compare/v0.1.6...v0.1.7)


### 🩹 Fixes

  - **README.md:** Update cover-src link to point to the correct image location The cover-src link was pointing to an incorrect location, which resulted in a broken image. The link has been updated to point to the correct location of the cover image. ([c1107ee](https://github.com/nyxblabs/dynot/commit/c1107ee))

### 🎨 Styles

  - **assets): remove unused and outdated cover images and add new cover image 📝 docs(README.md:** Update cover image and add comments The commit removes the unused and outdated cover images, cover-dynot_black.png and cover-dynot_light.png, and adds a new cover image, cover-github-dynot.png. The README.md file is updated to reflect the new cover image and comments are added to the markdown file to indicate where the cover image is located. ([0facb81](https://github.com/nyxblabs/dynot/commit/0facb81))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>

## v0.1.6

[compare changes](https://github.com/nyxblabs/dynot/compare/v0.1.5...v0.1.6)


### 🎨 Styles

  - **README.md:** Update badge colors to improve accessibility The badge colors have been updated to improve accessibility. The new colors are easier to distinguish for people with color vision deficiencies. ([15d3b28](https://github.com/nyxblabs/dynot/commit/15d3b28))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>

## v0.1.5

[compare changes](https://github.com/nyxblabs/dynot/compare/v0.1.3...v0.1.5)


### 📖 Documentation

  - **README.md:** Fix bundlephobia link for dynot package The bundlephobia link for the dynot package was pointing to the wrong package. This commit updates the link to point to the correct package. ([20e1b30](https://github.com/nyxblabs/dynot/commit/20e1b30))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>

## v0.1.3

[compare changes](https://github.com/nyxblabs/dynot/compare/v0.1.1...v0.1.3)


### 🏡 Chore

  - **package.json:** Update version to 0.1.2 This commit updates the version of the package to 0.1.2. No other changes were made to the package.json file. ([1edb8ac](https://github.com/nyxblabs/dynot/commit/1edb8ac))

### 🎨 Styles

  - **README.md:** Add cover image to README A new cover image was added to the repository's `.github/assets` directory. The README was updated to include the cover image using markdown syntax. The cover image is intended to improve the visual appeal of the repository and provide a quick overview of the project. ([8e828be](https://github.com/nyxblabs/dynot/commit/8e828be))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>

## v0.1.1


### 🚀 Enhancements

  - **git): add .gitattributes and .gitignore files ✨ feat(.gitattributes): set text=auto and eol=lf to ensure consistent line endings across platforms ✨ feat(.gitignore:** Ignore node_modules, dist, *.log* and coverage directories and files The .gitattributes file is added to ensure consistent line endings across platforms by setting the text=auto and eol=lf attributes. The .gitignore file is added to ignore the node_modules, dist, *.log* and coverage directories and files, which are not necessary to be tracked in the repository. ([de3f958](https://github.com/nyxblabs/dynot/commit/de3f958))
  - **github:** Add GitHub funding and issue templates Added GitHub funding and issue templates to the repository to improve the user experience and make it easier for users to contribute to the project. The funding.yml file allows users to support the project financially, while the issue templates provide a standardized format for bug reports, feature requests, and typo fixes. The pull request template also follows the conventional emoji commits and provides a checklist to ensure that the contributor has followed the contribution guidelines. Finally, the code of conduct file has been added to ensure that the project maintains a welcoming and inclusive environment for all contributors. ([7053d13](https://github.com/nyxblabs/dynot/commit/7053d13))
  - Add new files and configuration files for project Added new files cover-dynot_black.png and cover-dynot_light.png to the .github/assets directory. Added vitest.config.ts and webpack.config.js configuration files to the root directory of the project. These files are necessary for the project to run and build successfully. ([df3c315](https://github.com/nyxblabs/dynot/commit/df3c315))
  - **babel.ts:** Add support for TypeScript and legacy syntax in Babel transform This commit adds support for TypeScript and legacy syntax in the Babel transform. The `transform` function now accepts a `ts` and `legacy` option, which when set to true, adds the necessary plugins to support TypeScript and legacy syntax. The `@babel/plugin-transform-typescript`, `babel-plugin-transform-typescript-metadata`, `@babel/plugin-proposal-decorators`, `babel-plugin-parameter-decorator`, `@babel/plugin-syntax-import-assertions`, `@babel/plugin-proposal-nullish-coalescing-operator`, and `@babel/plugin-proposal-optional-chaining` plugins are added to the list of plugins to be used in the transform. ([bccdea4](https://github.com/nyxblabs/dynot/commit/bccdea4))
  - **types.ts:** Add interfaces for TransformOptions and DYNOTOptions This commit adds two interfaces to the types.ts file. The TransformOptions interface defines the options that can be passed to a transform function. The DYNOTOptions interface defines the options that can be passed to the DYNOT library. These interfaces improve the readability and maintainability of the code by providing a clear definition of the options that can be passed to these functions. ([b5bb8e9](https://github.com/nyxblabs/dynot/commit/b5bb8e9))
  - **utils.ts:** Add utility functions for caching, file system operations, and package.json parsing This commit adds several utility functions to the `utils.ts` file. The `getCacheDir()` function returns a path to a cache directory. The `isDir()` function checks if a given path is a directory. The `isWritable()` function checks if a given path is writable. The `md5()` function returns an MD5 hash of a given string. The `detectLegacySyntax()` function checks if a given string contains legacy syntax. The `isObject()` function checks if a given value is an object. The `readNearestPackageJSON()` function reads the nearest `package.json` file from a given path. These functions are useful for various file system operations and caching. ([0c7fcd0](https://github.com/nyxblabs/dynot/commit/0c7fcd0))
  - **babel-plugin-transform-import-meta.ts:** Add babel plugin to inline resolved filename into code when possible This commit adds a babel plugin that inlines the resolved filename into the code when possible instead of injecting a require. This improves the performance of the application by reducing the number of requires that need to be resolved at runtime. The plugin is based on the babel-plugin-transform-import-meta package, with the modification of inlining the resolved filename. ([09596fb](https://github.com/nyxblabs/dynot/commit/09596fb))
  - **import-meta-env.ts:** Add import-meta-env plugin to support runtime environment variables The import-meta-env plugin is added to support runtime environment variables. This plugin is based on the iendeavor/import-meta-env package and modified to use runtime only without the dotenv dependency. The plugin replaces the import.meta.env.PROPERTY syntax with process.env.PROPERTY at runtime. ([9410dc4](https://github.com/nyxblabs/dynot/commit/9410dc4))
  - **babel-codeframe.js:** Add codeFrameColumns function to stubs directory This commit adds a new file to the stubs directory, which contains a function named codeFrameColumns. This function returns an empty string. The purpose of this file is to provide a stub implementation of the codeFrameColumns function, which can be used in testing or development environments. ([049d033](https://github.com/nyxblabs/dynot/commit/049d033))
  - **helper-compilation-targets.js:** Add helper function to get compilation targets This commit adds a new file `helper-compilation-targets.js` which exports a function `getTargets()` that returns an empty object. This helper function is used to get the compilation targets for Babel. ([47805bd](https://github.com/nyxblabs/dynot/commit/47805bd))
  - **register.js:** Add registration functionality to dynot This commit adds a new file, register.js, which imports the dynot module and calls the register function. This allows dynot to register itself with the Dyno API, which is necessary for the application to function properly. ([f49c0a9](https://github.com/nyxblabs/dynot/commit/f49c0a9))
  - **index.js:** Add onError function and default transform option The onError function is added to handle errors thrown during the execution of the dynot function. The default transform option is set to use the babel module if no transform option is provided. This improves the usability of the module by providing a default option for the transform parameter and a way to handle errors that may occur during execution. ([7e176f5](https://github.com/nyxblabs/dynot/commit/7e176f5))
  - **dynot.js:** Add dynot command line interface This commit adds a new file `dynot.js` which contains the implementation of the dynot command line interface. The dynot command line interface allows users to run scripts in the context of the dynot environment. The script to be run is passed as an argument to the dynot command. If no script is provided, the usage instructions are printed to the console. ([2d7d3d7](https://github.com/nyxblabs/dynot/commit/2d7d3d7))
  - **dynot.js:** Add dynot command line interface This commit adds a new file `dynot.js` which contains the implementation of the dynot command line interface. The dynot command line interface allows users to run scripts in the context of the dynot environment. The script to be run is passed as an argument to the dynot command. If no script is provided, the usage instructions are printed to the console. ([63aa729](https://github.com/nyxblabs/dynot/commit/63aa729))
  - **test): add tests for getCacheDir function in utils.ts 🔥 chore(test): remove skipped tests in utils.test.ts 🔥 chore(bench:** Remove unused imports in esm.js and jiti.js The getCacheDir function in utils.ts now has tests to ensure it returns the correct cache directory. The skipped tests in utils.test.ts have been removed as they are no longer needed. Unused imports in esm.js and jiti.js have been removed to improve code readability. ([444e99b](https://github.com/nyxblabs/dynot/commit/444e99b))
  - **async, circular:** Add new test fixtures for async and circular dependencies Added new test fixtures for async and circular dependencies. The async fixture exports a constant string "works" from an async module. The circular fixture exports a function that adds a string "Foo" to a passed string and logs the result to the console. The circular fixture has two modules that import from each other to create a circular dependency. ([c4a3c0b](https://github.com/nyxblabs/dynot/commit/c4a3c0b))
  - **esm:** Add new ES modules fixtures for testing purposes Added new ES modules fixtures for testing purposes. The fixtures include an index.js file that imports consolji, test.js, and utils-lib.js. The test.js file exports an object with information about the file, directory, import.meta.url, and stack trace. The utils-lib.js file exports a version constant and an object with utilities from the utils.js file. The utils.js file exports a constant and a default export. ([9716b32](https://github.com/nyxblabs/dynot/commit/9716b32))
  - **test:** Add new test fixtures for exotic, hashbang, json, and syntax The new test fixtures are added to test various scenarios such as importing JSON files, using optional chaining, nullish coalescing, logical or assignment, and logical nullish assignment. These fixtures will help to ensure that the application works as expected in these scenarios. ([187625e](https://github.com/nyxblabs/dynot/commit/187625e))
  - **typescript:** Add new TypeScript fixtures for testing Added new TypeScript fixtures to the test suite to improve test coverage. The new fixtures include a decorated class, a satisfies test, and a test file with a namespace and type definition. ([20f88de](https://github.com/nyxblabs/dynot/commit/20f88de))
  - **test:** Add new test fixtures for various scenarios This commit adds new test fixtures for various scenarios. The import-map fixture includes an import map file and two modules that use it. The mixed fixture includes a CommonJS module that requires an ESM module. The native fixture includes a dynamic import of an ESM module and a test module that checks for the existence of the require function. The proto fixture includes a module that uses a built-in Node.js module. The pure-esm-dep fixture includes a module that uses a pure ESM package. ([7d0382c](https://github.com/nyxblabs/dynot/commit/7d0382c))
  - **import-map): add package.json file to support import maps 🆕 feat(json:** Add file.json test fixture The package.json file is added to support import maps. The file contains the exports and imports fields that are used to map module specifiers to URLs. The file.json test fixture is added to test JSON parsing functionality. ([9206f88](https://github.com/nyxblabs/dynot/commit/9206f88))
  - **README.md:** Add documentation for dynot package This commit adds a README.md file with documentation for the dynot package. It includes information on the features, usage, options, development, and license of the package. The documentation is intended to help users understand how to use the package and its various options. ([bb06f88](https://github.com/nyxblabs/dynot/commit/bb06f88))

### 📖 Documentation

  - **CHANGELOG.md:** Add changelog entries for various enhancements, chore, and tests The changelog entries include various enhancements such as adding .gitattributes and .gitignore files, GitHub funding and issue templates, new files and configuration files for the project, support for TypeScript and legacy syntax in Babel transform, utility functions for caching, file system operations, and package.json parsing, and many more. The changelog also includes chore entries such as adding custom eslint rules, disabling eslint rules, and updating the package version. Lastly, there are test entries for various scenarios such as importing JSON files, using optional chaining, nullish coalescing, logical or assignment, and logical nullish assignment, and many more. ([df576d3](https://github.com/nyxblabs/dynot/commit/df576d3))

### 🏡 Chore

  - **.eslintignore): add dist, package.json, and tsconfig.json to eslint ignore list 🆕 chore(.eslintrc:** Add custom eslint rules and extend @nyxb eslint configuration The .eslintignore file now includes dist, package.json, and tsconfig.json to be ignored by eslint. The .eslintrc file now extends the @nyxb eslint configuration and adds custom rules to disable unicorn/prefer-module, unicorn/prefer-node-protocol, unicorn/import-style, unicorn/no-null, @typescript-eslint/no-non-null-assertion, and indent. These changes improve the consistency and quality of the codebase. ([ea14d29](https://github.com/nyxblabs/dynot/commit/ea14d29))
  - **.eslintrc): disable no-html-link-for-pages, no-var-requires, and no-require-imports rules 🔧 chore(package.json:** Add rimraf and requireflow dependencies, remove nyxjson dependency, and add lint:fix script The no-html-link-for-pages, no-var-requires, and no-require-imports rules are disabled in the .eslintrc file. The rimraf and requireflow dependencies are added to the package.json file, while the nyxjson dependency is removed. A new lint:fix script is added to the package.json file to run eslint with the --fix flag. ([2e41c27](https://github.com/nyxblabs/dynot/commit/2e41c27))
  - **.eslintrc:** Add rules to disable no-unused-expressions and import/no-anonymous-default-export This commit adds a new .eslintrc file to the test directory with two rules to disable no-unused-expressions and import/no-anonymous-default-export. These rules were disabled to allow for more flexibility in testing. ([ffb0c6f](https://github.com/nyxblabs/dynot/commit/ffb0c6f))
  - **fixtures.test.ts:** Add fixtures test file and snapshot The fixtures.test.ts file was added to the project to test the fixtures directory. The fixtures directory contains various test cases for the dynot.js file. The test file uses the vitest library to run the tests and execa to execute the dynot.js file. The snapshots directory was also added to store the snapshots of the test results. ([e2c2fdd](https://github.com/nyxblabs/dynot/commit/e2c2fdd))
  - **package.json:** Update version to 0.1.0 The version number has been updated to 0.1.0 to reflect the changes made to the application. This is a minor version update as it does not include any breaking changes. ([36422f8](https://github.com/nyxblabs/dynot/commit/36422f8))

### ✅ Tests

  - **env, error-parse, error-runtime:** Add test fixtures for environment variables and error handling Added test fixtures for environment variables and error handling. The `env` fixture logs the values of `process.env.TEST` and `import.meta.env.TEST` to the console. The `error-parse` fixture intentionally causes a parse error by assigning an import statement to an undefined variable. The `error-runtime` fixture intentionally causes a runtime error by adding a null listener to the process object. These fixtures will be used to test the error handling capabilities of the application. ([95d03d4](https://github.com/nyxblabs/dynot/commit/95d03d4))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>

## ...main


### 🚀 Enhancements

  - **git): add .gitattributes and .gitignore files ✨ feat(.gitattributes): set text=auto and eol=lf to ensure consistent line endings across platforms ✨ feat(.gitignore:** Ignore node_modules, dist, *.log* and coverage directories and files The .gitattributes file is added to ensure consistent line endings across platforms by setting the text=auto and eol=lf attributes. The .gitignore file is added to ignore the node_modules, dist, *.log* and coverage directories and files, which are not necessary to be tracked in the repository. ([de3f958](https://github.com/nyxblabs/dynot/commit/de3f958))
  - **github:** Add GitHub funding and issue templates Added GitHub funding and issue templates to the repository to improve the user experience and make it easier for users to contribute to the project. The funding.yml file allows users to support the project financially, while the issue templates provide a standardized format for bug reports, feature requests, and typo fixes. The pull request template also follows the conventional emoji commits and provides a checklist to ensure that the contributor has followed the contribution guidelines. Finally, the code of conduct file has been added to ensure that the project maintains a welcoming and inclusive environment for all contributors. ([7053d13](https://github.com/nyxblabs/dynot/commit/7053d13))
  - Add new files and configuration files for project Added new files cover-dynot_black.png and cover-dynot_light.png to the .github/assets directory. Added vitest.config.ts and webpack.config.js configuration files to the root directory of the project. These files are necessary for the project to run and build successfully. ([df3c315](https://github.com/nyxblabs/dynot/commit/df3c315))
  - **babel.ts:** Add support for TypeScript and legacy syntax in Babel transform This commit adds support for TypeScript and legacy syntax in the Babel transform. The `transform` function now accepts a `ts` and `legacy` option, which when set to true, adds the necessary plugins to support TypeScript and legacy syntax. The `@babel/plugin-transform-typescript`, `babel-plugin-transform-typescript-metadata`, `@babel/plugin-proposal-decorators`, `babel-plugin-parameter-decorator`, `@babel/plugin-syntax-import-assertions`, `@babel/plugin-proposal-nullish-coalescing-operator`, and `@babel/plugin-proposal-optional-chaining` plugins are added to the list of plugins to be used in the transform. ([bccdea4](https://github.com/nyxblabs/dynot/commit/bccdea4))
  - **types.ts:** Add interfaces for TransformOptions and DYNOTOptions This commit adds two interfaces to the types.ts file. The TransformOptions interface defines the options that can be passed to a transform function. The DYNOTOptions interface defines the options that can be passed to the DYNOT library. These interfaces improve the readability and maintainability of the code by providing a clear definition of the options that can be passed to these functions. ([b5bb8e9](https://github.com/nyxblabs/dynot/commit/b5bb8e9))
  - **utils.ts:** Add utility functions for caching, file system operations, and package.json parsing This commit adds several utility functions to the `utils.ts` file. The `getCacheDir()` function returns a path to a cache directory. The `isDir()` function checks if a given path is a directory. The `isWritable()` function checks if a given path is writable. The `md5()` function returns an MD5 hash of a given string. The `detectLegacySyntax()` function checks if a given string contains legacy syntax. The `isObject()` function checks if a given value is an object. The `readNearestPackageJSON()` function reads the nearest `package.json` file from a given path. These functions are useful for various file system operations and caching. ([0c7fcd0](https://github.com/nyxblabs/dynot/commit/0c7fcd0))
  - **babel-plugin-transform-import-meta.ts:** Add babel plugin to inline resolved filename into code when possible This commit adds a babel plugin that inlines the resolved filename into the code when possible instead of injecting a require. This improves the performance of the application by reducing the number of requires that need to be resolved at runtime. The plugin is based on the babel-plugin-transform-import-meta package, with the modification of inlining the resolved filename. ([09596fb](https://github.com/nyxblabs/dynot/commit/09596fb))
  - **import-meta-env.ts:** Add import-meta-env plugin to support runtime environment variables The import-meta-env plugin is added to support runtime environment variables. This plugin is based on the iendeavor/import-meta-env package and modified to use runtime only without the dotenv dependency. The plugin replaces the import.meta.env.PROPERTY syntax with process.env.PROPERTY at runtime. ([9410dc4](https://github.com/nyxblabs/dynot/commit/9410dc4))
  - **babel-codeframe.js:** Add codeFrameColumns function to stubs directory This commit adds a new file to the stubs directory, which contains a function named codeFrameColumns. This function returns an empty string. The purpose of this file is to provide a stub implementation of the codeFrameColumns function, which can be used in testing or development environments. ([049d033](https://github.com/nyxblabs/dynot/commit/049d033))
  - **helper-compilation-targets.js:** Add helper function to get compilation targets This commit adds a new file `helper-compilation-targets.js` which exports a function `getTargets()` that returns an empty object. This helper function is used to get the compilation targets for Babel. ([47805bd](https://github.com/nyxblabs/dynot/commit/47805bd))
  - **register.js:** Add registration functionality to dynot This commit adds a new file, register.js, which imports the dynot module and calls the register function. This allows dynot to register itself with the Dyno API, which is necessary for the application to function properly. ([f49c0a9](https://github.com/nyxblabs/dynot/commit/f49c0a9))
  - **index.js:** Add onError function and default transform option The onError function is added to handle errors thrown during the execution of the dynot function. The default transform option is set to use the babel module if no transform option is provided. This improves the usability of the module by providing a default option for the transform parameter and a way to handle errors that may occur during execution. ([7e176f5](https://github.com/nyxblabs/dynot/commit/7e176f5))
  - **dynot.js:** Add dynot command line interface This commit adds a new file `dynot.js` which contains the implementation of the dynot command line interface. The dynot command line interface allows users to run scripts in the context of the dynot environment. The script to be run is passed as an argument to the dynot command. If no script is provided, the usage instructions are printed to the console. ([2d7d3d7](https://github.com/nyxblabs/dynot/commit/2d7d3d7))
  - **dynot.js:** Add dynot command line interface This commit adds a new file `dynot.js` which contains the implementation of the dynot command line interface. The dynot command line interface allows users to run scripts in the context of the dynot environment. The script to be run is passed as an argument to the dynot command. If no script is provided, the usage instructions are printed to the console. ([63aa729](https://github.com/nyxblabs/dynot/commit/63aa729))
  - **test): add tests for getCacheDir function in utils.ts 🔥 chore(test): remove skipped tests in utils.test.ts 🔥 chore(bench:** Remove unused imports in esm.js and jiti.js The getCacheDir function in utils.ts now has tests to ensure it returns the correct cache directory. The skipped tests in utils.test.ts have been removed as they are no longer needed. Unused imports in esm.js and jiti.js have been removed to improve code readability. ([444e99b](https://github.com/nyxblabs/dynot/commit/444e99b))
  - **async, circular:** Add new test fixtures for async and circular dependencies Added new test fixtures for async and circular dependencies. The async fixture exports a constant string "works" from an async module. The circular fixture exports a function that adds a string "Foo" to a passed string and logs the result to the console. The circular fixture has two modules that import from each other to create a circular dependency. ([c4a3c0b](https://github.com/nyxblabs/dynot/commit/c4a3c0b))
  - **esm:** Add new ES modules fixtures for testing purposes Added new ES modules fixtures for testing purposes. The fixtures include an index.js file that imports consolji, test.js, and utils-lib.js. The test.js file exports an object with information about the file, directory, import.meta.url, and stack trace. The utils-lib.js file exports a version constant and an object with utilities from the utils.js file. The utils.js file exports a constant and a default export. ([9716b32](https://github.com/nyxblabs/dynot/commit/9716b32))
  - **test:** Add new test fixtures for exotic, hashbang, json, and syntax The new test fixtures are added to test various scenarios such as importing JSON files, using optional chaining, nullish coalescing, logical or assignment, and logical nullish assignment. These fixtures will help to ensure that the application works as expected in these scenarios. ([187625e](https://github.com/nyxblabs/dynot/commit/187625e))
  - **typescript:** Add new TypeScript fixtures for testing Added new TypeScript fixtures to the test suite to improve test coverage. The new fixtures include a decorated class, a satisfies test, and a test file with a namespace and type definition. ([20f88de](https://github.com/nyxblabs/dynot/commit/20f88de))
  - **test:** Add new test fixtures for various scenarios This commit adds new test fixtures for various scenarios. The import-map fixture includes an import map file and two modules that use it. The mixed fixture includes a CommonJS module that requires an ESM module. The native fixture includes a dynamic import of an ESM module and a test module that checks for the existence of the require function. The proto fixture includes a module that uses a built-in Node.js module. The pure-esm-dep fixture includes a module that uses a pure ESM package. ([7d0382c](https://github.com/nyxblabs/dynot/commit/7d0382c))
  - **import-map): add package.json file to support import maps 🆕 feat(json:** Add file.json test fixture The package.json file is added to support import maps. The file contains the exports and imports fields that are used to map module specifiers to URLs. The file.json test fixture is added to test JSON parsing functionality. ([9206f88](https://github.com/nyxblabs/dynot/commit/9206f88))
  - **README.md:** Add documentation for dynot package This commit adds a README.md file with documentation for the dynot package. It includes information on the features, usage, options, development, and license of the package. The documentation is intended to help users understand how to use the package and its various options. ([bb06f88](https://github.com/nyxblabs/dynot/commit/bb06f88))

### 🏡 Chore

  - **.eslintignore): add dist, package.json, and tsconfig.json to eslint ignore list 🆕 chore(.eslintrc:** Add custom eslint rules and extend @nyxb eslint configuration The .eslintignore file now includes dist, package.json, and tsconfig.json to be ignored by eslint. The .eslintrc file now extends the @nyxb eslint configuration and adds custom rules to disable unicorn/prefer-module, unicorn/prefer-node-protocol, unicorn/import-style, unicorn/no-null, @typescript-eslint/no-non-null-assertion, and indent. These changes improve the consistency and quality of the codebase. ([ea14d29](https://github.com/nyxblabs/dynot/commit/ea14d29))
  - **.eslintrc): disable no-html-link-for-pages, no-var-requires, and no-require-imports rules 🔧 chore(package.json:** Add rimraf and requireflow dependencies, remove nyxjson dependency, and add lint:fix script The no-html-link-for-pages, no-var-requires, and no-require-imports rules are disabled in the .eslintrc file. The rimraf and requireflow dependencies are added to the package.json file, while the nyxjson dependency is removed. A new lint:fix script is added to the package.json file to run eslint with the --fix flag. ([2e41c27](https://github.com/nyxblabs/dynot/commit/2e41c27))
  - **.eslintrc:** Add rules to disable no-unused-expressions and import/no-anonymous-default-export This commit adds a new .eslintrc file to the test directory with two rules to disable no-unused-expressions and import/no-anonymous-default-export. These rules were disabled to allow for more flexibility in testing. ([ffb0c6f](https://github.com/nyxblabs/dynot/commit/ffb0c6f))
  - **fixtures.test.ts:** Add fixtures test file and snapshot The fixtures.test.ts file was added to the project to test the fixtures directory. The fixtures directory contains various test cases for the dynot.js file. The test file uses the vitest library to run the tests and execa to execute the dynot.js file. The snapshots directory was also added to store the snapshots of the test results. ([e2c2fdd](https://github.com/nyxblabs/dynot/commit/e2c2fdd))
  - **package.json:** Update version to 0.1.0 The version number has been updated to 0.1.0 to reflect the changes made to the application. This is a minor version update as it does not include any breaking changes. ([36422f8](https://github.com/nyxblabs/dynot/commit/36422f8))

### ✅ Tests

  - **env, error-parse, error-runtime:** Add test fixtures for environment variables and error handling Added test fixtures for environment variables and error handling. The `env` fixture logs the values of `process.env.TEST` and `import.meta.env.TEST` to the console. The `error-parse` fixture intentionally causes a parse error by assigning an import statement to an undefined variable. The `error-runtime` fixture intentionally causes a runtime error by adding a null listener to the process object. These fixtures will be used to test the error handling capabilities of the application. ([95d03d4](https://github.com/nyxblabs/dynot/commit/95d03d4))

### ❤️  Contributors

- Nyxb <contact@nyxb.xyz>

