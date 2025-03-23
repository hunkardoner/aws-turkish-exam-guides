
# AWS Certified Developer - Associate (DVA-C02) Sınav Kılavuzu (Türkçe)

---

## 📄 Sayfa 1

### Giriş

AWS Certified Developer - Associate (DVA-C02) sınavı, geliştirici rolünü üstlenen bireyler için tasarlanmıştır.
Bu sınav, bir adayın AWS bulut tabanlı uygulamaları geliştirme, test etme, dağıtma ve hata ayıklama konularındaki yetkinliğini ölçer.

Ayrıca adayın şu görevleri yerine getirme becerisini doğrular:
- AWS üzerinde uygulamalar geliştirme ve optimize etme.
- Sürekli entegrasyon ve dağıtım (CI/CD) iş akışları kullanarak paketleme ve dağıtım gerçekleştirme.
- Uygulama kodu ve verilerini güvenli hale getirme.
- Uygulama hatalarını tespit etme ve çözme.

### Hedef Aday Tanımı

Hedef adayın, AWS hizmetleriyle uygulama geliştirme ve sürdürme konusunda en az 1 yıllık doğrudan deneyime sahip olması beklenir.

### Genel BT Bilgisi Önerisi

- En az bir üst seviye programlama dilinde yetkinlik
- Uygulama yaşam döngüsü yönetimini anlama
- Bulut tabanlı uygulamalarda kod yazmaya dair temel bilgi
- İşlevsel uygulama geliştirme becerisi
- Geliştirme araçlarını kullanma deneyimi

### AWS Bilgisi Önerisi

- AWS API’leri, CLI ve SDK’lar ile uygulama geliştirme ve güvenli hale getirme
- AWS üzerinde CI/CD hattı ile uygulama dağıtımı

---

## 📄 Sayfa 2

### Hedef Adayın Sınav Kapsamı Dışındaki Görevleri

- Mimariler tasarlamak (örneğin: dağıtık sistemler, mikro hizmetler, veritabanı şemaları)
- CI/CD hatlarını tasarlamak ve oluşturmak
- IAM kullanıcıları ve gruplarını yönetmek
- Sunucuları ve işletim sistemlerini yönetmek
- AWS ağ altyapılarını tasarlamak (örneğin Amazon VPC, AWS Direct Connect)

### Sınav İçeriği

#### Soru Tipleri

- Çoktan Seçmeli: Bir doğru ve üç yanlış seçenek içerir
- Çoklu Yanıt: Beş veya daha fazla seçenekte iki veya daha fazla doğru yanıt vardır

Boş bırakılan sorular yanlış sayılır; tahmin yapmanın cezası yoktur.

#### Puanlanmayan İçerik

Sınavda ayrıca 15 puanlanmayan soru vardır. Bu sorular, gelecekte kullanılmak üzere test edilir ve sınavda belirtilmez.

---

## 📄 Sayfa 3

### Sınav Sonuçları

- Sınav sonucu 100–1000 arası ölçekli puan ile verilir. Geçer not: 720.
- Telafi edici puanlama modeli uygulanır: her bölümde geçme şartı yok, sadece toplam puan dikkate alınır.
- Bazı bölümler daha fazla soru içerir.

---



---

## 📄 Sayfa 6

### İçerik Alanı 2: Güvenlik

#### Görev 1: Kimlik Doğrulama ve Yetkilendirme

**Bilgi Gereksinimleri:**
- Kimlik federasyonu (SAML, OIDC, Amazon Cognito)
- Bearer token’lar (JWT, OAuth, AWS STS)
- Cognito kullanıcı ve kimlik havuzları farkı
- Resource, service ve principal bazlı politikalar
- Role-based access control (RBAC)
- ACL ile uygulama yetkilendirmesi
- Least privilege ilkesi
- AWS managed ve customer managed policy farkları
- IAM bilgisi

**Beceri Gereksinimleri:**
- Cognito ve IAM ile federasyon uygulama
- Bearer token ile uygulama güvenliği
- Programatik erişimi yapılandırma
- IAM role assume etme
- Yetkilendirme için policy tanımlama

