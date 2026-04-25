# 📚 <span style="color:#8E44AD">Vedic Maths: Square (वर्ग) करने की विधियाँ</span> 🚀
**Target Exam:** LDC 2026 | **Series:** Sarthi Series (Class 32) | **Teacher:** Jaydeep Sir

---

## 📊 <span style="color:#2980B9">Overview of Squaring Methods</span> [06:01](00:06:01)
वैदिक गणित में किसी संख्या का **Square (वर्ग)** करने के लिए मुख्य रूप से 5 विधियों का उपयोग किया जाता है:

| क्र.सं. | विधि का नाम (Method Name) | उपयोग (Usage) | खंड (Segments) |
| :--- | :--- | :--- | :--- |
| 1 | **Sutra Ekadhikena Purvena** | जिसका इकाई अंक (Unit Digit) **5** हो। | 2 खंड |
| 2 | **Upsutra Anurupyena** | 2 अंकों की संख्या के लिए। | 3 खंड |
| 3 | **Sankalan-Vyavkalan (Isht Sankhya)** | किसी भी संख्या के लिए (शून्यांक बनाकर)। | 1 फॉर्मूला |
| 4 | **Sutra Nikhilam (Aadhar/Upadhar)** | आधार (Base) के पास वाली संख्याओं के लिए। | 2 खंड |
| 5 | **Dwand Yoga (Criss-Cross)** | **Universal Method** (सभी संख्याओं के लिए)। | $2n-1$ खंड |

---

## 🛠️ <span style="color:#D35400">Method 4: Sutra Nikhilam (Yavadunam)</span> [13:48](00:13:48)
यह विधि **Base (आधार)** और **Sub-base (उपाधार)** पर काम करती है।

### 1. आधार विधि (Base Method) [15:42](00:15:42)
> **Formula:** $(Number + Deviation) \ | \ (Deviation)^2$

* **Aadhar (Base):** हमेशा $10, 100, 1000$ आदि की पावर में होता है।
* **Deviation (विचलन):** संख्या आधार से कितनी कम या ज्यादा है।
    * *Example:* $99^2$ (Base 100, Deviation -1) [17:14](00:17:14)
        * $(99 - 1) \ | \ (-1)^2 = 98 \ | \ 01 = \mathbf{9801}$
    * *Example:* $107^2$ (Base 100, Deviation +7) [21:33](00:21:33)
        * $(107 + 7) \ | \ (7)^2 = 114 \ | \ 49 = \mathbf{11449}$

### 2. उपाधार विधि (Sub-base Method) [30:32](00:30:32)
जब संख्या आधार के गुणज (Multiple) के पास हो (जैसे 200, 500)।
> **Formula:** $Sub\text{-}base \ Digit \times (Number + Deviation) \ | \ (Deviation)^2$

* *Example:* $508^2$ (Base 100, Sub-base 500, Digit 5, Deviation 8) [32:13](00:32:13)
    * $5 \times (508 + 8) \ | \ (8)^2 = 5 \times 516 \ | \ 64 = 2580 \ | \ 64 = \mathbf{258064}$

---

## ⚡ <span style="color:#C0392B">Method 5: Dwand Yoga (Criss-Cross / Duplex Method)</span> [42:25](00:42:25)
यह सबसे महत्वपूर्ण विधि है।

### महत्वपूर्ण नियम: [45:32](00:45:32)
* **खंडों की संख्या (Number of Segments):** यदि संख्या में $n$ अंक हैं, तो खंड $2n - 1$ बनेंगे।
    * *Example:* 6 अंकों की संख्या के लिए $2(6) - 1 = 11$ खंड बनेंगे। [49:05](00:49:05)

### द्वंद योग (Duplex) निकालने का तरीका: [50:16](00:50:16)
| अंकों की संख्या | तरीका (Method) | उदाहरण (Example) |
| :--- | :--- | :--- |
| **1 Digit (a)** | $a^2$ | $D(2) = 2^2 = 4$ |
| **2 Digits (ab)** | $2(a \times b)$ | $D(23) = 2(2 \times 3) = 12$ |
| **3 Digits (abc)** | $2(a \times c) + b^2$ | $D(123) = 2(1 \times 3) + 2^2 = 10$ |
| **4 Digits (abcd)** | $2(a \times d) + 2(b \times c)$ | $D(1234) = 2(1 \times 4) + 2(2 \times 3) = 20$ |

---

## 📝 <span style="color:#16A085">Practice Questions & Solutions</span>

### Q1. $2112^2$ (LDC 2018 Paper) [01:08:49]
* **Method:** Dwand Yoga (7 Segments)
* **Steps:** $D(2) | D(21) | D(211) | D(2112) | D(112) | D(12) | D(2)$
* **Results:** $4 | 4 | 5 | 10 | 5 | 4 | 4$
* **Final Adjustment:** $\mathbf{4460544}$

### Q2. $2026^2$ (Current Year Special) [01:12:50]
* **Result:** $\mathbf{4104676}$

### Q3. $3421^2$ में चौथे स्टेप (4th Step) पर आने वाला अंक क्या होगा? [01:30:51]
* चौथा स्टेप = $D(3421)$
* $2(3 \times 1) + 2(4 \times 2) = 6 + 16 = \mathbf{22}$

---

## 🧠 <span style="color:#27AE60">Quick Revision (Key Insights)</span>
1.  **Sutra Nikhilam:** आधार में जितने **Zero** होते हैं, दाहिने खंड (Right Part) में उतने ही अंक रखे जाते हैं। [21:07](00:21:07)
2.  **Dwand Yoga:** यह विधि किसी भी बड़े नंबर का वर्ग निकालने के लिए रामबाण है। 
3.  **Step Counting:** यदि दायाँ/बायाँ नहीं दिया हो, तो इकाई अंक (Unit Digit) की तरफ से पहला खंड गिनना शुरू करें। [01:15:33]
4.  **Practice:** वैदिक गणित केवल अभ्यास से ही तेज होती है।