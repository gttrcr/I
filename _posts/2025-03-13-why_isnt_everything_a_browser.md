---
title: Why isn't everything a browser?
date: 2025-03-13
permalink: /posts/2025/03/13
tags:
   - Computer science
   - Community
---

After years of fighting against the logic of web programming (a fight mostly in vain), the web is not its programming language, but its logic. The web, as we know it today, is built on a foundation of programming languages that have evolved over the years to create everything from simple static pages to complex web applications. 

1. The web was born in **1991** when Tim Berners-Lee created **HTML (HyperText Markup Language)** as a way to structure web pages.
2. HTML alone wasn't enough for dynamic content, so developers used **CGI (Common Gateway Interface)** scripts written in languages like **Perl** and **C** to generate dynamic web pages.
3. **JavaScript (1995)** was introduced by Netscape to enable interactive elements on web pages, making it possible to create dynamic content without server-side processing.
4. Around the same time, **CSS (Cascading Style Sheets)** was introduced to separate style from structure, allowing for better web design.
5. **Java (1995)** and **PHP (1995)** emerged as server-side languages, providing more powerful ways to handle backend logic.
6. **PHP, ASP.NET, and Java Servlets** became widely used for backend development.
7. **AJAX (Asynchronous JavaScript and XML)** allowed for smoother user experiences by enabling web pages to update content without refreshing.
8. **Ruby on Rails (2005)** made web development faster and more efficient by promoting convention over configuration.
9. **jQuery (2006)** simplified JavaScript, making it easier to manipulate HTML and handle events.
10. The rise of **single-page applications (SPAs)** led to frameworks like **AngularJS (2010), React (2013), and Vue.js (2014)**.
11. On the backend, **Node.js (2009)** allowed JavaScript to be used for server-side development.
12. **TypeScript** (a superset of JavaScript) became popular for its strong typing and better maintainability.
13. **JAMstack** (JavaScript, APIs, and Markup) grew as a modern web architecture.
14. **WebAssembly (Wasm)** opened the door for high-performance web applications using languages like Rust, C++, and Go.
15. AI and machine learning integration are shaping the future of web development.

But the history of the web and its programming languages ​​did not evolve by itself. Alongside the web there have always been (before the web itself) applications with which the user interacts on a daily basis.

The journey of application development and distribution has evolved dramatically, from early standalone software to today's cloud-based and AI-powered applications. It was not easy to identify them but, broadly speaking, the stages in the history of software development and distribution are as follows.

|        | **Development**                                                  | **Distribution**                                                             |
| ------ | ---------------------------------------------------------------- | ---------------------------------------------------------------------------- |
|        | **1950s-1980s: Standalone Programs**                             | **1950s-1980s: Physical Media & Manual Installation**                        |
| **1**  | Early programming languages: **Fortran, COBOL, Lisp**            | Software bundled with hardware (mainframes)                                  |
| **2**  | Programs written in **assembly language**                        | Manual input via **punch cards, magnetic tapes**                             |
| **3**  | Software developed for specific machines                         | Sharing required physical storage transportation                             |
|        | **1980s-1990s: Personal Computer Revolution**                    | **1980s-1990s: Commercial Software Sales**                                   |
| **4**  | Rise of **PCs** (IBM PC, Apple Macintosh)                        | Software sold on **floppy disks, CD-ROMs**                                   |
| **5**  | GUI-based applications emerge (**Windows, Mac OS**)              | Retail stores and mail-order catalogs distribute software                    |
| **6**  | Dominant programming languages: **C, C++, Pascal**               | **Shareware/freeware** allows trial versions before purchase                 |
|        | **Late 1990s-2000s: Internet & Open Source Movement**            | **Late 1990s-2000s: Online Downloads & SaaS**                                |
| **7**  | Web applications emerge (**Hotmail, early Google services**)     | Software downloads replace physical media (**Tucows, SourceForge**)          |
| **8**  | Rise of **open-source software** (**Linux, Apache, MySQL, PHP**) | Peer-to-peer networks (**Napster, BitTorrent**) spread software              |
| **9**  | Programming languages: **Java, PHP, Python**                     | **Software as a Service (SaaS)** gains popularity                            |
|        | **2010s-Present: Mobile & Cloud Era**                            | **2010s-Present: App Stores & Cloud Services**                               |
| **10** | Explosion of **mobile apps** (**iOS, Android**)                  | **App stores** (Apple App Store, Google Play) dominate distribution          |
| **11** | Cloud-based development and **serverless computing**             | Subscription-based models (**Netflix, Adobe Creative Cloud**)                |
| **12** | Cross-platform frameworks (**React Native, Flutter**)            | Open-source package managers (**npm, pip, Homebrew**) simplify installations |
|        | **2020s & Beyond: AI & Web3 Future**                             | **2020s & Beyond: Decentralized & AI-Powered Distribution**                  |
| **13** | AI-assisted coding (**GitHub Copilot, ChatGPT**)                 | **Progressive Web Apps (PWAs)** reduce reliance on app stores                |
| **14** | **Decentralized applications (dApps)** in blockchain ecosystems  | Decentralized, blockchain-based software distribution grows                  |
| **15** | Rise of **no-code/low-code platforms**                           | AI-powered cloud platforms enable instant scaling and updates                |

