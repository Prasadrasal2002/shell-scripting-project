# shell-scripting-project

**Step-by-Step Solution:**

Create the Script File:

Open a terminal on your Linux system.
Create a new file named "processrunning.sh" using a text editor like vi or nano

```bash
vi processrunning.sh
```

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

**Execute the Script:**

Run the script on your system:

```bash
./processrunning.sh
```
The script will display a list of all running processes, followed by the total number of processes.


**Review the Output:**


The script will first output a detailed list of running processes using the ps aux command.
It will then count the total number of processes and display this count.
The script will first output a detailed list of running processes using the ps aux command.
It will then count the total number of processes and display this count.




