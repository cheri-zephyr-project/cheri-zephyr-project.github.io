---
title: Getting Started
feature_text: |
  ## Getting Started
feature_image: "https://picsum.photos/1300/400?image=989"
excerpt: "Getting Started"
---

<!-- Perhaps crib from / link to: https://www.thecapablehub.org/blog/cheri-zephyr-getting-started/ -->
Here you can find all the resources you need to help you get started. Below resources is a list of useful questions and answers.

### Resources
We have a number of collaboration sites:

* [CHERI-Alliance Github](https://github.com/CHERI-Alliance/CHERI-zephyr): All of our official releases and source files can be currently found on the CHERI-Alliance github under the CHERI-zephyr repository. This is the main go-to place for accessing our software. Here you will also find releases of other CHERI-related software and tools.
* [Our Github Repository](https://github.com/cheri-zephyr-project/): We also have a number of additional resources including the development of our website on our own github repository.
* [CHERI-Alliance projects](https://cheri-alliance.org/discover-cheri/cheri-products/): CHERI-zephyr is listed as one of the official CHERI-Alliance software products. Here you will find more information about CHERI and other CHERI-related software and hardware being developed.
* [The Capable Hub](https://www.thecapablehub.org/blog/cheri-zephyr-getting-started/): The Capable Hub is involved with quality and upstream alignment of open-source CHERI software. They are currently collaborating with us on Continous Integration workflows for CHERI-Zephyr and have written a good blog here on how to get started with CHERI-Zephyr.


### Questions and Answers

**Q1: Who is leading the development of CHERI-Zephyr?**

**A1:** The University of Birmingham is currently leading the development of CHERI-Zephyr with contributions from Durham University and support from Codasip. We also have Continous Integration support from the Capable Hub.


**Q2: Who is funding this work?**

**A2:** This work is supported by Innovate UK and the Department for Science, Innovation and Technology for the adoption and diffusion of CHERI technology under project 10167245 (“CHERI-Zephyr++: A memory-safe, lightweight real-time operating system for critical RISC-V embedded systems”)


**Q3: What is the CHERI-Alliance?**

**A3:** The CHERI-Alliance is a consortium of academia, industry and other organisations driving forward the adoption of CHERI to provide memory safe hardware.


**Q4: Who are the developers of CHERI-Zephyr?**

**A4:** All our core developers are members of the CHERI-Alliance. We have a CHERI-zephyr working group which can be used to influence our development. We are also open to external contributions.


**Q5: Can anyone use CHERI-Zephyr?**

**A5:** Yes, it is all open source, and closely follows the parent Zephyr project guidelines, maintaining Apache 2 licences.


**Q6: I don't have CHERI-hardware, can I still try out the technology?**

**A6:** Yes, you don't need CHERI-hardware to try it out. The CHERI tools come with QEMU CHERI emulation platforms that allow you to run CHERI-Zephyr applications as if they were running on real CHERI hardware.


**Q7: Do I need to be a CHERI expert to be able to write a CHERI-compatible app for CHERI-Zephyr?**

**A7:** No, most of the CHERI porting effort is in the operating system and drivers. You do not need to be a CHERI expert to write basic apps, most portable modern C is compatible if you use the right type for the job (e.g do not use unsigned long when you mean uintptr_t) There is a CHERI C++ guide available if you get stuck!


**Q8: Who should I contact if I find a CHERI bug?**

**A8:** You can raise an issue on the CHERI-Alliance repository or [contact us](/contact/).


**Q9: Are there plans to upstream this into the parent Zephyr Tree?**

**A9:** Yes, this is our long term goal, once toolchains and hardware has stabalised.
