
# 🧭 Terminal Survival Cheat Sheet

Write commands here **in your own words** as you use them!

| Command | What It Actually Does | Example / Notes |
| --- | --- | --- |
| `pwd` | Shows what folder I'm currently standing in | Print Working Directory |
| `ls -la` | Lists everything in the folder, including hidden `.` files and permissions | Use `-lh` for human-readable file sizes |
| `cd` | Moves into a different directory | `cd ..` goes up one level; `cd ~` goes home |
| `cat` | Dumps the contents of a file onto the screen | Best for short files |
| `less` | Opens a file for scrolling without editing | Press `q` to quit! |
| `history` | Shows every command I've typed recently | Pair with `grep` to find old commands |
| EOF |  |  |

# 3. Lab Mission Issue Template

## cat << 'EOF' > .github/ISSUE_TEMPLATE/lab_mission.md

## name: "🧪 Lab Mission"
about: "A structured 30-45 minute hands-on Linux or Cloud lab"
title: "[Mission] "
labels: ["lab-mission"]

## 🎯 Scenario & Why It Matters in the Cloud

## 🛠️ Mission Objectives

* [ ] Objective 1
* [ ] Objective 2
* [ ] Document the commands used in `labs/` or `cheatsheets/`

## 💡 Commands & Tools to Explore

* `command1`
* `command2`

## ✅ Verification (How You Know It Worked)

