
[<<< Previous](text-editors.md) | [Next >>>](computing-in-humanities.md)


## Cloud-based Versus Local-Based environments

When doing an introductory coding workshop, instructors choose between using the local environment or a cloud bases environment. There are good pedagogical reasons for each choice. 
[Cloud-based Versus Local-Based Web Development Education: An Experimental Study in Learning Experience](https://files.eric.ed.gov/fulltext/EJ1144677.pdf)

Local = your laptop or desktop.
Cloud = not your computer, another server(s) in the 'cloud' (internet) such as M II or Github. 

## Since we are doing this DHRI online, we have chosen to do our computing workshop using containers

### Cloud based environments 
Some workshops will have you use notebooks rather than intstalling software. If you continue to learn coding, and take SMU OIT workshops in the future, you will be set up with [M II HPRC (ManeFrame II: High-Performance Research Computing) accounts](https://www.smu.edu/OIT/Services/HPC) where you may use notebooks. 
    * Advantages:
M II is already set up to work well on any device, and will have software pre-installed accessible via Internet.
Ownership and group access (access is contingent upon association with SMU)
You don’t have to install any software on your own computer.

Cloud based notebooks give instructors: 
More control on what we give access to for participants.
Can create structured projects for participants.
Versions are more controlled compared to installed versions.
Reproducible and sharable
Less reliant on strength of computer.

You may also see references to [Jupyter notebooks](https://jupyter.org/ ) in other digital humanities workshops.  


### Local Installations
* Local installations give you more control, more power, but the pedagogical tradeoff is that it is more difficult to manage and configure during class. Installation is dependent on type of device. Access to HPC is also contingent on circumstances, you may not have access to HPC in the future. 
The process of installing and learning how to work on your computer encourages more active troubleshooting as well, which is a useful long-term skill.
See also: [Minimal Computing](https://go-dh.github.io/mincomp/about/) 


### Containers
* Containers are a type of [operating system virtualization](https://en.wikipedia.org/wiki/OS-level_virtualization) where a single kernel is shared by all operating systems. This is contrasted with virtual machines that provide a virtualized hardware environment upon which an operating system can run. Containers, as such, are light weight compared to virtual machines, but are restricted to a single kernel type, e.g. Linux. The primary benefits on containers are:

* Isolation
* Reproducibility
* Portability

Singularity and Docker are popular toolsets used to create and manage containers on Linux. For security reasons, Docker is not usually allowed on HPC systems and this includes M2. M2 does have Singularity, which is largely compatible with Docker containers.

[Explnation from: Creating Portable Environments with Singularity and Docker](https://github.com/SouthernMethodistUniversity/singularity_docker)

We will be using Docker containers in the next workshop. 

#### Additional Discussion: 
What is elided in the process of computational work when using the HPC/HPRC? (We will return to this questions in the Data session as well)
"...valorizations of “the cloud” take  it  as  an  unquestioned  good  that  researchers  will  be  able to turn on the spigot without talking to a plumber – the point is that researchers should just be able to get on with their work and scale it in a relatively unregulated way. It is important to ask why that is held up as a necessary good" -[Digital Humanities Application Development in the Cloud](https://dl.acm.org/doi/pdf/10.1145/3355738.3355753?download=true)


"If you just graduated a software/data carpentry boot camp and want to go beyond your laptop’s capabilities, the next step in academia is typically to approached the data center of your university or alike. There, a user account application has to be filed for the High Performance Computing (HPC) facilities. After some more formalities, storage and computing time is awarded and you can successfully log into the cluster. And then? .... We will discuss this in the next section. -[From Sofware Carpentry site](https://software-carpentry.org/blog/2017/06/hpccarpentry.html )

# What is "Humanities High-Performance Computing"?

The term "high performance computing" (HPC) is often used interchangeably with "supercomputing." 
It refers to very fast computers, capable of performing calculations many times faster than standard desktop machines. 
High Performance Computing is used mainly by scientific disciplines for processing huge amounts of data, data mining, and simulation. 
[Humanities High-Performance Computing (HHPC)](https://www.neh.gov/divisions/odh/resource-library/humanities-high-performance-computing-resource) refers to the use of high-performance machines for humanities and social science projects. Humanities scholars often deal with large sets of unstructured data. This might take the form of historical newspapers, books, election data, archaeological fragments, audio or video contents, or a host of others.


[<<< Previous](text-editors.md) | [Next >>>](computing-in-humanities.md)

------

[<<< Return to introduction](https://github.com/SouthernMethodistUniversity/coding)
