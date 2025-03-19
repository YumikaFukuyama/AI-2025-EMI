# 🔹 Advanced Labs (高級ラボ) – 10 Labs, W5
## 2️⃣1️⃣​Prompt Variables (變數化設計, プロンプト変数化)
"Create a template to generate **product** descriptions using 6 placeholders in English, Chinese, and Japanese."
- Computer DELL XPS

**English:**
This Dell XPS features an Intel Core i7 processor, 16GB of RAM, and a 512GB SSD storage drive. It has a 13.4-inch OLED display and comes with Windows 11. Additionally, it is equipped with a backlit keyboard.

**Chinese (Traditional):**
这款Dell XPS配备了Intel Core i7处理器，16GB的内存和512GB SSD存储驱动器。它拥有一块13.4英寸的OLED显示屏，并预装了Windows 11。此外，它还配备了背光键盘

**Japanese:**
このDell XPSは、Intel Core i7プロセッサ、16GBのRAM、512GBのSSDストレージドライブを搭載しています。さらに、13.4インチのOLEDディスプレイとWindows 11が搭載されており、バックライト付きのキーボードも備えています。

## 2️⃣2️⃣​Automated Template Filling (自動化模板, 自動入力テンプレート)
"Please use the following template to write a product description for **[car]: '[Product Name] is a [Type] with [Feature 1] and [Feature 2], offering [Advantage].'**
- Porsche 911

**English:**
The Porsche 911 is a 911 with a turbocharged engine and an adaptive suspension, offering unmatched performance and comfort on the road.

**Chinese (Traditional):**
保时捷911是一款配备涡轮增压发动机和自适应悬挂的911，提供无与伦比的性能和舒适感。

**Japanese:**
ポルシェ911は、ターボエンジンとアダプティブサスペンションを備えた911で、道路上で比類のないパフォーマンスと快適さを提供します。

## 2️⃣3️⃣​Chain of Thought (CoT, 思維鏈)
"If I have 10 apples, give 3 away, buy 5 more, and eat 1, how many remain?"

Let's break it down step by step:

You start with 10 apples.

You give 3 apples away: 10 - 3 = 7 apples.

You buy 5 more apples: 7 + 5 = 12 apples.

You eat 1 apple: 12 - 1 = 11 apples.

So, you have 11 apples remaining.

## 2️⃣4️⃣​Multi-Step Math (多步數學, 数学的な推論)
"A car travels 60 km/h for 4 hours. How far does it go? Explain step-by-step."

Speed = 60 km/h (this is how fast the car is traveling)

Time = 4 hours (this is how long the car is traveling)

Use the formula:

*Distance=Speed×Time*

Substitute the given values into the formula:

Distance = 60 km/h × 4 hours

Calculate the result:

Distance = 240 km

So, the car travels 240 kilometers in 4 hours.

## 2️⃣5️⃣​Zero-shot CoT (零樣本CoT, ゼロショットCoT)
"A student has 20 dollars, buys a pen for 5 dollars, a book for 10 dollars. How much remains?"

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

**Expert 1:** The Data Scientist (Logical and Analytical Approach)

The location of the ball depends on a sequence of actions performed by the person. If the ball is moved between rooms, we need a clear record of the steps:

The ball starts in one room, let's call it Room A.

It is then moved to Room B.

The final location of the ball will be Room B, assuming no further movements occur.

To determine the ball's location accurately, we would need an input of the specific rooms and actions involved.

**Expert 2:** The Cognitive Scientist (Focus on Human Understanding)

From a cognitive perspective, the location of the ball is a question of memory and context. 

A person moves the ball between two rooms, but their perception of the ball's location relies on their awareness of where they placed it last. 

If they moved the ball from Room A to Room B, their current belief about the ball's location is based on their mental map, which updates each time the ball is relocated. 

If the person last moved it to Room B, that’s where the ball is perceived to be.

**Expert 3:** The Machine Learning Engineer (Contextual Understanding and Assumptions)

Using a machine learning model trained on similar situations, the model would use context and historical data to predict the ball’s location. 

Given that the ball was moved between rooms, the final state would be Room B, assuming the last move was to that room. 

If there’s no further input or action, and we base our answer on the last known movement, the ball is in Room B. 

However, we could adjust our prediction if there were additional complexities, like uncertainty in the movement or intermediate steps.

Final Conclusion:

In all three perspectives, Room B is where the ball is most likely to be, assuming it was moved there last and no further information suggests a different outcome.

## 2️⃣7️⃣​Variable Prompt Design (變數化提示詞, 変数化プロンプト)
"Create a prompt template for computing travel distance based on [Speed] and [Time]."
- 80km and 3 hours
"A vehicle travels at a speed of 80 km/h for 3 hours. How far does it go? Explain step-by-step."

