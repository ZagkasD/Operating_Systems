Two projects for the course Operating Systems.

The first one is the parallelization of the get and put functions of a Kiwi storage engine based on a log-structured merge stree. The storing is implemented on two layers (similar to ram and storage) and the parallelization is done with Linux's Pthread library.

The second one is the implementation of a journal about all the modifications happening in the system file of a linux kernel. The kernel is in directory format and the journal is done in the system file FAT of the kernel's library.
