## Copy: Model kopyalama



```bash
ollama cp deepseek-r1:1.5b ds15
```

Bu komut model ağırlık dosyalarını kopyalamaz.
Docker mantığında bir sanal yeni model manifestosu yaratır.
Ama asıl büyük dosyalar olan ağırlık dosyaları kopyalanmaz.


```bash
cd $OLLAMA_MODELS
tree
du -h
```
