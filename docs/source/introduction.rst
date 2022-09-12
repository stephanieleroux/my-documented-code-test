Introduction to dummypackage
#############################

This is the intro page.

This is a (dummy) collection of math tools i often use. 

This is also an example code to test the automatic building of a documentation, using  Sphinx and Readthedocs.


RST format
***********
These pages have to be written in `rst format <https://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html#headings>`_,  which is very close from markdown format.

**See section "formatting tips" below"**: you can also use markdown and latex.


Another section
*****************

You can put code blocks in those pages:
::

    import math
    print 'import done'

or:
::

    def main():
        """Example application: compute ((a+b)*2) where a=3, b=5."""
        msg = "Example application: compute ((a+b)*2) where a=3, b=5:"
        print(msg)
        print('RESULT:')
        res_add = add(3,5)
        res_mul = mul(res_add,2)
        print(res_mul)
 

You can add lists:

- one think
- second thing


Or numbered lists:

1. first thing
2. second thing

**See section "formatting tips" below"**: you can also use markdown and latex.
