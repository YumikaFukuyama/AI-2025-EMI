# 🔹 Advanced Labs (高級ラボ) – 10 Labs, W5
## 2️⃣1️⃣​Prompt Variables (變數化設計, プロンプト変数化)
"Create a template to generate product descriptions using 6 placeholders in English, Chinese, and Japanese.."
- Product Description Template
**English:**
[Product Name] is a [Feature 1] product that offers [Feature 2] for [Target Audience]. Designed with [Material/Technology], it ensures [Benefit]. Perfect for [Use Case], this product guarantees [Advantage]. Whether you're looking for [Solution/Effect], [Product Name] provides everything you need for [Result/Outcome].

**Chinese (Traditional):**
[產品名稱] 是一款具有 [特徵 1] 的產品，為 [目標客群] 提供 [特徵 2]。採用 [材料/技術] 設計，確保 [好處]。非常適合 [使用場景]，此產品保證 [優勢]。無論您尋找 [解決方案/效果]，[產品名稱] 都能為您提供實現 [結果/效果] 所需的一切。

**Japanese:**
[製品名] は [特徴 1] を備えた製品で、[ターゲットオーディエンス] 向けに [特徴 2] を提供します。[素材/技術] で設計されており、[利点] を保証します。[使用ケース] に最適で、この製品は [利点] を提供します。[ソリューション/効果] をお探しの場合、[製品名] は [結果/成果] を実現するために必要なすべてを提供します。

- Explanation of Placeholders:
[Product Name]: The name of the product.
[Feature 1]: A key feature or attribute of the product.
[Feature 2]: Another feature or unique selling point.
[Target Audience]: The group of people who will benefit most from the product.
[Material/Technology]: The material or technology used in the product.
[Benefit]: What the product does to improve the user's experience.
[Use Case]: A scenario where the product would be used.
[Advantage]: The main advantage that sets this product apart from others.
[Solution/Effect]: The problem the product solves or the effect it has.
[Result/Outcome]: The ultimate result or outcome the customer achieves with the product.

## 2️⃣2️⃣​Automated Template Filling (自動化模板, 自動入力テンプレート)
"Please use the following template to write a product description for [car]: '[Product Name] is a [Type] with [Feature 1] and [Feature 2], offering [Advantage].’'"

## 2️⃣3️⃣​Chain of Thought (CoT, 思維鏈)
"If I have 10 apples, give 3 away, buy 5 more, and eat 1, how many remain?"
**English:**
[Car Model] is a luxury sedan with advanced safety features and a fuel-efficient engine, offering a smooth, comfortable driving experience.

**Chinese (Traditional):**
[汽車型號] 是一款 豪華轎車，具備 先進的安全特性 和 高效能引擎，提供 順暢、舒適的駕駛體驗。

**Japanese:**
[車種名] は ラグジュアリーセダン で、先進的な安全機能 と 燃費効率の良いエンジン を備えており、快適でスムーズな運転体験 を提供します。

## 2️⃣4️⃣​Multi-Step Math (多步數學, 数学的な推論)
"A car travels 60 km/h for 4 hours. How far does it go? Explain step-by-step."
Distance = Speed × Time

Step-by-step explanation:
Identify the known values:

Speed (S) = 60 km/h
Time (T) = 4 hours
Apply the formula:

Distance = Speed × Time
Distance = 60 km/h × 4 hours
Multiply the values:

Distance = 240 km
Final Answer:
The car travels 240 kilometers.

## 2️⃣5️⃣​Zero-shot CoT (零樣本CoT, ゼロショットCoT)
"A student has 20 dollars, buys a pen for 5 dollars, a book for 10 dollars. How much remains?"
Step-by-step explanation:
Initial amount of money: 20 dollars
Cost of the pen: 5 dollars
Cost of the book: 10 dollars
Calculation:
Total cost = 5 dollars (pen) + 10 dollars (book) = 15 dollars
Remaining money = Initial amount - Total cost = 20 dollars - 15 dollars = 5 dollars
Final Answer:
The student has 5 dollars remaining.

## 2️⃣6️⃣​Tree-of-Thoughts (ToT, 思維樹技術)
"Where is the ball if someone moves it between rooms? Let three AI experts analyze the answer."
Expert 1: The Data Scientist (Logical and Analytical Approach)
The location of the ball depends on a sequence of actions performed by the person. If the ball is moved between rooms, we need a clear record of the steps:

The ball starts in one room, let's call it Room A.
It is then moved to Room B.
The final location of the ball will be Room B, assuming no further movements occur.
To determine the ball's location accurately, we would need an input of the specific rooms and actions involved.

Expert 2: The Cognitive Scientist (Focus on Human Understanding)
From a cognitive perspective, the location of the ball is a question of memory and context. A person moves the ball between two rooms, but their perception of the ball's location relies on their awareness of where they placed it last. If they moved the ball from Room A to Room B, their current belief about the ball's location is based on their mental map, which updates each time the ball is relocated. If the person last moved it to Room B, that’s where the ball is perceived to be.

