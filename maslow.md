``` pikchr
sidelen = 6cm
numlayer = 5
textpad = 0.3cm

P: line go sidelen heading 90 then sidelen heading 330 close \
   solid fill red
   text color white "physiological" with .c at textpad above P.s

line invisible from P.n go 5cm heading 150 then 5cm west close \
   solid fill orange
line thin color white from previous.sw to previous.se
text color white "safety" with .c at textpad above previous.s

line invisible from P.n go 4cm heading 150 then 4cm west close \
   solid fill yellow
line thin color white from previous.sw to previous.se
text color black "love &amp; belonging" with .c at textpad above previous.s

line invisible from P.n go 3cm heading 150 then 3cm west close \
   solid fill green
line thin color white from previous.sw to previous.se
text color white "esteem" with .c at textpad above previous.s

line invisible from P.n go 2cm heading 150 then 2cm west close \
   solid fill blue
line thin color white from previous.sw to previous.se
text color white "actualization" small with .c at textpad above previous.s
text same "self-" small with .c at 0.3cm above previous.c
```
