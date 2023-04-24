

# Partition

A partition, or naming context, is a portion of the AD DS database. Although the database consists of one file named Ntds.dit, different partitions contain 
different data. For example, the schema partition contains a copy of the Active Directory schema. The configuration partition contains the configuration objects
for the forest, and the domain partition contains the users, computers, groups, and other objects specific to the domain. Active Directory stores copies of 
partitions on multiple domain controllers and updates them through directory replication.

# Schema

A schema is the set of definitions of the object types and attributes that you use to define the objects created in AD DS.

# Domain

A domain is a logical administrative container for objects such as users and computers. A domain maps to a specific partition and you can organize the domain with 
parent-child relationships to other domains.

# Domain tree

A domain tree is a hierarchical collection of domains that share a common root domain and a contiguous Domain Name System (DNS) namespace.

# Forest

A forest is a collection of one or more domains that have a common AD DS root, a common schema, and a common global catalog.

# OU

An OU is a container object for users, groups, and computers that provides a framework for delegating administrative rights and administration by linking Group 
Policy Objects (GPOs).

# Container

A container is an object that provides an organizational framework for use in AD DS. You can use the default containers, or you can create custom containers. You 
can't link GPOs to containers.
