실패실패..

크롬에선 자동재생을 막았다.

광고 같은 곳에서 악용할까봐의 이유가 가장 크다고 한다.

### iframe, local mp3파일, audio태그 사용 -> 안됨

### iframe, youtube 링크 사용 ->안됨

> 혹시나 나중에 다른 해결책이 생각나면 시도해보는 걸로...

### 2020.07.25
javascript를 사용하면 된다.

var audio = new Audio("audo src");
audio.play(); 를 하면 자동재생을 할 수 있다!
