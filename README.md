# go-todo-app
A todo cli app, made in go

The result of me learning to code my first cli tool in go, following the tutorial here:  
https://spf13.com/presentation/building-an-awesome-cli-app-in-go-oscon/

I am currently at slide 210.

The steps to scaffold a cli tool in go:
- ```go get github.com/spf13/cobra```
- ```go get github.com/spf13/viper``` 
- ```cobra init --pkg-name github.com/ltpitt/go-todo-app -a ltpitt```
- ```go mod init github.com/ltpitt/go-todo-app```
- ```go build```
- ```go-todo-app.exe``` or ```./go-todo-app```
