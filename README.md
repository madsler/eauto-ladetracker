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
