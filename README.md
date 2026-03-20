# Data Analyst Portfolio | Semin Max

## 👨‍💻 **Resume**
| Версия | [📄 Скачать PDF](resume_ru.pdf) | [📄 Скачать PDF](resume_en.pdf) |
|--------|--------------------------------|--------------------------------|
| **Русский** | ✅ Moscow, Remote-ready | |
| **English** | | ✅ International, Ready to relocate\remote |

# Projects

### 1. **Superstore Sales Analysis** 
**Power BI + Pandas + Excel + VSLOOKUP**  
**$2.3M Sales | 12.5% Margin**  
[Dashboard](Superstore_PowerBI_Maksim.pdf) | [Pandas EDA](Superstore_eda.ipynb) | [Excel](Superstore_pivot%2Bvlookup.xlsx)

### 2. **Titanic Survival Analysis** 
**Pandas**  
**Women 1st Class: 96.8% survival**  
[Titanic EDA](Titanic_eda.ipynb)


## 🛠️ Навыки

| **Инструменты** | **Опыт** | **Проекты** |
|-----------------|----------|-------------|
| **SQL (SQLite)** | GROUP BY, SUM, COUNT, CASE WHEN, подзапросы | Superstore 9994 заказов |
| **Power BI** | Cards, Bar/Pie Charts, Maps, Slicers | [Дашборд](Superstore_PowerBI_Maksim.pdf) |
| **Excel** | Pivot Tables, VLOOKUP | Ценообразование 320+ строк |
| **Python** | pandas, SQL queries | Tinkoff анализ |

| **IT Backend (4+ года)** | **Опыт** |
|---------------------------|----------|
| **System Admin** | Active Directory, Jira/Confluence, Windows Server |
| **Tech Support** | АТОЛ, Ticketscloud, Ozon Bank, Tinkoff |
| **Инфраструктура** | PowerBI admin, SonarQube, Postman API |

## 🗄️ SQL Analysis
```sql
-- % прибыльных заказов по категориям (Technology #1!)
SELECT category, COUNT(CASE WHEN profit > 0 THEN 1 END)*100.0/COUNT(*) as profit_pct
FROM superstore GROUP BY category ORDER BY profit_pct DESC;
📈 Контакты
Telegram: @твой_ник

Email: msemin812@gmail.com

LinkedIn: Maxim Semin

Relocation: Serbia/Vietnam/Thailand ready
