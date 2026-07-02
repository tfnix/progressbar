# progressbar
*Barra de progresso básica e de fácil integração c/ React 19* 
<br>

<br>  

[Demo](https://tfnix.github.io/progressbar/)



Estilos (CSS) feitos com AI assistence!! 
  
*easy peasy lemon squeeze!*


```css
/* Animations */
@keyframes color-pulse-animation {
  0%   { background-color: #E40303; }
  20%  { background-color: #FF8C00; }
  40%  { background-color: #FFED00; }
  60%  { background-color: #008026; }
  80%  { background-color: #004DFF; }
  100% { background-color: #750787; }
}

@keyframes fade-in {
  from { opacity: 0; transform: translate(-50%, -40%); }
  to { opacity: 1; transform: translate(-50%, -50%); }
}

/* Updated class naming */
.color-pulse.fade-out {
  animation: fade-out 0.5s ease-out forwards;
}

@keyframes fade-out {
  from { 
    opacity: 1; 
    transform: translate(-50%, -50%) scale(1); 
  }
  to { 
    opacity: 0; 
    transform: translate(-50%, -40%) scale(1.2); 
  }
}
```
