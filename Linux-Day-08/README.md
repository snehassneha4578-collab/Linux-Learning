# Linux Process Management

## Aim

To learn basic Linux process management commands such as viewing processes, monitoring the system, managing background jobs, and terminating processes.

---

## Commands Used

### 1. View Current Processes

```bash
ps
```

### Output

![Output](output1.png)

---

### 2. View All Running Processes

```bash
ps -e
```

### Output

![Output](output2.png)

---

### 3. Monitor the System

```bash
top
```

### Output

![Output](output3.png)

Press **q** to exit.

---

### 4. View Background Jobs

```bash
jobs
```

### Output

![Output](output4.png)

---

### 5. Run a Process in the Background

```bash
sleep 60 &
```

### Output

![Output](output5.png)

---

### 6. Bring the Background Job to the Foreground

```bash
fg
```

### Output

![Output](output6.png)

---

### 7. Stop the Foreground Process

Press:

```text
Ctrl + C
```

### Output

![Output](output7.png)

---

### 8. Suspend a Running Process

Press:

```text
Ctrl + Z
```

### Output

![Output](output8.png)

---

### 9. Resume a Stopped Job in the Background

```bash
bg
```

### Output

![Output](outputday8.png)

---

### 10. Kill a Process

```bash
kill <PID>
```

Example:

```bash
kill 874
```

### Output

![Output](output10.png)

---

## Result

Successfully learned and executed Linux Process Management commands in Ubuntu Linux.
