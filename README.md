# Vaja6-ADC-scan-mode-conversion-Nucleo
Odgovori na vprašanja:

Določite in aktivirajte tri analogne vhode za kanale IN1, IN2 in IN3 za zunanje potenciometre kot Single-ended vhod. To bodo pini: 
PC0, PC1 in PC2.

Izbrani pini naj bodo vsi v isti grupi/skupini! Katera skupina je to? 
C.

Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pinov? 
ADC1_IN1, ADC1_IN2 in ADC1_IN3.

V oknu Configuration ADC pretvorbe V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Clock Prescaler nastavite tako, da bo
izračunana frekvenca vzorčenja 4 MHz. Koliko bo izbrana vrednost parametra? 
Asynchronous clock mode divided by 4.

Koliko je privzeta vrednost paramtera Number of Conversion? 
1.

Čas vzorčenja Sampling Time izberite 92.5 cikla. Koliko je čas vzorčenja v mikro sekundah? 
26,125 μs.

Kaj pomeni kratica DMA? 
Direct memory access.

Komentar:
Koda je delovala brezhibno, žal so pa bile težave pri vpostavljanju povezave med Nucelom in računalnikom. Kazalo je "Failed to start GDB server" in pozneje "No ST-LINK detected", zato ni bilo videa delovanja. Uporabljen mikrokontroler: Nucleo-L476RG

Avtorja: Brane Stojanović in Bojan Stojanović
