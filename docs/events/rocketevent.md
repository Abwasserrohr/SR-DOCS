# Ziel des Rocketevents
Ziel ist es, möglichst viele Kills zu bekommen und dabei möglichst selten zu sterben. Der Score ergibt sich dabei nach:
$$score=10\cdot\fraq{kills*kills}{deaths+5}$$

This expression $\sum_{i=1}^n X_i$ is inlined.

Die +5 soll verhindern, das Spieler einen Kill machen und dann verlassen. So wär ihr Score sehr hoch, ohne das sie viel geleistet hätten.


# Das Equipment
=== "Rakete"
    !!! note ""
        Die Rakete wird gerade aus dem Crossbow geschossen und trifft recht genau da, wo man hingezieht hat. Jedoch braucht sie recht lange zum Laden. An der Einschlagstelle folgt eine Explosion
    ![Rakete](/assets/images/rocketevent/rakete.png)
=== "Luftangriff"
    !!! note ""
        Der Luftangriff beschwärt einen Bomber (Ghast) der langsam aus den Block hin fliegt, den man angeschaut hat. Dort angekommen, wirft er ca. 10 sec. TNT ab.
    ![airattack](/assets/images/rocketevent/luftangriff.png)
=== "Granate"
    !!! note ""
        Die Granate fliegt nicht sehr weit und erzeugt eine Explosion bei Einschlag.
    ![grenade](/assets/images/rocketevent/granate.png)
=== "Zeitbombe"
    !!! note ""
        Die Zeitbombe erzeugt eine verfolgende Zeitbombe bei Einschlag, die nach ca. 10 Sec. explodiert.
    ![timebomb](/assets/images/rocketevent/zeitbombe.png)
=== "Darts"
    !!! note ""
        Darts sind Pfeile, die bei Gegner schaden verursachen und ihm 10 Sec. Blindheit geben. Gut geeignet, um einen Gegner kampfunfähig zu machen bevor man ihn angreift. Zudem kann der Crossbow sie deutlich schneller feuern als Raketen.
    ![darts](/assets/images/rocketevent/darts.png)
=== "Blendgranate"
    !!! note ""
        Blendgranaten verursachen Blindheit für 10 Sec. in einem gewissen Radius um den Einschlag. Gut geeignet, um einen Gegner kampfunfähig zu machen bevor man ihn angreift. Trifft auch hinter Wänden.
    ![blindegrenade](/assets/images/rocketevent/blendgranate.png)
=== "Streitaxt"
    !!! note ""
        Die Streitaxt verursacht mit jedem Schlag mehr schaden und man bekommt immer mehr Schnelligkeit. Jedoch bekommt man selbst auch durch sie immer mehr Schaden. Das eigene Leben fällt dadurch jedoch nicht unter 4 (2 Herzen).
    ![streitaxt](/assets/images/rocketevent/streitaxt.png)



# Die Upgrades

Pro Kill bekommt man 1-3 Punkte. Stirbt man, behält man diese Punkte. Sollte man weniger als 2 Punkte haben, werden die Punkte nach dem Tot auf 2 gesetzt. Diese Punkte kann man in die Folgenden Upgrade investieren kann.

| Upgrade              | Effekt                                                                         | Kosten Level   |
|----------------------|--------------------------------------------------------------------------------|----------------|
| Chickenspeed         | Laufgeschwindigkeit der Zeitbombe                                              | 1/4/7/10       |
| Explosion            | Radius der Explosionen von <br/>- Raketen <br/>- Granaten <br/>- Blendgranaten             | 1/4/9/16       |
| ExplosionProtection  | Explosionsschutz für die Rüstung                                               | 1/4/7/10       |
| Multishot            | Multishot für Crossbow. <br/>3 Pfeile/Raketen gleichzeitig                         | 5              |
| ProjectileProtection | Projektilschutz für die Rüstung                                                | 1/4/7/10       |
| Sharpness            | Schärfe (+3 pro Level)<br/> für den Crossbow für den Nahkampf                      | 1/4/9/16       |
| Unbreaking           | Haltbarkeit für Rüstung und Armbrust.<br/>Ohne Rüstung nimmt man sehr viel Schaden | 1/4/7/10       |

Man hat nach dem Spawn bzw. Respawn in der Arena 10 Sekunden Resistenz 5, erhält also keinen Schaden. Diese Zeit sollte man nutzen, um sich zu positionieren um nicht direkt getötet zu werden. Nach dem Einsatz einer Waffe, wird die Spawn Protection jedoch entfernt.
