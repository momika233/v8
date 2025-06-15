V8 JavaScript Engine
=============

V8 is Google's open source JavaScript engine.

V8 implements ECMAScript as specified in ECMA-262.

V8 is written in C++ and is used in Google Chrome, the open source
browser from Google.

V8 can run standalone, or can be embedded into any C++ application.

V8 Project page: https://v8.dev/docs


Getting the Code
=============

Checkout [depot tools](http://www.chromium.org/developers/how-tos/install-depot-tools), and run

        fetch v8

This will checkout V8 into the directory `v8` and fetch all of its dependencies.
To stay up to date, run

        git pull origin
        gclient sync

For fetching all branches, add the following into your remote
configuration in `.git/config`:

        fetch = +refs/branch-heads/*:refs/remotes/branch-heads/*
        fetch = +refs/tags/*:refs/tags/*


Contributing
=============

Please follow the instructions mentioned at
[v8.dev/docs/contribute](https://v8.dev/docs/contribute).
![CodeRabbit Pull Request Reviews](https://img.shields.io/coderabbit/prs/github/momika233/v8?utm_source=oss&utm_medium=github&utm_campaign=momika233%2Fv8&labelColor=171717&color=FF570A&link=https%3A%2F%2Fcoderabbit.ai&label=CodeRabbit+Reviews)
