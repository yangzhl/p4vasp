# make doc

* first you need to install epydoc
`pip install epydoc` or `pip install -r  ./requirement.txt`

* when use `make doc`, you may encounter this problem 
>| Import failed (but source code parsing was successful).
>|     Error: ImportError: dlopen(*/p4vasp/lib/_cp4vasp.so, 2): no suitable image found.  Did find:
>|                    *p4vasp/lib/_cp4vasp.so: unknown file type, first eight bytes: 0x7F 0x45 0x4C 0x46 0x02 0x01 0x01
>|            0x00
>|                    */p4vasp/lib/_cp4vasp.so: unknown file type, first eight bytes: 0x7F 0x45 0x4C 0x46 0x02 0x01 0x01
>|            0x00 (line 22)
>| 



