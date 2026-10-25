openemv_v4 - applet EMV Java Card
AID applet  : 54 48 4F 4D 41 53                         (THOMAS)
AID package : 54 48 4F 4D 41 53 20 53 41 4E 43 48 45 5A (THOMAS SANCHEZ)

1. Installer JDK 8, Java Card SDK 2.2.2, ant, ant-javacard.jar (a mettre dans ce dossier).
2. Dans build.xml, regler jckit="..." sur le dossier du SDK.
3. Lancer build.bat (Windows) ou build.sh (Linux/Mac) -> thomas_v4.cap
4. Installer : gp --install thomas_v4.cap
5. SELECT : 00 A4 04 00 06 54484F4D4153

Donnees en dur : PIN 4439 (SimpleEMVApplet.java), PAN 5502094680960488, expiration 270831 (EMVStaticData.java).

Sans rien installer : mettre ce dossier dans un depot GitHub (le dossier .github inclus),
onglet Actions -> "Build CAP" -> Run workflow, puis telecharger "thomas_v4_cap" (thomas_v4.cap).
