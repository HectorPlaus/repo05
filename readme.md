La diferencia entre merge FF y no FF solo es visual, ya que no afecta en ningun caso a nuestro codigo.

Con FF : git merge <branch>. Se nos hara una union de ramas directamente sin realizar un commit de confirmación.

Con No FF: git merge --no-ff <branch> -m ''. Se nos crea una nueva confirmación con varios padres. Lo que proporciona un mejor seguimiento del historial.

