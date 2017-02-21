---
layout: page
title: "Part 4: Parametric Equations and Polar Coordiantes"
---


---

## 4.3 Polar Coordinates

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 10.3

### 4.3.1 Definition of Polar Coordinates

<iframe width="560" height="315" src="https://www.youtube.com/embed/1tjeJmTmBbg" frameborder="0" allowfullscreen></iframe>

- The polar coordinate \\(p(r,\theta)\\) is defined to be Cartesian
  coordinate \\((r\cos\theta,r\sin\theta)\\).
- **Example** Plot the polar coordinates
  \\(p(2,\pi/3),p(\sqrt{2},3\pi/4),p(-2,4\pi/3),p(4,11\pi/6)\\).
- Note that every polar coordinate \\(p(r,\theta)\\) is equal to
  \\(p(r,\theta+k\pi)\\) for all even integers \\(k\\), and equal to
  \\(p(-r,\theta+k\pi)\\) for all odd integers \\(k\\).

### 4.3.2 Equations Relating Polar and Cartesian Coordinates

<iframe width="560" height="315" src="https://www.youtube.com/embed/ar4rY_uDrbY" frameborder="0" allowfullscreen></iframe>

- Polar and Cartesian coordinates may be related by the equations
  \\(x=r\cos\theta\\), \\(y=r\sin\theta\\), \\(x^2+y^2=r^2\\),
  and \\(\tan\theta=\frac{y}{x}\\).
- **Example**
  Convert the Cartesian coordinate \\((-2\sqrt3,2)\\) into a polar
  coordinate.

<iframe width="560" height="315" src="https://www.youtube.com/embed/pIXfMdVHxNk" frameborder="0" allowfullscreen></iframe>

- **Example**
  Convert the polar equation \\(r=\frac{1}{\sin\theta-\cos\theta}\\),
  \\(\pi/4<\theta<5\pi/4\\)
  into a Cartesian equation.
- **Example**
  Convert the Cartesian equation \\((x-2)^2+y^2=4\\)
  into a polar equation.

### 4.3.3 Common Polar Equations <!-- TODO add r=a\sin(\theta)-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/edC-bfH6xh8" frameborder="0" allowfullscreen></iframe>

- The equation \\(r=R\\) is a circle centered at the origin of radius
  \\(R\\).
- The equation \\(\theta=\alpha\\) is the line passing through the origin
  at the angle \\(\\alpha\\).
- The equation \\(r\cos\theta=a\\) is the vertical line \\(x=a\\).
- The equation \\(r\sin\theta=b\\) is the horizontal line \\(y=b\\).
- **Example** <!-- TODO fix minor issue in video -->
  Sketch the region where \\(0<\csc\theta\leq r\leq 2\\).
- The equations \\(r=a\pm a\cos\theta\\) and \\(r=a\pm a\sin\theta\\)
  are known as cardioids.
- **Example**
  Sketch the cardioid \\(r=4-4\sin\theta\\).

### Exercises for 4.3

1.  Convert the polar coordinates
    \\(p(\sqrt 3,2\pi/3),p(\sqrt 2,\pi/4),p(2,7\pi/6),p(-\sqrt 3,-\pi/3)\\)
    to Cartesian and plot them in the \\(xy\\) plane.
2.  Convert the Cartesian coordinates
    \\((4,-4),(-\frac{3}{2},-\frac{\sqrt 3}{2})\\)
    into polar coordinates.
3.  Convert the polar equation \\(r=\frac{5}{\sqrt{25-9\sin^2\theta}}\\)
    into a Cartesian equation. Name the curve.
4.  Convert the Cartesian equation
    \\(1-\frac{y}{x^2+y^2}=\frac{3}{\sqrt{x^2+y^2}}\\) into a polar equation.
4.  Convert the Cartesian equation for the line
    \\(y=\frac{x}{\sqrt 3}\\) into a polar equation.
4.  Sketch the region where \\(0< 3\sec\theta\leq r\leq 6\cos\theta\\).
    (Hint: Completing the square in \\(x^2-6x+y^2=0\\) yields
    \\((x-3)^2+y^2=9\\).)
4.  Sketch the cardioid \\(r=3+3\sin\theta\\).
4.  Sketch the cardioids \\(r=1+\cos\theta\\) and \\(r=1-\cos\theta\\).
    At what points do they intersect?
4.  (OPTIONAL)
    Sketch the "three-leaved rose" \\(r=\sin 3\theta\\).
1.  (QUIZ)
    Which of these polar coordinates gives the point \\((-\sqrt3,1)\\)?
    - \\(p(\sqrt2,3\pi/4)\\)
    - \\(p(\sqrt3,\pi/3)\\)
    - \\(p(2,5\pi/6)\\)
1.  (QUIZ)
    Convert the circle \\(x^2+(y-4)^2=16\\) into a polar equation.
    - \\(r=16\\)
    - \\(r=8\sin\theta\\)
    - \\(r=12\cos^2\theta-4\sin^2\theta\\)
1.  (QUIZ)
    Which of these equations gives the curve drawn below?
    - \\(r=3+3\cos\theta\\)
    - \\(r=3-3\sin\theta\\)
    - \\(r=3\tan\theta\\)

![Cardioid]({{site.baseurl}}public/cardioid.gif)

[Solutions 1-5]({{site.baseurl}}public/solutions/4.3a.pdf)

