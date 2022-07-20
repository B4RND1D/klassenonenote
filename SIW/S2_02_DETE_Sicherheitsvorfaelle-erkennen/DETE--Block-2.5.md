# DETE: Block 2.5

Created: 2022-02-17 20:12:34 +0100

Modified: 2022-02-17 20:13:10 +0100

---

![SiUJ Die digitale Höhere Fachschule Unterricht Block 3: Netzwerk 1 10.02.2022 ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image1.png)



![Refresh Computer-Netzwerke Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image2.png)



![Computer-Netzwerke ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image3.png)



![Nichtlokale Netze ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image4.png)



![OSI-Referenz-Modell • In der Praxis gibt es unterschiedlichste technische Systeme Open Systems Interconnection Model (OSI) Schicht S Schicht 4 (S) Instanz (S) Instanz Instanz Instanz Austausch bare Schi chten Schicht 3 Schnittstellen müssen gegenüber unten und oben standardisiert sein ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image5.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image6.png)



![IP/TCP-Referenz-Modell Verschachtelung TCP TCP TCP Aß)licaticn Layer Transpa•t Layer Network Layer Network Access Layer Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image7.png)



![Was ist ein Paket? Geschlossene Dateneinheit Beispiel: Header mit Sender Empfanger Grösse Payload Abschluss Check5umme Tipp: Macht eine Nachschlaze- Liste der im Kurs behandelten Protokolle ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image8.png)



![Wichtige Protokolle (OSI 1 - 4) ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image9.png)



![IEEE 802.1/3: Ethernet und MAC OSI Laver 1/2 Protokoll-Sammlung von Standards aus Hardware (Kabel, Hardware- Schnittstellen, Netzwerk-Karten) und Software (Protokolle) Standard in lokalen Netzwerken • Nicht zuverlässiges Protokoll trotz Prüfsumme 22 Ethernet-Frame: Min. 64, Max. 1518 Byte (mit Vl_AN.T.g: Max. 1522 Byte) ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image10.png)



![IEEE 802.1/3: Ethernet und MAC Standardmässig keine Authentisierung Möglicher Angriff Kleinst-Computer in der Lobby oder Sitzungsraum mit dem Netzwerk verbinden Network Access Control (NAC) Gerät muss sich sich Au th enti si eren MAC-Adresse • Zertifikats-Basiert (802.1X) 2 LAN ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image11.png)



