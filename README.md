**nimbasms-windev**

Pour utiliser le service d'envoi d'SMS

1. Importer la classe dans votre projet Windev
2. Assurez-vous de disposer des informations d'identification requises. Obtenez ces informations d'identification aupres de votre fournisseur de service SMS.
3. Modifier le nom du SenderName  en mettant votre Sender name dans la classe
4. Modifier la valeur du Basic Auth Token

Vous pouvez à present passer à l'envoie d'sms

**Usage**
L'utilisation de ce package est très simple et directe. Il suffit d'une seule étape pour l'utiliser :
Utilisez  la classe NimbaSMS  à l'intérieur de votre procedure et autres pour envoyer un message

> sms est un objet NimbaSMS()
> sms.EnvoyerSMS(622217957,"Bonjour Maitre")
