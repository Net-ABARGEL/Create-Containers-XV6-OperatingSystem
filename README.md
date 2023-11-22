Create Containers in XV6 Operating System

This project extends the XV6 operating system with containerization features. Containers provide a lightweight and portable way to encapsulate an application and its dependencies. This implementation allows the creation and management of containers within the XV6 operating system, providing a simple form of process isolation.

Features

Container Creation: Enables the creation of isolated containers within the XV6 operating system.
Process Isolation: Containers provide a level of process isolation, allowing multiple containers to run concurrently without interfering with each other.
Resource Management: Basic resource management features to allocate and control resources within containers.
Prerequisites

XV6 Operating System (make sure you have a working XV6 environment).

Usage

Clone XV6 Repository:
bash
Copy code
git clone https://github.com/mit-pdos/xv6-public.git
cd xv6-public
Copy Container Code:
Copy the container-related files into the XV6 source code directory.
Build XV6:
bash
Copy code
make
Run XV6:
bash
Copy code
make qemu
Create Containers:
Explore the commands or system calls to create and manage containers within the XV6 environment.

Contributing

Feel free to contribute by submitting issues or pull requests. Contributions are welcome!


Acknowledgments

This project is inspired by the need for containerization in resource-constrained environments.
Special thanks to the contributors and the XV6 community for their valuable feedback and support.

Author

Ido Abargel



