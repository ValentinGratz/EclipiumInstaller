# Eclipium Installer

Un installeur réalisé sous WPF en C# moderne épuré et simple d'utilisation.

# Configuration requise pour la compilation
-.Net Framework 4.6 ou supérieur

-Visual studio 2017 ou supérieur

# Configuration requise pour l'utilisateur
-.Net Framework 4.6 ou supérieur

# Génération de l'installeur

Remplacer {AppName} par le nom de l'application, {ImageUrl} par l'url du logo de l'application et {PackageUrl} par l'url du paquet d'installation.

# Paquet d'installation

Doit être un fichier zip contenant: un dossier bin contenant l'application et un fichier package.json sous cette forme:

{

"Name": "{NomDeApplication}",

"MainExe": "{NomDeExecutable(exemple: app.exe)}",

"VersionName": "{NomDeVersion}",

"VersionCode": {NumeroDeVersion},

"Date": "{DateDePublication}"

}
