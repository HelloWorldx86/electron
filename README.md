# electron
Only For v11.4.9
-_-!

Change
    1. http://s3.amazonaws.com not work and change to https://dev-cdn.electronjs.org
    2. https://electron-build-tools.s3-us-west-2.amazonaws.com/build-dependencies not work and change to myself cdn
    3. new sccache-linux-x64.zip is bug ? https://github.com/electron/electron/pull/23418 ,and i use the old one from https://github.com/electron/electron-frameworks

Do not use electron/build-tools to build. The version is too new and incompatible. Please refer to https://github.com/electron/electron/blob/v11.4.9/docs/development/build-instructions-gn.md, Using python2.7 and node14

Building older versions was a nightmare...