# 🛠️ DAP Innioasis G1 – Tools & Hacks / Outils & Hacks 🔓

---

## 1. 📲 App installation hack / Hack d'installation d'applications

### 🇬🇧 English

#### Solution 1: Fake app  
- **Concept:** 🎭 Create a fake application using an existing package name  
- **Tool:** [APK Builder](https://github.com/Thydekar/innioasis-g1-apk-builder) 🔨  
- **Steps:**  
  1. 🔍 Identify an existing app on the G1  
  2. ✏️ Modify target app's package name  
  3. ⬇️ Install disguised app  

#### Solution 2: System image integration  
- **Concept:** 💾 Embed app into `system.img` or `vendor.img`
- **Note:** ⚠️ **Can be combined with Solution 1 (untested)**  
- **Steps:**  
  1. 📂 Extract image  
  2. 🧩 Integrate via Android Kitchen  
  3. 🔄 Repack & flash 

#### Solution 3: Patching system.img  
- **Tool:** WIP 🔨 
- **Steps:**  
  1. 💽 Mount system image  
  2. 🔓 Apply installation patch  
  3. 🔄 Repack & flash  

---

### 🇫🇷 Français

#### Solution 1 : Fake app  
- **Principe :** 🎭 Créer une fausse application avec un package name existant  
- **Outil :** [APK Builder](https://github.com/Thydekar/innioasis-g1-apk-builder) 🔨  
- **Étapes :**  
  1. 🔍 Identifier une application existante  
  2. ✏️ Modifier le package name  
  3. ⬇️ Installer l'app déguisée  

#### Solution 2 : Intégration système  
- **Principe :** 💾 Injecter dans `system.img` ou `vendor.img`
- **Remarque :** ⚠️ **Combinaison avec Solution 1 possible (non testé)**  
- **Étapes :**  
  1. 📂 Extraire l'image  
  2. 🧩 Intégrer via Android Kitchen  
  3. 🔄 Reconstruire & flasher  

#### Solution 3 : Patch du system.img  
- **Outil :** WIP 🔨 
- **Étapes :**  
  1. 💽 Monter l'image système  
  2. 🔓 Appliquer le patch  
  3. 🔄 Reconstruire & flasher  

---

## 2. 🔓 Device unlock / Déverrouillage d'appareil

### 🇬🇧 English  
- **Purpose:** Reset forgotten lock code
- **Tool:** [Unlock Code Generator](https://seph29.github.io/innioasis-unlock-code-generator/) 🌐  
- **Steps:**
  1. Obtain the code from the G1 
  2. Generate the code
  3. Enter the code on the device  

### 🇫🇷 Français  
- **But :** Réinitialiser un code oublié
- **Outil :** [Générateur de code](https://seph29.github.io/innioasis-unlock-code-generator/) 🌐  
- **Étapes :**  
  1. Récupérer le code sur le G1 
  2. Générer le code
  3. Entrer le code sur l'appareil  

---

### ⚠️ Avertissement/Warning  
❗ **Risque de brick/Brick risk**
