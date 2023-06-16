^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package hri_actions_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.4.2 (2023-06-16)
------------------
* Revert "add actions to start/stop ASR"
  This reverts commit bbd9646771a5ba4ac6e680c1c2e036f4b4730fa6.
* Contributors: Séverin Lemaignan

0.4.1 (2023-01-17)
------------------
* add actions to start/stop ASR
* Contributors: Séverin Lemaignan

0.4.0 (2023-01-03)
------------------
* string constants should not use quotes
  While here:
  - remove a spurious comment on one of the comments lines
  - prefix moadlity string constants with __modality\_ for consistency
* Contributors: Séverin Lemaignan

0.3.2 (2022-12-05)
------------------
* Simple action to control (start/stop) applications
* Contributors: Séverin Lemaignan

0.3.1 (2022-12-05)
------------------
* Intent.msg: rename the field 'action' to 'intent' to avoid confusion
* Contributors: Séverin Lemaignan

0.3.0 (2022-12-02)
------------------
* add intents via Intent.msg
  'Intents' represents actions that a user (or sometimes, the robot
  itself) wants to be performed by the robot.
  They are used to decouple the user intent perception from the robot
  controller.
  The Intent.msg specifies an abstract model for these intents.
* Contributors: Séverin Lemaignan

0.2.0 (2022-08-18)
------------------
* add LookAtWithStyle.msg
* Contributors: Séverin Lemaignan

0.1.0 (2022-06-28)
------------------
* stamp PointTrajectory
* add PointTrajectoryAction
* add gaze action
* Contributors: Sara Cooper, Luca Lach
