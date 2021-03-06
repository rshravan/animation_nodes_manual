Compare
=======

Description
-----------
This node compares 2 values using standard mathematical inequalities such as
>,<,<=,>=,=,=! and return ``True`` if it was satisfied and ``False`` if not.

.. image:: images/compare_node.png
   :width: 160pt

Inputs
------

- **A** - The first value.
- **B** - The second value.

Outputs
-------

- **Result** - The resulted boolean.

Advanced Node Settings
----------------------

- **Change Type** - Changes the input type to other data type.

Note
----

- **A != B**
    Means A does not equal to B

- **A is B**
    Unlike A = B, This checks if the inputs are the same object.
    It means if 2 integer lists have the same value and length, it will still
    return ``False`` because they are not the same object even though
    they have the same elements.

Examples of Usage
-----------------

.. image:: gifs/compare_node_example.gif
