## Notes about the Testbench
- **direct_read_during_write**: simultaneous read and write  
- **write_full_read_empty**: write until the FIFO is full, then read until it becomes empty  

## Notes about the UVM
- **my_case0**: simultaneous read and write  
- **my_case1**: write until full while also performing simultaneous read/write  
- **my_case2**: write until full and then read until empty  
- **define**: allows modifying read/write clock periods (RPERIOD, WPERIOD), FIFO data width (DSIZE), and FIFO depth (ASIZE, DATA_DEPTH)
