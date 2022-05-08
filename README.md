# Kërko-fetua

Qëllimi i këtij dokumenti është të nxisë zhvillimin e një shërbimi që do të ju shërbejë besimtarëve të thejshte në veçanti por jo vetëm.

## Ideja

Ideja është, të zhvillohet një shërbim që do të indeksojë të gjitha ligjeratat e hoxhollarëve shqiptarë që kanë në youtube, dhe të mundësojë kërkimin e fetuave në një aplikacion mobil.

Aplikacioni mobil do të ketë një komponentë input ku përdoruesi do të mund të shkruajë pyetjen. Si rezultat do ti shfaqen të gjitha videot në youtube ku hoxhollarët flasin për atë temë. Nëse përdoruesi zgjedh njërën nga rezulatet, ai do të ridrejtohet te videoja në youtube, te minuta dhe sekonda e caktuar nga ku fillon hoxha ti përgjigjet pyetjes.

## Përfitimet

Së pari, kjo do t’u mundësojë besimtarëve të gjejnë shpejtë përgjigjen për pyetjen që kanë. Së dyti, shumë pyetje u parashtrohen hoxhollarëve disa herë. Ata duhet t’u përgjigjen të njëjtave pyetje shumë herë. Kjo do t’ua lehtësojë punën edhe hoxhollarëve.

## Zhvillimi teknik

Për zhvillimin e një aplikacioni të tillë duhen disa komponenta. Unë do t’i përmendë disa sipëfaqësisht, dhe në të ardhmen do ti detajizojmë më shumë. 

1. Algoritëm “Speech-To-Text” me “Machine Learning”
Përdorimi i këtij algoritmi do të jetë në transkribimin e të gjithë video ligjeratave. Si bazë mund të merret ndonjë algoritëm i njohur “open source” dhe të ushtrohet me të dhëna në gjuhën shqipe. Për këtë duhen përgatitur shumë të dhëna në gjuhën shqipe
2. Mikroshërbim (Microservice) që do të ndjekë çdo video ligjeratë e re që del ne youtube dhe me ndihmën e algoritmit sipërpërmendur ta transkribojë ligjeratën dhe ta indeksojë.
3. Shërbim API për kërkim 
Backend që do të mundësojë kërkimin në bazë zë pyetjes së përdoruesit
4. Aplikacion mobil
Aplikacion për Android dhe iOS e pse jo edhe për Windows, MacOS dhe Linux, të cilin do ta përdorin të interesuarit për të marrë përgjigjen për pyetjen që kanë.

## Kontributi juaj

Për t’u zhvilluar një shërbim i këtillë duhet ndihma e shumë zhvilluesve (developers). Vecanërisht për zhvillimin e algoritmit me “machine learning”.

## Open source

I gjithë projekti do të jetë open source.
