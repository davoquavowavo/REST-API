# REST-API

Til REST API øvelse

URL endpoint til at oprette mappe: files/create_folder_v2

HTTP-verb: POST

Svar fra API: {
    "metadata": {
        "name": "testmappe",
        "path_lower": "/testmappe",
        "path_display": "/testmappe",
        "id": "id:ZGXZKFNuGZ4AAAAAAAAABg"
    }
}


Beskriv kort kort om uniform interface: Gør brug af HTTP-verber som er en del af REST. Bruger URL til at identificere specifikke resourcer.

URL endpoint til at få mappedata: files/get_metadata

Statuskode: 200OK


Kunne ikke få fil upload til at virke selvom alt var specifiseret og URL var korrekt så jeg uploadede den manuelt på Dropbox.


Endpoint til at slette fil: files/delete_v2

HTTP verb: POST

Sti: "path": "/testmappe/lol.pdf"

Kunne ikke få de resterende til at fungere, selv med manuelt upload - ved ikke hvad problemet var.

