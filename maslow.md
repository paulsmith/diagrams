``` pikchr
sidelen = 6cm
numlayer = 5
textpad = 0.3cm
color = white

P: line go sidelen heading 90 then sidelen heading 330 close \
   solid fill 0xD92500
   text "physiological" with .c at textpad above P.s

line invisible from P.n go 5cm heading 150 then 5cm west close \
   solid fill 0x6A0C91
line thin from previous.sw to previous.se
text "safety" with .c at textpad above previous.s

line invisible from P.n go 4cm heading 150 then 4cm west close \
   solid fill 0xFF9F05
line thin from previous.sw to previous.se
text "love &amp; belonging" with .c at textpad above previous.s

line invisible from P.n go 3cm heading 150 then 3cm west close \
   solid fill 0x7AA61B
line thin from previous.sw to previous.se
text "esteem" with .c at textpad above previous.s

line invisible from P.n go 2cm heading 150 then 2cm west close \
   solid fill 0x4A79ED
line thin from previous.sw to previous.se
text "actualization" small with .c at textpad above previous.s
text same "self-" small with .c at 0.3cm above previous.c
```
