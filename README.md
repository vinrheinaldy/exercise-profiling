# Test Results

## Test 1 findAllStudents

### Before 
![all stud](https://github.com/user-attachments/assets/adfb19c5-813b-4abf-96d5-d622cc49e9e8)
![Screenshot 2025-03-14 202525](https://github.com/user-attachments/assets/0b603176-a183-4a8f-a444-a5a781071441)

### After
![all_stud_opt](https://github.com/user-attachments/assets/2d5d8f70-81c0-4b65-85d3-b8847c7c2340)
![Screenshot 2025-03-14 202553](https://github.com/user-attachments/assets/8c4d35cf-6b6d-4e5e-b640-a8371d6ee54c)

## Test 2 allStudentName

### Before 
![stud name](https://github.com/user-attachments/assets/6a12e7fb-a371-4236-8ef6-7ca55dde6ce6)
![Screenshot 2025-03-14 202536](https://github.com/user-attachments/assets/4f309e37-1802-46db-9e95-1b00a7449e66)

### After
![all_name_opt](https://github.com/user-attachments/assets/c0735b06-6bd5-425b-b17a-db8806222900)
![Screenshot 2025-03-14 202542](https://github.com/user-attachments/assets/6e82fcf6-e88f-442d-a1c3-4b1322266093)

## Test 3 highestGpa

### Before
![highest gpa non opti](https://github.com/user-attachments/assets/98f7b7ad-9f68-46b2-ada1-2ef0dc9dcef8)
![Screenshot 2025-03-14 202542](https://github.com/user-attachments/assets/cf0553a2-bd51-48c9-b60e-73feea30cd79)

### After
![gpa_opt](https://github.com/user-attachments/assets/571ebfd0-97a3-4318-92e1-34b937c6b81a)
![Screenshot 2025-03-14 202605](https://github.com/user-attachments/assets/c2445f05-8807-4391-b0d7-101771c44ec0)

## Difference:

### Test 1:
Before: 30023 (Error)

After : 9986

### Test 2:
Before: 30027 (Error)

After : 289

### Test 3:
Before: 129.4

After : 9

### Note : 
Jujur gatau itu knp error yang test 1 sama 2 di awal tapi abis di fix ga error, udah di run beberapa kali tetep error.

# Reflection
## Please answer the following questions:
1.What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?

2.How does the profiling process help you in identifying and understanding the weak points in your application?

3.Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

4.What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

5.What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

6.How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

7.What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

## Answers :

1. Menurut saya, dari hasil yang tadi saya baru kerjakan juga, JMeter lebih fokus kepada simulasi terhadap beban user yang datang, dan respons API. Sedangkan Intellij Profiler lebih melihat kepada backend developernya
contohnya dengan memberi tunjuk berapa banyak CPU & Memory yang digunakan oleh program.
2. Dengan profiling saya bisa melihat masing-masing API yang saya buat, sehingga saya bisa me-refactor function tersebut.
3. Sangat membantu.
4. Awal-awal saya lumayan sulit mencerna isi dari graph-graph yang diberikan oleh JMeter, untuk mengatasi mungkin saya harus lebih membiasakan diri untuk menggunakan JMeter.
5. Benefit utama adalah mengetahui bottleneck pada back-end. Dengan melihat graf CPU dan Memory kita bisa melihat resource yang terpakai banyak yang mana.
6. Ini biasa terjadi karena faktor eksternal, namun jika terjadi adalah dengan testing pada localhost agar lebih terkontrol.
7. Identifikasi bottleneck terletak pada bagian kode yang mana, tentunya bottleneck ini akan di benarkan dengan kode yang efisien dan tidak mengganggu kode lain.


