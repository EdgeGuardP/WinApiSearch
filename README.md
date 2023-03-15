# WinApiSearch


Look Up For WinAPI, Search For WinAPI,  Make Your Work Easier, Save Time, Helpfull for C++


WinAPI Search app was designed primarily for Windows developers, researchers and malware reverse engineers. Its original goal was to provide a utility to search for Win32 functions by name, but this app later grew to include additional functionality.

The following features are supported:

Search a single or multiple binary PE files by Win32 function name.
Support for Regular Expressions in search strings.
Search for specific PE files using the following filters:
Bitness: 32-bit, 64-bit.
Search only in export table, import table, or "delay load" import table of the PE headers.
Ability to differentiate between C and C++ functions, as well as among ordinal function names and export table forwarded functions.
Support for API-Sets or Windows "umbrella" libraries.
Search by certain PE header subsystem, such as: boot application, console application, GUI application, native application, EFI driver, EFI ROM, Win9x, POSIX or OS/2 subsystem, Windows CE or XBox subsystem, etc.
Search by certain PE header characteristics, such as: use of ASLR, App Container, Control Flow Guard, Data Execution Prevention, support for Large Address Awareness, manifest isolation, no binding, no SEH, Terminal Server Awareness, buffer overrun checks, code integrity signature checks, and more.
Search by presence of certain PE header directories, such as: .NET & COM runtime discriptor, base relocation table, bound import directory, debug directory, delay-load import table, exception directory, export directory, import directory, import address table (IAT), load configuration directory, security directory, thread local storage (TLS), resources directory (with specific resource types) and more.
Search by a compilation timestamp date range.
Search for PE files that import a certain module (DLL) by its name.
Search for Win32 and HRESULT error codes using their numerical values.
Search for Win32 and HRESULT errors by their message text.
Ability to undecorate (or demangle) Microsoft-specific symbol names.
Check PE file for correctness, including its structure and layout.
For each API it can retrieve the following:
Linear file offset, as well as the mapped offset of the function.
What physical module (or file on disk) the function resolves to.
Distinguish whether the symbol refers to an executable function or to a global variable.
Other details about the PE file that were given above.
Overall this app can be used as a replacement for Microsoft's discontinued Dependency Walker.



Interface :

![awd](https://user-images.githubusercontent.com/127977328/225385826-4fbdf4df-aeda-4f2a-b004-173e6574eb12.jpg)
