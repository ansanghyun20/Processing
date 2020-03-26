# Rep2_1.md
## 안동대 안상현
```

void setup() {
size(800, 300);
textSize(200);
}
int i, dir=1, sp=1;
void draw() {
 fill(0,0,255);
 background(255,255,0);
 text("Graphics", i, 200);
 if(i>width) dir=-1;
 if(i<0) dir=1;
 i = i+dir*sp;
}
void keyPressed(){
  sp = key - '0';
}

```

##리포트 소감
* 교수님 프로세싱으로 다루는 그래픽이 정말 신기하고 재밌습니다!
* 앞으로 컴퓨터 그래픽에 대해서 더 열심히 공부 하고싶습니다!
* [markdown 언어 ](https://gist.github.com/ihoneymon/652be052a0727ad59601)
