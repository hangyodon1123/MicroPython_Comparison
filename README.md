# MicroPython_Comparison
## calculator's turtle module
* function is Python 3.3.7 turtle module. <https://docs.python.org/3.3/library/turtle.html?highlight=turtle>
* TI ce_turtl (ver 1.00) for TI-84 Plus CE Python and more. <https://education.ti.com/fr/ressources-et-formations/modules-python>
* TI turtle (ver 2.0.0) for TI-84 Plus CE Python and more. <https://education.ti.com/en/product-resources/turtle-module/ti84ce-python>
* Numworks (OS 16.3.0) for Numworks. <https://www.numworks.com/resources/manual/>
* Casio CG50turtle (CasioEducation US) for Casio fx-CG50 and more. <https://www.youtube.com/watch?v=7R2lO-uWeHs>
### turtle motion [move and draw]
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
forward,fd | forward | forward | forward | forward,fd
backward,bk,back | backward | backward | backward | backward,bk,back
right,rt | right | right | right | right,rt
left,lt | left | left | left | left,lt
goto,setpos,setposition | goto | goto | goto | goto,setpos,setposition
setx | | | | setx
sety | | | | sety
setheading,seth | | setheading | setheading | setheading,seth
home | home | home | | home
circle | circle | circle | circle | circle
dot | dot | dot
stamp
clearstamp
clearstamps
undo
speed | speed | speed | speed | speed
((non)) | | done

### turtle motion [tell turtle's state]
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
position,pos | position | pos | position | position,pos
towards | | | | towards
xcor | | xcor | | xcor
ycor | | ycor | | ycor
heading | heading | heading | heading | heading
distance | | | | distance
((non)) | setheading

### turtle motion [setting and measurement]
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
degress
radians

### pen control [drawing state]
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
pendown,pd,down | pendown | pendown | pendown | pendown,pd,down
penup,pu,up | penup | penup | penup | penup,pu,up
pensize,width | pensize | pensize | pensize | pensize,width
pen
isdown | isdown | | isdown | isdown

### pen control [color control]
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
color | color | | color
pencolor | | pencolor | | pencolor
fillcolor | | fillcolor
((non)) | | | colormode

### pen control [filling]
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
filling
begin_fill | | begin_fill
end_fill | | end_fill

### pen control [more drawing control]
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
reset | | | reset | reset
clear | clear | clear | | clear
write | | write | write | write

### turtle state [visibility]
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
showturtle,st | show | showturtle | showturtle | showturtle,st
hideturtle,ht | | hideturtle | hideturtle | hideturtle,ht
isvisible | | | | isvisible
((non)) | | hidegrid

### turtle state [appearance]
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
shape | | | | shape
resizemode
shapesize,turtlesize
shearfactor
settiltangle
tiltangle
tilt
sharpetransform
get_shapepoly

### using events
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
onclick
onrelease
ondrag

### special turtle methods
function | TI ce_turtl | TI turtle | Numworks | Casio
----- | ----- | ----- | ----- | -----
begin_poly
end_poly
get_poly
clone
getturtle,getpen
getscreen
setundobuffer
undobufferentries
