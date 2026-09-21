# Cvičení 2

**Klonování repozitáře:**
- Klávesa Windows + R -> cmd -> Enter
```
mkdir c:\SCZO_2026
cd C:\SCZO_2026
git clone https://cesta.ke.forked.git.repozitari
uv sync
```

**Úkol 1:**
- Prozkoumejte funkci 'create_harmonic_function'. Jaké jsou její vstupy? Co bude výstupem? 
- Zobrazte si vedle sebe libovolnou harmonickou funkci a její amplitudové spektrum 
- Měnte vstupní parametry harmonické funkce a pozorujte jejich vliv na výstupní obraz a jeho spektrum.

**Úkol 2:**
- Prozkoumejte přiloženou funkci 'generate_rectangle'. Jaké jsou její vstupy? Co bude výstupem? 
- Zobrazte si vedle sebe obraz vystupující z funkce s libovolným nastavením parametrů a jeho amplitudové spektrum 
- Měnte vstupní parametry A a B funkce a pozorujte jejich vliv na výstupní obraz a jeho spektrum.

**Úkol 3:**
- Načtěte nultý kanál podvzorkovaného obrazu 'kometa_brno_podvzorkovana.png‘ 
- Zobrazte tento obraz spolu s jeho amplitudovým spektrem 
- Ověřte teorii, že každý obraz je tvořený z 2D harmonických složek.

**Úkol 4:**
- Načtěte obrazy 'obr1.jpg' a 'obr2.jpg', převeďte na šedotonové a zobrazte. 
- Vypočtěte jejich spektra a do jednoho figure zobrazte amplitudovou a fázovou část spektra. 
- Prohoďte amplitudová a fázová spektra obou obrazů a zobrazte obrazy po prohození v originální oblasti.


**Závěr cvičení:**
```
git add .
git commit –m „message“
git push origin main
```