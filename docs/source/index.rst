Welcome to Lumache's documentation!
===================================

**Lumache** (/lu'make/) is a Python library for cooks and food lovers
that creates recipes mixing random ingredients.
It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API. It is actually quite fun! And a source of never-ending amusement!

Now, let's step into a far more serious business and try to typeset some interesting math.
Inlined, it will look like :math:`\sin(\theta)^2 + \cos(\theta)^2 = 1`, which is not that bad. On the
other hand, one may also have it displayed by its own as in

.. math::

   \nabla \times \mathbf{B} = \mu_0 \mathbf{J}, \quad \partial_t \mathbf{B} = \nabla \times \mathbf{E},

   \nabla p = \mathbf{J} \times \mathbf{B}, \nabla \cdot \mathbf{B} = 0, \frac{d}{dt} \rho p^\gamma = 0

Now, let's play a bit with domains, beginning with the standard one. Assume we are dealing with a command-line application configured by options.

.. option:: -elapsed

   Prints the elapsed time to stdout.

.. option:: -qu=..., -qv=..., -qw=...

   Initial position in the coordinate system and units as defined by the respective `field_box_t` object.

And what if one sticks to a markdown kind of formatting options lists? The output would be something like the following.

+ `-elapsed` Prints the elapsed time to stdout.
+ `-energy=..., -pitch=...`
   Initial kinetic energy (measured in eV) and pitch (ie., the ratio :math:`v_\parallel/v` of the
   parallel to the total velocity).
+ `-qu=..., -qv=..., -qw=...`

   Initial position in the coordinate system and units as defined by the respective `field_box_t` object.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
