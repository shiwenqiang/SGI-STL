## SGI STL

#### Cygnus C++ 2.91 for windows

源文件概略可分为五组:
- C++ 标准规范下的C头文件(无扩展名), 例如cstdio, cstdlib, cstring...
- C++ 标准程序库中不属于STL范畴者, 例如stream, string...相关文件.
- STL 标准头文件(无扩展名), 例如vector, deque, list, map, algorithm, functional ...
- C++ standard定案前, HP所规范的STL头文件, 例如 vector.h, deque.h, list.h, map.h, algo.h, function.h ...
- SGI STL 内部文件(STL 真正实现于此), 例如 stl_vector.h, stl_deque.h, stl_list.h, stl_map.h, stl_algo.h, stl_function.h ...

>   以上引自[Hou02a]: <STL 源码剖析> 侯捷著, Page 16.

