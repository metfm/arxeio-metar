το αρχείο zwntana.html προσαρμοσμένο στο πρόγραμμα weewx στο linux
δημιουργούμε σε οποιοδήποτε skin (κατα προτίμηση στο seasons)   το αρχειο zwntana.html.tmpl
βαζουμε μέσα τον κώδικα του παρόντος αποθετηρίου.
προσθέτουμε στον φάκελο skin.conf του skin που εχουμε επιλέξει, στο τμήμα  [CheetahGenerator]

[[Zwntana]]
[[[index]]]
       template = zwntana.html.tmpl 
       
εκτελουμε στο τερματικο  sudo /etc/init.d/weewx reload

αν ολα εχουν γινει σωστά θα δουμε τοπικα το αρχειο στην σελιδα localhost/weewx/zwntana.html και στο διαδίκτυο στην σελίδα μας http://myweatherpage/zwntana.html
