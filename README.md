[![WTT Logo](https://github.com/wttech/aemc-ansible/raw/main/docs/wtt-logo.png)](https://www.wundermanthompson.com/service/technology)

[![Apache License, Version 2.0, January 2004](https://github.com/wttech/aemc-ansible/raw/main/docs/apache-license-badge.svg)](http://www.apache.org/licenses/)

# Node Wrapper(s)

Node/NPM/NPX wrapper scripts for automatic setup and utilization of Node.js in local or project-specific environments

# Usage

Instead of installing Node.js globally, you can replace your commands to use the wrapper scripts. This way, you can have multiple versions of Node.js installed on your machine and use them in different projects.

Copy the scripts to your project directory then replace the commands in your project scripts:

- Change `node` to `sh nodew`
- Change `npm` to `sh npmw`
- Change `npx` to `sh npxw`


For example:

```shell
% sh npxw --version
10.7.0
```

Note that the directory named 'node' will be created and be sure to ignore it in VCS. That's it! :)

# Authors

[Krystian Panek](mailto:krystian.panek@wundermanthompson.com)

# License

**Node Wrapper** is licensed under the [Apache License, Version 2.0 (the "License")](https://www.apache.org/licenses/LICENSE-2.0.txt)
