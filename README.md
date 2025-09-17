# GroceryApp sprint2 

## Branching strategie (Gitflow)

Ik gebruik **Gitflow** als branching strategie:

- **`main`**  
  Bevat de meest stabiele productiecode, met alleen getest en goedgekeurde code.  

- **`develop`**  
  Hier worden alle nieuwe features samengebracht na het mergen van de Use Case feature branches. 

- **`feature/*`**  
  Voor iedere Use Case wordt een aparte feature branch aangemaakt vanaf `develop`.  
  Na afronding wordt deze terug gemerged in `develop`.  

- **`release`**  
  Wordt gemaakt vanuit `develop` en wordt gebruikt voor een laatste check voor de release naar main gepusht kan worden.  

- **`hotfix`**  
  Wordt gemaakt vanuit `main` om urgente bugs direct te kunnen oplossen.  
  Na fixen wordt de branch terug gemerged naar `main` of eventueel `develop`.  

---
### UC04 Kiezen kleur boodschappenlijst  
Is compleet. Bugfix uitgevoerd.

### UC05 Product op boodschappenlijst plaatsen   
Is compleet. Bevinding gedocumenteerd. 

### UC06 Inloggen  
Is compleet.


 
