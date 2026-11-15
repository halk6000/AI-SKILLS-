---
name: testowanie
description: Stosuj przy testowaniu projektów i organizowaniu piaskownicy Windows.
---
# Testowanie

- W katalogu roboczym piaskownicy trzymaj folder kodu nazwany według projektu, testlogic (logika testów, np. PS1) oraz test (uruchamialne BAT).
- Pliki BAT uruchamiają właściwą logikę z testlogic; nie duplikuj jej.
- Izoluj procesy i ogranicz ich uprawnienia. Sam osobny katalog nie jest granicą bezpieczeństwa.
- Testuj zmienione działanie i ważne zależności; nie powtarzaj udanych testów bez powodu.
- Rozróżniaj wyniki rzeczywistych testów od przypuszczeń.
