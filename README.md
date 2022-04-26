# network-regular-check
Tracing if "specific log" occurred under a log file and trigger "required commands".

"specific log" considered as "SFF unsupported type" in this case..

"required commands" considered as "configure port x/x/x shutdown" and "configure port x/x/x no shutdown"

P.S: "specific log" and "required commands" can be anything as per requirement. 

Paramiko: 

Paramiko is a pure-Python (2.7, 3.4) implementation of the SSHv2 protocol, providing both client and server functionality. It provides the foundation for the high-level SSH library Fabric, which is what we recommend you use for common client use-cases such as running remote shell commands or transferring files.
