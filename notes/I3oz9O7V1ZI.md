# 📚 वैदिक गणित (Vedic Maths): वर्ग करने की विधियाँ 🚀

यह सेशन **LDC Exam 2026** को टारगेट करते हुए **सारथी सीरीज** की 32वीं क्लास है, जिसमें **Jaideep Sir** ने वर्ग (Square) निकालने की सभी 5 वैदिक विधियों को विस्तार से समझाया है।

---

## 📋 वर्ग करने की 5 मुख्य विधियाँ (Methods of Squaring)
[06:01](00:06:01)

| क्र.सं. | विधि का नाम (Method Name) | उपयोग (Usage) |
| :--- | :--- | :--- |
| 1 | <span style="color:#E67E22">**Sutra Ekadhikena Purvena**</span> | जिसका इकाई अंक (Unit Digit) **5** हो। |
| 2 | <span style="color:#E67E22">**Upsutra Anurupyena**</span> | **2 अंकों** की संख्या के लिए ($a^2 | 2ab | b^2$)। |
| 3 | <span style="color:#E67E22">**Sankalan Vyavkalan**</span> | इसे **Isht Sankhya Method** भी कहते हैं। |
| 4 | <span style="color:#E67E22">**Sutra Nikhilam**</span> | **Base/Sub-base** (आधार/उपाधार) विधि। |
| 5 | <span style="color:#E67E22">**Dwandwa Yoga**</span> | **Criss-Cross** विधि (सभी संख्याओं के लिए यूनिवर्सल)। |

---

## 🔍 विधि 4: Sutra Nikhilam (Base/Sub-base Method)
[13:48](00:13:48)

इसे **Yavadunam Tavadunam** विधि भी कहा जाता है। इसमें **दो खंड** (Two Blocks) बनते हैं।

### 🔹 (A) आधार विधि (Base Method)
> **Formula:** $$(Number)^2 = (Number + Deviation) \mid (Deviation)^2$$
* **Base:** 10, 100, 1000 आदि।
* **Deviation (विचलन):** $Number - Base$ [18:56](00:18:56)

| उदाहरण (Example) | आधार (Base) | विचलन (Deviation) | हल (Solution) | उत्तर (Result) |
| :--- | :--- | :--- | :--- | :--- |
| **99** | 100 | -01 | $(99 - 1) \mid (-01)^2$ | **9801** |
| **107** | 100 | +07 | $(107 + 7) \mid (7)^2$ | **11449** |
| **992** | 1000 | -08 | $(992 - 8) \mid (-08)^2$ | **984064** |

### 🔹 (B) उपाधार विधि (Sub-base Method)
[30:37](00:30:37)
जब संख्या आधार (10, 100) के सीधे पास न होकर उसके गुणज के पास हो।
> **Formula:** $$Sub-base Digit \times (Number + Deviation) \mid (Deviation)^2$$

* **Example 508:** Base = 100, Sub-base = 500, Sub-base Digit = **5**, Deviation = **+8**
* **Calculation:** $5 \times (508 + 8) \mid (8)^2 = 5 \times 516 \mid 64 = 258064$ [34:26](00:34:26)

---

## ⚡ विधि 5: Dwandwa Yoga / Criss-Cross Method
[42:25](00:42:25)

यह सबसे महत्वपूर्ण विधि है। इसे **Duplex Method** भी कहते हैं।

### 🔢 खंडों की संख्या (Number of Groups)
यदि संख्या में **'n'** अंक हैं, तो खंडों की संख्या होगी:
> **Formula:** $$2n - 1$$ [46:14](00:46:14)

* **Example:** 6 अंकों की संख्या के लिए $2(6) - 1 = \mathbf{11}$ खंड बनेंगे।

### 🧬 द्वंद योग (Duplex) निकालना सीखें:
[50:16](00:50:16)
1.  **1 Digit (a):** $a^2$ (जैसे: $2 \rightarrow 4$)
2.  **2 Digits (ab):** $2(a \times b)$ (जैसे: $23 \rightarrow 2(2 \times 3) = 12$)
3.  **3 Digits (abc):** $2(a \times c) + b^2$ (जैसे: $123 \rightarrow 2(1 \times 3) + 2^2 = 10$)
4.  **4 Digits (abcd):** $2(a \times d) + 2(b \times c)$

### 📝 उदाहरण: 2112 का वर्ग (LDC 2018)
[1:08:49](01:08:49)
* अंक = 4, खंड = $2(4)-1 = \mathbf{7}$
* खंड: $2 \mid 21 \mid 211 \mid 2112 \mid 112 \mid 12 \mid 2$
* द्वंद योग: $4 \mid 4 \mid 5 \mid 10 \mid 5 \mid 4 \mid 4$
* Final adjustment (एक खंड में एक अंक): **4460544** [1:12:27](01:12:27)

---

## 🧠 Quick Revision (Key Insights)

* **Sutra Nikhilam:** हमेशा याद रखें कि दाएं खंड में उतने ही अंक रहेंगे जितने आधार (Base) में **Zeros** हैं। [21:13](00:21:13)
* **Dwandwa Yoga:** यह यूनिवर्सल मेथड है। इसमें पहले अंकों को बढ़ाते हैं (जैसे 2, 21, 211) और फिर अंत से घटाते हैं।
* **2026 Square:** $2026^2 = \mathbf{4104676}$ [40:07](00:40:07)
* **Isht Sankhya:** संख्या में कुछ जोड़कर या घटाकर उसे शून्य (Zero) के करीब लाना।