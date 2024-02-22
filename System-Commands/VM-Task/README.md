# Welcome to the System Commands VM

## Get started with the course VM

- Your VM assignments can be found at the directory `/opt/se2001/<assignment_name>/`

- Your solution has to be present in directory `~/se2001/<assignment name>/`

- Once you have completed the assignment specified in the `/opt/se2001/<assignment_name>/README.md`, you have to run `synchro eval` from the respective assignment directory `~/se2001/<assignment name>/`

- If you get the below output, your code is passed and your submission is recorded.

```
Evaluation Successful.
Submission Successful.
```

- Other useful packages installed
  - `tmux` a terminal multiplexer useful in splitting the terminal, recover your terminal session even when you disconnected from VM.
  - `batcat` a rust based alternative to `cat` that will display the file contents with color

## FAQ

- I don't have the directory `se2001` in my home directory. What should I do?
  - Create the directory with `mkdir ~/se2001`

- How to reset my password?
  - It will work only if you already have a password, otherwise the below won't work.
  - Execute the command `passwd` and provide your current password and new password as per the prompt.
  - The password typed will not be visible during and after the input.

- How to reset my password if I forgot mine?
  - Send a mail to se2001@study.iitm.ac.in with subject `SE2001 VM PASSWORD RESET`

- I am getting `Evaluation failed.` in my output, what should I do?
  - Submission failed means that your task is not completed properly, verify your script with the problem statement in `/opt/se2001/<assignment_name>/README.md`.

- I am getting `Submission failed.` in my output, what should I do?
  - Submission failed means that your activity is not recorded, contact us through email/discourse.

## For other queries

- Search for the relevant discourse post and comment on it, if there is no relevant then create one and assign the tag `vm`