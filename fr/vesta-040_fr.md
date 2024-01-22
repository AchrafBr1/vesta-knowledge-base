# VESTA 040

Capteur de choc, de vibration et de bris de verre SVGS-5

SVGS-5 est un capteur de chocs, de vibrations et de bris de verre. Il est capable d'envoyer des signaux sans fil au panneau de commande lors de la détection d'un bris de vitre ou d'un choc/vibration.

![](<.gitbook/assets/0 (9).jpeg>)Identification des pièces

1.  **Bouton Apprendre/Test**

(Appuyez sur le bouton avec un outil pointu tel qu'un trombone.)

-   Appuyez une fois sur le bouton pour transmettre un code d'apprentissage/test.
-   Appuyez une fois sur le bouton pour passer en mode test pendant 3 minutes.
-   Appuyez sur le bouton pendant 5 secondes pour régler les paramètres de sensibilité à partir du panneau de commande.

1.  **Indicateur LED**

-   **S'allume pendant 1 seconde :**Lorsque le capteur est allumé.
-   **Clignote une fois :**Signal de transmission.
-   **Clignote trois fois lentement :**Batterie faible détectée lors de la mise sous tension.

**Caractéristiques**

-   _Détection de batterie et de batterie faible_
-   Le capteur en utilise un**P2477 ZV**Batterie au lithium comme source d'alimentation.
-   Le capteur peut détecter une faible tension de batterie. Lorsque la batterie est faible, un signal de batterie faible sera envoyé au panneau de commande avec une transmission régulière.
-   Lors du changement de batterie, utilisez un outil pointu pour ouvrir le logement de la batterie afin de retirer et d'insérer la batterie.
-   Lors de l'insertion de la batterie, le**positif(+)**Le côté de la batterie doit être orienté vers le haut.**JAMAIS**insérez la batterie avec le côté négatif (-) vers le haut.

![](<.gitbook/assets/1 (6) (1).jpeg>)

-   _**Surveillance**_

Le capteur transmettra un signal de supervision pour signaler régulièrement son état en fonction du réglage de l’utilisateur. L'intervalle par défaut est de 30 à 50 minutes.

-   _**Ajustement de la sensibilité**_

Le capteur peut envoyer un signal d'alarme au panneau de commande en fonction de différents niveaux de sensibilité définis dans le panneau de commande. Les niveaux de sensibilité incluent élevé, moyen et faible (la valeur par défaut est moyenne si aucun niveau de sensibilité n'est défini dans le panneau de commande). Plus la sensibilité est élevée, plus il est facile de déclencher le capteur lorsqu'un bris de fenêtre/verre ou une vibration de choc est détecté.

Une fois le capteur ajouté au panneau de configuration, vous pouvez définir davantage son niveau de sensibilité à partir du panneau de configuration ou de l'accueil.

Page Web du serveur de portail.

1.  Utilisez un outil pointu tel qu'un trombone pour appuyer sur le bouton de test du capteur pendant 5 secondes. La LED du capteur sera allumée en continu.
2.  Reportez-vous au manuel d'utilisation de votre panneau de commande pour modifier l'appareil. Les utilisateurs pourront ajuster les paramètres de sensibilité dans un délai de 10 secondes.
3.  Aller à**Type et sensibilité**et sélectionnez le paramètre souhaité dans le menu déroulant.
4.  Cliquez sur**D'ACCORD**confirmer. La LED du capteur s’atténuera pour indiquer un fonctionnement réussi.

