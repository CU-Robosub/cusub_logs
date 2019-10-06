# 10/5/19
* update sub's branch to develop
* merge conflict when pulling develop
* need to reclone repo b/c of broken tree @soroush
* gscam failed - touch CATKIN_IGNORE in directory to ignore the uneeded pkg
* BUG: localizer Detection.h failed -> debugging required (after all pkg catkin build failed and specific localizer catkin build failed, fixed by commenting out the Test file executables in CMakeLists.txt and executing another specific localizer catkin build)
* Full build successful
* connection with sub through tether working (didn't work during the week)
* MISSING: calibration sheet
* REORIENTED_GOAL: verify old roulette net working
* REORIENTED_GOAL: add optical flow to roulette net
* REORIENTED_GOAL: gather sg data (&fail cases) using old approach for comparison with detection tree implementation
* REORIENTED_GOAL: gather dropper data (& fail cases) using old approach for comparison with z-plane localizer
* BROKEN: depth sensor (no publication to depth odom)
* changed ekf to use dvl depth
* BUG: ImportError: No module named bangbang_dice_task -> comment out all bangbang & debug servo in smach_top.py
* Made diveday checklist
* BUG: common hangs in killing
* BUG: leviathan_description? sub model files?
* BUG: no odometry messages coming out of ekf, but all sensor topics going in working
* BUG: what is FATAL [1 1 1 1 1 1] in launching cusub_common
* Attempted replacing cusub_sim folder with old cusub_sim folder
* FIXED: odometry bug

Summary
Had to change plans since we lost calibration sheet
Sub's repo fixed and teleop function capable
Recorded data for the detection tree in ~/bags/dvector
Made a diveday checklist on Adam's phone

Todos
* Create new calibration sheet
* Integrate optical flow completely into darknet pipeline
* Use dvector data to create a detection tree
-------------------------------------------------------------------
