# verziókezelés alapjai
## 1. git letöltése
- [git for windows](https://gitforwindows.org/)
- [git scm](https://git-scm.com/)
## 2. konfigurációs parancsok
- git config --global user.name banhidaimatyas
- git config --global user.eamil banhidai.matyas@students.jedlik.eu
- git config --global credential.helper wincred
## 3. Repository létrehozása
- git init
## 4. Állomány hozzáadása a stage-hez (staging area)
> A stagen kévő állományokról tudunk állapotfelvételt (commit-ot) készíteni
> Üres mappa nem lerül a stage-re
- git add állomány_neve
- git add . (összes állomány és mappa hozzáadása)
## 5. állapotfelvétel (commit klszítése)
-git commit -m "commit message"

