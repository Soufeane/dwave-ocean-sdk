.. _opt_index_examples_advanced:

=====================
Hybrid Usage Examples
=====================

..  toctree::
    :maxdepth: 1
    :hidden:

    example_nl_cvrp
    example_bqm_structuralimbalance
    example_dqm_map
    example_kerberos_map
    example_dwavehybrid_workflow

For beginner examples, see the :ref:`opt_index_examples_beginner` section.

Nonlinear Models
================

These examples solve small instances of known optimization problems using
the `Leap <https://cloud.dwavesys.com/leap/>`_ service's hybrid
:term:`nonlinear-model <nonlinear model>` solver.

.. grid:: 3
    :gutter: 2

    .. grid-item-card:: :ref:`opt_example_nl_cvrp`
        :link: opt_example_nl_cvrp
        :link-type: ref

        Demonstrates more advanced usage options for solving nonlinear models.

Quadratic Models
================

These examples use the |cloud| service's :term:`quadratic model` solvers.

.. grid:: 3
    :gutter: 2

    .. grid-item-card:: :ref:`opt_example_bqm_structuralimbalance`
        :link: opt_example_bqm_structuralimbalance
        :link-type: ref

        Solves an unconstrained problem using the |cloud| service's hybrid BQM
        solver.

    .. grid-item-card:: :ref:`opt_example_dqm_map`
        :link: opt_example_dqm_map
        :link-type: ref

        Solves a discrete quadratic model (DQM) using the Leap service's hybrid
        DQM solver.

    .. grid-item-card:: :ref:`opt_example_kerberos_map`
        :link: opt_example_kerberos_map
        :link-type: ref

        Demonstrates using a *dwave-hybrid* out-of-the-box hybrid solver.

    .. grid-item-card:: :ref:`opt_example_dwavehybrid_workflow`
        :link: opt_example_dwavehybrid_workflow
        :link-type: ref

        Builds a hybrid workflow and solver for a large random-graph problem.

Demos
=====

D-Wave's `dwave-examples <https://github.com/dwave-examples>`_ GitHub repo
contains many more code examples.

.. grid:: 3
    :gutter: 2

    .. grid-item-card:: `Nurse scheduling <https://github.com/dwave-examples/nurse-scheduling>`_

        Example of constraint-satisfaction problem.

    .. grid-item-card:: `maze <https://github.com/dwave-examples/maze>`_

        Example of constraint-satisfaction problem.

    .. grid-item-card:: `circuit fault diagnosis <https://github.com/dwave-examples/circuit-fault-diagnosis>`_

        Example of constraint-satisfaction problem.

    .. grid-item-card:: `Map coloring <https://github.com/dwave-examples/map-coloring>`_

        Complements similar examples to those presented above.

    .. grid-item-card:: `job-shop scheduling <https://github.com/dwave-examples/job-shop-scheduling-cqm>`_

        Complements similar examples to those presented above.

    .. grid-item-card:: `RNA folding <https://github.com/dwave-examples/rna-folding>`_

        Prototype application.

    .. grid-item-card:: `portfolio optimization <https://github.com/dwave-examples/portfolio-optimization>`_

        Prototype application.

Jupyter Notebooks
=================

These examples, in a web-based interactive environment that includes documentation
and code, are helpful for both walking beginners through the theory and practice
of problem solving and explaining complex features. They can also serve as
a framework in which to develop your own code.

.. grid:: 3
    :gutter: 2

    .. grid-item-card:: `Structural imbalance notebook <https://github.com/dwave-examples/structural-imbalance-notebook>`_

        Complements the :ref:`opt_example_bqm_structuralimbalance` example.

    .. grid-item-card:: `Hybrid computing notebooks <https://github.com/dwave-examples/hybrid-computing-notebook>`_

        These notebooks walk you through using and developing hybrid solvers.

    .. grid-item-card:: `Pegasus notebook <https://github.com/dwave-examples/pegasus-notebook>`_

        Explains a feature of the quantum computer.

    .. grid-item-card:: `reverse annealing notebook <https://github.com/dwave-examples/reverse-annealing-notebook>`_

        Explains a feature of the quantum computer.

