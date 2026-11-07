# 6. Computer Diagnostics

6. Computer Diagnostics and
Troubleshooting
Duration: 90 min · Deliverable: evidence-based diagnostic report


Learning outcomes

Describe a fault precisely, collect observations using built-in Windows tools,
distinguish correlation from cause, and recommend safe reversible checks.


Theory and examples

1. Diagnosis begins with symptoms
“The computer is slow” is not an actionable diagnosis. Ask when the
problem occurs, which application is affected, whether it started recently
and whether it reproduces. Record device state, available disk space and
recent changes. Never reformat or reinstall Windows before understanding
the problem and protecting important data.

2. CPU load and workload
Task Manager shows CPU utilization over time. High usage while compiling,
updating or processing video may be normal. A process that consistently
consumes resources while idle deserves examination, but a one-time spike
is not proof of a fault. Compare the observation with the user’s actual task
and time.

3. Memory pressure and paging
Many open applications may exhaust usable RAM. Windows can move
memory pages to the storage device, which may increase disk activity and
make switching apps slow. A “90% used” reading without knowing the
application mix is not enough to justify an upgrade. Observe performance
under a reproducible workload.

4. Disk space and storage performance
A nearly full system drive can interfere with updates and temporary files.
Disk activity during copying or antivirus scans may be expected. Examine
free space and I/O utilization, but do not delete unknown system data.
Distinguish “disk full” from “disk busy” and from an actual hardware failure.

5. Startup apps and background maintenance

---

understood and with the device owner’s consent. Avoid third-party “instant
speed booster” tools.

6. Event Viewer and Reliability History
Windows logs events with time, source and severity. Some entries marked
Error occur even on normally working systems; one line does not establish
causation. Correlate relevant events with symptoms and reproduce where
safe. Reliability Monitor can present a timeline, when available.

7. A controlled troubleshooting method
Form a hypothesis, make one low-risk reversible change or observation, and
compare before/after. Changing multiple settings makes it difficult to tell
which step mattered. Keep a written log of steps and outcomes; document
cases where the cause remains unknown. Escalation is better than making
irreversible guesses.

8. Reporting and communication
A useful diagnostic report includes complaint, environment, evidence,
hypotheses, safe checks performed, measured result and remaining
limitations. State what was not tested. Avoid sensitive logs or personal
filenames in publicly shared examples. Recommend backups before any
significant repair.


Knowledge check

Choose one answer for questions 1–6. Answer questions 7–8 in your own
words. Explanations are collected at the end of Stage 1.

 1. What should you do first when someone says their PC is slow? A)
    Reinstall Windows immediately B) Delete the GPU driver C) Disable
    protection D) Clarify symptoms and gather observations

 2. What does high CPU utilization at a particular moment show? A) The
    processor is broken B) Significant computing activity at that moment C)
    The disk is completely full D) The screen is off

 3. Why compare Windows log events with the time of the problem? A)
    To separate related events from background messages B) To drain the
    battery faster C) To change file encoding D) To erase the log

 4. What may indicate insufficient RAM? A) Higher screen brightness B) A
    slow printer C) Heavy paging while many apps are open D) A currency
    exchange-rate change

 5. How should you treat unknown tools promising a 200% PC speed
    boost? A) Install without checking B) Disable all services C) Send the
    admin password D) Demand evidence; prefer built-in diagnostics

---

6. How should you test a troubleshooting hypothesis? A) Change ten
    settings at once B) Change one factor and compare C) Ignore when the
    symptom occurs D) Judge by appearance only

 7. Give three possible reasons why a website opens slowly and a safe way
    to distinguish each.

 8. Why does a single Event Viewer entry marked Error not prove the
    system is faulty?


Guided practice on a computer

A. A. Record a repeatable symptom

 1. Write down one practice complaint: “The browser opens slowly after
    sign-in.”
 2. Specify start time, frequency, steps to reproduce and expected/actual
    behavior.
 3. List two observations you still need before diagnosing.

Completion criteria: The report describes a measurable, repeatable issue.

B. B. Observe system resources

 1. Open Task Manager → Processes and Performance.
 2. Record CPU/RAM/Disk usage at rest and after opening one normal app.
 3. Record whether the observed load coincided with the reported
    symptom; do not kill unknown processes.

Completion criteria: Measurements are labeled with context and time.

C. C. Examine logs carefully

 1. Open Windows Event Viewer or Reliability Monitor if available.
 2. Find an entry near the time of a harmless test event; record its source
    and timestamp.
 3. Explain why this event alone cannot confirm root cause.

Completion criteria: The student distinguishes correlation from proof.


Independent task

Make a table with columns Symptom / Evidence / Hypothesis / Safe test /
Result for a fictional slow computer.


Homework

Submit diagnostic-report.md with at least two hypotheses, one safe
observational test and an explicit statement of remaining uncertainty.

---

Optional challenge: Compare two ways to improve responsiveness that do
not involve uninstalling applications.
