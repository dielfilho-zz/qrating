# QRating
Rating library using Bootstrap stars (glyphicon-star).

Dependencies
------------
Bootstrap : http://getbootstrap.com/

Usage
-----
<code>
  var $div1 = $q("div1").init({"stars":5, "color":"#000000", "size":"40px", "filled":true});
  var $div2 = $q("div2").init({"stars":10, "color":"#006699", "size":"20px", "filled":false});
  var rating1 = $div1.getRating();
</code>

--------------
+ stars : number of stars.
+ color : star's color.
+ size  : star's size.
+ filled: all the stars start selected
--------------
