# roadya.github.io

#bashshell
치환하기
~~~
1) find 로 파일을 찾아서
2) pipeline으로 그 값들을 넘겨서 sed -i 's/원래/바꿀래'
3) example
$> find . -name "*.cpp" -o -name "*.hpp" -o -name "*.c" -o -name "*.h"  |xargs sed -i 's/[[:space:]]*$//'
~~~
