# go-ut-gen purpose
The intent of *go-ut-gen* is to take an existing Go module and autogenerate all zero-value
calls to all methods accessible in the module. 
Naturally, this will somethimes lead to faults or hangs. An option to *go-ut-gen* will invoke
Go test repeatedly to catch the faults and mark the method with *t.Skip()*
