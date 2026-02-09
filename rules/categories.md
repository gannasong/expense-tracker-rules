# Expense Categories

## Category List

| Category | Keywords / Triggers |
|----------|-------------------|
| 伙食費 | 午餐, 晚餐, 早餐, 便當, 買菜, 全聯, 家樂福, Costco, 超市, 菜市場, 食材, 煮飯 |
| 外食 | 餐廳, 火鍋, 麥當勞, 外送, 小吃, 夜市, 聚餐, 壽司, 拉麵, 披薩, foodpanda, UberEats |
| 飲料 | 咖啡, 手搖, 茶, 星巴克, 路易莎, 50嵐, 飲料 |
| 超商 | 7-11, 全家, 超商, OK, 萊爾富, FamilyMart |
| 油錢 | 加油, 油錢, 中油, 台塑 |
| 通勤停車 | 停車, 高鐵, 捷運, Uber, 計程車, 公車, 通勤, ETC, 過路費, 火車, 台鐵 |
| 保健品 | 維他命, 保健, 營養品, 魚油, 益生菌 |
| 生活雜物 | 衛生紙, 洗衣精, 清潔, 日用品, 生活用品, 洗髮精, 沐浴乳, 牙膏 |
| 醫療相關 | 看診, 藥, 牙醫, 醫院, 診所, 掛號, 健檢 |
| 治裝費用 | 衣服, 鞋子, 褲子, 外套, 包包, 配件 |
| 育兒開銷 | 尿布, 奶粉, 玩具, 童裝, 幼兒, 托嬰, 保母 |
| 浪費 | (default) All other expenses |

## Disambiguation Rules

- Supermarket grocery shopping (全聯/家樂福/Costco buying groceries) -> 伙食費
- Supermarket buying cleaning supplies -> 生活雜物
- Convenience store (7-11/全家) -> 超商 (do not split into subcategories)
- Restaurant dining / eating out -> 外食
- Home-cooked meal ingredients -> 伙食費

## Payment Methods

| Method | Keywords |
|--------|----------|
| 現金 | (default) |
| 信用卡 | 刷卡, 卡, 信用卡 |
| 轉帳 | 轉帳, 匯款 |
| 行動支付 | Line Pay, Apple Pay, 街口, 行動支付 |

## Payer Rules

- Default payer: Miguel
- If message mentions: 老婆, 太太, Hannie, hannie -> payer = Hannie
