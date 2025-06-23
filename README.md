# Proteus XOR Devresi (Proteus #10)

🔗 [Web Siteme Bakmak İçin Tıkla](https://www.hakkiharmankaya.com/)

---

## 🧠 XOR Kapısı Nedir?

XOR (Exclusive OR), yalnızca girişlerden **biri 1** diğer **0** olduğunda çıkışta **1** üreten bir mantık kapısıdır. Diğer tüm durumlarda (0-0, 1-1) çıkış 0 olur.

Proteus’ta XOR kapısını temel mantık kapıları olan **AND**, **OR** ve **NOT** ile kendin oluşturabilirsin.

---

## 🧰 Gerekli Malzemeler

- 2 adet **AND Kapısı**
- 2 adet **NOT Kapısı**
- 1 adet **OR Kapısı**
- 2 adet **Switch** (Giriş A ve B için)
- 1 adet **LED**
- 1 adet **5V DC güç kaynağı**
- **Proteus simülasyon yazılımı**

---

## 🔧 Devre Tasarımı

### 1️⃣ Girişlerin Bağlanması

- Giriş A ve B için iki anahtar kullan.
- Her anahtarın bir ucunu **5V**, diğer ucunu hem **NOT** kapısına hem de ilgili **AND** kapılarına bağla.

### 2️⃣ NOT Kapıları

- A sinyalini NOT A yap ve birinci AND kapısına gönder.
- B sinyalini NOT B yap ve ikinci AND kapısına gönder.

### 3️⃣ AND Kapıları

- 1. AND: A ve NOT B
- 2. AND: NOT A ve B

### 4️⃣ OR Kapısı

- Her iki AND çıkışını OR kapısına bağla.
- OR kapısının çıkışını bir **LED**’e bağlayarak sonucu gözlemle.

---

## 🔬 Proteus’ta Kurulum Adımları

1. Proteus’u aç ve `P` tuşu ile bileşen ekleme penceresini aç.
2. `AND`, `OR`, `NOT`, `LED`, `Switch` ve `DC Power` bileşenlerini projeye ekle.
3. Yukarıdaki bağlantı şemasına uygun şekilde bağlantıları yap.
4. **Run** tuşuna basarak simülasyonu başlat.

---

## ✅ XOR Mantık Prensibi

| A | B | Çıkış (A XOR B) |
|---|---|-----------------|
| 0 | 0 | 0               |
| 0 | 1 | 1               |
| 1 | 0 | 1               |
| 1 | 1 | 0               |

Bu doğruluk tablosunu Proteus’ta kendi oluşturduğun devreyle test ederek doğrulayabilirsin.

---

## 🎯 Sonuç

Bu projeyle:

- XOR kapısının temel mantığını öğrendin.
- Proteus ortamında **temel mantık kapılarını birleştirerek daha karmaşık devreler** tasarlamayı deneyimledin.
- Dijital elektronik sistemlerin temellerine sağlam bir giriş yaptın.

🔗 [Web Siteme Bakmak İçin Tıkla](https://www.hakkiharmankaya.com/)
