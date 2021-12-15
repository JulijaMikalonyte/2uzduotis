# v1.1

Pirmos uzduoties tesinys
Pirmoje antrosios užduoties versijoje **struct duomenys** buvo pakeista į **class duoomenys**
Studentai šioje versijoje skirstomi pagal 1-ąją strategiją: kiekvienas studentas yra ir pagrindiniame std::vector<Student> Students konteineryje, ir viename iš suskaidytų konteinerių (std::vector<duomenys> VVargsiukai arba std::vector<duomenys> VProtingi).
  
  
**Duomenų rusiavimo spartos analizė:**
 
  **Naudojant Struct duomenys:**
 | 1000      |     10000 |  100000    | 1000000     |  10000000 |
 |-----------|-----------|------------|-------------|-----------|
 |0.029479 s | 0.312921 s| 3.381030 s | 31.171000 s |  |
 

  **Naudojant Class duomenys:**
   | 1000 |  10000 |  100000 | 1000000  |      10000000      |
   |------|--------|---------|----------|--------------------|
   |40 ms | 398  ms| 5004 ms | 43914 ms | neuzteko atminties |
   
  
  Taigi, naudojant **Class duomenys** skirstymas ir spausdinimas užtruko šiek tiek ilgiau. 
  
  **Spartos analizė naudojant Flag'us O1, O2, O3:**
   |Flag| 1000 |  10000 |  100000 | 1000000  |      10000000      | 
   |----|------|--------|---------|----------|--------------------|
   | O1 |39 ms | 416  ms| 4289 ms | 44563 ms | neuzteko atminties |
   | O2 |41 ms | 399  ms| 5124 ms | 47393 ms | neuzteko atminties |
   | O3 |39 ms | 402  ms| 4924 ms | 45495 ms | neuzteko atminties |

