# eauto-ladetracker
simple container managed tracking for charging my id7 and exporting a csv with all data for my companie to get my cash back

get it up and running:

Edit app.py column 77-86:

    ws["A4"] = "Kennzeichen"
    ws["B4"] = "EDIT"
    ws["A5"] = "Fahrer"
    ws["B5"] = "EDIT"
    ws["A6"] = "Abteilung"
    ws["B6"] = "EDIT"
    ws["A7"] = "Kostenstelle"
    ws["B7"] = "EDIT"
    ws["A8"] = "Kosten pro KW"
    ws["B8"] = "EDIT"
docker-compose up --build -d

reachable via browser: http://<IP>:5000


looks:
Input your data:
<img width="327" height="345" alt="image" src="https://github.com/user-attachments/assets/1eae8660-7fa5-49b0-b835-279ffc6a056d" />
Export your data:
<img width="183" height="62" alt="image" src="https://github.com/user-attachments/assets/95b32cda-2092-4ae6-8c88-493ea3c09006" />
Excel export look-a-like:
<img width="313" height="175" alt="image" src="https://github.com/user-attachments/assets/b0c24a47-e688-4769-8c15-51dacc57611a" />

