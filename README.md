# shm
**Find shmem files in linux system**

It's not my work, I found it on [StackExchange](https://unix.stackexchange.com/questions/482795/can-i-see-the-amount-of-memory-which-is-allocated-as-gem-buffers/483006#483006).

Example:

    root@gdh:~# shm -s
    852	/
    81408	/SYSV*
    0	/[aio]
    344	/dev/zero
    2048	/memfd:cubeb-shm-1423561-23-input
    2048	/memfd:cubeb-shm-1423561-23-output
    280056	/memfd:mozilla-ipc
    3112	/memfd:pulseaudio
    7556	/memfd:xorg
    12	/memfd:xshmfence
    377436
