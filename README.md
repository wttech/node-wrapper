[![WTT Logo](https://github.com/wttech/aemc-ansible/raw/main/docs/wtt-logo.png)](https://www.wundermanthompson.com/service/technology)

[![Apache License, Version 2.0, January 2004](https://github.com/wttech/aemc-ansible/raw/main/docs/apache-license-badge.svg)](http://www.apache.org/licenses/)

# Node Wrapper(s)

This project provides Node/NPM/NPX wrapper scripts. These scripts automate the setup and utilization of Node.js in local or project-specific environments.

# Rationale

The Node.js ecosystem is vast and diverse, leading to several challenges:

1. **Multiple Project Requirements**: Different projects may require different versions of Node.js, NPM, or NPX. This diversity can lead to conflicts when working on multiple projects simultaneously.

2. **Environment Constraints**: In certain environments, such as CI/CD pipelines or Docker containers, Node.js may not be installed by default. This can pose challenges in setting up and maintaining the development environment.

3. **Version Management**: Managing multiple versions of Node.js on the same machine can be complex and error-prone.

The Node Wrapper scripts aim to address these challenges by providing a flexible and easy-to-use solution for managing Node.js versions.

## Usage

The wrapper scripts allow you to use different versions of Node.js across various projects without needing a global installation.

To use the wrapper scripts, follow these steps:

1. Copy the scripts to your project directory.
2. Replace the commands in your project scripts:
    - Replace `node` with `sh nodew`
    - Replace `npm` with `sh npmw`
    - Replace `npx` with `sh npxw`

Here's an example:

```shell
% sh npxw --version
10.7.0
```

Please note that a directory named 'node' will be created. Make sure to add it to your VCS ignore list.

# Authors

[Krystian Panek](mailto:krystian.panek@wundermanthompson.com)

# License

**Node Wrapper** is licensed under the [Apache License, Version 2.0 (the "License")](https://www.apache.org/licenses/LICENSE-2.0.txt)
