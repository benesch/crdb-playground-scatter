# scatter testing

```bash
./balance 4 ~/Downloads/allocatortest-1node-10g-262ranges-store1/ 10g-4nodes
./boot-cluster 10g-4nodes --vmodule=allocator=3,replicate_queue=3,queue=3,store_pool=2,store=2,replica=1,replica_command=2,rule_solver=3
sleep 30
./restore tpch10
```
