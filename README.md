# Swift and Copy Sources container pattern

In this repository we share an example of "Swift and the Copy Source container pattern" for the workshop [5 containers patterns for 5 languages](https://l0rd.github.io/talks/containers-and-languages/index_en.html).

The original [kitura todolist](https://github.com/IBM-Swift/Kitura-TodoList) has been developed by IBM as one of the sample Swift web applications for [Kitura](https://github.com/IBM-Swift/Kitura). Kitura is a cool Swift Web framework and HTTP server.

```bash
git clone https://github.com/containerslanguages/swift
cd swift/kitura-todolist
docker build -t containerslanguages/swift-todolist .
docker run -d -p 8090:8090 containerslanguages/swift-todolist
open http://localhost:8090/v1/tasks
```
