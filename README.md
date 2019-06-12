# dstat-viz
Simple dstat result visualizer and toolkit

Usage; visualize memory usage in the machine with interval 10 seconds

```sh
$ pip install dstat-viz
$ dstat -tcmds --output data.csv 10
...
...
^C
$ dstat-viz --csv data.csv --out dstat-data.png
$ open dstat-data.png
```
