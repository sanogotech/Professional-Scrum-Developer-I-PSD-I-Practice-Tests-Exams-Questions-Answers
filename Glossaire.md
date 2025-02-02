
---

# **📖 Glossaire – Certification PSD 1**  

### **Architecture & Design**  
💡 **Définition** : L'architecture et le design logiciel définissent la structure d’un système logiciel, incluant ses composants, leurs interactions et les principes de conception utilisés pour garantir évolutivité, maintenabilité et performance.  

---

### **Class Coupling (Couplage de Classe)**  
💡 **Définition** : Mesure du degré de dépendance entre les classes dans un logiciel. Un couplage élevé peut rendre le code difficile à modifier et à tester.  

📌 **Bonnes pratiques :**  
- Favoriser un faible couplage pour une meilleure modularité.  
- Utiliser l’injection de dépendances et les interfaces pour réduire le couplage.  

---

### **Code Quality (Qualité du Code)**  
💡 **Définition** : Ensemble des bonnes pratiques garantissant un code propre, lisible, maintenable et sans défauts.  

📌 **Indicateurs de qualité :**  
- Respect des normes de codage  
- Faible complexité cyclomatique  
- Bonnes pratiques TDD/BDD  

---

### **Coding Best Practices (Meilleures Pratiques de Codage)**  
💡 **Définition** : Techniques et règles assurant un code efficace et robuste.  

📌 **Exemples :**  
- SOLID, DRY, KISS  
- Documentation claire  
- Tests unitaires et intégration continue  

---

### **Continuous Delivery (CD) – Livraison Continue**  
💡 **Définition** : Pratique permettant de s'assurer que le code est toujours dans un état déployable.  

📌 **Objectifs :**  
- Automatiser le processus de livraison  
- Assurer des mises en production fréquentes et fiables  

---

### **Continuous Deployment (CD) – Déploiement Continu**  
💡 **Définition** : Extension de la livraison continue où chaque modification validée est automatiquement déployée en production.  

📌 **Exigences :**  
- Tests automatisés robustes  
- Monitoring constant  

---

### **Continuous Integration (CI) – Intégration Continue**  
💡 **Définition** : Processus d’intégration fréquente du code dans un dépôt commun avec exécution automatique de tests.  

📌 **Avantages :**  
- Détection rapide des erreurs  
- Réduction des conflits de fusion  

---

### **Cross-Functional Teams (Équipes Multifonctionnelles)**  
💡 **Définition** : Équipe composée de membres aux compétences variées (dev, test, UX, ops) capables de livrer un produit de bout en bout.  

📌 **Bénéfices :**  
- Plus d’autonomie et de réactivité  
- Meilleure collaboration et innovation  

---

### **Cycle Time per Feature (Temps de Cycle par Fonctionnalité)**  
💡 **Définition** : Temps nécessaire pour développer, tester et livrer une nouvelle fonctionnalité en production.  

📌 **Optimisation :**  
- Automatisation des tests et déploiements  
- Limitation du travail en cours (WIP)  

---

### **Cyclomatic Complexity (Complexité Cyclomatique)**  
💡 **Définition** : Mesure de la complexité d’un programme basée sur le nombre de chemins d’exécution indépendants dans le code.  

📌 **Meilleures pratiques :**  
- Viser une complexité faible (<10)  
- Réfactorer le code en utilisant des méthodes plus petites  

---

### **Definition of Done (DoD) – Définition de Terminé**  
💡 **Définition** : Ensemble de critères permettant de s’assurer qu’un incrément est complètement fini (codé, testé, documenté, déployable).  

📌 **Exemple de DoD :**  
✅ Code revu et approuvé  
✅ Tests unitaires et intégration réussis  
✅ Documentation mise à jour  

---

### **Documentation**  
💡 **Définition** : Ensemble des informations écrites aidant à comprendre, utiliser et maintenir un logiciel.  

📌 **Types :**  
- Documentation utilisateur  
- Documentation technique  
- Documentation API  

---

### **Don't Repeat Yourself (DRY) – Ne vous répétez pas**  
💡 **Définition** : Principe de développement visant à éviter la duplication de code en favorisant la réutilisation et l’abstraction.  

📌 **Exemples :**  
- Utilisation de fonctions et de classes réutilisables  
- Centralisation des constantes et des configurations  

---

### **Efferent Couplings (Couplage Efférent)**  
💡 **Définition** : Nombre de dépendances d’un module vers d’autres modules. Un couplage efférent élevé peut indiquer un fort degré de dépendance externe.  

📌 **Réduction :**  
- Encapsulation des dépendances  
- Application du principe d’inversion des dépendances  

---

### **Keep It Simple, Stupid (KISS) – Restez simple**  
💡 **Définition** : Principe recommandant de garder le code aussi simple que possible pour en faciliter la compréhension et la maintenance.  

📌 **Exemple :**  
🔴 Mauvais : Une classe avec 500 lignes de code et 10 responsabilités  
✅ Bon : Plusieurs classes plus petites, chacune avec une seule responsabilité  

---

### **Mocking**  
💡 **Définition** : Technique utilisée en tests unitaires pour simuler le comportement d’un composant sans exécuter sa logique réelle.  

📌 **Outils :** Mockito, Jest, Moq  

---

### **Scrum Framework**  
💡 **Définition** : Cadre Agile permettant d’organiser le développement logiciel autour d’itérations (sprints) avec des rôles définis et des événements récurrents.  

---

### **Software Architecture (Architecture Logicielle)**  
💡 **Définition** : Organisation structurelle d’un système logiciel, définissant ses composants, interactions et principes directeurs.  

---

### **Software Design (Conception Logicielle)**  
💡 **Définition** : Processus de définition de la structure interne d’une application en respectant les principes de conception et de modularité.  

---

### **SOLID Principles (Principes SOLID)**  
💡 **Définition** : Ensemble de cinq principes favorisant un code maintenable et évolutif.  
📌 **SOLID :**  
- **S**ingle Responsibility Principle (SRP)  
- **O**pen/Closed Principle (OCP)  
- **L**iskov Substitution Principle (LSP)  
- **I**nterface Segregation Principle (ISP)  
- **D**ependency Inversion Principle (DIP)  

---

### **Spying**  
💡 **Définition** : Technique similaire au Mocking, permettant de capturer les appels faits à un objet réel pour vérifier son comportement en test.  

📌 **Outils :** Mockito, Sinon.js  

---

### **Stubbing**  
💡 **Définition** : Technique utilisée pour remplacer une méthode par une version simplifiée retournant des résultats préprogrammés.  

📌 **Utilisation :**  
- Simuler des réponses API en tests  
- Éviter les dépendances lourdes  

---

### **Technical Debt (Dette Technique)**  
💡 **Définition** : Accumulation de choix techniques sous-optimaux entraînant des coûts futurs en maintenance et refactoring.  

📌 **Prévention :**  
- Refactoring continu  
- Respect des bonnes pratiques  

---

### **Test Driven Development (TDD) – Développement Piloté par les Tests**  
💡 **Définition** : Approche de développement où les tests sont écrits avant le code, forçant une conception centrée sur les exigences.  

📌 **Cycle TDD :**  
1️⃣ Écrire un test  
2️⃣ Écrire juste assez de code pour le passer  
3️⃣ Refactoriser  

---

### **Test First Development (TFD) – Développement Orienté Test**  
💡 **Définition** : Approche où les tests sont définis avant le développement, mais avec moins de rigueur que TDD.  

---

📌 **Ce glossaire couvre les concepts essentiels pour la certification PSD 1. Besoin de précisions sur un point ? 🚀**
