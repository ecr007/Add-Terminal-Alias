# Add-Terminal-Alias

<h3><span id="step_3_determine_which_shell_you_are_using">Step 3: Determine which shell you are using.</span></h3>

```echo $SHELL```

For most newer systems, you will probably be using zshell, so you will see a zsh, but if you are using bash shell, you will see bash. For our example below, we will use zsh.

<img src="img-1.png" />

<h3><span id="step_4_open_the_shell_profile_file">Step 4: Open the shell profile file.</span></h3>

For bash shell, the file would be .bash_profie, and for zshell (as in our example), the file is .zprofile. Since these files are hidden, you will have to use the -a parameter if you want to see them in the directory with the ls command. 

Use the nano command to open the file in the nano editor.

nano .zprofile

<img src="img-2.png" >

<h3><span id="step_5_add_the_alias_commands_to_the_file">Step 5: Add the alias commands to the file.</span></h3>

Once you open the file, use the cursor arrows to move to the bottom, then add your alias command to the end of the file. 

<img src="img-3.png" >

<h3><span id="step_6_exit_terminal_and_restart_it">Step 6: Exit Terminal and restart it.</span></h3>

Exit the Terminal altogether. When you restart Terminal, your alias command will take effect.
