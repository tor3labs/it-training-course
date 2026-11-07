# 2. Operating Systems and Windows

2. Operating Systems and Windows 11
Duration: 90 min · Deliverable: OS and process inventory


Learning outcomes

Distinguish hardware, OS, drivers, applications, processes and services;
inspect Windows 11 safely and interpret basic resource indicators.


Theory and examples

1. What an operating system does
An operating system manages CPU time, memory, devices, files, accounts
and networking; it also supplies interfaces used by programs. Windows,
Linux and macOS are examples. It does not replace applications: a browser,
editor or calculator still runs on top of the OS. Some activities happen in the
background without any visible window.

2. Kernel and user applications
The kernel performs privileged coordination of processes, memory and
devices. User applications normally run with restricted permissions and ask
the OS to perform sensitive operations. This separation reduces accidental
damage. It is not a promise that software cannot fail, so updates and
backups remain essential.

3. Programs, processes and threads
A program is stored instructions and resources, for example an installed
browser. A process is a running instance of a program with allocated
resources. Multiple browser tabs may involve several processes; one
process can contain multiple threads. Do not infer that every Task Manager
item is suspicious because it is unfamiliar.

4. Device drivers
Drivers translate operating-system requests into operations understood by
particular devices. Windows may install approved drivers automatically, but
not every device has all optional functions. A driver issue may appear in
Device Manager as a warning. Prefer Windows Update or the actual device
manufacturer over third-party driver packs.

5. Memory and process scheduling
Windows shares processor time between processes and allocates memory
for their data. CPU percentage is a momentary measurement; memory
marked cached is not necessarily wasted. A background task may

---

legitimately use resources while performing maintenance or updates.
Observe trends before claiming a problem.

6. Services and startup items
A service is a background component that may run without its own window.
Services can support networking, updates, printing or time synchronization.
Startup applications may launch after sign-in; their presence can affect
startup responsiveness. Identifying an item is safer than disabling it blindly.

7. Updates and restarts
System updates can deliver security fixes, drivers and stability
improvements. Some components cannot be replaced while they are in
active use; a restart completes the transition. Save documents before
updates. Avoid forcing a power-off just because an update takes longer
than expected.

8. Windows 11 editions and tools
Windows 11 Home and Pro share many tools but have different management
features. Settings → System → About shows edition and version; Task
Manager shows processes; winver shows the OS build; msinfo32 shows
system information. Use these built-in tools to learn the system before
adding third-party utilities.


Knowledge check

Choose one answer for questions 1–6. Answer questions 7–8 in your own
words. Explanations are collected at the end of Stage 1.

 1. What is the primary responsibility of an operating system? A) Draw
    windows only B) Manage resources and provide services to
    applications C) Replace all user applications D) Work only while
    connected to the internet

 2. What is a process? A) A running instance of a program B) Only an .exe
    file on disk C) A storage partition D) A keyboard shortcut

 3. What does Task Manager normally display? A) Room temperature only
    B) The PC case model only C) CPU and RAM usage by processes D) A
    list of product license keys

 4. Why are device drivers needed? A) To store photos B) To
    communicate with a particular hardware device C) To replace the
    power supply D) To compress files

 5. What should you do about an unfamiliar process using resources? A)
    End it immediately B) Delete the Windows directory C) Disable
    protection D) Identify it and collect evidence first

---

6. How does a program differ from a process? A) A program is stored
    code; a process is a running instance B) Only games have processes C)
    A process is physical hardware D) Both mean any file

 7. Give an example of a Windows service and explain why it may have no
    window.

 8. Why may Windows require a restart after installing updates?


Guided practice on a computer

A. A. Identify Windows

 1. Press Win + R, type winver , record the displayed release/build without
    serial numbers.
 2. Open Settings → System → About and record the edition, architecture
    and RAM.
 3. Use msinfo32 to find system information; mark unavailable fields as
    unknown.

Completion criteria: Edition and version are identified from actual system
screens.

B. B. Observe a process

 1. Open Task Manager → Processes and locate a familiar application.
 2. Note its CPU and memory use at idle; open a document or browser tab
    and observe changes.
 3. Record three observations and one interpretation that remains only a
    hypothesis.

Completion criteria: Facts and guesses are clearly separated.

C. C. Inspect startup and services without changing them

 1. Open Task Manager → Startup apps and list two recognizable items.
 2. Press Win + R → services.msc (if available); identify a known service
    and read its description.
 3. Close the tools without disabling services or changing startup entries.

Completion criteria: The student describes purposes rather than blindly
stopping components.


Independent task

Explain a path from opening an application icon to its process using CPU
and RAM. Name the role of the OS.

---

Homework

Submit a short windows-report.md with OS edition/build, a process
observation and an example of a background service; avoid personal
identifiers.

Optional challenge: Compare two different causes of high CPU utilization
and explain how you would differentiate them.
