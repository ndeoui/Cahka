# INSTALLATION

Vous pouvez installer **NomDuProjet** en utilisant les exécutables (binaires), `pip` ou via un gestionnaire de paquets tiers. Consultez le [wiki](lien-vers-votre-wiki) pour des instructions détaillées.

## RELEASE FILES (Fichiers de publication)

### Recommandés

| Fichier | Description |
|---------|-------------|
| `projet` | Binaire indépendant de la plateforme. Nécessite Python (recommandé pour Linux/BSD). |
| `projet.exe` | Binaire Windows x64 autonome (recommandé pour Windows). |
| `projet_macos` | Exécutable universel MacOS autonome (recommandé pour MacOS). |

### Alternatives

| Fichier | Description |
|---------|-------------|
| `projet_linux` | Binaire Linux (glibc 2.17+) x86_64 autonome. |
| `projet_linux.zip` | Exécutable Linux x86_64 non empaqueté (sans mise à jour auto). |
| `projet_win.zip` | Exécutable Windows x64 non empaqueté (sans mise à jour auto). |

### Divers (Misc)

| Fichier | Description |
|---------|-------------|
| `projet.tar.gz` | Archive source (Source tarball). |
| `SHA2-256SUMS` | Sommes SHA256 (pour vérifier l'intégrité des fichiers). |
| `SHA2-256SUMS.sig` | Fichier de signature GPG pour les sommes SHA256. |

La clé publique permettant de vérifier les signatures GPG est disponible [ici](lien-vers-cle). Exemple d'utilisation :

```bash
curl -L [https://github.com/votre-nom/votre-projet/raw/master/public.key](https://github.com/votre-nom/votre-projet/raw/master/public.key) | gpg --import
gpg --verify SHA2-256SUMS.sig SHA2-256SUMS
