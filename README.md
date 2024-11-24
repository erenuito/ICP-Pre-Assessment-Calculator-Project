# Risein


# 🧮 **Hesap Makinesi Aktörü**  
Bir aktör tabanlı hesap makinesi uygulaması! **`Motoko`** dilinde yazılmış bu basit ve etkili hesap makinesi, temel matematiksel işlemleri asenkron olarak gerçekleştirebiliyor. 🚀  

![Calculator](https://img.shields.io/badge/Calculator-Motoko-blue?style=flat-square)  
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)  

## ✨ **Özellikler**  
Bu hesap makinesi aşağıdaki işlemleri destekler:  
- **Toplama** ➕  
- **Çıkarma** ➖  
- **Çarpma** ✖️  
- **Bölme** ➗ *(Sıfıra bölme hatasına karşı güvenli)*  
- **Temizle** 🧹  

---

## 📂 **Kod Özeti**  

### 📥 **Toplama**  
`toplama(s: Int): async Int`  
Bir sayı ekler ve sonucu döner:  
hesap_makinesi.toplama(5); // hucre = 5

###📥 **Çıkarma** 
cikarma(s: Int): async Int
Bir sayı çıkarır ve sonucu döner:
hesap_makinesi.cikarma(2); // hucre = 3

###📥 **Çarpma** 
carpma(s: Int): async Int
Bir sayıyla çarpar ve sonucu döner:
hesap_makinesi.carpma(4); // hucre2 = 4

###📥 **Bölme** 
bolme(s: Int): async ?Int
Bir sayıya böler ve sonucu döner. Eğer sıfıra bölme yapılırsa null döner:
hesap_makinesi.bolme(2); // ?hucre = 1
hesap_makinesi.bolme(0); // null

###🧹 **Temizle** 
temizle(): async ()
Hafızayı sıfırlar.
hesap_makinesi.temizle(); // hucre = 0

🌟 Görseller ve Örnekler



