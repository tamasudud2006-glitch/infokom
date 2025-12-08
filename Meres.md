## DVB-T MÉRÉSI JEGYZŐKÖNYV

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum  
**Mérés időpontja**: 2025.12.08.  
**Mérő műszerek**: METEK HD - SV:1.17.2002 - SN: 2109010000052  
**Felelős személy**: Udud Tamás  
**Cél**: A DVB-T jel minőségi paramétereinek mérése.  

---

### 1. **Bevezetés**

A mérés célja a DVB-T jel paramétereinek ellenőrzése a földfelszíni digitális műsorszórás során. 
A mérési pont a **V3 LABOR**, ahol a DVB-T adások vételének minőségét értékeljük.

### 2. **Mérési helyszín és környezet**

- **Koordináták**: 48°06'20"N 20°46'48"E
- **Antenna típusa**: [SMART HD 550 szobaantenna](https://bolt.sat.hu/opticum-smart-hd-550-szobaantenna-3135?srsltid=AfmBOoq5nEHH0aM1MYhOp06UG-G1v6voMY-3hBfHwIylpXZsaC2rHt3o)  
- **Antenna magassága**: 1.7 m
- **Környezet jellemzői**: V3 labor, városi körülmények között  
- **Adó távolsága**: 780,08 m

<details>   
  <summary> ADÓTORONY - VÉTELI HELY távolság </summary>
  
  <img src="https://sandorpeteer.github.io/tavkozles/img/map.png" alt="TVtorony" />
  
</details>

<br>

### 3. **Mérési paraméterek**

| Paraméter           | Érték |
|---------------------|-------|
| Adó frekvencia       | 634.5 MHz |
| Sávszélesség         | 8MHz |
| Moduláció típusa     | DVBT / QPSK / 8K / 1/32  |
| Jelerősség (RSSI)    | 46 dBu |
| MER                  | 27.8 dB |
| Noise Margin         | 24.1 |
| Hiba nélkül vett adás időtartama | 102 sec |   


<details>   
  <summary> A Miskolci TV adótorony által sugárzott frekvenciák </summary>
 
</details>

<details>   
  <summary> A CH45 -ös csatornán mért spektrum </summary>
  <img width="1280" height="720" alt="its_snapshot_0001" src="https://github.com/user-attachments/assets/e8abd699-4ac2-4512-9773-17a599165155" />

</details>

<details>   
  <summary> A CH45 -ös csatornán mért jelerősség, jel/zaj viszony, és bithibák </summary>
  <img src="https://sandorpeteer.github.io/tavkozles/img/its_snapshot_0002.bmp" alt="NOISE MARGIN" />
</details>

<details>   
  <summary> A CH45 -ös csatorna konstellációs diagramja </summary>
  <img src="https://sandorpeteer.github.io/tavkozles/img/its_snapshot_0004.bmp" alt="CONSTELLATION" />
</details>

<details>   
  <summary> A CH45 -ös csatornán a DUNATV HD jelszint és TV adás </summary>
  <img src="https://sandorpeteer.github.io/tavkozles/img/its_snapshot_0003.bmp" alt="DUNATV" />
</details>

<details>   
  <summary> A CH45 -ös csatornán a DUNATV HD műsora </summary>
  <img src="https://sandorpeteer.github.io/tavkozles/img/its_snapshot_0005.bmp" alt="DUNATV" />
</details>

<br>

### 4. **Mérési eredmények**

- **Jelerősség**: A mért jelerősség **64 dBu**. Ez az érték stabil volt **200 másodperces időtartam alatt**, és megfelel a DVB-T előírásoknak. A mérési helyen a jel optimális volt.  
  
- **Modulációs paraméterek**: A **64-QAM** moduláció esetén a mért jel/zaj viszony (SNR) **12 dB** körül váltakozott, ami megfelel a követelményeknek.  

- **Modulation Error Ratio (MER)**: A mért MER érték **28.2 dB** volt, amely azt mutatja, hogy a vétel **probléma mentes** volt.  

### 5. **Elemzés**

Az eredmények alapján a mérési helyen megfelelő minőségű DVB-T vétel biztosítható. A jelerősség és SNR értékek a megadott határértékek között mozogtak. A MER alacsony, és nem okozott észlelhető minőségromlást a vételben. A moduláció stabil volt, és nem voltak nagyobb interferenciák a mérések során.  

### 6. **Következtetések**

- A mérési helyen a DVB-T jel stabil és megfelelő minőségű.  
- A rendszer modulációs és vételi paraméterei kielégítik a DVB-T előírásokat.  
- A jel/zaj viszony és a jelminőség értékei optimálisak voltak a földfelszíni sugárzás vételéhez.  

### 7. **Javaslatok**

Ha szükséges, meg kell vizsgálni az antennarendszer fejlesztésének lehetőségét, vagy további méréseket kell végezni különböző időjárási körülmények között, hogy hosszú távon is biztosított legyen a megfelelő minőségű vétel.

---

**Aláírás**:  
Felelős mérő személy: ..............................  
Dátum: .............................................
