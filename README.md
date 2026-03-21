<div align="center">

# مكتبة الشبكات للغة المرجع
### Al-Marjaa Network Library

[![Version](https://img.shields.io/badge/version-3.4.0-blue.svg)](https://github.com/radhwendalyhamdouni/Al-Marjaa-Network)

**المخترع والمطور: رضوان دالي حمدوني**

</div>

---

## 🎯 نظرة عامة

مكتبة الشبكات للغة المرجع - HTTP Client/Server, WebSocket.

---

## 📦 التثبيت

```toml
[dependencies]
almarjaa-network = { git = "https://github.com/radhwendalyhamdouni/Al-Marjaa-Network" }
```

---

## 💡 مثال الاستخدام

```rust
use almarjaa_network::{HttpClient, Server};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    let client = HttpClient::new();
    let response = client.get("https://api.example.com").send()?;
    println!("Response: {}", response.text()?);
    Ok(())
}
```

---

**صُنع بـ ❤️ للعالم العربي**
