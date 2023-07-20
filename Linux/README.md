# Vi du
drwxr-xr-x
d: filetype (directory)
rwx: quyen cua user
r-x: quyen cua group
r-x: quyen cua others
# Them/Bot quyen cho other/group
```bash
chmod u-x <filepath>
chmod o-x <filepath> # other user - eXecute permission
chmod g+w <filepath> # group + write permission
```
Quy uoc: 4 (for read), 2 (for write), 1 (for execute)
```bash
chmod (-R) 640 <filepath>
```
=> user = 6 = 4+2: rw-
=> group = 4     : r--
=> other = 0     : ---
# Switch to root user
```bash
sudo -i
```
# Add new user
```bash
useradd <username>
```
# Add new group
```bash
groupadd <groupname>
```
# Grant user to group
```bash
usermod -aG <groupname> <username>
```
# View uid/name, group id/name
```bash
id <username>
```