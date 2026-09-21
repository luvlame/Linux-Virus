# LUH DELETER (Prank Script) 

> ** WARNING: This is a JOKE / PRANK script created for learning purposes only.**
> **DO NOT RUN THIS SCRIPT. It contains a destructive command that will permanently delete files.**
> **The author takes no responsibility for any damage caused by misuse.**

## What This Is

A simple Python GUI application built with **Tkinter** as a learning exercise to practice:
- Building desktop GUIs with Tkinter
- Handling button click events
- Using message boxes (`showinfo`, `showwarning`)
- Understanding how shell commands are called from Python via `os.system()`

The "functionality" is a **joke** — it pretends to delete everything. It is not a real tool and should never be used as one.

## Why It Exists

This was created as a **humorous learning project** to explore how easy it is to call system-level commands from Python — and to understand **why that's dangerous**.

It serves as a reminder of:
- How destructive commands can be triggered accidentally
- Why you should **never run untrusted scripts**
- The importance of **input validation and sandboxing** in real applications

## ⚠️ Critical Warning

```python
os.system("rm -rf ~/test_folder")   # "safe" demo — deletes a test folder
os.system("rm -rf /")               # ☠️ DANGEROUS — attempts to wipe the entire system
