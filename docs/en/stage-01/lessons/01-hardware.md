# 1. Computer Architecture

1. Computer Architecture and
Components
Duration: 90 min · Deliverable: hardware inventory and a justified
equipment choice


Learning outcomes

Explain how hardware and software cooperate, identify the main
components, inspect actual specifications in Windows 11, and distinguish
measurements from assumptions.


Theory and examples

1. A computer as an information-processing system
Input devices, storage and networks provide data; programs define
operations; processors and memory perform them; outputs include
screens, files and network messages. A computer is a system, not a single
fast chip. Its slowest relevant component can constrain an application. For
example, insufficient RAM may cause intensive disk swapping even with a
strong CPU.


                         RAM

      INPUT              CPU                      GPU                OUTPUT

  keyboard, network                          visual processing       screen, file

                        SSD/HDD

2. CPU: instructions, cores and clock speed
The central processing unit executes instructions such as arithmetic,
comparisons, branching and memory access. A core executes instructions;
a software thread is a sequence of program work, while a logical processor
is an exposed hardware execution resource. Clock frequency in GHz
measures cycles per second, not universal performance. Compare CPU
architecture, workload, cache, power and cooling rather than GHz alone.

3. RAM: working memory
Random-access memory holds data and instructions that running programs
need immediately. Ordinary RAM loses its contents when power is removed,
unlike SSD/HDD storage. More RAM helps with multiple applications, but
adding it does not automatically accelerate every task. When available

---

physical memory is insufficient, Windows may move pages to disk; this is
usually slower than RAM.

4. SSD, HDD and persistent storage
Storage retains files across shutdowns. Hard disk drives use mechanical
rotating parts; solid-state drives use flash memory and usually have much
lower random-access latency. Capacity and speed are separate
characteristics. A nominal 512 GB drive may display a smaller numeric
capacity in Windows because decimal GB and binary GiB differ and some
space is reserved.

5. GPU and displays
Graphics processors are designed for highly parallel work, notably
rendering 2D/3D images and some computing workloads. An integrated
GPU often shares system resources; a discrete GPU usually has its own
processing hardware and frequently dedicated video RAM. The monitor
shows the resulting image: it is not the graphics processor. For ordinary
office tasks a discrete GPU may be unnecessary.

6. Motherboard, interfaces and power
The motherboard connects processing, memory, storage and peripheral
controllers. Interfaces such as USB, HDMI, Ethernet and PCIe have different
purposes; identical connector shapes do not guarantee equal functionality
or throughput. Power supplies provide appropriate electrical power, while
cooling maintains safe operating temperatures. Excessive heat can reduce
performance through throttling.

7. Input/output devices and drivers
A keyboard and microphone are input devices; a display and speakers are
outputs; touchscreens are both. Drivers allow the operating system to
communicate with hardware. Missing or incompatible drivers can reduce
functionality or cause devices not to be recognized. Never install random
driver utilities to solve an unidentified problem.

8. Selecting hardware for a workload
For study and office tasks, prioritize a responsive SSD, adequate RAM,
readable screen and reliable keyboard. Programming may benefit from
more memory, CPU capacity and space for tools. 3D workloads benefit
from suitable GPU and cooling. Evaluate the price, expandability and actual
software requirements; no specification alone determines the best choice.

---

Knowledge check

Choose one answer for questions 1–6. Answer questions 7–8 in your own
words. Explanations are collected at the end of Stage 1.

 1. Which component normally loses stored data after power is
    removed? A) SSD B) HDD C) RAM D) USB flash drive

 2. What does a CPU primarily do? A) Displays pixels directly on the
    monitor B) Executes program instructions C) Stores documents
    permanently D) Powers the computer electrically

 3. Why does an SSD often start programs faster than an HDD? A) It
    usually accesses data with lower latency B) It always has higher
    capacity C) It replaces the CPU D) It includes a built-in GPU

 4. What does RAM capacity describe? A) Internet bandwidth B)
    Maximum SSD size C) Amount of working memory D) Monitor refresh
    rate

 5. Which component matters most for demanding 3D graphics, all else
    being equal? A) Card reader B) GPU C) Microphone D) Network cable

 6. Why is CPU frequency alone insufficient for comparing processors?
    A) It applies only to audio B) Every CPU executes the same work per
    cycle C) It indicates memory size D) Architecture, cores and workloads
    also matter

 7. Explain the difference between RAM and persistent storage in two
    sentences.

 8. List four specifications you would check for a programming laptop and
    explain why.


Guided practice on a computer

A. A. Build a hardware inventory

 1. Open Start → Settings → System → About. Record CPU model, installed
    RAM, OS edition and system type.
 2. Press Win + R, run msinfo32 , and note the computer manufacturer/
    model if available.
 3. Open the hardware-report template in Stage 1 resources and enter the
    findings. Never publish serial numbers, device identifiers or license
    keys.

Completion criteria: Recorded values can be verified in Windows, without
exposing unique personal identifiers.

B. B. Observe actual resource usage

 1. Open Task Manager with Ctrl + Shift + Esc, then Performance.

---

2. Inspect CPU, Memory, Disk and GPU (if listed). Record approximate idle
    usage.
 3. Launch an ordinary application; observe which indicators change and
    describe two differences.

Completion criteria: The student distinguishes current utilization from
hardware capacity.

C. C. Choose a computer

 1. Compare A: 4 cores, 8 GB RAM, HDD 1 TB; B: 6 cores, 16 GB RAM, SSD
    512 GB; C: 8 cores, 16 GB RAM, SSD 1 TB, discrete GPU. A is cheapest;
    B costs less than C.
 2. Choose for office work, programming and 3D graphics, giving at least
    two reasons for each choice.
 3. Name two additional facts needed for a fully informed decision.

Completion criteria: Decisions are reasoned and do not assume that the
highest number always wins.


Independent task

Draw an input → CPU/RAM → storage/output diagram containing at least six
named parts. Explain its data flow aloud.


Homework

Submit hardware-report.md , a comparison table for A/B/C, and five
sentences about the first upgrade you would choose for your device and
why.

Optional challenge: Explain how a CPU with fewer cores might outperform
another CPU on a single-threaded program.
