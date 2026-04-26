# 🚀 YouTube Class Notes: Vedic Maths (Part 4)
## Topic: <span style="color:#2E86C1">Square Root (वर्गमूल) - Final Session</span> 📊
**Target Exam:** LDC 2026 | **Series:** Sarthi Series (Class 34)

---

### 📝 <span style="color:#8E44AD">Class Intro & Resources</span> [00:20](00:00:20)
* **Book:** शिक्षक की 'Complete Mathematics' बुक को टाइप-वाइज और इजी-टू-एडवांस मैनर में अरेंज किया गया है।
* **App:** 'Abhyas Maths' ऐप पर LDC 2026 की टेस्ट सीरीज और लाइव बैच उपलब्ध है।
* **Contact:** WhatsApp @ 9720010900 [04:11](00:04:11)

---

### ♾️ <span style="color:#D35400">Infinite Series Shortcut (अनंत श्रेणी)</span> [04:35](00:04:35)

जब कोई संख्या रूट के अंदर बार-बार अनंत तक रिपीट हो, तो निम्न 4 स्थितियाँ बनती हैं:

| Case Type | Example Format | Method / Shortcut |
| :--- | :--- | :--- |
| **Plus (+)** | $\sqrt{90 + \sqrt{90 + \dots}}$ | 90 के टुकड़े करें ($10 \times 9$) → **बड़ा अंक** (10) उत्तर होगा। |
| **Minus (-)** | $\sqrt{30 - \sqrt{30 - \dots}}$ | 30 के टुकड़े करें ($6 \times 5$) → **छोटा अंक** (5) उत्तर होगा। |
| **Multiply (Infinite)** | $\sqrt{30 \times \sqrt{30 \dots \infty}}$ | वही संख्या उत्तर होगी → **30** |
| **Multiply (Finite)** | $\sqrt{x \times \sqrt{x \dots}}$ (n बार) | Formula: $x^{\frac{2^n - 1}{2^n}}$ |

> **Important Concept:** गुणनखंड (Factors) ऐसे होने चाहिए जिनके बीच का अंतर **1** हो। [05:31](00:05:31)

#### **Q. Finite Multiplication Example:** [18:21](00:18:21)
$\sqrt{3 \times \sqrt{3 \times \sqrt{3 \times \sqrt{3}}}}$ ($n=4$)
* Step: $2^4 = 16$. 
* Power: $\frac{16-1}{16} = \frac{15}{16}$
* **Ans: $3^{\frac{15}{16}}$**

---

### 🧬 <span style="color:#27AE60">Nested Roots (रंग-बिरंगे नंबर)</span> [22:33](00:22:33)

**Q. $\sqrt{5 + \sqrt{11 + \sqrt{19 + \sqrt{29 + \sqrt{49}}}}}$**
* **Strategy:** अंत से शुरू करें (Start from Last).
* 1. $\sqrt{49} = 7$
* 2. $29 + 7 = 36 \rightarrow \sqrt{36} = 6$
* 3. $19 + 6 = 25 \rightarrow \sqrt{25} = 5$
* 4. $11 + 5 = 16 \rightarrow \sqrt{16} = 4$
* 5. $5 + 4 = 9 \rightarrow \sqrt{9} = 3$
* **Final Ans: 3** ✅ (REET 2022)

---

### 🔢 <span style="color:#2E86C1">PYQ: Decimals & Perfect Squares</span> [25:36](00:25:36)

**Q1. $\sqrt{104.04} + \sqrt{1.0404} + \sqrt{0.010404}$** [26:15](00:26:15)
* दिया है: $\sqrt{10404} = 102$
* Calculation: $10.2 + 1.02 + 0.102 = \mathbf{11.322}$ ✅

**Q2. 1452 को किस छोटी संख्या 'a' से गुणा/भाग करें कि वह पूर्ण वर्ग बन जाए?** [28:51](00:28:51)
* **Prime Factorization:** $1452 = 2 \times 2 \times 11 \times 11 \times 3$
* **Logic:** यहाँ 2 और 11 के जोड़े बन रहे हैं, लेकिन **3** अकेला है।
* **Ans: a = 3** ✅ (Sangank 2021)

---

### 🏛️ <span style="color:#C0392B">6-Digit Square Root (द्वंद योग / भाग विधि)</span> [35:23](00:35:23)

छह अंकों की संख्या का वर्गमूल निकालना सबसे महत्वपूर्ण है।

**Rules:**
1. **Steps (खंड):** जितने जोड़े बनेंगे, उतने ही खंड होंगे। 6 अंकों में **3 खंड** बनेंगे। [37:42](00:37:42)
2. **Method:** भाग विधि (Long Division) या द्वंद योग (Duplex Method).

#### **Solved 6-Digit Examples:**

| Number | Method Insight | Final Answer | Timestamp |
| :--- | :--- | :--- | :--- |
| **725904** | $8^2 < 72$, Double of 8 = 16 used for division. | **852** | [36:59](00:36:59) |
| **207936** | $4^2 < 20$, Double of 4 = 8 used for division. | **456** | [46:58](00:46:58) |
| **364816** | $6^2 = 36$, 12 used for division. | **604** | [48:53](00:48:53) |
| **992016** | अंकों का योग पूछा गया: $9+9+6 = 24$. | **24** | [1:05:03](01:05:03) |
| **915849** | $9^2 < 91$, 18 used for division. (CET 2023) | **957** | [1:03:20](01:03:20) |

---

### 🧠 <span style="color:#16A085">Quick Revision / Key Insights</span>

* **Quadratic Equation Method:** $\sqrt{x + \sqrt{x \dots}}$ को बेसिक से हल करने पर $x^2 - x - 90 = 0$ जैसी समीकरण बनती है। [06:51](00:06:51)
* **Nearest Whole Number:** $\sqrt{300}$ का निकटतम मान 17 होगा क्योंकि $17^2=289$ (अंतर 11) और $18^2=324$ (अंतर 24)। [33:13](00:33:13)
* **Duplex Hint:** यदि भाग देने पर शेषफल इतना कम बचे कि अगला द्वंद न घट पाए, तो भाग एक बार कम दें। [55:20](00:55:20)
* **Bilingual Terminology:** * <span style="color:#2E86C1">Square Root</span> - वर्गमूल
    * <span style="color:#2E86C1">Long Division Method</span> - भाग विधि
    * <span style="color:#2E86C1">Quadratic Equation</span> - द्विघात समीकरण
    * <span style="color:#2E86C1">Infinite Series</span> - अनंत श्रेणी

---
**Motivational Quote:** "मेहनत का कोई शॉर्टकट नहीं होता, लेकिन कांसेप्ट से चीजें आसान हो जाती हैं।" ✍️