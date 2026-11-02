# 🤖 Cline - NVIDIA Powered AI Coding Assistant

<p align="center">
  <img src="https://shields.io" alt="Maintained" />
  <img src="https://shields.io" alt="License" />
  <img src="https://shields.io" alt="NVIDIA" />
</p>

Bu depo (repository), popüler açık kaynaklı yapay zekâ kodlama asistanı **[Cline](https://github.com)** projesinin bir çatallamasıdır (fork). 

Bu özel versiyonun temel amacı; Cline'ın otonom ajan yeteneklerini, **NVIDIA GPU donanımları**, **NVIDIA NIM (NVIDIA Inference Microservices)** ve **NVIDIA NeMo Fabric** altyapısıyla en yüksek performans, düşük gecikme ve maksimum gizlilikle yerel (local) veya hibrit olarak çalışacak şekilde optimize etmektir.

---

## 🚀 Öne Çıkan Özellikler

* ⚡ **NVIDIA Donanım Optimizasyonu:** Yerel RTX GPU'lar, DGX istasyonları ve kurumsal altyapılarda ultra hızlı kod tamamlama.
* 🧠 **Nemotron 3.5 Lightning Desteği:** 30B MoE mimarisi ve 1M context penceresi ile büyük projelerde derinlemesine akıl yürütme.
* 🔒 **Maksimum Gizlilik:** Kod tabanınızı dışarıya göndermeden, tamamen kendi NVIDIA altyapınızda güvenli otonom kodlama deneyimi.
* 🛠️ **Plan and Act Modu:** NVIDIA modellerinin akıl yürütme gücüyle terminal komut çalıştırma, dosya düzenleme ve `/undo` (geri alma) checkpoint uyumluluğu.

---

## 🛠️ Kurulum ve Yapılandırma

### 1. Eklentiyi Yükleyin
VS Code veya Cursor eklenti mağazasından (Extensions) **Cline** eklentisini kurun.

### 2. NVIDIA NIM veya Bulut Bağlantısı
NVIDIA modellerini kullanmak için Cline ayarlarından (Settings) **OpenAI Compatible** seçeneğini seçin ve aşağıdaki alanları doldurun:

* **Base URL:** `https://nvidia.com`
* **API Key:** [NVIDIA API Catalog](https://nvidia.com) üzerinden aldığınız API anahtarınız.
* **Model ID:** `nvidia/llama-3.1-nemotron-70b-instruct` *(veya tercih ettiğiniz diğer NVIDIA modelleri)*

---

## 🤝 Katkıda Bulunma (Contribution)

Bu proje geliştirmeye ve optimizasyonlara açık bir topluluk projesidir. Eğer siz de NVIDIA tabanlı AI kodlama araçlarını geliştirmek istiyorsanız:
1. Bu depoyu **Fork** edin.
2. Yeni bir özellik dalı (branch) açın: `git checkout -b feature/yeniozellik`.
3. Değişikliklerinizi **Commit** edin: `git commit -m 'feat: yeni özellik eklendi'`.
4. Dalınızı **Push** edin: `git push origin feature/yeniozellik`.
5. Bir **Pull Request** (Çekme İsteği) oluşturun.

---

## 📜 Lisans

Bu proje, orijinal proje ile uyumlu olacak şekilde **MIT Lisansı** altında lisanslanmıştır.
