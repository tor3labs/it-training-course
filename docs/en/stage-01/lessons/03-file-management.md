# 3. Files and File Systems

3. Files, Folders and File Systems
Duration: 90 min · Deliverable: organized practice folder with verified
copies


Learning outcomes

Use paths and extensions correctly, distinguish files from file systems, copy
and move practice data, and recognize misleading filenames.


Theory and examples

1. Files, folders and paths
A file is a named set of data; a folder groups files and other folders. A path
identifies its location. In Windows, C:\Users\... is an absolute path, while a
path relative to the current folder does not begin at a fixed root. A shortcut
links to a target and does not duplicate its contents.


    it-course/stage01


                        input/                 original files


                        working/               edits in progress


                        result/                finished files


                        backup/                copies (not always independent)

2. File extensions and real formats
The extension .txt , .pdf or .exe is part of the filename and helps
applications choose how to open it. Renaming .txt to .pdf does not
convert the internal data to PDF. Turn on File Explorer → View → Show →
File name extensions to avoid confusing invoice.pdf.exe with a document.

3. Common file formats
TXT is plain text; Markdown is structured plain text; DOCX is an editable
document package; PDF preserves page layout; CSV holds tabular text
data; PNG and JPEG hold images. Formats vary in suitability for editing,
archival use and sharing. The same content can be exported into several
formats without being the same file internally.

4. Copying, moving and deleting
Copying creates another file while leaving the original; moving changes
location and may involve a physical copy between drives. Deleting to
Recycle Bin offers possible recovery, but not every deletion passes through

---

it. The Undo action is not a substitute for backups. Always work on practice
data rather than someone else’s documents.

5. File systems
NTFS, FAT32 and exFAT are systems for organizing data on a storage
volume, not document formats. NTFS supports richer permissions and large
files; exFAT is useful for portable drives across systems. A volume may be
formatted with one file system even while it contains thousands of different
file formats.

6. Storage sizes and visibility
Files are measured in bytes and larger units (KB/MB/GB, or KiB/MiB/GiB).
Total and free disk space can be inspected in File Explorer. Hidden files and
protected system folders serve particular purposes; enabling display is not
permission to edit them. Folder sizes may include many nested files.

7. Searching and sorting
File Explorer supports searches by name, type and other properties, but
search results depend on location and indexing. Sort by name, date or size
to locate the right item. Consistent file naming such as 2026-11-report-
v1.md helps version recognition. Avoid creating many files named
final_final_new .


8. ZIP archives
A ZIP archive bundles multiple files and may compress them. It is useful for
exchanging practice projects, but creating ZIP in the same directory is not
an off-site backup. Examine archive contents before extraction and avoid
executing unknown files. Extraction creates usable files; simply viewing ZIP
does not confirm every program will run.


Knowledge check

Choose one answer for questions 1–6. Answer questions 7–8 in your own
words. Explanations are collected at the end of Stage 1.

 1. What does an absolute path describe? A) Only the file extension B) A
    location from a known root C) Folder size D) Administrator privileges

 2. What happens if you rename notes.txt to notes.pdf without
    conversion? A) Data becomes PDF automatically B) The file is deleted
    C) The name changes but the data format does not D) Windows
    encrypts the file

 3. Which operation leaves the original and produces a second copy? A)
    Copy B) Move C) Rename D) Sort

 4. Which is a file system? A) .docx B) .pdf C) .png D) NTFS

---

5. Why show file extensions? A) To increase RAM B) To recognize file
    types and deceptive executable names C) To raise CPU frequency D)
    To install Windows updates

 6. What can a ZIP archive do? A) Store exactly one file only B)
    Automatically back up in another building C) Collect and compress
    multiple files D) Replace the file system

 7. Explain the difference between a file format and a file system.

 8. Propose a readable folder structure for course assignments and explain
    your choices.


Guided practice on a computer

A. A. Set up a safe practice area

 1. In Documents, create it-course/stage01/files-lab/input , working ,
    result and backup .

 2. Create three harmless .txt files in input using Notepad and write a
    different sentence in each.
 3. Turn on visible file extensions and check filenames in File Explorer.

Completion criteria: Only exercise files were created and no pre-existing
personal files were moved.

B. B. Copy, move, rename and compare

 1. Copy one file from input to working , then edit the copied file.
 2. Rename the working copy and compare it with the original to confirm
    the latter did not change.
 3. Move another practice file into result ; describe how its new path
    differs.

Completion criteria: Copy and move are distinguished using actual file
locations.

C. C. Archive and restore

 1. Select the result folder, use Compress to ZIP file if available (or built-in
    Send to ZIP).
 2. Open the archive and list its contents; extract it into a newly created
    test folder.
 3. Open the extracted .txt file and compare its text with the source.

Completion criteria: Extraction and inspection confirm files are readable.

---

Independent task

Draw the folder tree showing input , working , result and backup ; label one
absolute and one relative path.


Homework

Submit a screenshot or text tree of the exercise folder (no personal paths),
a ZIP with practice files, and a brief explanation of copy versus move.

Optional challenge: Explain two reasons why a file named report.pdf.exe
is suspicious.
