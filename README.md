# rsyncBackupScript

rsync {options} {source} {destination}

in the actual run of the backup script, dont forget to remove the --dry-run option.

works on linux and mac

It is recommended that you backup to an encrypted drive

Read the commented out lines in rsyncScript. Consider uncommenting and running all of the lines the first time, to get the directories and stuff all set up. 

For each subsequent use, run manually by copy pasting the rsync command from rsyncScript, into the terminal

list.txt contains the directories to be backed up, relative to the source path in the rsync command

The Summaries directory contains the text files of the output from each time you run the rsync command to do a backup.
