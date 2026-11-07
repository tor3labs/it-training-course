# 5. Users, Permissions and Services

5. Users, Permissions, Processes and
Services
Duration: 90 min · Deliverable: non-invasive account and access audit


Learning outcomes

Understand authentication, authorization, standard vs administrator
accounts, UAC and file permissions; inspect them without changing
someone else’s configuration.


Theory and examples

1. Why operating systems use accounts
An account associates settings, files and access rights with a person or
service. Accounts help prevent one user from accidentally modifying
another user’s data. On a family computer, separating user accounts is
often safer than sharing one administrator profile. Windows may offer local
and Microsoft accounts with different sign-in and synchronization
capabilities.

2. Authentication versus authorization
Authentication asks who you are, for example through a password,
biometric sign-in or security key. Authorization decides what an
authenticated user may do, such as read, modify or delete a document. A
correct password does not grant permission to every folder. For safety,
never share real passwords in screenshots or coursework.

3. Standard and administrator privileges
Standard accounts are designed for daily work without broad system
control. Administrators can change many settings and install system-wide
software. The principle of least privilege means giving users or programs
only the rights needed for a particular task. It reduces the damage possible
from errors or malicious applications.

4. UAC elevation requests
User Account Control displays prompts when a task requests higher
privileges. A prompt may appear during installation or changes to important
settings. It is a request to approve a more powerful operation, not a
certification of trustworthiness. If the action is unexpected, stop, identify
the program and consult the owner or teacher.

---

5. File permissions and NTFS
NTFS supports permissions for files and folders, including reading and
modifying. Permissions may be inherited from parent folders and can
interact with group memberships. The Security tab in file properties is
useful for inspection. Changing ACLs on Windows directories or another
person’s files can lock users out and is outside this practice.

6. Processes: work associated with accounts
Processes run under security contexts that affect access to files and
devices. Some system processes run as special service accounts. Task
Manager can display users and resource consumption, but displayed details
may depend on permissions. Never assume that an unfamiliar process
should be terminated.

7. Windows services
Services provide background functions such as networking, time, updates
or printing. They may start automatically, manually or when triggered.
Stopping a service without understanding dependencies can interrupt the
OS or other applications. The exercise is limited to reading service names
and descriptions.

8. Safe audit habits
An audit records current settings and exposure without necessarily
changing them. Note the account type, available permissions and missing
information. A safer recommendation is often “ask the administrator” rather
than “turn off protection”. Protect the resulting report from revealing
account names, email addresses or security identifiers.


Knowledge check

Choose one answer for questions 1–6. Answer questions 7–8 in your own
words. Explanations are collected at the end of Stage 1.

 1. What is a standard user account useful for? A) Changing BIOS every
    sign-in B) Blocking all apps C) Doing daily tasks without broad
    administrative privileges D) Deleting files automatically

 2. What does authorization mean? A) Checking whether a password is
    correct B) Determining allowed actions after identity is established C)
    Turning on the PC D) Connecting the monitor

 3. What does a UAC prompt indicate? A) A request for potentially
    elevated rights B) All batteries are low C) File encoding changed D) Wi-
    Fi is slow

 4. Which Windows file system typically supports detailed access-
    control lists? A) FAT12 B) FAT32 C) ISO 9660 D) NTFS

---

5. Why should you avoid stopping an unfamiliar Windows service? A) It
    always speeds up CPU B) It immediately deletes all files C) The system
    or an application may depend on it D) Every service needs the internet

 6. What does least privilege mean? A) Give everyone administrator rights
    B) Give only permissions needed for the task C) Never update software
    D) Store files only in Recycle Bin

 7. Explain authentication and authorization using a private documents
    folder.

 8. Why should an unexpected administrator prompt trigger verification
    rather than automatic approval?


Guided practice on a computer

A. A. Observe account type

 1. Open Settings → Accounts → Your info or another available account-
    information screen.
 2. Identify whether the current user has standard or administrator rights if
    the interface reveals it.
 3. Record only the account type; do not capture email, username or ID in a
    public report.

Completion criteria: The report does not reveal private account identifiers.

B. B. Inspect file permissions

 1. Create a harmless practice file in your own Stage 1 exercise folder.
 2. Open its Properties → Security if present and inspect Read/Write/
    Modify information.
 3. Explain which operations are permitted; do not edit ACLs.

Completion criteria: The student identifies rights while leaving them
unchanged.

C. C. Observe a background service

 1. Open services.msc if permitted or watch the teacher’s demonstration.
 2. Find a known service, read its description and its displayed startup
    state.
 3. List one service dependency risk and close the panel without modifying
    it.

Completion criteria: No service is stopped or reconfigured.

---

Independent task

Give two examples of tasks that normally should not require administrator
privileges and one change that may require elevation.


Homework

Submit a short access-audit.md listing account type, safe file-permission
observations, UAC behavior and three security recommendations.

Optional challenge: Explain how inherited NTFS permissions could cause
an unexpected lack of access to a practice folder.
