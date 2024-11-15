# Protection-in-Power-System
Typhoon Hill Model with SCADA panel and model settings for Double Line Transmission model with relays and Grid Fault.
Grid -> 11KV, 50Hz
Wind power plant -> 400V, 250 KVA, 50Hz
Transformer -> 400V/11KV
Load -> 11KV / 100KVA
Fault Direction Determination:
   Fault within -90° to 90° of polarizing voltage = Forward Fault
   Fault within 90° to 270° = Reverse Fault

Relay Characteristic Angle (RCA): Used RCA = 0 
   Phase angle where relay is most sensitive to current.
   RCA alignment with fault current angle enables precise direction detection.
   
Torque Angle Calculation (for A-GND Fault):
   Formula: Ჶ = ∠Vbc - ∠Iaf + RCA
