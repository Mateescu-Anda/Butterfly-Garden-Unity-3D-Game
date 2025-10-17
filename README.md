# Butterfly Garden 

**Butterfly Garden** este un **joc 3D creat în Unity**, care combină explorarea cu un **sistem de inventar interactiv** și **abilități temporare** obținute prin colectarea florilor magice. Jucătorul poate gestiona obiectele printr-o interfață intuitivă cu funcționalitate **drag-and-drop**, își poate salva preferințele în **hotbar-ul persistent** și poate activa diverse abilități speciale.

---

##  Caracteristici

- **Sistem complet de inventar:** colectează, stochează și gestionează florile printr-o interfață intuitivă.  
- **Hotbar persistent:** salvează florile preferate între sesiuni folosind `PlayerPrefs`.  
- **Drag-and-drop:** mută obiectele între sloturi cu interacțiune vizuală (Unity events: `IBeginDragHandler`, `IDropHandler`).  
- **Abilități speciale:** fiecare floare oferă o abilitate unică (viteză sporită, dublu salt, scut, oprirea timpului, eliminarea inamicilor).  
- **UI adaptiv:** afișează descrieri și feedback vizual în timp real.  
- **Management global:** `GameManager` coordonează activarea abilităților și interacțiunea cu componentele gameplay (`PlayerAbilities`, `LevelTimer`, `Wasp`).  
- **Persistență și salvare:** hotbar-ul este restaurat automat la fiecare pornire a jocului.

---

##  Tehnologii folosite

- **Unity Engine (C#)**  
- **ScriptableObjects** pentru definirea datelor florilor  
- **PlayerPrefs** pentru salvare locală  
- **UI Toolkit / Canvas System** pentru interfața grafică

---

##  Cum se joacă

1. Explorează nivelul pentru a colecta flori magice.  
2. Gestionează florile în inventar și hotbar.  
3. Activează abilitățile speciale pentru a depăși obstacole și inamici.  





