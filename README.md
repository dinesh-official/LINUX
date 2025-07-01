
## 🐧 LINUX

### 📁 Directory Structure

| Directory | Description                                                                                                            |
| --------- | ---------------------------------------------------------------------------------------------------------------------- |
| `/`       | Root directory. The top of the directory tree.                                                                         |
| `/bin`    | Essential **binary** executables (e.g., `ls`, `cp`, `mv`) needed for system booting and single-user mode.              |
| `/etc`    | System **configuration files** (e.g., network, user accounts, services).                                               |
| `/home`   | **User home directories**, e.g., `/home/alex`. Each user stores personal files and settings here.                      |
| `/opt`    | **Optional or third-party software** packages (e.g., proprietary software, add-ons).                                   |
| `/tmp`    | **Temporary files**. Cleared on reboot. Often used by programs during execution.                                       |
| `/usr`    | **User-related programs** and data. Contains read-only user utilities and applications (`/usr/bin`, `/usr/lib`, etc.). |
| `/var`    | Variable data like logs and spool files.      |



### 📂 Comparative Directory Listing
| Directory | Description                                                                                 |
| --------- | ------------------------------------------------------------------------------------------- |
| `/bin`    | Essential binaries used in both single-user and multi-user environments.                    |
| `/cdrom`  | Temporary mount point for CD-ROMs. May not be present on all systems.                       |
| `/cgroup` | Control groups filesystem. Used for process/resource management (e.g., CPU, memory limits). |
| `/dev`    | Device files representing hardware or virtual devices (e.g., `/dev/sda`, `/dev/null`).      |
| `/boot`   | Boot-related files such as the Linux kernel (`vmlinuz`), `initrd`, and GRUB configuration.  |
| `/etc`    | System configuration files (e.g., user accounts, services, network settings).               |
| `/lib`        | Essential **shared libraries** for binaries in `/bin` and `/sbin`.                |
| `/lib64`      | 64-bit **shared libraries**, mainly used on 64-bit systems.                       |
| `/lost+found` | Recovered files from disk errors or crashes (used by `fsck`).                     |
| `/media`      | Temporary mount point for **external media** (e.g., USB drives, CDs).             |
| `/export`     | Commonly used as a mount point for **NFS exports** (not standard on all systems). |


---


