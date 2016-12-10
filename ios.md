---
layout: project
title: Photography
thumbnail: images/photography_thumb.png
abstract: 
---

## iOS

When I was learning about BSpline curves, I created two iOS applications to help me visualize the curves that result from control points and knot vectors. The first application was a BSpline Curve drawing tool. You can lay down control points, experiment with the degree of the curve and edit the knot vector to control how the curve follows the control points.

![A BSpline curve with degree 3][splines_1]
![A BSpline curve with degree 11][splines_2]
![Editing the knot vector][splines_3]
Screenshots from the BSpline editor

The second application renders a BSpline Surface and uses the iOS accelerometer to allow the user to move the device around the shape to see it from different angles. It reads a surface definition file from a server, so I could edit the table of control points and knot vectors to change the shape.

![A BSpline Surface from the side][surface_1]
![A different view of the surface using the accelerometer][surface_2]
Screenshots from the BSpline surface viewer


[splines_1]: images/splines_1.jpg
{: width=177px height=265px }
[splines_2]: images/splines_2.jpg
{: width=177px height=265px }
[splines_3]: images/splines_3.jpg
{: width=177px height=265px }
[surface_1]: images/surface_1.jpg
{: width=265px height=177px }
[surface_2]: images/surface_2.jpg
{: width=265px height=177px }
