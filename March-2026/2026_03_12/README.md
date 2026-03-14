# 🛠️ Log: March 12, 2026
**Focus:** Terminal Infrastructure & Signal Management

## 🕒 The Incident
* **Crisis:** Encountered an infinite browser refresh loop caused by invalid CSS syntax (`tra`). 
* **Failure Point:** Attempted `Ctrl+C` which failed due to a detached or suspended process (SIGTSTP). 
* **The "Junior" Move:** Deleted the entire project directory to stop the loop.

## 🛠️ The Technical Fix (Architect Protocol)
* **Port Analysis:** Learned to use `lsof -i :8000` to identify zombie PIDs.
* **Process Termination:** Mastered `kill -9 [PID]` and `killall Python` to force-stop background servers.
* **Memory Management:** Executed `sudo purge` to reclaim inactive RAM. Identified memory pressure (82%) caused by "Vampire Apps" (WhatsApp/Spotify).

## 🚩 Lessons Learned
1. **Never delete code to stop a process.** The system is separate from the source.
2. **Git is a Safety Net.** Restore point via `git checkout` is better than a total loss.

