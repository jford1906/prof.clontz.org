---
layout: page
title: "Part 4: Parametric Equations and Polar Coordiantes"
---



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
