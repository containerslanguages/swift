# The Swift language and the Copy Sources container pattern

In this repository we share the source code related to the Swift language and the Copy Source container patter of the workshop [5 containers patterns for 5 languages](https://l0rd.github.io/talks/containers-and-languages/index_en.html).

The original kitura todolist has been developed by IBM and can be found [here](https://github.com/IBM-Swift/Kitura-TodoList)

```bash
git clone https://github.com/containerslanguages/swift
cd swift/kitura-todolist
docker build -t swift-todolist .
did=$(docker run -d -P swift-todolist)
echo "Navigate to http://localhost:$(docker port $did 8090/tcp | cut -d \: -f 2)
```