![Internet Protokoll v4 Grundlage des Internets Routable-Proto col Pakete können über mehrere Pfade an ihr Ziel gelangen So können Netzwerke verbunden v,'erden Bietet die Möglichkeit der Subnetz-BiIdung • IPv4-Adresse: 32 Bits Version IHL Type of Service Total Length Time to Live Flags Header Source Address Destination Address padding Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image12.png)



![Internet Protokoll v4 Aufteilung von Netz und Host Viele Netzte mit weniger Hosts oder weniger Netzte mit vielen Hosts Netz-Segmen tierung ist auch Secu rit.,' -Relevan t (zo nierung mittels F irewall) 2. 128 /2 t2g6ag2 Netzanteil I p-Adresse / Sub maske len Netz IP 1-255 Host ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image13.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image14.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image15.png)



![Transport-Layer Bisher: 1 Host = 1 Adresse Wir möchten aber mehrere Dienste auf einem Host betreiben Destination-Port bezeichnet die Ziel-Anwendung Es gibt 216 = 65536 Ports Port 1-1024 sind «well known Ports», sie sollten nicht für eigene Anwendungen verwendet werden 53: ONS 443 21: ssH ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image16.png)



![User Datagram Protocol OSI Layer 4 Eine Anwendung (Programm) kann von Betriebssystem eine UDP-Verbindung beantragen WOP ist verbindungslos Pakete 5ind unabhängigvoneinander (UDP) WOP stellt keine zuverlässige Verbindung her Sollte der Prüfsummencheckim Ethernet- Frame fehlschlagen wird ein Paket ersatzlos Vorteile Einfachheit Cer-ch',vindigkcit Wenig Overhead ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image17.png)



![Transmission Control Protocol (TCP) Server Zuverlässiges Protokoll Pakete können auf der anderen Seite korrekt zusammengebaut werden 3-Wav- Handshake Ackno'.•.'l edgement garantiert Zuv erlässi gkeit Sequenz-Nummer garantiert Reihenfolge Jede Datenübertrazunz muss vom Partner mit einem ACK- Paket beståtizt werden So kann die Reihenfolge und Vollständigkeit der Pakete überprüft werden Client ack--- se ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image18.png)



![Wireshark Sidi ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image19.png)



![Wireshark Tool um Paket-Basierte Protokolle analyziseren Es decodiert die Pakete gemäss deren Protokoll Es kann genuzt werden um den Datenstrom live zu decodieren Traffic kann in PCAP-FiIes gespeichert werden ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image20.png)



![Wireshark ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image21.png)



![Wireshark 1. 2. 3. 4. Display Filer Pakete filtern Referenz: h ttp s:/ /wiki.wireshark.oæ/Disp lavFilters Dekodierte Pakete «Zeitstrahl>) der Pakete auf dem Interface Protokoll-Stack «Aufsch ach etlungn des Pakets Binäre Daten des Frames Wie die Daten auf dem Netzwerkinterface aussehen ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image22.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image23.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image24.png)



![Wireshark Display Filter Werte English c.like verknüpfen AND OR and r ip.srce192.1.I.1 tr.dstte:31 --- e.6.29 in -GET). Sian FilterSection html ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image25.png)



![Wireshark Suche Display Filter filtern nur Pakete Suche inerhalb des Daten-Stroms mit CTRL+F Text/Regex/Hex-Suche ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image26.png)



![Hacking Lab: Einführung in Wireshark Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image27.png)



![Hacking Lab: Listen to VolP phone call Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image28.png)



![Hacking Lab: TCP-Traffic untersuchen und Reverse Shell bauen (Teil 1) Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image29.png)



![Wichtige Anwendungs-Layer- Protokolle ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image30.png)



![Anwendungen Bisher war das Betriebssystem verantwortlich Dieses Stellt Schnittstellen bereit (SYSTEMCALLS) um eine Verbindung aufzubauen und zu nutzen SOCKET-Operationen Senden/Empfangen Socket (Steckdose) ist ein interner Endpunkt einer Verbindung OSI Reference Model a Presentation a Session Conceptual Application ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image31.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image32.png)



![Dynamic Host Configuration Protocol (DHCP) Ein Host muss folgende Parameter definiert haben: IP-Adresse Subn atz-M aske Standard Gateway DNS-Server Kann man manuell konfigurieren Ist bei grösseren Netzwerken mühsam ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image33.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image34.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image35.png)



![Verzeichnisdienste Hierarchische Datenbank für Benutzer, Gruppen oder System-Intorm ationen Vereinfacht die Verwaltunz von Inventar, Benutzer und Gruppen Wird z.B. im Intranet einer Orzanisation ab einer zewissen Grösse verwendet Protokoll: Lizhtweizht Directory Access Protocol Active Directory ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image36.png)



![Dateitransfer-Protokolle Protokolle speziell zum Austausch von Dateien Abbildung von Ordner-Strukturen Beispiele: Network File System Server Message Block (Stv18, ursprüngiich Common Internet File System File Transfer Protocol SSH File Transfer Protocol Web -based Distributed Au thoring and Versioning (Web DAV) Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image37.png)



![Netzwerk-Management-Protokolle Kategorie von Protokollen zum Clberwachen und Steuern von Geräten (Router, Switches, Server, Drucker usw.) Beispiele: Telnet • Secure Shell (SSH) Simple Network Man agementProtocol (SNMP) Remote Desktop Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image38.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image39.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image40.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image41.png)



![Simple Mail Transfer Protocol (SMTP) Einfaches Protokoll zum Austausch von E-Mails Nachricht kann Über mehrere Mail-Gateways ans Ziel Beispiel: Mail-Gateway im Firmen-Netzt Kein standardmässiger Schutz der Daten gemäss CIA-Triad Sie" ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image42.png)



![Verschlüsselte Protokolle ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image43.png)



![Verschlüsselte Protokolle Bisher habe wir unverschlüsselte Protokolle angeschaut Ein passiver Man-In-The-Middle kann potentiell sensitive Daten auslesen Ein aktiver Man-In-The-Middle kann Daten auch verändern AVAlLA31LlTY Sic" ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image44.png)



![Transport Layer Security TLS DER Verschlüsselunzs-Standard bei Datenübertrazunz Verantwortlichkeit der Anwendunz (OSI Laver 5) Verb reitete Implementierunz openSSL (C Programmier-Sprache) BouncyCaÄle (Java Programmier- Sprache) Viele Anwendunzs-Protokolle nutzten TLS OSI Reference Model a Application a Presentation a Session Transport Network Data Link Physical 1 1 TCP/IP Conceptual Layers Application Tra n sport Network Network Interface Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image45.png)



![Transport Layer Security TLS Stellt zwei CIA-Triad Anforderungen sicher • Integrity (Integrität) durch Au thentisieren Confiden tialitl,' (Vertraulichkeit) durch Verschlüsselung Verschlüsselung ohne Authentisierung ist anfällig auch Man-In-The- Middle Angriffe cnc.hacking---lab.com ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image46.png)



![Transport Layer Security TLS Authentisieren mittels asymmetrischer Verschlüsselung Signieren von Zertifikaten mittels privatem Schüsseln Ein Zertifikat ist öffentlicher Schlüssel Metadaten Gütigket Namen Auseller Er',weiterungen Signatur ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image47.png)



![Transport Layer Security TLS Beispiel eines RSA-Schlüsselpaars -BEGm RSA PRIVATE Ml IJKQ X i/ 09 P+ 8L JUGe i Gv7vd2zSH7pOJQQus e 2 „f6hoKrBLe/ d0kn_R RSA PRIVATE -BEGm PUBLIC Ml IC MB gkqhk 7hni 24 4QT um: i/ 09 P+ PUBLIC Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image48.png)



![Transport Layer Security TLS Aus performancegründen wird der Traffic danach symmetrisch verschlüsselt Mittels asymmetrischer Crypto wird dazu ein gemeinsames Passwort ausgetauscht Schlüsselaustausch -Pro tokoll Beispiel: RSA Es ',verden nur öffentliche Schlüssel ausgetauscht Dies kann auch Über einen unsicheren Kanal passieren ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image49.png)



![Transport Layer Security TLS Wie kann der Client die Identität des Servers überprüfen? Public-Kev-Infrastru c ture tee Certificae Authortr•/ (CA) Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image50.png)



![Transport Layer Security TLS Chain of Trust Ena Leaf-Zarfifika Zettifikzt im 8 rmvser Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image51.png)



![Transport Layer Security TLS Cipher-Suite bestimmt die Parameter der Sitzung Asvmmetrische Crvp to für die Au thentisierung Symmetrische Crvp to für die Verschlüsselung m ent TLS ECDHE RSA WITH SHA sym Cip with Size hash rithm me " age authentication Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image52.png)



![Transport Layer Security TLS • High-Level: TLS-Verbindung Handshake Client und Server einigen Sich auf die verwendete Verschlüsselung-Verfah ren Client verifiziert die Identität des Servers verifiziert die Identitst des client Esv,'ird ein Schlüssel für die Versch lüsselung ausgetau scht (Asvmmetri sche Kryptograp hie) Client und Server nutzen diesen Schlüssel für die i Symmetrische Krvptographie) Fun Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image53.png)



![Transport Layer Security TLS Probleme bei TLS Ungültige Zertifikate Ablaufdatum überschritten Nicht von einer vertrauenswürdigen Wiederrufen Veraltete Signatur-Algorithmen Unsichere Konfiguration (Cipher-Suite) Unsichere Verschlüsselungsal gorithm en Es gibt jedoch Werkzeuge um die gängigen Config-Probleme aufzuzeigen ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image54.png)



![Transport Layer Security TLS @Qualys SSL R.p«t: eh Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image55.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image56.png)



![Hacking Lab: TLS mis- configurations Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image57.png)



![Hacking Lab: Decrypting SSL/TLS Traffic Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image58.png)



![](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image59.png)



![Virtuelle Private Netzwerke (VPN) Wenn mehrere Standorte verbinden werden sollen geht Netzwerk-Traffic wird in in einem verschlüsse Iten «Tunnel» im öffentlichen Netzt gese ndet Kann verschiedene Netzte ve rbinden oder ein Endpunkt remote einbinden Intemet VPN Regional Off C e Remote roaming ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image60.png)



![Virtuelle Private Netzwerke (VPN) Windows Server 2016 DirectAccess WIREGUARD Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image61.png)



![Secure Shell Sichert die Kommunikation zwischen zwei Geräten Wird oft zur Steuerung verwendet (Entfernte Kommandozeile) Kan auch zur allgemeinen Datenübertragung Verwendet werden • Secure Copy (SCP) Nutzt asymmetrische Kryptographie zur Authentifizierung Anmeldung am System selber kann alternativ auch mit dem Passwort erfolgen ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image62.png)



![Hacking Lab: TCP-Traffic untersuchen und Reverse Shell bauen (Teil 2) Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image63.png)



![Hacking Lab: DNS-Tunnel detektieren Sian ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image64.png)



![Hacking Lab: PCAP-Datei mit Python bearbeiten ](../media/S2_02_DETE_Sicherheitsvorfaelle-erkennen-DETE--Block-2.5-image65.png)



































































