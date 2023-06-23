# ExampleBrowserTestJS

The repo exists to prevent submodule recursion.  (Otherwise, this would be in `browsertestjs/example`.)

## The main project [BrowserTestJS](https://github.com/Cyphrme/BrowserTestJS).

# [Link to example/live demo](https://cyphrme.github.io/BrowserTestJSExample/browsertest/browsertest.html)

Example of using BrowserTestJS as a git submodule in a project.

`BrowserTestJS` is added as a submodule in this example repo to demonstrate how
a project is recommended to implement the package and was added to this example
repo by using the command:

## Installing BrowserTestJS
```sh
git clone git@github.com:Cyphrme/BrowserTestJS.git         browsertest
git submodule add git@github.com:Cyphrme/BrowserTestJS.git browsertest
```

# Update/Bump/Sync to latest BrowserTestJS Version
```sh
git submodule update --init --recursive --remote
```

# Run the tests locally
```sh
(
cd browsertest
go run server.go
)
```


Tests also work on Github.  For example, using this repo, the link is:
https://cyphrme.github.io/BrowserTestJSExample/browsertest/browsertest.html

For an example of how to embed the `BrowserTestJS` testing page directly in
another page, see `iframe.html.example`.



----------------------------------------------------------------------
# Attribution, Trademark Notice, and License
BrowserTestJS and BrowserTestJSExample are released under The 3-Clause BSD License. 

"Cyphr.me" is a trademark of Cypherpunk, LLC. The Cyphr.me logo is all rights
reserved Cypherpunk, LLC and may not be used without permission.