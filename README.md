# n2sl_intern2
ssh n2sl@10.20.16.67 -p 51111
password: n2sl9341@#

//connecting from host
ssh intern@192.168.100.2
password: n2sl9341@#

Hi Ghayrat,

https://github.com/Mellanox/gpu_direct_rdma_access?tab=readme-ov-file



GitHub - Mellanox/gpu_direct_rdma_access: example code for using DC QP for providing RDMA READ and WRITE operations to remote GPU memory
example code for using DC QP for providing RDMA READ and WRITE operations to remote GPU memory - Mellanox/gpu_direct_rdma_access
github.com
This is a sample related to gpu_direct_rdma.
By default , the settings related to MLNX_OFED are set, so you can skip them.
You only need to set the GPU-specific settings.
This sample utilises RDMA to transfer data directly from the server to GPU memory.
There is a slight difference from the sample.
transfer data to GPU memory, which is the same thing.
However, you are utilising Bluefield-2 (smart NIC).
transferring data from Bluefield-2 memory to GPU memory. 
It would be good to know the difference and work with it.

Let me know if you don't understand something.

Thanks,
Hyunsu kim
