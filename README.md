# QRating ![Alt text](http://www.i2symbol.com/images/myspace/symbols/black_star_u2605_icon_64x64.png)
Rating library using Bootstrap stars (glyphicon-star).

Dependencies
------------
Bootstrap : http://getbootstrap.com/

Usage
-----
<code> var $div1 = $q("div1").init({"stars":5, "color":"#000000", "size":"40px", "filled":true}); </code><br/>
<code> var $div2 = $q("div2").init({"stars":10, "color":"#006699", "size":"20px", "filled":false});</code><br/>
<code> var rating1 = $div1.getRating();</code><br/>

--------------
+ stars : number of stars.
+ color : star's color.
+ size  : star's size.
+ filled : all the stars start selected.
+ 
--------------