#### Görev 2: Şifreleme Uygulama

**Bilgi Gereksinimleri:**
- Dinlenme/aktarımda şifreleme
- Sertifika yönetimi (AWS Private CA)
- Anahtar koruma ve rotasyonu
- Client-side vs server-side şifreleme farkı
- AWS managed vs customer managed KMS key farkı

**Beceri Gereksinimleri:**
- Şifreleme anahtarları ile veri şifreleme/çözme
- Geliştirme için sertifika ve SSH key üretme
- Hesaplar arası şifreleme
- Key rotation yönetimi

---

## 📄 Sayfa 7

#### Görev 3: Uygulama Kodunda Hassas Veri Yönetimi

**Bilgi Gereksinimleri:**
- Veri sınıflandırması (PII, PHI)
- Ortam değişkenleri
- Secrets Manager ve Parameter Store kullanımı
- Kimlik bilgilerini güvenli şekilde yönetme

**Beceri Gereksinimleri:**
- Ortam değişkenlerini şifrelemek
- Secrets Manager ile güvenli veri yönetimi
- Verileri sanitize etme

---

## 📄 Sayfa 8

### İçerik Alanı 3: Deployment

#### Görev 1: Artifact Hazırlama

**Bilgi Gereksinimleri:**
- Uygulama yapılandırma verilerine erişim (AppConfig, Secrets Manager)
- Lambda paketleme, katman ve konfigürasyon seçenekleri
- Git kullanımı
- Container image’lar

**Beceri Gereksinimleri:**
- Paket bağımlılıkları ve yapılandırmaları yönetme
- Dizin yapısı düzenleme
- Repository kullanımı
- Kaynak gereksinimlerini uygulama

#### Görev 2: Uygulama Testi

**Bilgi Gereksinimleri:**
- AWS dağıtım servisleri
- Mock endpoint entegrasyonu
- Lambda alias’ları ve versiyonları

**Beceri Gereksinimleri:**
- AWS ile test etme
- Entegrasyon bağımlılıklarını çözme
- API Gateway stage’lerini yapılandırma
- AWS SAM ile farklı ortamlara dağıtım yapma

---

## 📄 Sayfa 9

#### Görev 3: Otomatik Dağıtım Testleri

**Bilgi Gereksinimleri:**
- API Gateway stages
- CI/CD akışında branch’ler ve aksiyonlar
- Otomatik test türleri

**Beceri Gereksinimleri:**
- JSON payload test olayları oluşturma
- API kaynaklarını farklı ortamlara deploy etme
- Lambda alias, container tag, Amplify branch ile test ortamı oluşturma
- AWS SAM ve CloudFormation ile IaC uygulama
- Ortamları ayırt ederek yönetme (dev/test/prod)

#### Görev 4: AWS CI/CD ile Kod Dağıtımı

**Bilgi Gereksinimleri:**
- Git
- AWS CodePipeline approval süreçleri
- AppConfig, Secrets Manager entegrasyonu
- CI/CD iş akışları ve araçları (CDK, SAM, CodeArtifact, Amplify)
- Lambda paketleme yöntemleri
- Deployment stratejileri: canary, blue/green, rolling

**Beceri Gereksinimleri:**
- IaC şablonlarını güncelleme
- Ortamları yönetme
- Dağıtım stratejileriyle versiyon dağıtma
- Repository’ye commit ile build/test/deploy tetikleme
- Farklı ortamlara orchestrated deployment
- Rollback uygulama
- Versiyon yönetimi için tag/branch kullanımı
- Runtime konfigürasyon ile dinamik deployment

---

## 📄 Sayfa 10

### İçerik Alanı 4: Troubleshooting & Optimization

#### Görev 1: Root Cause Analysis

**Bilgi Gereksinimleri:**
- Logging ve monitoring sistemleri
- Logs Insights sorgu dili
- Veri görselleştirme
- Kod analiz araçları
- HTTP hata kodları
- SDK exception türleri
- AWS X-Ray service maps

