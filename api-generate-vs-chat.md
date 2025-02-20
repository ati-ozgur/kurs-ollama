## API Generate vs chat

 



Aşağıda çevirisi yapılmış [Reddit yazısı](https://www.reddit.com/r/ollama/comments/1c96zr3/can_i_get_some_help_understanding_the_api_please/)

> Generate, sıfır atış (zero shot) cağrısıdır.
> Yani bir istek gönderirsiniz ve model bir yanıt üretir.
> Bu, konuşmanın sonudur. 

> Chat (sohbet), ileri geri konuşma yapabilir ve önceki aramaları bağlama dahil eder.


Aşağıdaki örnek [ollama github sorunlardan](https://github.com/ollama/ollama/issues/2774
) alınmıştır.


> Generate: Oluştur: Tek bir mesaj gönder ve yanıt al.

> Chat: tek bir mesaj ve önceki sohbet geçmişini gönderip yanıt alın.

TODO: Aşağıdaki test edin, birlikte sohbet etmek için iki mesaj mı göndermemiz gerekiyor yoksa tek tek mesajlar da işe yarıyor mu?


**İngilizce**

> What's the capital of France?
> LLM: Paris

> And what about Germany?
> LLM: ???

**Türkçe**
> Fransa'nın başkenti neresidir?
> LLM: Paris

> Peki ya Almanya?
> LLM: ???


## Diğer öğreticiler

- https://geshan.com.np/blog/2025/02/ollama-api/
