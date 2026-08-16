# AgentSpace — Blueprint Engine

Bu klasör AgentSpace'in **Metodolojik Şablon Motorunu** (Blueprint Engine) içerir.

## Nasıl Çalışır?

Yeni bir proje açıldığında kullanıcı bir blueprint seçer.
Ajanlar, göreve başlamadan önce bu blueprint'i okur ve
tüm kuralları, klasör yapısını ve standartları hafızasına yükler.

## Önemli Kural

Blueprintler **tasarım SÜREÇ kurallarını** içerir.
Bir önceki projenin rengi, görseli veya UI'si 1-1 kopyalanmaz.
Her yeni proje görsel olarak tamamen özgün olur, kalite süreç olarak tutarlı kalır.

## Blueprint Listesi

| Dosya | Proje Tipi |
|---|---|
| `_base.yaml` | Tüm blueprint'lerin miras aldığı evrensel kurallar |
| `mobile-react-native.yaml` | React Native / Expo mobil uygulamaları |
| `web-nextjs-fullstack.yaml` | Next.js tam yığın web uygulamaları |
| `backend-node-microservice.yaml` | Node.js/Express mikro servisler |
| `backend-rust-service.yaml` | Rust + Actix/Axum yüksek performanslı servisler |
| `ml-python-pipeline.yaml` | Python tabanlı ML/AI pipeline'ları |
