turtlebot_samples
==================================

Collection of miscellaneous samples of `Turtlebot <http://wiki.ros.org/Robots/TurtleBot>`_.

Why not included in turtlebot_apps suite?
------------------------------------------------

See `Discussion <https://github.com/turtlebot/turtlebot_apps/pull/146>`_.

Prerequisite
==============

* (Only tested on) Ubuntu 14.04 64bit. 
* ROS Indigo needs to be installed.

Install
==========

As of June 2016 this package is available only as source (ie. not binary/apt-gettable form) yet.

Install from binary
---------------------

(TBD)

Install from source
---------------------

1. Obtain `turtlebot_samples` package at `github <https://github.com/130s/turtlebot_samples>`_ and build.

::

  $ cd %YOUR_CATKING_WORKSPACE%/src
  $ git clone https://github.com/130s/turtlebot_samples.git
  $ cd %YOUR_CATKING_WORKSPACE%
  $ catkin_make   (or your favorite build tool e.g. `catkin_tools <https://catkin-tools.readthedocs.io/en/latest/index.html>`_)
  $ source devel/setup.bash

Operation
==========

Running frontier_exploration sample
--------------------------------------------

`frontier_exploration <http://wiki.ros.org/frontier_exploration>`_ provides ROS interface for the users to let the robot explore a region you want it to while it's making a map. In a sample available in `turtlebot_samples` you can try the feature of `frontier_exploration` with `Turtlebot` on `Gazebo` simulator. 

Simply running the following launch will start all necessary nodes.

  $ roslaunch turtlebot_samples exploration_gazebo.launch

APIs
========

ROS API
--------

Published Topics
~~~~~~~~~~~~~~~~~~

N/A yet

Services
~~~~~~~~~~~~~~~~~~

N/A yet

Parameters
~~~~~~~~~~~~~~~~~~

N/A yet

Support
==========================

* Questions should be asked on `ROS answer forum <http://answers.ros.org/questions/>`_.
* Pull request is always welcomed :) at `github <https://github.com/130s/turtlebot_samples/pulls>`_.
