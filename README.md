# ------------------------------------------------------------
css: using margin auto on flex children
position: absolute & relative
use align-self: center with display flex
position: fixed
# ------------------------------------------------------------
child with margin-left: auto; margin-bottom: auto; parent display:flex moving in opposite direction that is to right top of the parent
# ------------------------------------------------------------
parent display:flex 
child with -->
margin-left: auto;
margin-right: auto;                                                      margin-top: auto;
moving to the center at the bottom of the parent

margin: auto auto auto 0; --> left middle
margin: auto 0 0 auto; --> right bottom corner
# ------------------------------------------------------------
parent: {
    position: relative;
}
child {
    position: absolute;
    top: 0;
    left: 0;
}
# ------------------------------------------------------------
css: put 2elements in opposite sides of parent element and minimum space between 20px
display: flex
justify-content: space-between
gap: 20px
# -------------------------------------------------------------
### to the browser's window in the center
position: fixed --> 
top: 0;
bottom: 0;
left: 0;
right: 0;
# -------------------------------------------------------------
css IMAGE: to remove white space under image use property --> display: block