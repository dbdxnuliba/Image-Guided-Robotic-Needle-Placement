***Post Cloning setup****
After cloning the repository, build the workspace by running the following commands in the terminal

  1. cd rnm_group_2
  2. catkin_make

If the build executes, then you are good to go.

If it fails, you must source your workspace by :

  1. return to root directory 
        -> cd ~
  2.Run the following command on the terminal
        -> gedit .bashrc
  3. A document will open scroll to the bottom of the document and you will find
        -> source /home/rnm/catkin_ws/devel/setup.bash
      Replace this with
         -> source /home/rnm/rnm_group_2/devel/setup.bash
 	Save and close the file.

   4. Now build the workspace
