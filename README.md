# Bash Script Guide

## Creating a Bash Script

### Step 1: Create the Script
Create a `bash_script.sh` with the following content:

```bash
#!/bin/bash
echo "Hello World"
```

**Note for Windows Users:** When creating bash scripts in Windows, be aware that saving the file might introduce Windows line ending characters (^M), which can cause issues when running the script in Unix-like systems. To avoid this, use a text editor that supports saving files with Unix line endings, like Notepad++ (Edit -> EOL Conversion -> Unix LF).


## Running

To make the script executable:

```bash
chmod +x bash_script.sh
```

Execute:
```bash
./bash_script.sh
```

## Additional Commands

### Checking Script Content
```bash
cat bash_script.sh
```

### Checking Execution Permissions
Checking permissions, make sure the file has executable permissions (there must be an x in the permissions, for example -rwxr-xr-x).
```bash
ls -l bash_script.sh
```