# Richard Chien

## Links

- Email: stdrc AT outlook DOT com \| rcx AT live DOT com
- GitHub: <https://github.com/richardchien>
- LinkedIn: <https://www.linkedin.com/in/richard-chien/>
- Blog: <https://stdrc.cc>

## Education

### 2008 — Now, Self-Education

Programming

- I started to learn visual programming and Visual Basic at Grade 5, C at Grade 9.
- Almost all of my programming skills are self-taught.
    - I learn from books, online courses, tutorials, blogs, documentations, and by writing real projects.

### Sep 2020 — Mar 2023 (expected), Shanghai Jiao Tong University

Master of Engineering (Software Engineering)

- I ranked first in the Postgraduate Admission Test.

### Sep 2015 — Jun 2020, Changzhou University

Bachelor of Engineering (Internet of Things)

## Projects

### I Created

- **[OneBot](https://github.com/botuniverse/onebot)** (2020-now): A chatbot API standard derived from CQHTTP, aiming to unify the API for different chatbot platforms. Currently the ecosystem of the latest version of the standard, OneBot 12, is growing steadily with the help of many community developers.
- [Go LibOneBot](https://github.com/botuniverse/go-libonebot) (Go, 2021-now): A library to help developers implement OneBot standard on new chatbot platforms conveniently.
- **[CQHTTP](https://github.com/kyubotics/coolq-http-api)** (C++17, 2017-2020): A chatbot middleware to convert low-level ABIs of a chatbot platform called CoolQ to high-level HTTP and WebSocket APIs, making chatbot development easy with programming languages for web (PHP, Python, etc). It solved the problem faced by many chatbot developers, hence gained up to 1.8k stars on GitHub, and powered 5k+ chatbots in its prime, reaching approximately hundreds of thousands of end users.
- **[CQCPPSDK](https://github.com/kyubotics/cqcppsdk)** (C++17, 2017-2020): A C++ SDK for CoolQ, extracted from CQHTTP to reduce coupling and improve code reuse. It wraps CoolQ's low-level ABIs and provides users with modern C++ APIs.
- **[NoneBot](https://github.com/nonebot/nonebot)** (Python, 2016-2021): A chatbot framework that supports commands, message pattern matching, interactive sessions and more features, making interactive chatbot development quite convenient and intuitive, even possible for middle school students. Due to its easy-to-use API and detailed documentation, it has gained 1.8k stars on GitHub.
- [QDP](https://github.com/richardchien/qdp) (Python, 2018) & [OBTunnel](https://github.com/richardchien/obtunnel) (Rust, 2021): To verify the idea that it is possible to transmit arbitrary binary data through QQ messages, I designed and implemented a simple communication protocol called QDP, which has similar APIs to UDP. Later in 2021, I refined the idea and reimplemented the functionality in Rust, using TUN for compatibility with existing network stack.
- [BlogA](https://github.com/verilab/blog-a) & [VeriPress](https://github.com/verilab/veripress) & [PurePress](https://github.com/verilab/purepress) (Python, 2016-now): During learning, I love to write some notes or tutorials and post them on my blog. For a better blogging experience, I built my own blog engine in 2016, and kept refining it until now.
- [DBox](https://github.com/richardchien-archive/dbox) (Java, 2016-2017): A SQLite ORM library for Android built while I was learning Android development. It supports defining model classes with Java annotations and provides intuitive CRUD APIs.

### I Contributed

- While building a toy blog engine using Rust, I contributed a little bit to [Actix Web](https://github.com/actix/actix-web/pull/1934) and [Tera](https://github.com/Keats/tera/pull/597).
- While writing operating systems, I contributed a little bit to [Circle](https://github.com/rsta2/circle/pulls?q=is%3Apr+author%3Arichardchien).
- While automating the generation of API docs for my Python projects, I fixed a bug for [pdoc](https://github.com/pdoc3/pdoc/pull/153).

## Experience

### Jun 2022 - Now, Singularity Data, Database Engineer Intern

...

### Sep 2020 — Now, Institute of Parallel and Distributed Systems, Master Student

I have been working on a new microkernel operating system (ChCore) at IPADS. My work is mostly about refining the microkernel and its virtualization support, porting device drivers and POSIX applications, and refactoring the building system and user-level supporting libraries (LibChCore).

As my final project, I implemented Adaptive System Module for ChCore, with which one binary module can be dynamically loaded into either kernel land or user land without the need to rewrite or recompile any code, making the tradeoff between isolation/safety and performance more flexible.

### Jul 2018 — Aug 2018, Wuhan Jieyu Technology Co. Ltd., Software Engineer Intern

I participated in the development of both frontend and backend for a community operation product and an internal web console, using Vue.js for frontend and Tornado for backend. I had done all jobs assigned to me on time, and gained experience of online log analysis and team collaboration during the internship.

### Nov 2016 — Jan 2017 & Jul 2017 — Oct 2017, MiLove Entrepreneurial Team, Software Engineer

I was in charge of the maintenance of MiLove website and the customization of WordPress framework. I also built a [message forwarding tool](https://github.com/richardchien-archive/wechat-intercom) to forward messages between WeChat and Intercom, which helped improve the efficiency of customer service.

During the second period, I built a new backend for the e-commerce website using Django web framework.

### Jun 2016 - Aug 2016, VnetLink, Technical Support

I worked for VnetLink (a startup company that provides network traffic optimization service) as technical support. My responsibility was to help customers solve problems encountered while using our service.

## Open Source Contributions

### Jan 2017 — Now, OneBot & NoneBot Community

Leader of the OneBot & NoneBot community ([Bot Universe](https://github.com/botuniverse), [NoneBot](https://github.com/nonebot), [Kyubotics](https://github.com/kyubotics))

- Promoted the idea of open source in QQ chatbot community by creating CQHTTP (now OneBot standard) and NoneBot.
- Developed and maintained a large part of the ecosystem at the early days of the community.
- Mentored on three projects of the community in [Summer 2021 of Open Source Promotion Plan](https://nonebot.dev/ospp-2021.html).
- The community now has 8k stars on GitHub totally.

### Oct 2018 — Jun 2020, Changzhou University Open Source Association

Founder and leader of [CCZU OSA](https://github.com/cczu-osa)

- Founded the Open Source Association during my undergraduate to promote open source.
- Built a [chatbot](https://github.com/cczu-osa/aki) to help students achieve a better college life.
- Created and maintained some [TeX templates](https://github.com/cczu-osa/tex-templates).
- Gave a talk titled ["Beyond the Code"](https://www.bilibili.com/video/BV1Ut411y7vn/) to popularize open source knowledge.

## Talks

- "Modern CMake By Example" (Nov 3, 2021)
    - [Screen record](https://www.bilibili.com/video/BV1Yv4y1g7fq)
    - [Code](https://github.com/richardchien/modern-cmake-by-example)
- Paper Reading: "NrOS: Effective Replication and Sharing in an Operating System" (Jul 29, 2021)
    - [Paper](https://www.usenix.org/system/files/osdi21-bhardwaj.pdf)
    - [Slides](https://stdrc.cc/slides/nros/)
- "Why Write OS In Rust? v2.0" (Jul 2, 2021)
    - [Screen record](https://www.bilibili.com/video/BV1tP4y1x7h7)
    - [Slides](https://stdrc.cc/slides/write-os-in-rust-2.0/slides.html)
- "ChCoreCon #7: Why Write OS In Rust?" (Mar 1, 2021)
    - [Slides](https://stdrc.cc/slides/write-os-in-rust/slides.html)
- "Re-learn C++: Share A Tip of the Tip of the Iceberg of Modern C++" (May 30, 2020)
    - [Slides](https://slides.com/richardchien/cczu-osa-meet-cpp)
- "Training on Python and Chatbot Development" (Jan 12-16, 2019)
    - [Screen records](https://www.bilibili.com/video/BV19t411679V)
    - [Syllabus](https://shimo.im/docs/yb89I6ct1Ooy1mOA)
- "Beyond the Code" (Nov 24, 2018)
    - [Screen records](https://www.bilibili.com/video/BV1Ut411y7vn)