Finally, we can also identify challenges in the history of computing, in the very history of software development, application distribution and web development

|        | **Development Challenges**                                                                        | **Distribution Challenges**                                                                  |
| ------ | ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| **1**  | Limited hardware capabilities in early computing (1950s-1990s)                                    | Software was distributed on **floppy disks, tapes, and CDs**, making updates slow and costly |
| **2**  | No standardized programming languages in early computing                                          | Piracy due to lack of licensing enforcement in early software distribution                   |
| **3**  | Debugging was manual and time-consuming in early software                                         | Platform fragmentation (**IBM PC, Apple, mainframes**) caused compatibility issues           |
| **4**  | Early web security threats (**viruses, SQL injections, XSS attacks**)                             | Slow internet speeds made software downloads impractical                                     |
| **5**  | Browser incompatibility (**Netscape vs. Internet Explorer**) causing inconsistent user experience | Illegal software distribution through **P2P networks (Napster, BitTorrent, etc.)**           |
| **6**  | Backend scaling issues with growing web applications                                              | Conflicts over **open-source licensing and software patents**                                |
| **7**  | Mobile device fragmentation (**iOS, Android, Windows**)                                           | **App Store restrictions and high commission fees (30%)**                                    |
| **8**  | Power efficiency challenges for mobile and web apps                                               | **Cybersecurity threats (hacked apps, malware, data breaches, phishing attacks)**            |
| **9**  | Balancing performance across **web, mobile, and desktop**                                         | **Subscription model fatigue** as companies move away from one-time purchases                |
| **10** | Security and data privacy concerns in cloud computing                                             | **Cloud provider monopolies (AWS, Azure, Google Cloud)** create dependency issues            |
| **11** | Ethical concerns over **AI-assisted development (job displacement, bias)**                        | **Decentralized applications (dApps) lack clear regulation**                                 |
| **12** | Complexity of blockchain-based applications                                                       | **Security risks in blockchain-based software distribution**                                 |
| **13** | Quantum computing could break existing encryption standards                                       | **Rise of AI-generated malware and software distribution risks**                             |

It would also be possible to study the interesting relationships between the challenges of computer science and the programming languages ​​that generate/solve them, but this goes beyond our reflection today. I want to conclude the first part of this blog with a small summary of what the challenges of the past have been and what, probably, will be challenges. Below is a table listing three-word summaries of the main past and future challenges for each category with supporting references for further reading.

|                  | **Past Challenges (3 words)**          | **Future Challenges (3 words)**               |
| ---------------- | -------------------------------------- | --------------------------------------------- |
| **Web**          | Compatibility, Speed, Security         | Privacy, Interoperability, Resilience         |
| **Development**  | Complexity, Fragmentation, Scalability | Automation, AI, Standardization               |
| **Distribution** | Physical, Piracy, Fragmentation        | Decentralization, Regulation, Personalization |

**References:**  
For historical and technical challenges in web and software development, see insights on browser compatibility and early internet speed issues on [MDN Web Docs](https://developer.mozilla.org). For trends in modern challenges like decentralization and AI in software distribution, see analyses from industry sources such as [Wired](https://www.wired.com) and [Smashing Magazine](https://www.smashingmagazine.com).
