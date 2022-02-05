# PIC18_notes
Problems meet in ECM

#################################### ERROR-1 ##########################################
when build target in MPLAB IDE, error: "*** no rule to make target '.build-imp1' .... "
#######################################################################################
Solution: 
1. move to 'project' select designated project.
2. right click choose 'Properties', which should appear in the bottom of the menu.
3. in 'connect to hardware tool...' choose 'PICkit4...', then close it
4. click 'clean and build' or 'make device main project'