**Beceri Gereksinimleri:**
- Kod debug etme
- Metrik, log ve trace yorumlama
- Log sorgulama
- CloudWatch EMF ile özel metrik oluşturma
- Dashboard kullanımı
- Deployment hatalarını log ile analiz etme

---

## 📄 Sayfa 11

#### Görev 2: Observability için Kod Enstrümantasyonu

**Bilgi Gereksinimleri:**
- Distributed tracing
- Logging vs monitoring vs observability
- Structured logging
- Metrik türleri (custom, embedded, built-in)

**Beceri Gereksinimleri:**
- Logging stratejisi uygulama
- Custom metric yayan kod yazma
- Trace için annotation ekleme
- Alarm/uyarı bildirimleri oluşturma
- AWS ile distributed tracing gerçekleştirme

---

## 📄 Sayfa 12

#### Görev 3: Uygulamaları Optimize Etme

**Bilgi Gereksinimleri:**
- Caching
- Concurrency
- Messaging servisleri (SQS, SNS)

**Beceri Gereksinimleri:**
- Performans profiling
- Minimum kaynak tespiti
- Filter policy kullanımı
- Request header’a göre cache

---

## 📄 Sayfa 13

### Ek Bilgiler

**Sınavda Yer Alabilecek Kavramlar:**
- Analytics
- Application Integration
- Compute
- Containers
- Database
- Developer Tools
- Governance
- Networking
- Security
- Storage


---

## 📄 Sayfa 4

### İçerik Alanı 1: AWS Hizmetleri ile Geliştirme

#### Görev 1: AWS üzerinde barındırılan uygulamalar için kod geliştirme

**Bilgi Gereksinimleri:**
- Mimarî desenler (örneğin: event-driven, microservices, monolithic, choreography, orchestration, fanout)
- Idempotency
- Stateful ve stateless kavramları arasındaki farklar
- Tightly coupled ve loosely coupled bileşenler
- Fault-tolerant tasarım desenleri (örneğin: jitter ile exponential backoff, dead-letter queues)
- Synchronous ve asynchronous desenler

**Beceri Gereksinimleri:**
- Java, C#, Python, JavaScript, TypeScript, Go dillerinde resilient uygulamalar geliştirme
- API geliştirme (request/response transformasyonları, validation kuralları, status code override)
- AWS SAM ile unit test yazma ve çalıştırma
- Messaging servisleri ile çalışan kod yazma
- AWS SDK’leri ve API’leri ile entegre çalışan kod yazma
- AWS ile data streaming işleme

#### Görev 2: AWS Lambda için kod geliştirme

**Bilgi Gereksinimleri:**
- Event source mapping
- Stateless uygulama tasarımı
- Unit testing
- Event-driven mimari
- Ölçeklenebilirlik
- Lambda’dan VPC içi kaynaklara erişim

**Beceri Gereksinimleri:**
- Environment variable, memory, timeout, concurrency, runtime gibi yapılandırmaları belirleme
- Lambda Destinations, DLQ kullanarak event lifecycle ve hata yönetimi
- AWS servisleriyle test yazma
- Lambda’yı AWS servisleriyle entegre etme
- Lambda performansını ayarlama

---

## 📄 Sayfa 5

#### Görev 3: Uygulama geliştirmede veri depoları kullanma

**Bilgi Gereksinimleri:**
- Relational ve non-relational databases
- CRUD operasyonları
- High-cardinality partition key kullanımı
- File, object ve database bazlı cloud storage seçenekleri
- Strongly consistent ve eventually consistent veri modelleri
- Query ve scan farkı
- DynamoDB key ve indexing bilgisi
- Caching stratejileri (write-through, read-through, lazy loading, TTL)
- Amazon S3 storage class’ları ve lifecycle management
- Ephemeral vs persistent storage desenleri

