# Лаборатори №6: Category-Partition ба PICT

**Оюутны нэр:** Ч.Оюумаа  
**Оюутны код:** B232270133

F.CSA313 — Программ хангамжийн чанарын баталгаа ба тест (2026)

## Алхам 1: PICT-ийг эх кодоос бүтээх

- Орчин: macOS (Apple Silicon), Homebrew-ээр `cmake` суулгасан, Xcode Command Line Tools.
- PICT-ийн эх кодыг лабын репоосоо гадна `~/tools/pict` хавтаст clone хийв.
- `cmake -S . -B build -DCMAKE_BUILD_TYPE=Release` болон `cmake --build build -j4` командаар бүтээж, `build/cli/pict`-ийг `/usr/local/bin/` руу хуулав.
- Нотолгоо: [`results/pict-build.txt`](results/pict-build.txt) — PICT-ийн commit болон хэрэглээний заавар.
- PICT-ийн эх код болон `build/` хавтас энэ репод ороогүй (`.gitignore`-д нэмсэн).
