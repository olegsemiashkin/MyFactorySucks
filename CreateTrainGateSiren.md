# 🚨 Train Gate Siren

🔗 [Blueprint on FactorioPrints](https://factorioprints.com/view/-OQ-G6KwzfAPI7D0K3O4)

Triggers a siren when a train enters a gate section.  
Useful for warning systems, immersive train crossings, or automatic barriers.

---

## 🧱 Components
- Train stop  
- Decider combinator  
- Programmable speaker  
- Electric poles  
- Red & green wires

---

## 🔌 Circuit Network Setup

**Train Stop → Decider Combinator → Speaker**

- Train stop is configured to **read train ID**.  
- Decider combinator checks:  
  `Train ID > 0 → output "A" = 1`  
- Speaker is configured to **play a siren** when signal **A ≥ 1**.

---

## 💡 Behavior

Whenever a train enters the stop, the stop outputs a **Train ID**.  
The decider combinator detects the presence of a train and sends signal **A**.  
The speaker reacts by playing a siren sound and displaying an alert.

---

## 🎯 Use Cases

- Railway crossings with sound alerts  
- Immersive stations with incoming train warnings  
- Trigger other logic (e.g. lights, gates, alerts)

---

## 📸 Preview

![Preview](https://i.imgur.com/HEdZl1q.png)

---

Created by [olegsemiashkin](https://github.com/olegsemiashkin)  
License: MIT
