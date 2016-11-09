# The Windows Research Kernel AKA WRK
Is a part of the source code of the actual windows NT Kernel.
WRK is designed for academic uses and research, by no means
it can be used for commercial purposes.


# Properties
This is actually part of the windows kernel, which means
you can find the source code of many kernel-level 
NT API functions, Structures & Data that is **not** defined in the
standard API headers.

# Uses
Since you can find here the full source codes of many APIs
and structures which aren't defined in the public headers
WRK can be used to study the kernel so you can actually
understand what is going on *'behind the scenes'*. You can find potential exploits or
make your kernel modules harder to reverse by using the
actual source of a structure/API instead of importing it from
ntoskrnl.exe.

# To Be Noted
This is not nearly the full source code of the kernel,
lots of files are missing or removed. Also, this code is still
somewhat protected (although leaked). Commercial use of this 
code is highly prohibited. Use only for personal and research
purposes.
