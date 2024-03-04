# Diagramme de classe

![Classes](uml/classes.png)

## Vrai ou faux

Etant donné le diagramme de domaine ci-dessus, les assertions suivantes sont-elles vraies ou fausses ?

- Etudiant est une classe d’association - Faux
- Un étudiant peut participer à autant de cours qu’il veut - Vrai
- Plusieurs professeurs peuvent enseigner la même discipline - Faux
- Un professeur peut enseigner plusieurs disciplines - Vrai
- Un cours peut être enseigner à 2 étudiants - Faux
- Un cours peut être enseigner à 20 étudiants - Vrai

## Question ouverte

Représentez la même association avec la notation UML « petit losange »

- Quelles informations perd-on par rapport au diagramme ci-dessus ?

  -> ici une association ternaire. On perd le fait que cours est une classe d'association et devient une classe à part
  entière. Dû aux cardinalités, on perd le fait qu'il y a automatiquement un cours pour chaque association de Professeur
  à discipline. On pourrait avoir un cours tout seul ou un cours pour 2 associations.