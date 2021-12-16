# 2uzduotis
-pirmos uzduoties tesinys-
# v1.1

Pirmoje antrosios užduoties versijoje **struct duomenys** buvo pakeista į **class duoomenys**
Studentai šioje versijoje skirstomi pagal 1-ąją strategiją: kiekvienas studentas yra ir pagrindiniame std::vector<Student> Students konteineryje, ir viename iš suskaidytų konteinerių (std::vector<duomenys> VVargsiukai arba std::vector<duomenys> VProtingi).
  
**Duomenų rusiavimo spartos analizė:**
 
  **Naudojant Struct duomenys:**
 | 1000      |     10000 |  100000    | 1000000     |  10000000    |
 |-----------|-----------|------------|-------------|--------------|
 |0.029479 s | 0.312921 s| 3.381030 s | 31.171000 s |  329.378298 s|
 
**Naudojant Class duomenys:**
| 1000       |  10000    |  100000   | 1000000    |      10000000      |
|------------|-----------|-----------|------------|--------------------|
| 0.029072 s | 0.310462 s| 3.451180 s| 33.272768 s| neuzteko atminties |
  
**Spartos analizė naudojant Flag'us O1, O2, O3:**
|Flag|      1000 |     10000 |     100000 |    1000000  |      10000000      | 
|----|-----------|-----------|------------|-------------|--------------------|
| O1 |0.028021 s | 0.323732 s| 3.513615 s | 30.708895 s | neuzteko atminties |
| O2 |0.028930 s | 0.321897 s| 3.466218 s | 31.026003 s | neuzteko atminties |
| O3 |0.049524 s | 0.315273 s| 3.367303 s | 32.113235 s | neuzteko atminties |


# v1.2
