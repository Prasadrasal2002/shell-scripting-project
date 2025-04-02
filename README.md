# shell-scripting-project

**Step-by-Step Solution:**

Create the Script File:

Open a terminal on your Linux system.
Create a new file named "processrunning.sh" using a text editor like vi or nano

```bash
vi processrunning.sh
```

![image](https://github.com/user-attachments/assets/5a28973e-58db-48b6-9452-8500ab313cc7)


**Write the Script:**

Add the following lines to the file:

```bash
#!/bin/bash
echo "Displaying all running processes:"
ps aux
echo "Total processes running: $(ps aux | wc -l)"
```

**Make the Script Executable:**

Change the permissions of the script to make it executable:

```bash
chmod +x processrunning.sh
```

![image](https://github.com/user-attachments/assets/0b93debf-a851-4f02-a2d6-382ccd0b304b)


**Execute the Script:**

Run the script on your system:

```bash
./processrunning.sh
```
The script will display a list of all running processes, followed by the total number of processes.

![image](https://github.com/user-attachments/assets/c2a71ffb-8396-4882-8848-cd8d364687f6)



**Review the Output:**


The script will first output a detailed list of running processes using the ps aux command.

It will then count the total number of processes and display this count.

The script will first output a detailed list of running processes using the ps aux command.

It will then count the total number of processes and display this count.

![image](https://github.com/user-attachments/assets/1f5aeb21-b552-426f-8352-d43c631bf453)





