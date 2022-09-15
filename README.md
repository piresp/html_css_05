# Curso Alura "CSS: dispondo elementos com Flexbox e Grid"  

## 01 - Alinhamento
## 02 - Grid  

----------------------------------------  

## 01 - Alinhamento  
  
**justify-content:**    
flex-start (valor padrão), flex-end, center, space-around, space-evenly e space-between.  

**align-items:**  
stretch (valor padrão), flex-start, flex-end e center  

**Row:** justify-content: "x", align-items: "y"

**Column:** justify-content: "y", align-items: "x"

----------------------------------------  

## 02 - Grid

Usar **fr** unidade de medida 

Criar linhas e colunas:  

.class {  
  **grid-template-rows**: n fr n fr;  
  **grid-template-columns**: n fr n fr;   
  }  
  
----------------------------------------  
  
Mescla de linhas e colunas:

.class {   
  **grid-columns**: span n;  
  **grid-rows**: span n;  
  }  
  
----------------------------------------  
  
Espaçamento entre celulas: 

.class {  
  **gap**: n px;  
  **row-gap**: n px;    
  **column-gap**: n px;  
  }  
  
---------------------------------------- 

