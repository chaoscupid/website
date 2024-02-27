# Welcome to the Source Code for `chaoscupid`

This is the source code for the `chaoscupid` site.

This code is licensed under the 
[Creative Commons Attribution 4.0 International Public License][cc].

[cc]: https://creativecommons.org/licenses/by/4.0/legalcode

## Contributing to these Docs

This site is built using [Hugo][]. Once you have [installed Hugo][install] and its dependencies, 
then you should be able to run the site locally by navigating to the root directory of this repo and entering:

[Hugo]: https://gohugo.io
[install]: https://gohugo.io/installation/

### Installing the theme

If you haven't already, you'll need to initialize the themes that this site depends on by executing the following commands from the root of the cloned repo:

```shell
$ git submodule init
...

$ git submodule update
```

### Running the website locally

```shell
$ hugo server
```

If all goes well then you should see:

```shell
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
```

This message gives you the URL to navigate to to see the site running locally.