[Solutions 6-12]({{site.baseurl}}public/solutions/4.3b.pdf)



---

## 4.4 Areas and Lengths using Polar Coordinates

#### Textbook References

- University Calculus: Early Transcendentals (3rd Ed)
    - 10.5

### 4.4.1 Area Between Polar Curves

<iframe width="560" height="315" src="https://www.youtube.com/embed/Gz0vRIShjRk" frameborder="0" allowfullscreen></iframe> <!-- TODO drop f(\theta) -->

- The area of the circle sector of angle \\(\theta\\) is given by
  \\(A=\pi r^2\times\frac{\theta}{2\pi}=\frac{1}{2}r^2\theta\\).
- Therefore the area bounded by \\(\alpha\leq\theta\leq\beta\\),
  \\(r=f(\theta)\\) is
  \\(A=\frac{1}{2}\int_\alpha^\beta(f(\theta))^2\,d\theta\\).
- **Example**
  Find the area bounded by the cardioid \\(r=2+2\sin\theta\\).

<iframe width="560" height="315" src="https://www.youtube.com/embed/VvmPhO5nY00" frameborder="0" allowfullscreen></iframe>

- To obtain the area where \\(f(\theta)\leq r\leq g(\theta)\\),
  where \\(f\\) is an inside curve and \\(g\\) is an outside curve,
  find the clockwise angle \\(\alpha\\) and counter-clockwise angle
  \\(\beta\\) where they intersect, and use
  \\(A=\frac{1}{2}\int_\alpha^\beta((g(\theta))^2-(f(\theta))^2)\,d\theta\\).
- **Example**
  Find the area outside the circle \\(x^2+y^2=1\\) and inside the
  cardioid \\(r=1-\cos\theta\\).

### 4.4.2 Length of a Polar Curve

<iframe width="560" height="315" src="https://www.youtube.com/embed/TZAQB6AkB7w" frameborder="0" allowfullscreen></iframe>

- The polar curve \\(r=f(\theta)\\) where \\(\alpha\leq\theta\leq\beta\\)
  may be parametrized by \\(x=f(\theta)\cos\theta,y=f(\theta)\sin\theta\\)
  with the same bounds, using \\(\theta\\) in place of \\(t\\) as the
  parameter.
- Therefore its length is given by
  \\(L=\int_\alpha^\beta\sqrt{
      (\frac{dx}{d\theta})^2+(\frac{dy}{d\theta})^2
  }\,d\theta\\)
  which simplifies to
  \\(L=\int_\alpha^\beta\sqrt{
      (f(\theta))^2+(f'(\theta))^2
  }\,d\theta\\).
- **Example**
  Show that the circumference of the circle of radius \\(R\\) is \\(2\pi R\\).
- **Example**
  Find the circumference of the spiral \\(r=\theta^2\\) from
  \\(p(0,0)\\) to \\(p(5,\sqrt 5)\\).

### Exercises for 4.4

1.  Find the area inside \\(r=\cos2\theta\\) where \\(0\leq\theta\leq\pi/4\\).
1.  Find the area bounded by the cardioid \\(r=1-\cos\theta\\).
2.  Sketch the region where \\(\|x\|\leq y\leq\sqrt{1-x^2}+1\\).
    Show that its area is \\(\frac{\pi}{2}+1\\).
    (Hint: Show that this is the area inside \\(r=2\sin\theta\\)
    where \\(\pi/4\leq\theta\leq3\pi/4\\).)
1.  Find the length of one rotation of the spiral \\(r=e^\theta\\).
1.  Use the polar arclength formula to show that the circumference of the
    circle \\(r=4\sin\theta\\) is \\(4\pi\\).
1.  Show that the length of the cardioid \\(r=2+2\cos\theta\\) is
    \\(\int_0^{2\pi}\sqrt{8+8\cos\theta}\,d\theta=16\\).
1.  (OPTIONAL)
    Prove that if \\(x=f(\theta)\cos\theta\\) and \\(y=f(\theta)\sin\theta\\)
    then
\\(\int_\alpha^\beta\sqrt{
    (\frac{dx}{d\theta})^2+(\frac{dy}{d\theta})^2
}\,d\theta
=\int_\alpha^\beta\sqrt{
    (f(\theta))^2+(f'(\theta))^2
}\,d\theta\\).
1.  (QUIZ)
    Which of these integrals is the area of the cardioid \\(r=4+4\sin\theta\\)?
    - \\(\int_0^{2\pi}(8+16\sin\theta+8\sin^2\theta)\,d\theta\\)
    - \\(\int_0^{\pi/2}(16+16\sin^2\theta)\,d\theta\\)
    - \\(\int_0^{\pi}6\sin^2\theta\,d\theta\\)
1.  (QUIZ)
    Which of these integrals is the length of the curve \\(r=\cos^2\theta\\)
    where \\(0\leq\theta\leq\pi/2\\)?
    - \\(\int_0^{\pi/2}4\sin\theta\sqrt{1-\cos^2\theta}\,d\theta\\)
    - \\(\int_0^{\pi/2}(\cos^4\theta-\pi)\,d\theta\\)
    - \\(\int_0^{\pi/2}\cos\theta\sqrt{1+3\sin^2\theta}\,d\theta\\)

[Solutions 1-7]({{site.baseurl}}public/solutions/4.4a.pdf)
[Solutions 8-9]({{site.baseurl}}public/solutions/4.4b.pdf)
