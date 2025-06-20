## Challenge Description
You’re a cybersecurity analyst investigating a server’s activity logs in the `server.log` file. 
One user did something sneaky and left a flag behind!
Your goal is to analyze the `server.log` file and find the temporary `FLAG{...}`. 
This user broke up the flag into 3 parts all contained within the same `server.log` file - you'll need all three pieces!

_Server log files_ are automatically generated by a server (a big computer), and keep track of activity and events! 
Things like users logging in and out, uploading files, user navigation, etc.

In this challenge, you can simply browse through the log file until you find something useful, but it will take quite a while.
Don't get fooled by the fake flags! (`FLAG{FAKE FLAG}`)
Try using a tool like `grep`, and play around with different strings to search for! 
Maybe find the user who uploaded the real flag and search for their log entries.
You will have to do some digging no matter what, but you can narrow down the entries to search through.

Users that have access to this server - `users = ['alice', 'charlie', 'diana', 'bob', 'eve', 'frank', 'grace', 'heidi']`.

## Challenge Steps
1. Navigate to the `/home/ubuntu/Chatty-Server` directory
2. Search through the `server.log` file until you find the temporary `FLAG{...}` (three words separated by underscores)
3. Run `/challenge/verify`, enter the temporary `FLAG{...}`, and receive your official `pwn.college{...}` flag!
