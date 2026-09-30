# Secure File Management & User Configuration — Kali Linux

A GitHub-ready submission workspace for the practical task **"Secure File Management & User Configuration on Kali Linux."**

## Task objective

Demonstrate fundamental Linux file-system and user-management commands by creating a dedicated `agent007` workspace, organizing files, applying permissions, copying/removing files, recovering a deleted backup, and observing ownership changes.

> **Important:** This repository contains the workflow and documentation only. It does **not** claim that the commands have been executed. Evidence files are intentionally left for the student to populate from their own Kali Linux lab.

## Source requirements covered

The workflow follows the uploaded task's requirements, including:
- Create `agent007` with a home directory and `/bin/bash`.
- Add `agent007` to the `sudo` group.
- Set the user's password and switch to `agent007`.
- Perform the file operations as `agent007`; the task specifically allows `useradd` and `usermod` as exceptions.
- Build `/home/agent007/mission/intel` and `/home/agent007/mission/ops/backup`.
- Create `targets.txt`, `routes.txt`, and `keys.txt`.
- Capture `ls`, `ls -l`, and `ls -la` outputs into `listing1.txt`, `listing2.txt`, and `listing3.txt`.
- Copy `routes.txt` to `backup/`, remove `keys.txt`, set `targets.txt` to owner read/write, group read-only, others no permissions.
- Remove the backup copy and recover it by copying from `intel/`.
- As root, change ownership of `targets.txt` to another user such as `root`, then switch back to `agent007` and observe the result.
- Submit command history, final recursive listing, and a 4–5 line explanation of `chmod`, `ls -l`, and `useradd`.

See `docs/WORKFLOW.md` for the step-by-step procedure and `commands/command-history.txt` for the command sequence.
