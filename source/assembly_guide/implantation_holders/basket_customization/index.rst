.. _assembly-metal-basket-customization:

Basket customization
====================

The supplied basket is a generic basket that fits many high-density connectors. You can adapt the basket system to your probe in two ways. The standard basket is in the `3Dneuro connector-basket repository <https://github.com/3Dneuro/r2-metal-implantation-system/tree/main/connector_baskets>`__ as STL, STEP and Fusion 360 files. More designs will follow there.

Option 1: modify or print your own basket
-----------------------------------------

#. Download the STL, or modify it for your connector/EIB. Keep the interface to the rod (Ø1.75 mm bore, M3 set-screw hole) unchanged, and change only the part that holds the connector.
#. Print it at 100% scale and remove all support material. If the M3 thread did not print cleanly, cut it with an M3 tap.
#. Check that the basket slides onto its rod without play and without force.
#. Loosen the set screw that holds the old basket, slide it off, slide the new one on, set its height and tighten the set screw.

Option 2: modify the 1.5 mm stainless-steel rod
-----------------------------------------------

- **Length:** cut a shorter rod, or use a longer one, to match the length of your probe's flex cable.
- **Shape:** bend the rod to bring the connector to a different position, for example to clear other implants or to route the flex cable more gently. If you opt for bending, you might want to replace the stainless steel rod by a softer metal rod (for example, copper).

After modifying the rod, check that it still passes through its sleeve or holder and that the basket can still slide far enough to tension the flex cable.

.. tip::

   Try a new basket or rod shape with a dummy connector or old probe before using it with a real probe.

See :ref:`user-manual-metal-custom-baskets` in the manual for choosing a basket.

.. admonition:: Tip: pay it forward
   :class: tip

   If you developed a new basket holder design, `get in touch <mailto:contact@3dneuro.com>`__ or create a pull request in the `git repository <https://github.com/3Dneuro/r2-metal-implantation-system/>`__, and we will add it to our git repository and the documentation to make it available to the broader research community!
