# ctfbox

Docker image including ctf tools

* build-essential, gdb, strace, ltrace, netcat
* [socat](http://www.dest-unreach.org/socat/)
* [nmap](https://nmap.org/)
* [rp++](https://github.com/0vercl0k/rp)
* [peda](https://github.com/longld/peda)
* [angr](http://angr.io/), [z3py](https://github.com/Z3Prover/z3)
* [pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool)
* [qira](http://qira.me/)
* [afl](http://lcamtuf.coredump.cx/afl/)

## Usage

```
$ sudo docker run --privileged --net=host -it inaz2/ctfbox
```

* `--privileged` is required for gdb
* `--net=host` runs the container with host network
