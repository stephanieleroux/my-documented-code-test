# Build documentation

## Section 1
This is text for section 1.

## Section 2
This is some other text for section 2.
With lists:

* item1
* item 2

And with blocks of code:

```
#python
import numpy as np

t = np.arange(1,10,2)

```

## Enable latex  equations:
You need to enable latex in the `source/conf.py` file first by adding this line:

```
myst_enable_extensions = ["dollarmath", "amsmath"]
```
Then you can write some latex:

$$
   \begin{eqnarray}
      y    & = & ax^2 + bx + c \\
      f(x) & = & x^2 + 2xy + y^2
   \end{eqnarray}
$$

For more infos, and more extensions, see [this page: https://myst-parser.readthedocs.io/en/latest/syntax/optional.html](https://myst-parser.readthedocs.io/en/latest/syntax/optional.html) .

