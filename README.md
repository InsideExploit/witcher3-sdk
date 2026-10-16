# witcher3-sdk

C++ SDK of The Witcher 3 next-gen (REDengine 3), dumped from the running game with [witcher3-dumper](https://github.com/InsideExploit/witcher3-dumper).

Each folder is one game build:

| Build | Folder |
| --- | --- |
| 5.0.1048522 (P4CL 13413172) | [`5.0.1048522`](5.0.1048522) |

| File | Contents |
| --- | --- |
| `Classes.hpp` | Classes and structs, script variables (`script()->name`) and functions. Natives carry their RVA. |
| `Enums.hpp` | Enums and bitfields. |
| `Asserts.hpp` | Size, alignment and offset checks. Include it in one translation unit. |
| `CVars.ini` | Config variables; `"witcher3.exe"+RVA` is each value's address. |
| `ExecCommands.html` | Console command reference. Open it in a browser. |
