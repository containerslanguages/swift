# The Swift language and the Copy Sources container pattern

In this repository we share the source code related to the Swift language and the Copy Source container patter of the workshop [5 containers patterns for 5 languages](https://l0rd.github.io/talks/containers-and-languages/index_en.html).

The original [kitura todolist](https://github.com/IBM-Swift/Kitura-TodoList) has been developed by IBM as one of the sample Swift web applications for [Kitura](https://github.com/IBM-Swift/Kitura). Kitura is a cool Swift Web framework and HTTP server.

```bash
git clone https://github.com/containerslanguages/swift
cd swift/kitura-todolist
docker build -t swift-todolist .
did=$(docker run -d -P swift-todolist)
port=$(docker port $did 8090/tcp | cut -d \: -f 2)
echo "Open to http://localhost:$port/v1/tasks"
```
