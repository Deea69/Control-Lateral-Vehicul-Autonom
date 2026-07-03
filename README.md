# Control-Lateral-Vehicul-Autonom

Partea practică a lucrării de licență are ca obiectiv analiza și compararea performanțelor regulatorului PID și ale regulatorului LQR pentru controlul lateral al unui vehicul autonom.
Modelul vehiculului este implementat în MATLAB/Simulink. 
Sunt analizate mai multe scenarii de schimbare a benzii de circulație și sunt comparate performanțele celor două metode de control.

Conținutul proiectului
1. **Cod_Vehicul.m** – definește parametrii vehiculului, modelul matematic și calculează matricea de câștig a regulatorului LQR.
2. **PID_vehicul_LaneChange.mdl** – modelul Simulink pentru controlul lateral utilizând regulatorul PID.
3. **LQR_vehicul_LaneChange.mdl** – modelul Simulink pentru controlul lateral utilizând regulatorul LQR.

Cerințe software
1. MATLAB R2025b (sau versiune compatibilă)
2. Simulink
3. Control System Toolbox

Rulare
1. Deschideți proiectul în MATLAB.
2. Rulați scriptul "Cod_Vehicul.m".
3. Deschideți modelul Simulink dorit.
4. Executați simularea folosind butonul "Run".
