# FekiAI

FekiAI est une app gratuite pour Mac. Ce dépôt sert seulement à la télécharger : le code de l'app n'y est pas publié.

Pour Mac avec puce Apple (M1 et plus récent), macOS 14 ou plus récent.

**[Télécharger FekiAI.dmg](https://github.com/Fefou24/fekiai/releases/latest/download/FekiAI.dmg)**

English below.

## Installer

FekiAI ne paie pas la vérification des apps par Apple. Au premier lancement, macOS bloque donc l'app et demande votre accord. Vous le donnez une seule fois. Choisissez une des trois façons.

### Façon 1 : par les Réglages

1. Ouvrez le fichier `FekiAI.dmg` téléchargé.
2. Glissez **FekiAI** dans **Applications**.
3. Ouvrez FekiAI. macOS affiche un message de blocage : cliquez sur **Terminé**.
4. Ouvrez **Réglages Système**, puis **Confidentialité et sécurité**.
5. Descendez jusqu'à **Sécurité**. À côté de FekiAI, cliquez sur **Ouvrir quand même**.
6. Confirmez avec votre mot de passe ou Touch ID.

Le `.dmg` contient aussi une page « Help - Aide » qui montre ces étapes.

### Façon 2 : par une commande

1. Ouvrez le fichier `FekiAI.dmg` téléchargé, puis glissez **FekiAI** dans **Applications**.
2. Ouvrez l'app **Terminal** : appuyez sur Commande + Espace, écrivez « Terminal », puis Entrée.
3. Collez cette commande, puis appuyez sur Entrée.

```bash
xattr -dr com.apple.quarantine /Applications/FekiAI.app && open /Applications/FekiAI.app
```

Cette commande retire de FekiAI la marque « téléchargé depuis Internet », puis ouvre l'app. Elle ne change rien d'autre sur votre Mac.

### Façon 3 : tout installer par une ligne

1. Ouvrez l'app **Terminal**.
2. Collez cette ligne, puis appuyez sur Entrée.

```bash
curl -fsSL https://github.com/Fefou24/fekiai/releases/latest/download/install.sh | bash
```

La ligne télécharge FekiAI, contrôle que le fichier est le bon, le place dans Applications et l'ouvre. macOS n'affiche aucun blocage. Si une ancienne copie de FekiAI est dans Applications, elle va dans la Corbeille.

## Vos données restent sur votre Mac

FekiAI n'a pas de compte et pas de serveur. Vos discussions, vos fichiers et vos clés restent sur votre Mac. L'app parle seulement aux services d'IA que vous branchez vous-même.

---

# FekiAI (English)

FekiAI is a free Mac app. This repository only hosts the download: the app's code is not published here.

For Macs with Apple silicon (M1 and later), macOS 14 or later.

**[Download FekiAI.dmg](https://github.com/Fefou24/fekiai/releases/latest/download/FekiAI.dmg)**

## Install

FekiAI does not pay for Apple's app verification. On the first launch, macOS blocks the app and asks for your approval. You give it once. Use one of the three ways.

### Way 1: with Settings

1. Open the downloaded `FekiAI.dmg` file.
2. Drag **FekiAI** to **Applications**.
3. Open FekiAI. macOS shows a blocking message: click **Done**.
4. Open **System Settings**, then **Privacy & Security**.
5. Scroll down to **Security**. Next to FekiAI, click **Open Anyway**.
6. Confirm with your password or Touch ID.

The `.dmg` also holds a "Help - Aide" page that shows these steps.

### Way 2: with a command

1. Open the downloaded `FekiAI.dmg` file, then drag **FekiAI** to **Applications**.
2. Open the **Terminal** app: press Command + Space, type "Terminal", then Return.
3. Paste this command, then press Return.

```bash
xattr -dr com.apple.quarantine /Applications/FekiAI.app && open /Applications/FekiAI.app
```

This command removes the "downloaded from the Internet" mark from FekiAI, then opens the app. It changes nothing else on your Mac.

### Way 3: install everything with one line

1. Open the **Terminal** app.
2. Paste this line, then press Return.

```bash
curl -fsSL https://github.com/Fefou24/fekiai/releases/latest/download/install.sh | bash
```

The line downloads FekiAI, checks that the file is the right one, puts it in Applications and opens it. macOS shows no blocking message. If an earlier copy of FekiAI is in Applications, it goes to the Trash.

## Your data stays on your Mac

FekiAI has no account and no server. Your chats, your files and your keys stay on your Mac. The app talks only to the AI services you connect yourself.
