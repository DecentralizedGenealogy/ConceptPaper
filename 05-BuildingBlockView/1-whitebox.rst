########################################
    Whitebox Overall System
########################################

========================================
    Meta
========================================

Here you describe the decomposition of the overall system using the
following white box template. It contains

-  an overview diagram

-  a motivation for the decomposition

-  black box descriptions of the contained building blocks. For these we
   offer you alternatives:

   -  use *one* table for a short and pragmatic overview of all
      contained building blocks and their interfaces

   -  use a list of black box descriptions of the building blocks
      according to the black box template (see below). Depending on your
      choice of tool this list could be sub-chapters (in text files),
      sub-pages (in a Wiki) or nested elements (in a modeling tool).

-  (optional:) important interfaces, that are not explained in the black
   box templates of a building block, but are very important for
   understanding the white box. Since there are so many ways to specify
   interfaces why do not provide a specific template for them. In the
   worst case you have to specify and describe syntax, semantics,
   protocols, error handling, restrictions, versions, qualities,
   necessary compatibilities and many things more. In the best case you
   will get away with examples or simple signatures.

**<Overview Diagram>**

Motivation
   *<text explanation>*

Contained Building Blocks
   *<Description of contained building block (black boxes)>*

Important Interfaces
   *<Description of important interfaces>*

Insert your explanations of black boxes from level 1:

If you use tabular form you will only describe your black boxes with
name and responsibility according to the following schema:

+-----------------------+-----------------------------------------------+
| **Name**              | **Responsibility**                            |
+=======================+===============================================+
| *<black box 1>*       |  *<Text>*                                     |
+-----------------------+-----------------------------------------------+
| *<black box 2>*       |  *<Text>*                                     |
+-----------------------+-----------------------------------------------+

If you use a list of black box descriptions then you fill in a separate
black box template for every important building block . Its headline is
the name of the black box.

.. _`__name_black_box_1`:

<Name black box 1>
~~~~~~~~~~~~~~~~~~

Here you describe <black box 1> according the the following black box
template:

-  Purpose/Responsibility

-  Interface(s), when they are not extracted as separate paragraphs.
   This interfaces may include qualities and performance
   characteristics.

-  (Optional) Quality-/Performance characteristics of the black box,
   e.g.availability, run time behavior, ….

-  (Optional) directory/file location

-  (Optional) Fulfilled requirements (if you need traceability to
   requirements).

-  (Optional) Open issues/problems/risks

*<Purpose/Responsibility>*

*<Interface(s)>*

*<(Optional) Quality/Performance Characteristics>*

*<(Optional) Directory/File Location>*

*<(Optional) Fulfilled Requirements>*

*<(optional) Open Issues/Problems/Risks>*

.. _`__name_black_box_2`:

<Name black box 2>
~~~~~~~~~~~~~~~~~~

*<black box template>*

.. _`__name_black_box_n`:

<Name black box n>
~~~~~~~~~~~~~~~~~~

*<black box template>*

.. _`__name_interface_1`:

<Name interface 1>
~~~~~~~~~~~~~~~~~~

…

.. _`__name_interface_m`:

<Name interface m>
~~~~~~~~~~~~~~~~~~
