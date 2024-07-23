Absolutely! Here's how to find the exact area under the curve:

**1. Set up the definite integral:**

The area under the curve `f(x) = tan(x)` from `x = 0` to `x = π/3` is given by the definite integral:

```
∫[0, π/3] tan(x) dx
```

**2. Rewrite tan(x)**

Recall that tan(x) = sin(x)/cos(x)

```
∫[0, π/3] sin(x)/cos(x) dx
```

**3. Use substitution (u-substitution):**

* Let `u = cos(x)`
* Then, `du = -sin(x) dx` 
* Rearrange:  `-du = sin(x) dx`

* Change the limits of integration:
    * When x = 0, u = cos(0) = 1
    * When x = π/3, u = cos(π/3) = 1/2

Now, the integral becomes:

```
∫[1, 1/2] -1/u du 
```

**4. Integrate:**

The integral of -1/u is -ln|u|

```
-ln|u|  evaluated from 1 to 1/2
```

**5. Evaluate the definite integral:**

```
[-ln(1/2)] - [-ln(1)] = -ln(1/2) + ln(1)
```

Since ln(1) = 0, the answer simplifies to:

```
-ln(1/2) = ln(2) 
```

**Therefore, the exact area under the curve is ln(2), which corresponds to answer choice D.**
