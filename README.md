# Data-Cleaning-Membership

Data yang digunakan pada _project_ ini adalah data 'Gym Membership', dan melakukan _Cleaning treatment_ menggunakan Python pada data RAW tersebut,
dari data yang telah "Bersih" dapat di tampilkan Visualisasi dan ditambahkan Feature Engineering untuk Proses Machine Learning.
Dan selanjutnya ditarik insight dari segi bisnis dari data tsb.

Case Stages
- Data Cleaning
- Data Visualisasi
- Feature Engineering
- Data Understanding
- PowerBI Dashboard

# Data Cleaning : 
1. Missing Value Check
2. Duplicate Check
3. Numerical Columns
4. Copying DataFrame
5. Cleaning Name Column (Trim, Remove Extra Space and Special Char)
6. Cleaning Age Column (Change Data Type, Fill NA, Fix Anomalies Age)
7. Cleaning Marital Column (Renaming, Fill NA)
8. Cleaning Phone No. Column (Fill Na, Invalid phone number)
9. Cleaning Job Column (Fill Na, Trim Roman Number)
10. Cleaning Membership Date Column (Replace Data)
11. Remove Duplicate

# Data Visualisasi : 
1. Age Distribution
2. Marital Distribution
3. Job Title Freq
4. Membership Date Trend
5. Geo Distribution

# Feature Engineering :
1. Age Group
2. Membership Duration
3. City & State
4. Membership Month & Year
5. Is Married


# Data Understanding
- Insight statement
  1.  Dari Age Distribution dapat di identifikasi majority age range sehingga dapat di maksimalkan strategi New member untuk pada demografi age tsb yang sesuai dengan target, ataupun memberikan service dan kebutuhan yang sesuai age group nya
     ![image](https://github.com/rezakusnadi/Data-Cleaning-Membership/assets/92531579/787f544f-520b-46cc-8384-fa5c1bf366da)
  2.  Marital Status terbanyak pada Married status, dapat di maksimal kan event or promotion yang bertema family, for the new member ataupun layanan yang dapat di sesuaikan dengan marital status para member
     ![image](https://github.com/rezakusnadi/Data-Cleaning-Membership/assets/92531579/0705688b-5187-488c-b7a1-87dc0a07f8c4)
  3.  Dari Top 5 Freq Job Title, ternyata banyak White Collar yang menjadi membe, insight untuk targeted promotional selanjutnya,
      juga terdapat banyak null dalam pengisian, concern dalam pengisian data member
     ![image](https://github.com/rezakusnadi/Data-Cleaning-Membership/assets/92531579/8cc8fe5c-adc7-49fc-9ada-f50994f28f5d)
  4.  Mengambil Membership Trend pada recent tahun pada data 2022,
      dapat di lihat pola musiman dalam pendaftaran, untuk dapat membantu perencanaan promosi atau event
     ![image](https://github.com/rezakusnadi/Data-Cleaning-Membership/assets/92531579/0549925e-0a5b-4ea1-8854-60792f84b768)
  5.  aktifitas dan efektifitas outlet pada setiap kota, evaluasi outlet
     ![image](https://github.com/rezakusnadi/Data-Cleaning-Membership/assets/92531579/324ba26c-2b40-45a3-a700-e6f54458902a)

# PowerBI Dashboard

  Membership Dashboard
  ![image](https://github.com/rezakusnadi/Data-Cleaning-Membership/assets/92531579/2a645e49-6f2c-4129-881c-9a2a33480e53)
  
  Tooltip For City on Top State <br>
    ![image](https://github.com/rezakusnadi/Data-Cleaning-Membership/assets/92531579/4e29aa5f-a632-4093-a2a5-1d29425c59c5)


