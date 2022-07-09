# go-todo-app
A todo cli app, made in Golang.

I have written this repo in order to get rid of endless "todo_something.txt" files and learn some Go.

So the go-todo-app was born, I am making it following the interesting tutorial I found here:  
https://spf13.com/presentation/building-an-awesome-cli-app-in-go-oscon/

I am currently at slide 293.

The steps to scaffold a cli tool in go:
- ```go get github.com/spf13/cobra```
- ```go get github.com/spf13/viper``` 
- ```cobra init --pkg-name github.com/ltpitt/go-todo-app -a ltpitt```
- ```go mod init github.com/ltpitt/go-todo-app```
- ```go build```
- ```go-todo-app.exe``` or ```./go-todo-app```
