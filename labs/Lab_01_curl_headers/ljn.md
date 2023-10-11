##### вызвали www.exaple.com
```

86134@ngjj MINGW64 /
$ curl www.exaple.com
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   146  100   146    0     0    294      0 --:--:-- --:--:-- --:--:--   294<html>
<head><title>403 Forbidden</title></head>
<body>
<center><h1>403 Forbidden</h1></center>
<hr><center>nginx</center>
</body>

</html>
```
##### вызвали www.exaple.ru
```
commandline

86134@ngjj MINGW64 /
$ curl www.exaple.ru
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (6) Could not resolve host: www.exaple.ru

```
##### вызвали http://exaple.ru

```
86134@ngjj MINGW64 /
$ curl http://exaple.ru
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (6) Could not resolve host: exaple.ru

```
##### вызвали https://exaple.ru

```
86134@ngjj MINGW64 /
$ curl https://exaple.ru
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (6) Could not resolve host: exaple.ru

```
