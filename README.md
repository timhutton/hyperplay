hyperplay
=========

*Explore tilings on the hyperbolic plane*

[**PLAY HERE!**](http://timhutton.github.io/hyperplay/)

Usage:
------

To start with it shows the [{3,q}](https://en.wikipedia.org/wiki/Triangular_tiling#Related_polyhedra_and_tilings) family of tilings, and intermediate forms. 

Move the mouse left and right to change the curvature of space. Negative curvature gives us hyperbolic tilings. Zero curvature gives us plane tiling. Positive curvature gives us polyhedra. 

Use the ```+``` and ```-``` buttons to change the number of sides in the base polygon.

<a href="http://timhutton.github.io/hyperplay/"><img src="http://timhutton.github.io/hyperplay/logo.png" width="300" /></a>

What the heck am I looking at?
------------------------------

Notice that there's a triangle in the center that never changes. We will use the edges of this triangle as mirrors. 

First we reflect the triangle in each of those mirrors. Our triangle has now got three more triangles around it, one fixed to each edge.

We repeat this process again and again. We end up with lots of triangles, all joined edge to edge.

At some values of curvature the triangles all overlap neatly and we get a nice *tiling*. This can be a flat tiling like you could use in your bathroom, or it could lie in a curved space like on a ball. A tiled ball is a polyhedron of course.

One nice thing about making tilings like this ([Wythoff Construction](https://en.wikipedia.org/wiki/Wythoff_construction)) is that we can do the same thing in negatively curved ([hyperbolic](https://en.wikipedia.org/wiki/Hyperbolic_space)) space to get the hyperbolic tilings like [{5,4}](https://en.wikipedia.org/wiki/Order-4_pentagonal_tiling) shown above. We render these with the [Poincare disk model](https://en.wikipedia.org/wiki/Poincar%C3%A9_disk_model) which is why the pentagons get small and stretched towards the outside.

Credits:
--------

Thanks to Adam P. Goucher for getting me started with hyperbolic tessellation! [Here's a blog post](http://cp4space.wordpress.com/2014/09/12/hyperbolic-minecraft/) he wrote about it.

He made his own interactive demonstration of Wythoff Construction, [here](http://demonstrations.wolfram.com/WythoffConstructionOfPolyhedra/).

Discussions:
------------

* [Comments](https://plus.google.com/110214848059767137292/posts/fXR8AChDbSY) on the original Google+ post.
* [The Aperiodical](http://aperiodical.com/2014/09/have-fun-playing-with-curvature/)
* [Hacker News](https://news.ycombinator.com/item?id=8317895)


