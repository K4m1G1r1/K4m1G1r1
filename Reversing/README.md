# 🧠 Reversing — The Binary Altar

*Binaries whisper. I listen and make them scream.*

Esta carpeta es el laboratorio de ingeniería inversa: Android, ELF, PE, firmware, y otras corrupciones.

## Subcarpetas

- ![android](/Reversing/android/) — apks, smali notes, frida scripts
- ![elf_pe](/Reversing/elf_pe/) — binarios Linux/Windows, gdb notes
- ![firmware](/Reversing/firmware/) — dumps, binwalk results
- ![tools](/Reversing/tools/) — scripts útiles (frida snippets, patchers)
- ![CVE-studies](/Reversing/CVE_studies/) — CVEs encontrados y estudiados

## Workflow por experimento

1. **Snapshot** — binario original en `artifacts/`
2. **Static** — strings, binwalk, jadx/Ghidra notes
3. **Dynamic** — frida scripts, hooking, debugging logs
4. **Patch / PoC** — parche o PoC reproducible
5. **Reflections** — vulnerabilidad, posible CVE, mitigación
