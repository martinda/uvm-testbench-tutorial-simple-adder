# How to run

This is an example of the `-exitstatus` command line option.

To run the simulation you just need to type:

```
make -f Makefile.vcs
```

To check the exit status:

```
echo $?
```

With `-exitstatus`, we expect the exit status to be non-zero, but it return zero. Why?

# Original code

This is a fork of another repository, modified to examplify the `exitstatus` command line option.

The original UVM testbench documentation can be found at: http://colorlesscube.com/uvm-guide-for-beginners/
