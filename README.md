@RequestParam(name="nameGET",required = false,defaultValue = "World")
nous permet de parametrer l'url d'appel.
return "greeting"; permet de retourner le fichier html choisi
model.addAttribute("nameGET", nameGET); : envoie le nom a qui nous disons bonjour 

