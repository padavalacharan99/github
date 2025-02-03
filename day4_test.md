
# Linux Basic Commands - Advanced Tasks

## File and Directory Management

1. **Change to the Parent Directory**  
   - Move to the parent directory from the current location.  
   
   **Answer:**  
   cd ..
# Student's Answer Here
```

2. **List Hidden Files**  
   - List all hidden files and directories in the current directory.  
   
   **Answer:**  
   ls -a
# Student's Answer Here
```

3. **Remove a Directory**  
   - Delete a directory named `oldfolder` from the current location.  
   
   **Answer:**  
   mkdir oldfolder
   rmdir oldfolder
# Student's Answer Here
```

4. **Create a Directory Structure**  
   - Create a directory structure `/home/user/project/src/` using one command.  
   
   **Answer:**  
   mkdir -p /home/user/project/src/

# Student's Answer Here
```

5. **Check Disk Space for a Specific File**  
   - Display the disk space usage of `largefile.tar`.  
   
   **Answer:**  
   touch largefile.tar
    du -h largefile.tar
# Student's Answer Here
```

6. **Show Available Space on All Mounted Filesystems**  
   - Display the available space on all mounted filesystems in a human-readable format.  
   
   **Answer:**  
   df -h
# Student's Answer Here
```

7. **Edit a File Using Vim**  
   - Open `readme.txt` with Vim editor.  
   
   **Answer:**  
   vim readme.txt
   i for insert esc and :wq save and exit

# Student's Answer Here
```

8. **Move Multiple Files**  
   - Move `file1.txt`, `file2.txt`, and `file3.txt` from `/home/user/documents/` to `/home/user/backup/`.  
   
   **Answer:**  
   mkdir -p /home/user/backup/
# Student's Answer Here
```

9. **Copy Files Recursively**  
   - Copy all files and subdirectories from `/home/user/docs/` to `/home/user/docs_backup/`.  
   
   **Answer:**  
   cp -r /home/user/docs /home/user/docs_backup/`.
# Student's Answer Here
```

10. **Create a File with a Specific Size**  
    - Create a file named `largefile.txt` with a size of 1GB.  
   
    **Answer:**  
    dd if=/dev/zero of=largefile.txt bs=1M count=1024
# Student's Answer Here
```

11. **Display the Last Few Lines of a File**  
    - Show the last 10 lines of `server.log`.  
   
    **Answer:**  
  touch server.log
  echo "log file created" server.log    
  tail -n 10 server.log
# Student's Answer Here
```

12. **Search for a File**  
    - Find a file named `config.yaml` within `/etc/`.  
   
    **Answer:**  
   sudo touch config.yaml
   sudo find /etc/ -name config.yaml 
# Student's Answer Here
```

13. **Search for a Pattern in a Directory**  
    - Search for the word "failed" in all `.log` files within `/var/log/`.  
   
    **Answer:**  
    sudo grep -i "failed" /var/log/*.log
# Student's Answer Here
```

14. **Print the Current Working Directory**  
    - Display the absolute path of the current working directory.  
   
    **Answer:**  
    pwd
# Student's Answer Here
```

15. **Create an Empty File Using the `touch` Command**  
    - Create an empty file named `emptyfile.txt`.  
   
    **Answer:**  
   touch emptyfil.txt
# Student's Answer Here
```

16. **Count the Number of Lines in a File**  
    - Count the number of lines in `script.sh`.  
   
    **Answer:**  
    touch script.sh
    wc l script.sh
# Student's Answer Here
```

17. **Initialize a Git Repository**  
    - Initialize a new Git repository in the current directory.  
   
    **Answer:**  
    git init
# Student's Answer Here
```

18. **Clone a Git Repository Using SSH**  
    - Clone a Git repository using SSH from GitHub.  
   
    **Answer:**  
    git clone ssh url
# Student's Answer Here
```

19. **View the Git Commit Log**  
    - Display the commit history of the repository.  
   
    **Answer:**  
    git log
# Student's Answer Here
```

20. **Check the Status of a Git Repository**  
    - Check the current status of your Git repository.  
   
    **Answer:**  
    git status
# Student's Answer Here
```

21. **Stage a Single File in Git**  
    - Stage the file `update.sh` for commit.  
   
    **Answer:**  
    git add .
# Student's Answer Here
```

22. **Commit Changes with a Specific Message**  
    - Commit the staged changes with the message "Initial commit".  
   
    **Answer:**  
    git commit -m "file name" 
