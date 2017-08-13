=========
Searching
=========

Learning searching algorithms easily!

Quick Start Guide
-----------------

.. code-block:: python

    # import the required searching algorithm
    from pygorithm.searching import binary_search

    myList = [12, 4, 2, 14, 3, 7, 5]

    # pre-requisite for binary search is that the list should be sorted
    myList.sort()

    # to search an element in the above list
    index = binary_search.search(myList, 7)
    print(index)

Features
--------

* Searching algorithms available:
    - Linear Search (linear_search)
    - Binary Search (binary_search)
    - Breadth First Search (breadth_first_search)
    - Depth First Search (depth_first_search)

* To see all the available functions in a module there is a `modules()` function available. For example,

.. code:: python

    >>> from pygorithm.searching import modules
    >>> modules()
    ['binary_search', 'breadth_first_search', 'depth_first_search', 'linear_search']

* For Searching:
  Remember ``search()`` function in `binary_search` module takes two parameters as a sorted list and the target element to be searched.

.. code-block:: python

    # import the required searching algorithm
    from pygorithm.searching import binary_search

    myList = [12, 4, 2, 14, 3, 7, 5]

    # pre-requisite for binary search is that the list should be sorted
    myList.sort()

    # to search an element in the above list
    index = binary_search.search(myList, 7)
    print(index)

* Get time complexities of all the searching algorithms

.. code-block:: python

    from pygorithm.searching import binary_search

    # for printing time complexities of binary_search
    print(binary_search.time_complexities())

* Get the code used for any of the algorithm

.. code-block:: python

    from pygorithm.searching import binary_search

    # for printing the source code of binary_search
    print(binary_search.get_code())


Binary Search
-------------

* Functions and their uses

.. function:: binary_search.search(List, key)

- **List**            : *Sorted* list in which the key is to be searched
- **key**             : key to be searched in the list
- **Return Value**    : returns the position (index) of the key if key found, else returns -1

.. function:: binary_search.time_complexities()

- **Return Value**    : returns time complexities (Best, Average, Worst)

.. function:: binary_search.get_code()

- **Return Value**    : returns the code for the ``binary_search.search()`` function

Linear Search
-------------

* Functions and their uses

.. function:: linear_search.search(List, key)

- **List**            : the list in which item is to searched
- **key**             : key to be searched in the list
- **Return Value**    : returns the position (index) of the key if key found, else returns -1

.. function:: linear_search.time_complexities()

- **Return value**      : returns time complexities (Best, Average, Worst)

.. function:: linear_search.get_code()

- **Return Value**      : returns the code for the ``linear_search.search()`` function

Breadth First Search
--------------------

* Functions and their uses

.. function:: breadth_first_search.search(graph, startVertex)

- **graph**           : takes the graph data structures with edges and vertices
- **startVertex**     : it tells the function the vertex to start with
- **Return Value**    : returns the bfs for the ``graph``

.. function:: breadth_first_search.time_complexities()

- **Return Value**    : returns time complexities

.. function:: breadth_first_search.get_code()

- **Return Value**    : returns the code for the ``breadth_first_search.search()`` function

Depth First Search
------------------

* Functions and their uses

.. function:: breadth_first_search.search(graph, start, path)

- **graph**           : takes the graph data structures with edges and vertices
- **start**           : it tells the function the vertex to start with
- **path**            : returns the list containing the required dfs
- **Return Value**    : returns the bfs for the ``graph``

.. function:: breadth_first_search.time_complexities()

- **Return Value**    : returns time complexities

.. function:: breadth_first_search.get_code()

- **Return Value**    : returns the code for the ``depth_first_search.search()`` function
