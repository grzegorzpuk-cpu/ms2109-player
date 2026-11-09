# MS2109 Web Player (poprawiona wersja)

Strona: https://grzegorzpuk-cpu.github.io/ms2109-player/

Odtwarzacz dla tanich kart przechwytujących HDMI na układzie MacroSilicon MS2109, oparty na pomyśle z
[yume-chan/ms2109-player](https://github.com/yume-chan/ms2109-player).

Zmiany względem oryginału:
- rozpoznaje nowsze karty z VID `345f` (np. `345f:2109`), nie tylko `534d:2109`, a w razie potrzeby pozwala wybrać urządzenie ręcznie,
- osobno prosi o dostęp do kamery i mikrofonu i pokazuje błędy na ekranie zamiast czarnego ekranu,
- naprawiony dźwięk stereo (2 kanały wyjścia, wyłączone echo cancellation / noise suppression / AGC),
- wybór trybu obrazu (1080p 60/30/25, 720p) i dźwięku (konwersja przeplotu lub bez konwersji),
- działa także otwarta z dysku (`index.html`).

Działa w Chrome / Edge.
