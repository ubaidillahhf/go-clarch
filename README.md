# GO CLARCH

> Go Clean Architecture Boilerplate
> New to Clean Architecture? [Learn Here](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

[![Go Report Card](https://goreportcard.com/badge/github.com/ubaidillahhf/go-clarch)](https://goreportcard.com/report/github.com/ubaidillahhf/go-clarch)

## ๐ Contains

- [The 4 Layer](#-the-layer)
- [Fiber Go web framework](#-fiber-go)
- [Air live reloading](#-air)
- [Debugger](#-debugger)
- [Postman Docs](#-postman-docs)
- [References](#-references)

## ๐ฐ The Layer

| Layer                | Directory          |
| -------------------- | ------------------ |
| Frameworks & Drivers | /app/infra         |
| Interface            | /app/interfaces    |
| Usecases             | /app/usecases      |
| Entities             | /app/domain/entity |

## โก Fiber Go

We use fiber for routing and more, you can change whatever you like (echo, gin, chi, etc).
Why fiber? learn [here](https://gofiber.io/)

## ๐ Air

If you familiar with nodemon in nodejs, air is exactly same. Provide hot reloading when files change with auto build.

Visit: https://github.com/cosmtrek/air for installation guide

## ๐งช Debugger

If you come from PHP maybe you use var_dump(), if u from javasript maybe u use console.log(), in GO u can use fmt.Println().

But if u don't know before, using debugger is awesome and helpful (If u use VS Code), u just go to debug and run the debugger. The config in .vscode in the project. Wanna try? Learn [here](https://medium.com/@slamflipstrom/debugging-with-visual-studio-code-857904a8a590)

## ๐ Postman Docs

- https://documenter.getpostman.com/view/21757760/2s8YstTZ9f

## ๐ References

- https://github.com/khannedy/golang-clean-architecture
- https://github.com/evrone/go-clean-template
- https://github.com/Creatly/creatly-backend
