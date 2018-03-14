# run-slackups

How this is intended to work is that you create a slackup.md (Its a standup but we call it a slackup because we post it in slack) and then run `run_slackups` and it creates an html page out of the markdown language. It uses a preformatted html file that uses bootstrap.

You do need to `sudo apt-get install markdown` in order to use this script.

when you first clone the repo, you'll need to run `bash bootstrap.sh` or `mkdir content slackups`

Your slackups need to be formatted like so `2018-03-14.md`

Feel free to help make this to where users can make this more flexible to their liking (changing slackups dir to standups, etc)
