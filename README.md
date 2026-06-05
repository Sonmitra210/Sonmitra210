## Hi there 👋

# Hi there, I'm Sonmitra Seth 👋

*B.Tech in Computer Science and Engineering @ Indian Institute of Technology (IIT) Guwahati*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://linkedin.com/in/sonmitra-seth)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/Sonmitra210)
[![Email](https://img.shields.io/badge/Email-sonmitra.seth@gmail.com-red?logo=gmail)](mailto:sonmitra.seth@gmail.com)

## 🎓 Education

| Degree/Certificate | Institute/Board | CGPA/Percentage | Year |
| :--- | :--- | :--- | :--- |
| **B.Tech. Major** | Indian Institute of Technology, Guwahati | 9.30 | 2024-Present |
| **Senior Secondary** | CBSE Board | 96.4% | 2024 |
| **Secondary** | CBSE Board | 97.4% | 2022 |

## 💻 Technical Skills

* **Programming Languages:** C++, C, JavaScript, Python\*, TypeScript, Verilog
* **Development Technologies:** HTML, CSS, Node.js, Express.js\*, React.js\*
* **Miscellaneous:** Git, GitHub, Linux, MongoDB, LaTeX\*, Vivado

*\* Elementary proficiency*

## 🚀 Featured Projects

### [High-Frequency Limit Order Book (SPSC Queue)](https://bit.ly/Limit-Order-Book)
*Ultra-low latency C++ matching engine processing 1.93M+ trades/sec per CPU core*
* Engineered a lock-free Single-Producer Single-Consumer (SPSC) Ring Buffer pipeline to decouple TCP network ingestion from the core matching logic, ensuring the engine never blocks on asynchronous I/O.
* Designed a custom contiguous Memory Pool to pre-allocate 1,000,000 order nodes at startup, completely eliminating OS-level dynamic heap allocation (new/delete) overheads and kernel context switches on the hot path.
* Achieved constant-time O(1) order cancellations by integrating an intrusive doubly-linked list for strict Price-Time Priority (FIFO) with an unordered hash map for instantaneous memory address resolution.
* Benchmarked sub-microsecond latencies (206ns resting, 517ns matching) using Google Benchmark (-O3 Release) and validated memory safety for complex partial fills and spread crossing via Google Test.

### [High-Performance 5-Stage RISC-V Pipeline Processor](https://bit.ly/Risc_V_Processor)
*Cycle-accurate RV32IM soft-core deployed on Artix-7 FPGA*
* Engineered a 5-stage pipelined RISC-V soft-core in Verilog supporting the full RV32IM instruction set, capable of executing custom bare-metal C applications compiled via the standard GCC toolchain.
* Integrated comprehensive data forwarding for RAW hazards and a dynamic Branch Target Buffer (BTB), optimizing branch target address calculation directly within the early instruction decode stage.
* Developed a configurable multi-cycle memory subsystem with internal byte-level bypassing and integrated a dedicated L1 Cache memory hierarchy to accelerate data access and minimize all pipeline stalls.

### [VideoConnect Real-Time Conferencing Platform](https://bit.ly/Video-Connect)
*Full-Stack Web Application for Virtual Meetings*
* Developed a robust P2P video conferencing architecture utilizing WebRTC for media transport and Socket.io for signaling, enabling seamless, low-latency audio-visual communication and connection stability.
* Implemented a fully integrated real-time chat system facilitating instant messaging alongside active video streams, ensuring precise state synchronization and handling concurrent communication flows for all participants.
* Built a comprehensive meeting history dashboard using MongoDB to persist complex session metadata allowing users to efficiently track, retrieve, and review detailed logs of all previously held conferences.
* Created a secure authentication system featuring encrypted login and registration flows to strictly manage user identities, ensuring robust data privacy, session integrity, and exclusive access to personal account history.

## 🏆 Achievements

* **Codefest 2026 Prelims:** Ranked 1571 (2026)
* **Codeforces:** Max Rating: 1697 (Expert) | Handle: Sonmitra (2026)
  * Codeforces Round 1073 (Division 2): Secured a Global Rank of 717 among 26,000+ participants
  * Codeforces Round 1079 (Division 2): Secured a Global Rank of 855 among 25,000+ participants
* **WBJEE (West Bengal Joint Entrance Examination):** Ranked 56 (2024)
* **Qualified IOQM:** Participated in INMO (Indian National Mathematical Olympiad) (2022-23)
* **IAT (IISER Aptitude Test):** Ranked 429 (2024)

## 📚 Key Courses Taken
*\* Awarded AA grade (10/10)*

* **Computer Science:** Computer Architecture\*, Data Structures and Algorithms\*, Design and Analysis of Algorithms\*, Digital Design\*, System Software Lab, Database Management Systems
* **Mathematics:** Probability Theory and Random Processes, Number Theory and Algebra\*

---
*Feel free to reach out to me at [s.sonmitra@iitg.ac.in](mailto:s.sonmitra@iitg.ac.in) or connect with me on LinkedIn!*
