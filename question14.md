Absolutely! Here's how to solve the problem:

**1. Find the Velocity Function:**

* Acceleration is the derivative of velocity. So, to find the velocity function, v(t), we need to integrate the acceleration function, a(t):

   v(t) = ∫ a(t) dt = ∫ -3 dt = -3t + C 

* We're given the initial velocity, v₀ = 9.  This means v(0) = 9. We can use this to solve for the constant C:

   9 = -3(0) + C
   C = 9

* Therefore, the velocity function is:

    v(t) = -3t + 9

**2. Find When the Particle Changes Direction:**

* The particle changes direction when its velocity is zero. So, we need to solve the equation v(t) = 0:

    -3t + 9 = 0
    t = 3

**3. Calculate the Distance Traveled in Each Interval:**

* **Interval 1 (0 ≤ t ≤ 3):** The particle is moving in the positive direction (v(t) is positive).
   * To find the distance traveled, we integrate the velocity function from 0 to 3:
     ∫[0,3] (-3t + 9) dt = [-3/2 t² + 9t] evaluated from 0 to 3 = 27/2

* **Interval 2 (3 ≤ t ≤ 7):** The particle is moving in the negative direction (v(t) is negative).
    * To find the distance traveled, we integrate the absolute value of the velocity function from 3 to 7:
      ∫[3,7] |(-3t + 9)| dt = ∫[3,7] (3t - 9) dt = [3/2 t² - 9t] evaluated from 3 to 7 = 24

**4. Total Distance Traveled**

Add the distances traveled in each interval:

Total distance = 27/2 + 24 = 75/2 meters

**Answer:**

The total distance traveled by the particle is 75/2 meters. So the answer is (E).