Expert 3: The Machine Learning Engineer (Contextual Understanding and Assumptions)
Using a machine learning model trained on similar situations, the model would use context and historical data to predict the ball’s location. Given that the ball was moved between rooms, the final state would be Room B, assuming the last move was to that room. If there’s no further input or action, and we base our answer on the last known movement, the ball is in Room B. However, we could adjust our prediction if there were additional complexities, like uncertainty in the movement or intermediate steps.

Final Conclusion:
In all three perspectives, Room B is where the ball is most likely to be, assuming it was moved there last and no further information suggests a different outcome.

## 2️⃣7️⃣​Variable Prompt Design (變數化提示詞, 変数化プロンプト)
"Create a prompt template for computing travel distance based on [Speed] and [Time]."
Travel Distance Calculation Prompt Template
Prompt:

Given the following information:

Speed: [Speed] km/h
Time: [Time] hours
Calculate the Distance traveled using the formula:
Distance = Speed × Time

Example Use:
Prompt:

Given the following information:

Speed: 80 km/h
Time: 3 hours
Calculate the Distance traveled.

## 2️⃣8️⃣​Historical Chain of Thought (歷史推理, 歴史的な推論)
"Explain the fall of the Roman Empire step-by-step."
1. Economic Decline
Overexpansion: The Roman Empire became too large to govern effectively, leading to a strained economy. Provinces faced high taxes and a lack of resources, causing internal economic instability.
Inflation and Devaluation: The empire relied heavily on slaves and conquests for wealth. As the empire's expansion slowed, there was less wealth, which led to inflation. Additionally, the Roman currency was devalued, weakening the economy further.
Heavy Taxes: To fund the empire’s military and vast bureaucracy, taxes increased, burdening the citizens and farmers.
2. Political Instability
Weak Leadership: The Roman Empire suffered from frequent leadership changes, with many emperors being overthrown or assassinated. This lack of stable leadership weakened the political structure.
Division of the Empire: In 395 AD, Emperor Theodosius divided the empire into the Western Roman Empire and the Eastern Roman Empire (Byzantine Empire). The Western Empire was much weaker and more vulnerable to invasions.
3. Military Problems
Barbarian Invasions: Various groups of "barbarians," including the Visigoths, Vandals, and Huns, attacked Roman borders. The Western Roman Empire struggled to defend itself from these external threats.
Mercenary Armies: The Roman military began to rely more on mercenaries—soldiers from other regions who were less loyal to Rome and sometimes even turned against the empire.
Decline in Military Discipline: The quality of the Roman army deteriorated over time. Many soldiers were not as well-trained or disciplined as in earlier periods.
4. Social and Cultural Decay
Decline in Civic Pride: Romans began to lose a sense of civic duty and pride in their empire. The upper classes became more focused on luxury and personal wealth rather than serving the state.
Rise of Christianity: As Christianity spread throughout the empire, it weakened traditional Roman religious and cultural practices. Some historians argue that the decline of Roman paganism led to a loss of unity within the empire.
5. Environmental Factors
Plague and Famine: The empire faced numerous plagues and famines that decimated its population. The weakening of the population made it harder to defend borders and maintain infrastructure.
Climate Change: Some historians suggest that climate changes, such as a cooler and drier period, could have impacted agriculture, leading to food shortages and further weakening the empire.
6. The Final Collapse
The Sack of Rome (410 AD): In 410 AD, the Visigoths, led by Alaric, sacked the city of Rome. This event marked a significant blow to the prestige and power of the Western Roman Empire.
The Fall of the Western Roman Empire (476 AD): In 476 AD, the last Roman emperor, Romulus Augustulus, was overthrown by the Germanic chieftain Odoacer. This event is commonly seen as the formal end of the Western Roman Empire.
7. Legacy
While the Western Roman Empire fell, the Eastern Roman Empire (Byzantine Empire) continued for another thousand years, until the fall of Constantinople in 1453.
The fall of Rome influenced the development of medieval Europe and the eventual rise of the Holy Roman Empire.
Final Thought:
The fall of the Roman Empire was not caused by a single event but by a combination of internal weaknesses and external pressures over time. It is often seen as a gradual process rather than a sudden collapse.

## 2️⃣9️⃣​Financial AI Analysis (財務分析AI, 財務分析のAI)
"A restaurant makes $100 per seat. If it has 50 seats and operates 7 days a week, calculate revenue."
Step 1: Calculate Daily Revenue
The restaurant makes $100 per seat.
It has 50 seats.

Daily Revenue=100(dollars per seat)×50(seats)=5000dollars per day
Step 2: Calculate Weekly Revenue
The restaurant operates 7 days a week.
So, the weekly revenue is:
Weekly Revenue=5000(daily revenue)×7(days)=35,000dollars per week
Final Answer:
The restaurant’s weekly revenue is $35,000.
## 3️⃣0️⃣​Real-Time AI Automation (實時AI應用, AI自動化)
"Automate data extraction and generate a summary for the provided datasheet."
**Data Extraction:**

Identify and extract key fields or columns from the datasheet (e.g., sales data, customer information, or product details).
**Generate Summary:**

Create a concise summary based on the extracted data (e.g., total sales, trends, key metrics).

