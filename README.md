Bypassing Event Tracing for Windows (ETW) in golang.

A simple Python script that first checks if NtProtectVirtualMemory and NtAllocateVirtualMemory are hooked or not. Then it loads the ntdll.dll with LoadLibrary and gets the address of the function EtwEventWrite using GetProcAddress. Finally, it writes the patch bytes into the process.
