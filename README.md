# RPA
Robotic Process Automation projects

I am automating a tedious and labor-intensive process: the search of financial institutions on public registers from financial supervisory authorities.
See article 3-2 (3) of the law of 12 November 2004 on the fight against money laundering and terrorist financing.

This is my first try with UiPath, a RPA software. 

I tried with a bank, "BNP PARIBAS SECURITIES SERVICES", and searched on the CSSF register's website (https://supervisedentities.apps.cssf.lu/#Home).

The idea is to obtain some proof of regulation/supervision by inputting the name of the entity in the search bar programatically.
Then, take a screenshot and save it.

I believe I can enhance this feature by timestamping the saved screenshot, to make it a better auditable document.
