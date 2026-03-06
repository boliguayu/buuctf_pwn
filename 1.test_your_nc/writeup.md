~~~ asm
00401135    int32_t main(int32_t argc, char** argv, char** envp)
00401140        system(line: "/bin/sh")
0040114b        return 0
~~~

直接给了bin sh 就是检查环境有没有装好

代码直接连接运行即可拿到shell
