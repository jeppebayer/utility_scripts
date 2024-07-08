The 'utility_scripts' directory contains scripts made available for all users who are affiliated with the EcoGenetics centre.
You only need to do the following once to create easy access to the scripts in this folder.

In the command line run the followling:
    echo -e "export PATH=\$PATH:/faststorage/project/EcoGenetics/utility_scripts" >> "$HOME"/.bashrc

then run the following:
    source "$HOME"/.bashrc

You will now have easy access from the command line to some scripts we used at EcoGenetics such as:
    - 'project_setup': Sets up the directory structure for a new project. Use it from your own directory as you start a new project. For help run 'project_setup -h'
    - More to come...
