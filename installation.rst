Installation
############

.. note::

    Instructions here assume that you have and are in the ROS2 workspace
    root directory.

Cloning repositories
********************

In your ROS2 workspace, clone the repository:

.. code-block:: console

   git clone https://github.com/ijnek/team_ijnek.git src/team_ijnek
   vcs import src < src/team_ijnek/dependencies.repos --recursive

Building
********

To build the package and its dependencies, in the workspace root directory, run:

.. code-block:: console

   colcon build
