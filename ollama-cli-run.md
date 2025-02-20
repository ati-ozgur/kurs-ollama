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


Aşağıdaki komut süfleye verilen cevabı gösterir ve tekrar komut satırına döner

```bash
ollama run phi "What is your name"
```

### Opsiyonlar

- --format json ile sonucun json olmasına çalışılır.
- --keepalive modelin ne kadar süre hafızada tutulacağı



