# gis
1
        
        1. Integroni ne nje faqe web, harten e google(GoogleMap) me dimensione 700px me 500px, 
        qender koordinaten(41.3275, 19.8187), shkalle 15, pamje te rrjetit rrugor.

        2. Identifikoni qendren e hartes me shenjuesin(Marker) me titull 'Tirana'.

        3. Degjoni ngjarjet e klikimit ne harte. Perdorni simbolin BACKWARD_CLOSED_ARROW te klases SymbolPath, 
        per te shfaqur ne harte pikat e klikuara. Shtoni mbi çdo simbol, nje infowindow me te dhenat lat,lng te koordinates.

2
        
        1. Nisuni nga objekti marker(i krijuar ne Detyren nr.1), ndertoni me ane te klikimeve ne harte rrugen 
        qe ju con drejt pikes destinacion. Destinacioni eshte nje vendodhje, e percaktuar nga ju, e ndryshme nga e para. 
        Shembull, koordinatat: 41.33,19.82. Duke perdorur objektin Polyline vizualizoni rrugen e formuar klikim pas klikimi. 
        Vija te paraqitet me ngjyre te verdhe, trashesi vije 1.5px.

        2. Shfaqni ne harte objektin Polygon, pathi i te cilit nis me objektin LatLng e krijuar ne Detyren nr.1. 
        Polygon-i do te formohet duke degjuar ngjarjet dbclick ne harte. Polygon-i nuk duhet te permbaje me teper se 5 objekte LatLng. 
        Ne piken e 5-te te klikuar, largohet pika e nisjes dhe shtohet pika e re.

        3. Ndertoni dhe shfaqni ne harte objektin Rectangle, i cili formohet duke perdorur skajet e polyline-it te krijuar ne piken 1, si NE dhe SW.

        4. Degjoni ngjarjet e klikimit mbi objektin polyline te krijuar ne piken 1. Mbi cdo pike te klikuar vendoset nje rreth me qender, 
        koordinatat e pikes, dhe rreze 1*numrin_e_klikimit_mbi_polyline. Pra, pika e pare e klikuar ka rreze 1, pika e dyte e klikuar ka rreze 2, 
        pika e n-te ka rreze n.
