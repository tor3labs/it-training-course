# 7. Backups and Recovery

7. Archives, Backups and Data Recovery
Duration: 90 min · Deliverable: backup log with successful restoration


Learning outcomes

Distinguish archives from true backups, plan independent copies, execute a
safe recovery test, and understand versioning and integrity checks.


Theory and examples

1. Why backups matter
Important files can be lost through hardware failure, accidental deletion,
ransomware, theft or a mistaken edit. A backup is an independent
recoverable copy, not a shortcut or a file moved to another folder. Identify
which files matter and how much recent work you can afford to lose. Test
recovery before trusting any backup routine.

                                   LOCAL COPY
                                  external storage
        ORIGINAL                                                 RESTORE
       working copy                                             test + verify


                                     OFF-SITE
                                  another location

2. Archive versus backup
ZIP and 7z are archive formats that package files and may compress them.
A ZIP stored beside the original on the same failing drive does not protect
against drive failure. A backup strategy is defined by independent storage,
frequency, retention and restore verification, not by the extension of the
archive.

3. The 3-2-1 rule
A common recommendation is three copies of important data including the
working copy, two kinds of media, and one copy at another location. The
rule is a planning heuristic, not a guarantee against every risk. An external
disk disconnected when not needed and a protected cloud location can
complement each other.

4. Full, incremental and differential copies
A full backup captures the selected data set. An incremental backup
records changes since the preceding backup point in the chain; a
differential backup records changes since the last full backup. Restore

---

complexity, storage use and retention differ. For this beginner practice, a
simple complete copy is enough to demonstrate restoration.

5. Synchronization is not always backup
Cloud sync keeps files aligned between devices; unintended deletions or
corrupted files may be synchronized too. Some services offer version
history, but availability and retention vary. Check whether you can retrieve
an earlier version and whether data remains recoverable if the account is
compromised.

6. Integrity and hashes
A cryptographic hash such as SHA-256 provides a compact fingerprint of
file contents. Matching hashes make identical contents overwhelmingly
likely but do not prove the file has a legal or trusted origin. Windows can
compute hashes using certutil -hashfile when appropriate; use it only on
harmless practice data.

7. Restore tests
The critical question is whether you can recover and open a usable file.
Restore into a new practice folder so the original stays intact. Compare
content and, optionally, hashes. Record location, date, file list and result so
that a failed restore can be investigated.

8. A realistic personal backup plan
For family photos, decide where originals live, how often they change,
where independent copies go, how to protect access and how often to test
recovery. Consider available space and connectivity. Do not put passwords
or private photos in a public course repository. Maintain a short log rather
than relying on memory.


Knowledge check

Choose one answer for questions 1–6. Answer questions 7–8 in your own
words. Explanations are collected at the end of Stage 1.

 1. Which option best protects against loss of one physical drive? A) A
    copy on an independent external drive B) A second filename on the
    same drive C) A desktop shortcut D) A move within the same drive

 2. What verifies that a backup is usable? A) Renaming the archive B)
    Changing wallpaper C) Restoring and checking its contents D) Turning
    off updates

 3. What does the “3” represent in the 3-2-1 recommendation? A) Three
    different passwords B) Three copies, including the working copy C)
    Three archive programs D) Three network ports

---

4. How does an incremental backup normally differ? A) It always
    includes every file B) It is stored only on DVD C) It never needs a base
    backup D) It stores changes since the preceding point in the chain

 5. Why is cloud synchronization not automatically a backup? A) Errors
    and deletions may also synchronize B) Clouds never store documents
    C) PCs cannot use cloud storage D) All services delete files daily

 6. What do matching SHA-256 hashes of two files suggest? A) They
    have the same filename B) They are in the same folder C) Their
    contents are almost certainly identical D) They were created the same
    day

 7. Give an example in which a ZIP stored on drive C: fails to protect your
    files.

 8. List five elements of a backup plan for family photographs.


Guided practice on a computer

A. A. Prepare source files

 1. Create it-course/stage01/backup-lab/source and two harmless text
    files.
 2. Write unique identifying sentences in each, save and close them.
 3. Record their filenames and approximate sizes.

Completion criteria: All files are synthetic practice content.

B. B. Create a copy on independent storage if possible

 1. Create a ZIP or simple folder copy on an approved external drive or
    cloud folder.
 2. If independent storage is unavailable, use another practice folder but
    clearly label the exercise demonstrational, not disaster-protective.
 3. Write down the backup location and timestamp.

Completion criteria: The student recognizes whether the copy is
independent of the source drive.

C. C. Restore and verify

 1. Create a new restored folder separate from source .
 2. Extract or copy backed-up files into restored , then open both text files.
 3. Compare their sentences with the source and record the result in
    backup-restore-log.md .


Completion criteria: The restore was performed and verified, not just
assumed.

---

Independent task

Explain the difference between an archive, synchronization and a restorable
backup in three short paragraphs.


Homework

Submit a backup plan with sources, schedule, locations, retention, access
protection and one documented restore test.

Optional challenge: Use file hashes to compare a synthetic text file and its
restored copy, then describe what a hash does and does not prove.
