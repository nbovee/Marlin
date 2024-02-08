config files are flagged with "--skip-worktree" to ensure they are not commit as they are updated each time a build occurs
to allow these to be commit, the "--no-skip-worktree" can be used

more specifically the command is:
`git update-index --skip-worktree Marlin/Configuration.h Marlin/Configuration_adv.h`