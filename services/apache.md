apache
======


## 폴더 권한
apache데몬이 호스팅 폴더에 접근하기 위해서는 read, execute 권한이 있어야 한다.
해당 폴더에서 모든 하위 폴더 및 파일의 접근권한은 아래와 같이 수정한다.

```
chmod ./ 755 -R
```

[참고](http://adnoctum.tistory.com/473)
