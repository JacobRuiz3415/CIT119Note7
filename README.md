# CIT119Note7
## Main Points
- Volatile memory is a memory that is erased if the power is interrupted.
- This type of memory is commonly used in Ram memory.
- RAM memory is quick and easily accessible by the computer, but it gets deleted once a task ends;
- Nonvolatile is the memory that is permanently stored in a computer.
- This is also known as data storage.
- There are many things to protect your memory in case of disaster.
- Disaster recovery is a set tool and procedure for data recovery.
- Fault tolerance is the idea that the system will continue even if a component fails.
- You can design a system with this idea by having a single hard drive for backup.
- Replication in terms of data means creating a copy of the data or system.
- Replication is the most expensive of fault tolerance options, as it requires additional infrastructure for these backups.
- Redundancy tried to back up the entire system.
- Basically, you have backup infrastructure as a disaster contingency, but it runs at a reduced capacity.
- It should run long enough to repair the main system
- For an Enterprise, it might require more advanced tools for data storage.
- One simple tool for data replication is a Redundant Array of Independent Disks or RAID for short.
- As the name says, it is an array of connected Internal drives.
- The data is replicated data on many redundant drives.
- The most common RAID levels 1,5, and 6.
- Level 0 just uses two drives, and it can increase read speed, but it doesn’t create redundancy.
- in level 1, data in copied in two disks, but have the slowest read speed.
- Level 5 and Level 6 uses more disks to create fault tolerance.
- The data is backup once a month.
- A file server is an instance of a computer that accepts and responds to requests made by another program.
- The files need to be accessed by authorized users.
- Network Attached Storage or NAS  is a device that provides additional storage to a network.
- A storage Area network or SAN is a network dedicated to data storage.
- Cloud storage is a type of cloud computing where data storage is provided by a cloud provider via the internet.
- It is a pay-as-you-go model 
- There are three core types of cloud storage, Object, File, and Block.
- Object storage is when you store unstructured data.
- Amazon S3 is the core service for object storage in AWS.
- The service stores data objects in resources called “buckets.”
- Buckets can store up to 5 terabytes.
- EBS storage is where data from EC2 Instances are stored as volumes.
- Data from instances are stored in organized blocks.
## Quotes
- “With cloud storage, there is no hardware to purchase, storage to provision, or capital being used for "someday" scenarios. You can add or remove capacity on demand, quickly change performance and retention characteristics, and only pay for storage that you actually use. Less frequently accessed data can even be automatically moved to lower cost tiers in accordance with audit-able rules, driving economies of scale.”
- “S3 features include capabilities to append metadata tags to objects, move and store data across the S3 Storage Classes, configure and enforce data access controls, secure data against unauthorized users, run big data analytics, and monitor data at the object and bucket levels. Objects can be accessed through S3 Access Points or directly through the bucket hostname.”
## New facts
- Level 1+0 is a hybrid RAID that involves having two stripped sets of disks and then mirroring them.
- RAID 1+0 provides the best benchmark for systems such as databases.
- The AFR (Annual Failure Rate) of Amazon EBS is between 0.1% and 1%.
- Most home routers have a USB port for the connection of a hard drive as NAS
- S3 Glacier is good for archiving.
