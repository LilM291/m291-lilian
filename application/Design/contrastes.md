# Contraste et accessibilité

Selon les seuils WCAG AA présentés par WebAIM, le texte courant doit avoir un contraste d’au moins **4,5:1**; le grand texte, **3:1**.

Dans la maquette retenue, **chaleureux.css**, les combinaisons principales sont bien contrastées : le texte foncé sur le fond clair atteint **10,51:1**, le vert sur le fond clair **5,60:1**, et le texte clair du bouton vert **6,04:1**. Ces éléments dépassent le seuil AA et restent faciles à distinguer.

Quelques accents n’atteignent toutefois pas **4,5:1** pour du petit texte : le texte secondaire gris atteint **4,01:1**, le rouge sur fond clair **3,88:1**, et le texte blanc du bouton rouge **4,45:1**. Pour viser une conformité AA sur tout le site, il faudrait assombrir ces couleurs ou réserver le rouge au grand texte et aux éléments décoratifs.

**Conclusion :** le texte principal et les actions vertes respectent les seuils AA, mais certains textes secondaires et rouges restent à ajuster avant de conclure à une conformité complète. À noter : `accueil.html` charge actuellement `audacieux.css`; les ratios ci-dessus concernent `chaleureux.css`, le choix final indiqué dans `choix.md`.
