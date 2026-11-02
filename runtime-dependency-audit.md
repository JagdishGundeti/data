# Runtime dependency audit

- Status: **TECHNICAL_INVENTORY_COMPLETE_LEGAL_APPROVAL_NOT_ASSESSED**
- Package: `RTLAnalysisStudio-20261102-024031Z.zip`
- Package SHA-256: `7D214766A2C42DE2DAF5AF844052E3FF8A6950AC53637FD61F43CFABE1F061B0`
- Application SHA-256: `6A1E56E3ECF3393F21F910A082D29CB34BA681D8250FDD6337A381FDC8384DCE`
- Architecture: **x64**
- ZIP entries: **78**; forbidden entries: **0**

## Direct executable imports

| DLL | Classification | In package | Host runtime version | Host runtime SHA-256 |
|---|---|---:|---|---|
| `api-ms-win-crt-convert-l1-1-0.dll` | Windows OS component | False |  | `` |
| `api-ms-win-crt-filesystem-l1-1-0.dll` | Windows OS component | False |  | `` |
| `api-ms-win-crt-heap-l1-1-0.dll` | Windows OS component | False |  | `` |
| `api-ms-win-crt-locale-l1-1-0.dll` | Windows OS component | False |  | `` |
| `api-ms-win-crt-math-l1-1-0.dll` | Windows OS component | False |  | `` |
| `api-ms-win-crt-runtime-l1-1-0.dll` | Windows OS component | False |  | `` |
| `api-ms-win-crt-stdio-l1-1-0.dll` | Windows OS component | False |  | `` |
| `api-ms-win-crt-string-l1-1-0.dll` | Windows OS component | False |  | `` |
| `comctl32.dll` | Windows OS component | False |  | `` |
| `gdi32.dll` | Windows OS component | False |  | `` |
| `kernel32.dll` | Windows OS component | False |  | `` |
| `mfc140u.dll` | Microsoft runtime / MFC â€” redistribution and deployment review | False | 14.44.35211.0 | `643CE7FE6A203C53A96A00F272A1A5B42D5B0C320C84364A6FE866307A19BB65` |
| `msvcp140.dll` | Microsoft runtime / MFC â€” redistribution and deployment review | False | 14.44.35211.0 | `0F885B509A685D2BBFA652FED26B5FB31D88FBDAB0A978C641D1C7B8AA460AA9` |
| `user32.dll` | Windows OS component | False |  | `` |
| `vcruntime140.dll` | Microsoft runtime / MFC â€” redistribution and deployment review | False | 14.44.35211.0 | `D5E4D9A3E835FA679450145D6A7D94E36573A509317111904D9B3712C30D9066` |
| `vcruntime140_1.dll` | Microsoft runtime / MFC â€” redistribution and deployment review | False | 14.44.35211.0 | `1F2D41C4AA5DB0BC33EBF7B66D72943A817D7CE6CBE880502A9403823633093F` |

## External tool evidence

### Slang
- Status: CAPTURED
- Path: `C:\Dev\xCode\chips\slang-windows-x86_64\slang.exe`
- Version output: `slang version 12.0.0+545f88b2e`
- SHA-256: `2487DD3B42A8052C8EEBBEAAA4ED6FE18FFDEFDBF0D42818EDB14B7AB725D304`

### Verilator
- Status: NOT_SUPPLIED

## Scope limitations
- This inventory parses the executable direct PE import table; it does not resolve transitive DLL imports or delay-loaded dependencies.
- A hash and version string establish identity evidence, not license rights or legal approval.
- Slang and Verilator are user-installed and are not bundled by the project release script.
- Microsoft runtime/MFC redistribution eligibility must be confirmed against the actual Visual Studio edition/toolset terms.

This report is technical inventory evidence only. It is not legal advice or a redistribution approval.
