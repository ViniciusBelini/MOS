
# Simple Operating System Written in x86 Assembly and MOS (a Native OS and Assembly-based Language)

This project is the development of a **simple operating system** created using **x86 Assembly** language, alongside **MOS**, a custom assembly-based language designed specifically for this operating system. **MOS** serves as both the name of the operating system and a specialized language created for it. The goal of this project is to demonstrate the fundamentals of operating system design and development at a low-level, focusing on hardware interaction, system booting, memory management, and process handling.

**Key Features:**

-   **x86 Assembly**: The operating system is built using the x86 architecture, which is a widely-used instruction set for modern processors. It allows for direct interaction with the hardware, making it an excellent choice for low-level programming and learning how computers work under the hood.
    
-   **MOS (Custom Assembly Language and Operating System)**: MOS is a unique assembly language developed specifically for this operating system. It provides high-level abstractions for system tasks, making it easier to manage OS processes, system calls, and memory. The use of MOS illustrates how specialized languages can be created to cater to specific system requirements, with MOS representing both the operating system and the language that powers it.
    
-   **Bootloader**: The system features a bootloader that is capable of loading the operating system from disk into memory and starting the execution process. This is a critical part of the OS, as it is the first software to run when the computer is powered on or rebooted.
    
-   **Memory Management**: The OS implements basic memory management, providing mechanisms for allocating and freeing memory, as well as managing memory access rights. This ensures that different parts of the system and user programs do not interfere with each other.
    
-   **Kernel**: The heart of the operating system is its kernel, which is responsible for managing resources, scheduling tasks, and handling system calls. It provides the essential services that allow higher-level programs to interact with the hardware.
    
-   **Multitasking**: While basic, the OS supports rudimentary multitasking, allowing for the execution of multiple processes or tasks at the same time. This feature lays the foundation for more advanced process management and scheduling algorithms in the future.
    
-   **Filesystem**: The operating system includes a simple filesystem that allows basic file operations, such as reading and writing files, to be performed. This filesystem can be extended to support more complex features such as directories, file permissions, and file systems.
    
-   **System Calls**: MOS provides a set of system calls that allow user programs to interact with the underlying hardware through the kernel. This abstraction enables a clean separation between user space and kernel space, enhancing both security and stability.
    
-   **Text-Based User Interface (TUI)**: The operating system includes a basic text user interface (TUI) that allows users to interact with the system through simple command inputs. The TUI can display messages, prompt for input, and execute system commands, providing a foundation for further development of more advanced user interfaces.
    

#### Purpose:

This operating system was created as an educational project to help understand the core principles of operating system design and low-level programming. By building everything from scratch using Assembly, it offers a unique opportunity to dive into the intricacies of hardware communication, memory management, and kernel development. It also serves as a platform for experimentation and exploration of operating system concepts.

#### Development and Future Plans:

The current version of the operating system is basic but functional, with many features still in development. Future updates may include:

-   Support for more complex multitasking and process scheduling.
    
-   Enhancements to the memory management system, including virtual memory and paging.
    
-   Implementation of network support, allowing the OS to communicate over networks.
    
-   Expansion of the filesystem to support directories, file permissions, and more complex file operations.
    
-   Integration with graphical user interfaces (GUIs) for better user interaction.
    

This project is open-source, and contributions are welcome. If you're interested in exploring operating system development or want to learn more about low-level programming with Assembly, feel free to contribute or use this as a starting point for your own projects.
