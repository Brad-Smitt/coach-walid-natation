# 📧 Guide d'Installation - Template Email Formspree

## 🎯 **Objectif**
Configurer un email automatique professionnel qui sera envoyé à chaque visiteur qui soumet un formulaire sur votre site.

## 🔧 **Étape 1 : Accéder à Formspree**

1. **Allez sur [formspree.io](https://formspree.io)**
2. **Connectez-vous** à votre compte
3. **Cliquez sur votre formulaire** "Coach Walid - Lead Magnet"

## 📝 **Étape 2 : Configurer l'Email Automatique**

### **Dans votre dashboard Formspree :**

1. **Cliquez sur "Settings"** (en haut à droite)
2. **Allez dans l'onglet "Notifications"**
3. **Trouvez "Auto-responder"** et cliquez sur "Configure"

## 🎨 **Étape 3 : Utiliser le Template**

### **Option A : Copier-Coller le HTML**
1. **Ouvrez le fichier** `template-email-lead-magnet.html`
2. **Copiez tout le contenu** (Ctrl+A, Ctrl+C)
3. **Collez dans Formspree** (dans le champ "Message")
4. **Cliquez sur "Save"**

### **Option B : Personnaliser le Template**
1. **Modifiez le fichier** selon vos besoins
2. **Changez les couleurs** si nécessaire
3. **Ajustez le message** selon votre ton
4. **Mettez à jour les liens** si besoin

## ⚙️ **Étape 4 : Configuration Avancée**

### **Variables Personnalisées :**
Le template utilise ces variables qui seront automatiquement remplacées :
- `{{prenom}}` → Prénom du visiteur
- `{{email}}` → Email du visiteur
- `{{nom}}` → Nom du visiteur

### **Personnalisation des Couleurs :**
Dans le CSS, vous pouvez changer :
```css
--primary-color: #005f99;      /* Bleu principal */
--accent-color: #00b4d8;      /* Bleu accent */
--secondary-color: #0077cc;    /* Bleu secondaire */
```

## 🧪 **Étape 5 : Tester**

1. **Sauvegardez** votre configuration
2. **Allez sur votre site** et soumettez un formulaire
3. **Vérifiez votre email** pour recevoir l'auto-réponse
4. **Vérifiez le dashboard** Formspree pour voir les soumissions

## 📱 **Étape 6 : Optimisation Mobile**

Le template est déjà **100% responsive** et s'adapte à tous les appareils.

## 🎨 **Personnalisations Recommandées**

### **1. Logo Personnalisé**
Remplacez l'emoji 🏊‍♂️ par votre vrai logo :
```html
<div class="logo">
    <img src="URL_DE_VOTRE_LOGO" alt="Coach Walid" style="width: 100%; height: 100%; object-fit: contain;">
</div>
```

### **2. Couleurs de Marque**
Ajustez les couleurs selon votre charte graphique dans le CSS.

### **3. Message Personnalisé**
Modifiez le texte selon votre ton et votre style.

### **4. Liens de Contact**
Mettez à jour les liens vers vos vrais réseaux sociaux.

## 🚨 **Résolution des Problèmes**

### **Problème : Email ne s'envoie pas**
- Vérifiez que l'auto-répondeur est activé
- Testez avec un email valide
- Vérifiez les logs Formspree

### **Problème : Template ne s'affiche pas**
- Vérifiez que le HTML est bien copié
- Testez avec un template simple d'abord
- Vérifiez la compatibilité email

### **Problème : Variables non remplacées**
- Vérifiez que les noms des champs correspondent
- Testez avec différents formulaires
- Vérifiez la syntaxe des variables

## 📊 **Suivi et Analytics**

### **Dans Formspree Dashboard :**
- **Voir toutes les soumissions**
- **Analyser les taux de conversion**
- **Exporter les données**
- **Suivre les performances**

## 🎯 **Prochaines Étapes**

Une fois ce template configuré, vous pourrez :
1. **Créer d'autres templates** pour différents types de formulaires
2. **A/B Tester** différents messages
3. **Optimiser** selon les retours des visiteurs
4. **Automatiser** d'autres processus

---

## 🎉 **Félicitations !**

Votre système d'email automatique est maintenant **professionnel et efficace** !

**Vos visiteurs recevront un email magnifique** avec :
- ✅ Remerciement personnalisé
- ✅ Lien direct vers la fiche technique
- ✅ Votre signature professionnelle
- ✅ Call-to-action pour réserver un cours

**C'est un énorme plus pour votre business !** 🏊‍♂️✨
