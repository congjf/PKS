
### How to install the GoSublime Dev Branch in the Sublime (3.1.1 build 3176)

When I want to edit go code with the sublime text 3, found the GoSublime plugin cannot be get from the `install package` command. And the official site of GoSublime plugin suggests users to use the development branch. 

So, record the GoSublime plugin install steps below.

1. Install the Go and config the ENV variable GOPATH&GOROOT
2. Install the Sublime
3. Get the GoSublime dev branch file
4. **Put the GoSublime development branch files into the Sublime packages folder (like: `C:\Users\<Your System User Name>\AppData\Roaming\Sublime Text 3\Packages`)**
5. Restart Sublime, and open a Go code file
6. Save the Go code file, and find the Tip information which hint you to press the `ctrl+.` and `ctrl+x`
7. **Press `ctrl+shift+P`, open the command palette, and enter `edit margo extension`**

> PS: if you cannot complete the go package install(like `guru`), you should install these packages by yourself(like `go get golang.org/x/tools/cmd/guru`).

[Configuration of GoSublime](https://gist.github.com/congjf/19f50aee8879567a176c9e53eb5902d3)
