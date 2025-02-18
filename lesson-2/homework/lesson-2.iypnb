1. Mijozlar Ma'lumotlari:
•  CustomerID: Unikal identifikator.
•  Yosh (Age): Bu ma'lumot customers.csv faylidan olinadi.
•  LoanType va Amount: Yoshga qarab, kredit turi va miqdori belgilanishi kerak.
Aksariyat mijozlar yoshiga qarab quyidagi tarzda kredit olishadi:
•  18-24 yosh: Student, Personal, Auto (Amount: 5M - 30M UZS).
•  25-35 yosh: Personal, Auto, Mortgage, Business (Amount: 20M - 100M UZS).
•  36-50 yosh: Mortgage, Business, Personal (Amount: 50M - 500M UZS).
•  50+ yosh: Mortgage, Personal, Auto (Amount: 50M - 300M UZS).
2. Kredit Turlari va Miqdori (Amount)
•  Har bir yosh guruhiga mos kredit turi va miqdori belgilab olinadi.
•  Foiz stavkalari ham kredit turiga mos bo‘lishi kerak: 
o  Student loan: Yuqori foiz (20%-25%).
o  Personal loan: O‘rtacha foiz (12%-18%).
o  Auto loan: O‘rtacha foiz (14%-18%).
o  Mortgage: Past foiz (10%-15%).
o  Business loan: O‘rtacha foiz (15%-20%).
3. StartDate va EndDate
•  StartDate: Mijozning kreditni olish sanasi. Realistik sanalar tanlanadi.
•  EndDate: Kreditning tugash sanasi. Mijozning yoshiga va kredit turiga qarab, muddat belgilanishi kerak (1-5 yil).
•  StartDate va EndDate orasidagi farq noto‘g‘ri kiritilishi kerak (masalan, StartDate > EndDate yoki noto‘g‘ri sanalar).
4. Kredit Statusi (Status)
•  Status turlari: 
o  Closed: Kredit to‘liq yopilgan.
o  Rejected: Kredit rad etilgan.
o  Pending: Kredit arizasi ko‘rib chiqilmoqda.
o  Approved: Kredit tasdiqlangan.
5. Problematic Data
•  4% Problematic data kiritish. Bu faqat StartDate va EndDate bo‘yicha bo‘ladi: 
o  EndDate > StartDate.
o  Noto‘g‘ri sanalar (kelajakdagi yoki eski sanalar).
o  StartDate va EndDate farqi salbiy.
6. Realistik Data Generatsiyasi:
•  customers.csv faylini o‘qish va mijoz yoshini olish.
•  Yoshga qarab, LoanType, Amount, InterestRate, StartDate, EndDate, va Status kabi ma'lumotlarni belgilash.
•  StartDate va EndDateni generatsiya qilishda realistik, lekin ba'zi noto‘g‘ri sanalar qo‘shish (4% problematic data).
•  Har bir mijozga LoanID (Identity) yaratish va CustomerIDni Loans jadvaliga kiritish.
7. Data Generatsiya Bilan Bog‘liq Masalalar:
•  Row Sonini Tanlash: 8,000 mijoz uchun data generatsiyasi.
•  Har bir CustomerID ga mos keladigan kredit ma'lumotlarini yaratish.
•  Mijozlarning yoshiga qarab kredit turini va miqdorini realistik qilib taqsimlash.
