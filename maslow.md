``` pikchr
sidelen = 6cm
textpad = 0.4cm
color = white

define @layer {
  line invisible from P.n go $1 heading 150 then $1 west close \
    solid fill $2
  line thin from previous.sw to previous.se
  text $3 small with .c at textpad above previous.s
}

P: line go sidelen heading 90 then sidelen heading 330 close

@layer(6cm, 0xD92500, "physiological")
@layer(5cm, 0x6A0C91, "safety")
@layer(4cm, 0xFF9F05, "love &amp; belonging")
@layer(3cm, 0x7AA61B, "esteem")
@layer(2cm, 0x4A79ED, "actualization")
text "self-" small with .c at textpad above previous.c
```
