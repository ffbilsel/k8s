<h1>Karşılaştığım Sorun</h1>

[opentelemetry-prometheus metric iletişimi makalesi](https://medium.com/@tathagatapaul7/opentelemetry-in-kubernetes-deploying-your-collector-and-metrics-backend-b8ec86ac4a43)

[opentelemetry kubernetes deployment](https://medium.com/opentelemetry/deploying-the-opentelemetry-collector-on-kubernetes-2256eca569c9)

Üstteki makaleler opentelemetry'nin uygulamayla aynı podda çalıştığını gösterir şekilde. Veriyi opentelemetry okuyor. Fakat [node.js metric oluştucu] linkinde uygulama metricleri direkt prometheus'a göndermeye çalışıyor. Başka türlü çalışan uygulama bulamadım. Sonuçta prometheus'ta metric okuyamadım.

Bu tutoriallar sonucu yazdığım kodları ekliyorum.
