# RPA
Robotic Process Automation project

I am automating a tedious and labor-intensive process: the search of financial institutions on public registers from financial supervisory authorities.
See article 3-2 (3) of the Luxembourg law of 12 November 2004 on the fight against money laundering and terrorist financing.
>> https://www.cssf.lu/fileadmin/files/Lois_reglements/Legislation/Lois/L_121104_AML_upd170418_eng.pdf

This is my first try with UiPath, a RPA software. 

I searched a bank, "BNP PARIBAS SECURITIES SERVICES" on the CSSF register's website (https://supervisedentities.apps.cssf.lu/#Home).

The idea is to obtain some proof of regulation/supervision by inputting the name of the entity in the search bar programmatically.
Then, take a screenshot and save it.

I believe I can enhance this feature by timestamping the saved screenshot, to make it a better auditable document.
