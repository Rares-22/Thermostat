# Thermostat

Obiectivul principal al acestui proiect este dezvoltarea unui termostat pentru o centrala termica in limbajul de programare hardware VHDL.
Acesta are urmatoarele functionalitati:
- Poate seta o temperatura minima si maxima.
- Daca temperatura scade sub cea minima, acesta trimite un semnal care va porni centrala si va creste temperatura cu 1 grad la fiecare 3 minute
- Daca temperatura este peste cea maxima, acesta trimite un semnal care va opri centrala, iar temperatura va scadea cu un grad la fiecare 3 minute
- Afiseaza temperatura si ora pe un decodificator 7-segmente

Implementarea proiectului s-a realizat pe placa FPGA Basys 2.
