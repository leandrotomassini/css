# Notas Flexbox
```
#menu {
    /*Cuando la pantalla se redusca ocuparan todo el ancho*/
    flex-grow: 1;
    /* Le da un ancho*/
    flex-basis: 40%;
    /*Que se posicione en el 100% de la caja*/
    height: 100%;
    padding-right: 20px;
}

#menu>ul {
    /*Los elementos uno al lado del otro*/
    display: flex;
    /*Los posiciona como fila*/
    flex-direction: row;
    /*Si se sobresale lo ponga abajo*/
    flex: wrap;
    /* Alinearlos al medio en lo alto*/
    align-items: center;
    /* Un espacio entre cada elemento y pegados al start y al end */
    justify-content: space-between;
    /*Ocupar toda la altura*/
    height: 100%;
    list-style: none;
}



```
