## Run: Model Çalıştırma

```bash
ollama run --help
```

```bash
ollama run model-adi süfle [opsiyonlar]
```
[] arasındakiler verilmeyebilir.

Örneğin:

```bash
ollama run phi
```

Eğer model yerelde yoksa, kütükten indirilir ve arkasından çalıştırılır.
Aşağıda, yukarıdaki komutun sonucunu görebilirsiniz.


```text
ollama run phi 
pulling manifest
pulling 04778965089b... 100% ▕███████████████████████████████████████████████████████████████████████▏ 1.6 GB 
pulling 7908abcab772... 100% ▕███████████████████████████████████████████████████████████████████████▏ 1.0 KB 
pulling 774a15e6f1e5... 100% ▕███████████████████████████████████████████████████████████████████████▏   77 B 
pulling 3188becd6bae... 100% ▕███████████████████████████████████████████████████████████████████████▏  132 B 
pulling 0b8127ddf5ee... 100% ▕███████████████████████████████████████████████████████████████████████▏   42 B 
pulling 4ce4b16d33a3... 100% ▕███████████████████████████████████████████████████████████████████████▏  555 B 
verifying sha256 digest
writing manifest
success
>>> Send a message (/? for help)
```


Aşağıdaki komut süfleye verilen cevabı gösterir ve tekrar komut satırına döner


```bash
ollama run phi "What is your name"
```

### Opsiyonlar

- --format json ile sonucun json olmasına çalışılır.
- --keepalive modelin ne kadar süre hafızada tutulacağı



