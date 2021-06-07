.. _launching_a_player:

Launching a player
------------------

.. note::

  This tutorial assumes you have installed `SimSpark`_, `NaoSoccerSim`_, `ROS2 Nao Package`_,
  as well as this package.

To launch the player in SimSpark, first start the simulator:

.. code-block:: console

  rcsoccersim3d

Launch our simulated soccer player:

.. code-block:: console

  ros2 launch team_ijnek_launch simulated_player_launch.py

You should see the robot launched in the simulator as shown below.

.. image:: images/launch_robot.png


.. _SimSpark: https://gitlab.com/robocup-sim/SimSpark/-/wikis/home
.. _NaoSoccerSim: https://github.com/ijnek/naosoccer_sim
.. _ROS2 Nao Package: https://github.com/ijnek/nao