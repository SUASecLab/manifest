SUASecLab
============

Fist steps
---------

Before being able to start changing any source code, you have to get a copy of it.
The SUASecLab uses the `repo` tool for source code management (overlay for git to handle many repositories).
You can find more information about `repo` at the website of the [Android developers](https://source.android.com/docs/setup/reference/repo).

To obtain a copy of the source code, run the following:

````
mkdir SUASecLab
cd SUASecLab
repo init -u git@github.com:SUASecLab/manifest.git -b default
````

You can now clone the code (or get code updates) with the following command:

````
repo sync
````
