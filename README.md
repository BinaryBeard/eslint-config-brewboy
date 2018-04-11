# eslint-config-brewboy

[![npm](https://img.shields.io/npm/v/eslint-config-brewboy.svg)](https://npmjs.org/package/eslint-config-brewboy) [![downloads](https://img.shields.io/npm/dm/eslint-config-brewboy.svg)](https://npmjs.org/package/eslint-config-brewboy)

## Usage

1. Add this as a dev dependency to your `package.json`

    ```bash
    npm install --save-dev eslint-config-brewboy
    ```

2. Add **ableat** to your eslint configuration file

    **`.eslintrc`**

    ```json
    {
        "extends": [
            "brewboy"
        ]
    }
    ```

    **`.eslintrc.yml`**

    ```yaml
    extends:
      - brewboy
    ```
3. (OPTIONAL) If you're using an editor like Atom or VSCode, you can install this configuration globally

    ```bash
    npm install -g eslint-config-brewboy
    ```
