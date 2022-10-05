For several years, programmability has become increasingly important in network architectures. A first generation of programmable networks was born ten years ago with the Software Defined Networking (SDN) concept and its implementations (OpenFlow) which offers a first level of control plane programmability. Then, the Network Function Virtualization (NFV) was introduced to enable the deployment of software functions. Today, the data plane programmability, mainly instantiated by P4 that further extends the concept of network programmability, is approaching.

In parallel, a new trend to finely split services into micro-services appeared. The expected benefits rely on an easier development and maintenance, better quality, scalability and responsiveness to new scenarios than monolithic approaches, while offering more possibilities for operators and management facilities through orchestration.
As a consequence, it appears that network functions, such as routing/switching, filtering, field translation, etc. can be split in several micro-services, implemented through different means, according to the software environments, and at different topological locations, thus opening the way to fully end-to-end programmable networks.

In this context, the fundamental question of the placement (topological location) and the execution environment (support node, such as a container or P4-based) of network functions, and more specifically micro-services that compose them, arises.

To date, even if some proposals start to include several networking programmable technologies (i.e. ONOS integrating SDN and P4), none of them consider a global end-to-end orchestration providing a multilevel and multi-technology abstract view for the optimization of network services finely cut into microservices, neither offer advanced network service orchestration algorithms.

This need for multi-level and multi-technology orchestration is even more important with the emergence of new services, such as immersive services, which exhibit very strong quality of service constraints (i.e. latency cannot exceed a few milliseconds), while preserving end-to-end security. In the project we will focus on such immersive services, and taking as example the use-case of a telesurgery and a remote drone operation.

In this context, the MOSAICO (Multi-layer Orchestration for Secured and low lAtency applICatiOns) project proposes to design, implement and validate a global and multi-layer orchestration solution, able to control several underlying network programmability technologies to compose micro-services forming the overall network service.

For further information: https://www.mosaico-project.org/
