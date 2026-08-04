# File Permissions Investigation

## Scenario

A security analyst was asked to review file permissions on a Linux system to ensure that sensitive files were properly protected and executable files had the correct permissions.

---

## Objective

Learn how to view and modify Linux file permissions using the `chmod` command.

---

## Tools Used

- Ubuntu (WSL)
- Linux Terminal
- Bash

---

## Commands Used

```bash
ls -l
chmod 600 confidential.txt
chmod +x script.sh
pwd
```

---

## Investigation Steps

1. Created three files:
   - confidential.txt
   - public.txt
   - script.sh
2. Used `ls -l` to view the default file permissions.
3. Changed `confidential.txt` to permission **600**.
4. Verified the permission change using `ls -l`.
5. Made `script.sh` executable using `chmod +x`.
6. Verified that the executable permission was successfully applied.

---

## Findings

- `confidential.txt` was secured with **600** permissions, allowing only the file owner to read and write the file.
- `public.txt` retained the default permissions, making it readable by other users.
- `script.sh` was successfully changed into an executable file.

---

## Lessons Learned

- How to view Linux file permissions using `ls -l`
- How to secure sensitive files using `chmod 600`
- How to make scripts executable with `chmod +x`
- Why proper file permissions are important for protecting sensitive information

---

## Skills Demonstrated

- Linux Administration
- File Permission Management
- Bash
- Cybersecurity Fundamentals