**Beceri Gereksinimleri:**
- Verileri serialize/deserialize ederek storage’a yazma
- Data store yönetimi
- Veri yaşam döngüsü yönetimi
- Caching servisleri ile entegrasyon

---

## 📄 Sayfa 6-7

_(Sayfa 6 ve 7 daha önce detaylı olarak çevrildi – Görev 1-2-3: Security)_

---

## 📄 Sayfa 8-9

_(Sayfa 8 ve 9 daha önce detaylı olarak çevrildi – Görev 1-4: Deployment)_

---

## 📄 Sayfa 10-11

_(Sayfa 10 ve 11 daha önce detaylı olarak çevrildi – Görev 1-2: Troubleshooting and Observability)_

---

## 📄 Sayfa 12-13

_(Sayfa 12 ve 13 daha önce detaylı olarak çevrildi – Görev 3 ve Appendix Giriş)_


---

## 📄 Sayfa 14–16

### ✅ Sınav Kapsamındaki AWS Hizmetleri ve Özellikleri

#### Analytics
- Amazon Athena  
- Amazon Kinesis  
- Amazon OpenSearch Service  

#### Application Integration
- AWS AppSync  
- Amazon EventBridge  
- Amazon SNS  
- Amazon SQS  
- AWS Step Functions  

#### Compute
- Amazon EC2  
- AWS Elastic Beanstalk  
- AWS Lambda  
- AWS SAM

#### Containers
- AWS Copilot  
- Amazon ECR  
- Amazon ECS  
- Amazon EKS

#### Database
- Amazon Aurora  
- Amazon DynamoDB  
- Amazon ElastiCache  
- Amazon MemoryDB  
- Amazon RDS

#### Developer Tools
- AWS Amplify  
- AWS CloudShell  
- AWS CodeArtifact  
- AWS CodeBuild  
- AWS CodeDeploy  
- Amazon CodeGuru  
- AWS CodePipeline  
- AWS X-Ray

#### Management and Governance
- AWS AppConfig  
- AWS CDK  
- AWS CloudFormation  
- AWS CloudTrail  
- Amazon CloudWatch  
- Amazon CloudWatch Logs  
- AWS CLI  
- AWS Systems Manager

#### Networking and Content Delivery
- Amazon API Gateway  
- Amazon CloudFront  
- Elastic Load Balancing (ELB)  
- Amazon Route 53  
- Amazon VPC

#### Security, Identity, and Compliance
- AWS Certificate Manager (ACM)  
- Amazon Cognito  
- AWS IAM  
- AWS KMS  
- AWS Private CA  
- AWS Secrets Manager  
- AWS STS  
- AWS WAF

#### Storage
- Amazon EBS  
- Amazon EFS  
- Amazon S3  
- Amazon S3 Glacier

---

### 🚫 Sınav Kapsamı Dışındaki AWS Hizmetleri

#### Analytics
- Amazon QuickSight

#### Business Applications
- Amazon Chime  
- Amazon Connect  
- Amazon WorkMail

#### End User Computing
- Amazon AppStream 2.0  
- Amazon WorkSpaces

#### Frontend Web and Mobile
- AWS Device Farm

#### Game Tech
- Amazon GameLift

#### Machine Learning
- Amazon Lex  
- Amazon Polly  
- Amazon Rekognition

#### Management and Governance
- AWS Managed Services (AMS)  
- AWS Service Catalog

#### Media Services
- Amazon Elastic Transcoder

#### Migration and Transfer
- AWS Application Discovery Service  
- AWS Application Migration Service  
- AWS DMS

#### Security, Identity, and Compliance
- AWS Shield Advanced  
- AWS Shield Standard

#### Storage
- AWS Snow Family  
- AWS Storage Gateway

---

### 📋 Anket

Bu sınav kılavuzu faydalı oldu mu?  
Geri bildiriminizi paylaşmak için [bu anketi doldurun](https://amazonmr.au1.qualtrics.com/jfe/form/SV_8vLR1a9uG9zu9Po?course_title=Dev-Associate&course_id=DVA-C02&Q_Language=EN).
