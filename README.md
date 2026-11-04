# CacheFuse

Cache anahtarını yalnızca belirtilen girdilerin deterministik özetinden türetir.

## Girdi

values ve keys.

## Kullanım

Python 3.11+, standart kütüphane.

```sh
python cachefuse.py input.json
python verify.py
```

Dosya verilmezse stdin okunur. Sonuç stdout üzerinde JSON olarak yazılır. Girdi hatası çıkış kodu 2 üretir.

Örnek sonuç:

```json
"44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a"
```
