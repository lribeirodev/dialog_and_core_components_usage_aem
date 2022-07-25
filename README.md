# Projeto Simples Utilizando Core Components e Dialogs

## Criamos neste projeto 3 grupo de componentes
ui.apps\src\main\content\jcr_root\apps\treinamento-fiec\components\componentes-treinamento\base

ui.apps\src\main\content\jcr_root\apps\treinamento-fiec\components\componentes-treinamento\produto-1

ui.apps\src\main\content\jcr_root\apps\treinamento-fiec\components\componentes-treinamento\produto-2

ui.apps\src\main\content\jcr_root\apps\treinamento-fiec\components\componentes-treinamento\produto-3

## Neste projeto também criamos templates personalizados
ui.content\src\main\content\jcr_root\conf\treinamento-fiec\settings\wcm\templates\page-content

ui.content\src\main\content\jcr_root\conf\treinamento-fiec\settings\wcm\templates\template-produto-2

ui.content\src\main\content\jcr_root\conf\treinamento-fiec\settings\wcm\templates\template-produto-3

## Neste projeto também criamos policies personalizadas
ui.content\src\main\content\jcr_root\conf\treinamento-fiec\settings\wcm\policies\.content.xml

Policy do Template Page Content<br/>
policy_1658727323728

Policy do Template 2<br/>
policy_1658727391527

Policy do Template 3<br/>
policy_1658727470856

## Neste projeto também criamos páginas para testar os componentes
ui.content\src\main\content\jcr_root\content\treinamento-fiec\home\exemplo-1

ui.content\src\main\content\jcr_root\content\treinamento-fiec\home\exemplo-2

ui.content\src\main\content\jcr_root\content\treinamento-fiec\home\exemplo-3


## Para buildar o projeto e subir o projeto para a instância

mvn clean install -Padobe-public -PautoInstallPackage -PautoInstallBundle

### Dica Atalho do VsCode para abrir os Paths acima

Copie o path e no teclado aperte CTRL + P e cole o path e de enter