# Student's Answer Here
```

23. **Push Changes to a Remote Repository**  
    - Push committed changes to the `main` branch of a remote repository.  
   
    **Answer:**  
   git push
# Student's Answer Here
```

24. **List All Running Processes**  
    - List all the currently running processes.  
   
    **Answer:**  
    ls -la
# Student's Answer Here
```

25. **Find Processes by Name**  
    - Find all processes with the name `nginx`.  
   
    **Answer:**  
    ps aux | grep nginx
# Student's Answer Here
```

26. **Kill a Process by PID**  
    - Terminate the process with PID `12345`.  
   
    **Answer:**  
    ps -p 12345
    pgrep
    ps aux
    kill 12345
# Student's Answer Here
```

27. **Check System Uptime**  
    - Display the system uptime (how long the system has been running).  
   
    **Answer:**  
    uptime
# Student's Answer Here
```

28. **Monitor Real-Time System Performance**  
    - Use a command to monitor system performance in real time (CPU usage, memory, etc.).  
   
    **Answer:**  
    top
# Student's Answer Here
```

29. **Check System Load Average**  
    - Display the system load average for the past 1, 5, and 15 minutes.  
   
    **Answer:**  
    uptime
# Student's Answer Here
```

30. **Display System Information**  
    - Display detailed information about the system (OS, kernel version, etc.).  
   
    **Answer:**  
    uname -a
# Student's Answer Here
```

31. **Check Available Memory**  
    - Display the available physical and swap memory on the system.  
   
    **Answer:**  
    free -h
# Student's Answer Here
```

32. **Check Network Interface Configuration**  
    - Display the network interface configuration for the system.  
   
    **Answer:**  
    ip a
# Student's Answer Here
```

33. **Check Listening Ports**  
    - Display all the listening network ports on the system.  
   
    **Answer:**  
    ss -tuln
# Student's Answer Here
```

34. **Check for Active User Sessions**  
    - Display all active user sessions on the system.  
   
    **Answer:**  
    who
    w
    whoami
# Student's Answer Here
```

35. **Display Disk Usage of the Home Directory**  
    - Display the disk usage of `/home/` in a human-readable format.  
   
    **Answer:**  
    du -sh /home/
# Student's Answer Here
```

36. **View a Specific System Log**  
    - Display the last 50 lines of the system log file `/var/log/syslog`.  
   
    **Answer:**  
    sudo tail -n 50 /var/log/syslog`.
# Student's Answer Here
```

37. **Change File Permissions for a Specific User**  
    - Change the permissions of `testfile.txt` to be read and write for the owner only.  
   
    **Answer:**  
    touch testfile.txt
    chmod 600 testfile.txt
    ls -l testfile.txt
# Student's Answer Here
```

38. **Change File Ownership**  
    - Change the ownership of `backup.sql` to user `admin`.  
   
    **Answer:**  
    sudo useradd -g admin admin
    sudo passwd admin
    sudo chown admin backup.sql
    sudo chown charan backup.sql
# Student's Answer Here
```

39. **Create a Symbolic Link to a File**  
    - Create a symbolic link to the file `data.txt` named `data_link.txt`.  
   
    **Answer:**  
    ln -s data.txt data_link.txt
    to verifi ls -l data_link.txt
# Student's Answer Here
```

40. **View System Kernel Version**  
    - Display the current kernel version of the system.  
   
    **Answer:**  
    uname -r
# Student's Answer Here
```

41. **Monitor Disk I/O in Real-Time**  
    - Monitor disk input/output statistics in real-time.  
   
    **Answer:**  
    sudo apt update
    sudo apt istall systat
    iostat x 1
# Student's Answer Here
```

42. **Change User Password**  
    - Change the password for the user `johndoe`.  
   
    **Answer:**  
    sudo useradd johndoe
    sudo passwd johndoe

# Student's Answer Here
```

43. **Create a Cron Job**  
    - Create a cron job that runs a backup script every day at midnight.  
   
    **Answer:**  
    crontab -e
# Student's Answer Here
```

44. **Check for Open File Descriptors**  
    - List all open file descriptors on the system.  
   
    **Answer:**  
    sudo lsof
# Student's Answer Here
```

45. **Create a Compressed Archive**  
    - Create a compressed `.tar.gz` archive of the directory `/home/user/documents/`.  
   
    **Answer:**  
    tar -czvf documents.tar.gz /home/user/documents/
# Student's Answer Here
```

## Submission Instructions
For each task, students must:
- Write down the exact commands they used.
- Provide a screenshot or file output where required.