-   Pour plus de détails sur la plage du mode de détection des chocs/vibrations, voir la section Installation dans la section suivante.
-   _**Mode de détection**_
-   La fonction de détection des chocs/vibrations de l’appareil peut être déclenchée selon différents modes sélectionnés dans le panneau de commande.
-   **Mode de choc à impulsion unique**_**(mode par défaut pour SVGS-5 Si aucun mode de détection n'est défini dans le Panneau de configuration)**_

Le dispositif se déclenche par une seule détection de choc dépassant le seuil de détection.

-   **Mode multi-impulsions/vibrations accumulées**

L'appareil est déclenché par l'une des conditions suivantes :

1.  Quand**3**le nombre d'impulsions est détecté dans**20****secondes**.
2.  Lorsque des vibrations mineures accumulées sont détectées avec**2 minutes**dépasse le seuil de détection.

-   Pour plus de détails sur la plage du mode de détection de chocs/vibrations, voir la section**Installation**dans la section ultérieure.
-   _**Mode d'essai**_

Le capteur peut être mis en mode test de 3 minutes en appuyant sur le bouton de test :

-   Appuyez une fois sur le bouton Apprendre/Test, la LED clignotera pour indiquer que le capteur est mis en mode test.
-   En mode test, chaque fois que le capteur est déclenché, la LED clignote.
-   Le capteur quittera le mode test après 3 minutes.
-   _**Minuterie de mise en veille**_

Le capteur entrera dans un temps de veille de 2 minutes après chaque déclenchement. Le capteur ne retransmettra pas le signal de détection pendant cette période de 2 minutes. Chaque déclenchement de détection de choc pendant cette période ramènera la minuterie de mise en veille à 2 minutes. Le temps de veille n'expirera que si aucun choc n'est détecté pendant 2 minutes, puis le capteur reviendra à un fonctionnement normal et transmettra le prochain signal de détection de choc.

Apprentissage et installation

-   _**Apprentissage**_

1.  Retirez l'alimentation de l'isolant de la batterie sur le capteur.
2.  Reportez-vous au manuel du panneau de commande pour mettre le panneau en mode d'apprentissage.
3.  Appuyez une fois sur le bouton Apprendre/Test pour transmettre un code d'apprentissage.
4.  Reportez-vous au manuel d'utilisation de votre panneau de commande pour terminer le processus d'apprentissage.

-   _**Surface et matériau de montage**_

Le capteur doit être monté directement sur une surface en verre ou en contreplaqué.

-   Épaisseur du verre : Verre plaqué, trempé et feuilleté : Minimum 5 mm.
-   Épaisseur du contreplaqué : 9 mm maximum.
-   Épaisseur du coffre-fort : minimum 3 mm
-   _**Sensibilité et plage de détection**_

La sensibilité du capteur est ajustée via le panneau de configuration. La plage de détection de différentes sensibilités varie en fonction des matériaux de la surface de montage.

|                                       | Verre                               | Contre-plaqué                               | Coffre-fort                 |   |
| ------------------------------------- | ----------------------------------- | ------------------------------------------- | --------------------------- | - |
| Matériel                              | Verre plaqué/trempé/feuilleté/câblé | Contre-plaqué                               | Acier / Dioxyde de Silicium |   |
| Épaisseur                             | Minimum 5 mm                        | Maximum 9mm                                 | Min.                        |   |
| Mode de détection de chocs/vibrations | Mode impulsion unique               | Mode multi-impulsions/vibrations accumulées |                             |   |
| Sensibilité                           | Faible                              | 8000mm                                      | 2000mm                      | - |
| Moyen                                 | 10000mm                             | 2500mm                                      | -                           |   |
| Haut                                  | 12000mm                             | 3000 mm                                     | 1400 mm                     |   |

-   _**Étapes d'installation et lignes directrices**_

1.  Ajustez la sensibilité du capteur comme vous le souhaitez en fonction du matériau de la surface de montage à l'aide du tableau fourni précédemment.

section.

**Installation fenêtre/mur :**

Déterminez l'emplacement de montage sur la fenêtre ou le mur. Le capteur peut être monté au centre ou dans le coin. Si un capteur ne parvient pas à couvrir toute la surface, utilisez plusieurs capteurs.

\\<NOTE>

-   Lors du montage dans un coin, assurez-vous de maintenir une distance d'au moins 10 mm entre le capteur et le bord de la fenêtre ou du mur. Ajustez la direction du logement de la batterie (**Ne faites pas face au coin**) pour éviter des difficultés lors du retrait du logement de la batterie.

**Installation du coffre-fort :**

Lors du montage sur un coffret de sécurité, montez le capteur à pas plus de 2 cm du pivot de la porte.

1.  ![](<.gitbook/assets/5 (12).png>)Nettoyez et séchez l'emplacement de montage. Ne pas installer sur une surface sale ou Web.
2.  Utilisez le ruban adhésif double face fourni (Ø35 mm x 8 mm) pour l'appliquer sur le capot arrière du SVGS et coller le capteur sur l'emplacement de montage.

\\<NOTE>

-   Veuillez ne pas appliquer le ruban adhésif double face sur le capot avant où se trouvent le bouton de test et l'indicateur LED, et n'appliquez pas le ruban deux fois.

![](<.gitbook/assets/6 (7) (1).png>)

-   _**Directive d'installation**_
-   Assurez-vous toujours de tester la plage de détection après l'installation pour confirmer la plage de détection réelle.
-   Le ruban adhésif peut perdre son caractère collant avec le temps. Assurez-vous de vérifier le capteur au moins une fois tous les 6 mois.
-   Évitez de monter dans un endroit exposé à des vents forts qui pourraient disloquer le capteur.
-   Évitez de monter dans un endroit sujet aux secousses ou aux vibrations, ce qui provoquerait une fausse alarme.
-   Réglez le capteur sur une faible sensibilité lors de l'installation sur des fenêtres mobiles pour éviter les fausses alarmes.
-   Évitez de monter à un endroit où le capteur pourrait facilement entrer en collision avec un objet.
-   Lors du montage sur contreplaqué :

1.  Utilisez uniquement un réglage de sensibilité élevée.
2.  Le montage sur un mur à côté de grands meubles peut affecter la plage de détection du capteur et la plage de transmission du signal. Assurez-vous de tester le capteur si vous choisissez de le monter à un tel endroit.

-   La plage de détection du capteur dépend de la taille et du matériau du ruban adhésif. Le tableau des plages de sensibilité fourni dans ce document est testé avec du ruban adhésif fourni par l'usine. Si un ruban adhésif différent est utilisé, assurez-vous de retester la plage de détection.
