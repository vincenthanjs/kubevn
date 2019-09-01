# kubevn
kubevn will be a collections of yaml, as a start for virtual network and security objects. This idea was inspired by Jared when he talks about "platforms platforms" described by Joe Baeda. 

The thought that came across my mind after understanding about project pacific, if now kubernetes can be extended to create VM workloads, how about networking and security objects? Why can't we use the same deployment specifications in YAML to mix VM workloads and Virtual Networks(VN) in a single deployment as well?







https://blogs.vmware.com/vsphere/2019/08/project-pacific-technical-overview.html
Virtual Machines

The supervisor includes a Virtual Machine operator that allows kubernetes users to manage VMs on the Supervisor. You can write deployment specifications in YAML that mix container and VM workloads in a single deployment that share the same compute, network and storage resources.

The VM operator is just an integration with vSphere’s existing virtual machine lifecycle service, which means that you can use all of the features of vSphere with kubernetes managed VM instances. Features like RLS settings, Storage Policy, and Compute policy are supported.

In addition to VM management, the operator provides APIs for Machine Class and Machine Image management. To the VI admin, Machine Images are just Content Libraries.
