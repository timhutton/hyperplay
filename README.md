hyperplay
=========

*Explore tilings on the hyperbolic plane*

[**PLAY HERE!**](http://timhutton.github.io/hyperplay/)

<a href="http://timhutton.github.io/hyperplay/"><img src="http://timhutton.github.io/hyperplay/logo.png" width="300" /></a>

To start with it shows the {3,q} family of tilings, and intermediate forms. When you move the mouse left and right the construction process (reflection in the edges of the base polygon) stays the same but the curvature of the space itself changes. Negative curvature gives us hyperbolic tilings. Zero curvature gives us plane tiling. Positive curvature gives us polyhedra. 

Use the ```+``` and ```-``` buttons to change the number of sides in the base polygon.

What the heck am I looking at?
------------------------------

Notice that there's a triangle in the center that never moves. We will use the edges of this triangle as mirrors. 

First we reflect the triangle in each of those mirrors. Our triangle has now got three more triangles around it, one fixed to each edge.

We repeat this process again and again. We end up with lots of triangles, all joined edge to edge.

At some values of curvature the triangles all overlap neatly and we get a nice *tiling*. This can be a flat tiling like you could use in your bathroom, or it could lie in a curved space like on a ball. A tiled ball is called a polyhedron.

The nice thing about making tilings like this ([Wythoff Construction](https://en.wikipedia.org/wiki/Wythoff_construction)) is that we can do the same thing in negatively curved (hyperbolic) space to get the hyperbolic tilings like {5,4} shown above.

Credits
-------

Thanks to Adam P. Goucher for getting me started with hyperbolic tessellation! [Here's a blog post](http://cp4space.wordpress.com/2014/09/12/hyperbolic-minecraft/) he wrote about it.

He made his own interactive demonstration of Wythoff Construction, [here](http://demonstrations.wolfram.com/WythoffConstructionOfPolyhedra/).
