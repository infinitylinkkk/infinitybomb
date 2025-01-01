# İnfinityBomber

![InfinityBomber Kullanım Örneği](https://github.com/infinitylinkkk/infinitybomb/blob/d92569105057f6d08fa9b4398a1dfd9467f80844/IMG_20250101_114836.jpg)

InfinityBomber, hedef numaraya toplu SMS göndermenizi sağlayan basit bir araçtır. Araç, **Turbo** ve **Normal** mod olmak üzere iki farklı hız seçeneği sunar.

## 🚨 Uyarı

Bu araç yalnızca **yasal ve eğitim amaçlı** kullanılmalıdır. Kötüye kullanım, ciddi sonuçlara yol açabilir. Sorumluluk tamamen kullanıcıya aittir.

---

## 📲 Termux Kurulumu

1. **Termux'u indirin ve açın.**  
   Termux uygulamasını [Google Play](https://play.google.com) veya F-Droid'den indirip yükleyebilirsiniz.

2. **Bağımlılıkları yükleyin.**  
   Termux'u açtıktan sonra aşağıdaki komutları sırasıyla çalıştırın:  
   ```bash
   pkg update && pkg upgrade -y
   pkg install git python -y
   pip install requests
   git clone https://github.com/infinitylinkkk/infinitybomb.git
   cd infinitybomb
   pip install -r requirements.txt
   python3 infinitybomb.py
