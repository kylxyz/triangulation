# triangulation
# I dont know why the expressed the ASCII figure is not what I expected.
# however if you try edit mode of this file you can see it.

This is for calculating 3D coordinates of an unknown point P(xp,yp,zp). 
With given several parameters of the surveying.
Known (input):
-	A(xa,ya,za)
-	B(xb,yb,zb)
-	L(distance of AB, unit m)
-	A_rad (radian of A)
-	B_rad (radian of B)
-	a (azimuth angle of P'A )
-	t (elevation angle of PA)

Therefore:
-	xp = xa + L*sin(B_rad)*sin(a) / sin(A_rad+B_rad);
-	yp = ya + L*sin(B_rad)*cos(a) / sin(A_rad+B_rad);
-	zp = za + L*sin(B_rad)*tan(t) / sin(A_rad+B_rad);
                                         


Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
