# Rep2_2.md
## 안동대 안상현
```

PFont f;
void setup(){
size(800,300);
f = createFont("굴림",64);
textFont(f);
}
int i, dir=1, sp=1;
void draw() {
 fill(128,128,255);
 background(255,255,255);
 text("안동대 컴공 사랑합니다", 50, i+50);
 if(i>height-50) dir=-1;
 if(i<0) dir=1;
 i = i+dir*sp;
}
void keyPressed(){
  sp = key - '0';
}

```
