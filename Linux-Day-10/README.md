# 🐧 Linux Day 10 – Environment Variables

## 📚 Topics Covered

* Environment Variables
* USER Variable
* HOME Variable
* SHELL Variable
* PATH Variable
* Creating Environment Variables
* Displaying Environment Variables

---

## 💻 Commands Practiced

### Display all environment variables

```bash
printenv
```

### Display the current user

```bash
echo $USER
```

### Display the home directory

```bash
echo $HOME
```

### Display the current shell

```bash
echo $SHELL
```

### Display the PATH variable

```bash
echo $PATH
```

### Create a new environment variable

```bash
export COURSE=Linux
```

### Display the new environment variable

```bash
echo $COURSE
```

---

## 📝 My Output

```text
sneha@Sneha-PC:~$ echo $PATH
/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/usr/lib/wsl/lib:/mnt/c/Program Files/WindowsApps/MicrosoftCorporationII.WindowsSubsystemForLinux_2.7.10.0_x64__8wekyb3d8bbwe:/mnt/c/Program Files/Eclipse Adoptium/jdk-21.0.11.10-hotspot/bin:/mnt/c/WINDOWS/system32:/mnt/c/WINDOWS:/mnt/c/WINDOWS/System32/Wbem:/mnt/c/WINDOWS/System32/WindowsPowerShell/v1.0/:/mnt/c/WINDOWS/System32/OpenSSH/:/mnt/c/Program Files/Git/cmd:/mnt/c/Users/sneha/AppData/Local/Programs/Python/Launcher/:/mnt/c/Users/sneha/AppData/Local/Microsoft/WindowsApps:/mnt/c/Users/sneha/AppData/Local/Programs/Microsoft VS Code/bin:/snap/bin

sneha@Sneha-PC:~$ export COURSE=Linux

sneha@Sneha-PC:~$ echo $COURSE
Linux
```

---

## 📸 Output Screenshot

> Add your terminal screenshot here.

Example:

```markdown
![Linux Day 10 Output](images/output.png)
```

---

## 🎯 What I Learned

* Environment variables store system and user information.
* `printenv` displays all environment variables.
* `$USER` shows the logged-in username.
* `$HOME` shows the home directory.
* `$SHELL` shows the current shell.
* `$PATH` contains directories where Linux searches for commands.
* `export` creates an environment variable.
* `echo` displays the value of an environment variable.

---

## ✅ Day 10 Status

**Completed Successfully ✔️**
