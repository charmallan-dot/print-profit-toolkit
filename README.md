# 💰 Print Profit Toolkit

**Print-on-demand profit calculator and product validator**

---

## 🎯 What It Does

- Calculate POD profit margins across platforms (Redbubble, TeeSpring, Merch by Amazon)
- Validate product ideas before creation
- Identify high-margin niches
- Track competitor pricing

---

## 📡 API Endpoints

### `POST /api/calculate`
Calculate profit margins

**Request:**
```json
{
  "platform": "redbubble",
  "product": "t-shirt",
  "cost": 5.99,
  "price": 19.99
}
```

### `POST /api/validate`
Validate product opportunity

---

## 💰 Monetization

**Model:** Freemium SaaS

- **Free:** 10 calculations/month
- **Pro ($19/mo):** Unlimited + competitor tracking
- **Agency ($79/mo):** Team + API access

---

## 📈 Status

🟢 LIVE (v3.0) - Ready for deployment

---

**Built by:** charmallan-dot  
**Version:** 1.0.0
