Jak użyć:

1. Skopiuj zawartość tego ZIP do repo zmk-config-redoxft.
2. Zastąp istniejący build.yaml.
3. Dodaj folder boards/shields/redoxft_dongle.
4. Dodaj plik config/redoxft_dongle.conf.
5. Commit + Push.
6. W GitHub Actions powinny pojawić się pliki:
   - redox_left_peripheral-nice_nano-zmk.uf2
   - redox_right_peripheral-nice_nano-zmk.uf2
   - redoxft_dongle-nice_nano-zmk.uf2
   - settings_reset-nice_nano-zmk.uf2

Pierwsze uruchomienie dongle:

1. Wgraj settings_reset na lewą połówkę, prawą połówkę i dongle.
2. Wgraj redox_left_peripheral na lewą połówkę.
3. Wgraj redox_right_peripheral na prawą połówkę.
4. Wgraj redoxft_dongle na dodatkowe nice!nano używane jako dongle.
5. Podłącz dongle do komputera przez USB.
6. Włącz obie połówki.
7. Sparuj w systemie jako Redox FT albo używaj po USB przez dongle.

Uwaga:
Po przejściu na dongle klawiatura działa przez dongle. Bez dongle połówki nie będą normalnie pisać do komputera, bo centralą jest teraz dongle.
