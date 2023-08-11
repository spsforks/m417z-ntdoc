FileHandle HANDLE to File Object \
with locked region. \
IoStatusBlock IO result of function \
call. \
ByteOffset Offset in file where unlock \
region begins. \
Length Length of region to unlock. \
Key Pointer to 4\-bytes key associated \
with lock. See \
NtLockFile for additional information about locking by key \
usage.

Documented by: \
Reactos \
Tomasz Nowak \
Requirements:

Library: ntdll.lib

See also: \
NtCreateFile \
NtLockFile \
NtOpenFile \
NtReadFile \
NtReadFileScatter \
NtWriteFile \
NtWriteFileGather