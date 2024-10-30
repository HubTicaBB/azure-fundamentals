# Microsoft Azure Fundamentals: Describe cloud concepts

# 1 Describe Cloud Computing

> Cloud computing is the delivery of computing services over the internet.

Computing services include common IT infrastructure such as virtual machines, storage, databases, and networking. Cloud 
services also expand the traditional IT offerings to include things like Internet of Things (IoT), machine learning
(ML), and artificial intelligence (AI).

Because cloud computing uses the internet to deliver these services, it doesn’t have to be constrained by physical 
infrastructure the same way that a traditional datacenter is. That means if you need to increase your IT infrastructure 
rapidly, you don’t have to wait to build a new datacenter—you can use the cloud to rapidly expand your IT footprint.

Just like when you shop your own computer, cloud computing lets you choose the power and features you need for running 
software. The difference is, with cloud computing the PC is in the cloud provider's datacenter, instead of physically
with you. This let's you pay for only the services you use, plus someone else gets to manage the upkeep of the computer.

Each cloud provider will have their own selection of services you can choose from, but the basic services, provided by
all cloud providers, are:
- Compute power (how much processing your computer can do)
- Storage (the volume of data you can store on your computer)

## 1.1 The Shared Responsibility Model

Start with a traditional corporate datacenter. The company is responsible for maintaining the physical space, ensuring 
security, and maintaining or replacing the servers if anything happens. The IT department is responsible for maintaining 
all the infrastructure and software needed to keep the datacenter up and running. They’re also likely to be responsible 
for keeping all systems patched and on the correct version.

With the shared responsibility model, these responsibilities get shared between the cloud provider and the consumer. 
Physical security, power, cooling, and network connectivity are the responsibility of the cloud provider. The consumer 
isn’t collocated with the datacenter, so it wouldn’t make sense for the consumer to have any of those responsibilities.

At the same time, the consumer is responsible for the data and information stored in the cloud. (You wouldn’t want the 
cloud provider to be able to read your information.) The consumer is also responsible for access security, meaning you 
only give access to those who need it.

Then, for some things, the responsibility depends on the situation. If you’re using a cloud SQL database, the cloud 
provider would be responsible for maintaining the actual database. However, you’re still responsible for the data that 
gets ingested into the database. If you deployed a virtual machine and installed an SQL database on it, you’d be 
responsible for database patches and updates, as well as maintaining the data and information stored in the database.

With an on-premises datacenter, you’re responsible for everything. With cloud computing, those responsibilities shift. 
The shared responsibility model is heavily tied into the cloud service types (covered later in this learning path): 
- Infrastructure as a service (IaaS),
- Platform as a service (PaaS), and
- Software as a service (SaaS).

IaaS places the most responsibility on the consumer, with the cloud provider being responsible for the basics of 
physical security, power, and connectivity. On the other end of the spectrum, SaaS places most of the responsibility 
with the cloud provider. PaaS, being a middle ground between IaaS and SaaS, rests somewhere in the middle and evenly 
distributes responsibility between the cloud provider and the consumer.

The following diagram highlights how the Shared Responsibility Model informs who is responsible for what, depending on 
the cloud service type.
