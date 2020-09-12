## Welcome to flutter_lab

flutter
[widgets-intro](https://flutter.dev/docs/development/ui/widgets-intro)
[layout](https://flutter.dev/docs/development/ui/layout)
<span style="color:blue">
![ผัง](https://flutter.dev/assets/ui/layout/sample-flutter-layout-46c76f6ab08f94fa4204469dbcf6548a968052af102ae5a1ae3c78bc24e0d915.png)
</span>

```flow
st=>start: Start:>http://www.google.com[blank]
e=>end:>http://www.google.com
op1=>operation: My Operation
sub1=>subroutine: My Subroutine
cond=>condition: Yes
or No?:>http://www.google.com
io=>inputoutput: catch something...
para=>parallel: parallel tasks

st->op1->cond
cond(yes)->io->e
cond(no)->para
para(path1, bottom)->sub1(right)->op1
para(path2, top)->op1
```
