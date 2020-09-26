Welcome to MaxwellExcelWiki's documentation!
============================================

测试1
#######

测试2
*******

测试3
++++++



测试5
::::::::

测试6
-----------

``*13411*``

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   VideoList

.. seealso::

   Module :py:mod:`zipfile`
      Documentation of the :py:mod:`zipfile` standard module.

   `GNU tar manual, Basic Tar Format <http://link>`_
      Documentation for tar archive files, including GNU tar extensions.

.. highlight:: python
   :linenothreshold: 5
   
.. hlist::
   :columns: 3

   * A list of
   * short items
   * that should be
   * displayed
   * horizontally

* this is
* a list

    * with a nested list

      * and some subitems

* and here the parent list continues

term (up to a line of text)
   Definition of the term, which must be indented

   and can even consist of multiple paragraphs

next term
   Description.

This is a normal text paragraph. The next paragraph is a code sample ::

   It is not processed in any way, except
   that the indentation is removed.

   It can span multiple lines.

This is a normal text paragraph again.

>>> 1 + 1
2

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

0000 

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

This is a paragraph that contains `a link`_.

.. _a link: https://domain.invalid/


.. _my-reference-label:

Section to cross-reference
==========================

This is the text of the section.

It refers to the section itself, see :ref:`my-reference-label`.


.. _my-figure:

.. figure:: whatever

   Figure caption

Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_

.. rubric:: Footnotes

.. [#f1] Text of the first footnote.
.. [#f2] Text of the second footnote.

Lorem ipsum [Ref]_ dolor sit amet.

.. [Ref] Book or article reference, URL or whatever.

.. This is a comment.

..
   This whole indented block
   is a comment.

   Still in the comment.


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