Identify the given values:

Speed = 80 km/h

Time = 3 hours

Use the formula:

*Distance = Speed × Time*

Distance = 80 km/h × 3 hours

Calculate:

Distance = 240 km

The vehicle travels 240 kilometers in 3 hours.


## 2️⃣8️⃣​Historical Chain of Thought (歷史推理, 歴史的な推論)
"Explain the fall of the Roman Empire step-by-step."

**1. Economic Decline**

Overexpansion: The Roman Empire became too large to govern effectively, leading to a strained economy. 

Provinces faced high taxes and a lack of resources, causing internal economic instability.

Inflation and Devaluation: 

The empire relied heavily on slaves and conquests for wealth. As the empire's expansion slowed, there was less wealth, which led to inflation. 

Additionally, the Roman currency was devalued, weakening the economy further.

Heavy Taxes: To fund the empire’s military and vast bureaucracy, taxes increased, burdening the citizens and farmers.

**2. Political Instability**

Weak Leadership: 
The Roman Empire suffered from frequent leadership changes, with many emperors being overthrown or assassinated. 

This lack of stable leadership weakened the political structure.

Division of the Empire: 

In 395 AD, Emperor Theodosius divided the empire into the Western Roman Empire and the Eastern Roman Empire (Byzantine Empire). 

The Western Empire was much weaker and more vulnerable to invasions.

**3. Military Problems**

Barbarian Invasions: Various groups of "barbarians," including the Visigoths, Vandals, and Huns, attacked Roman borders. The Western Roman Empire struggled to defend itself from these external threats.
Mercenary Armies: The Roman military began to rely more on mercenaries—soldiers from other regions who were less loyal to Rome and sometimes even turned against the empire.
Decline in Military Discipline: The quality of the Roman army deteriorated over time. Many soldiers were not as well-trained or disciplined as in earlier periods.
**4. Social and Cultural Decay**
Decline in Civic Pride: Romans began to lose a sense of civic duty and pride in their empire. The upper classes became more focused on luxury and personal wealth rather than serving the state.
Rise of Christianity: As Christianity spread throughout the empire, it weakened traditional Roman religious and cultural practices. Some historians argue that the decline of Roman paganism led to a loss of unity within the empire.
**5. Environmental Factors**
Plague and Famine: The empire faced numerous plagues and famines that decimated its population. The weakening of the population made it harder to defend borders and maintain infrastructure.
Climate Change: Some historians suggest that climate changes, such as a cooler and drier period, could have impacted agriculture, leading to food shortages and further weakening the empire.
**6. The Final Collapse**
The Sack of Rome (410 AD): In 410 AD, the Visigoths, led by Alaric, sacked the city of Rome. This event marked a significant blow to the prestige and power of the Western Roman Empire.
The Fall of the Western Roman Empire (476 AD): In 476 AD, the last Roman emperor, Romulus Augustulus, was overthrown by the Germanic chieftain Odoacer. This event is commonly seen as the formal end of the Western Roman Empire.
**7. Legacy**
While the Western Roman Empire fell, the Eastern Roman Empire (Byzantine Empire) continued for another thousand years, until the fall of Constantinople in 1453.
The fall of Rome influenced the development of medieval Europe and the eventual rise of the Holy Roman Empire.
Final Thought:
The fall of the Roman Empire was not caused by a single event but by a combination of internal weaknesses and external pressures over time. It is often seen as a gradual process rather than a sudden collapse.

## 2️⃣9️⃣​Financial AI Analysis (財務分析AI, 財務分析のAI)
"A restaurant makes $100 per seat. If it has 50 seats and operates 7 days a week, calculate revenue."
**Step 1:** Calculate Daily Revenue
The restaurant makes $100 per seat.
It has 50 seats.
Daily Revenue=100(dollars per seat)×50(seats)=5000dollars per day

**Step 2:** Calculate Weekly Revenue
The restaurant operates 7 days a week.
So, the weekly revenue is:
Weekly Revenue=5000(daily revenue)×7(days)=35,000dollars per week
**Final Answer:**
The restaurant’s weekly revenue is $35,000.

## 3️⃣0️⃣​Real-Time AI Automation (實時AI應用, AI自動化)
"Automate data extraction and generate a summary for the provided datasheet."
**Data Extraction:**
Identify and extract key fields or columns from the datasheet (e.g., sales data, customer information, or product details).
**Generate Summary:**
Create a concise summary based on the extracted data (e.g., total sales, trends, key metrics).

