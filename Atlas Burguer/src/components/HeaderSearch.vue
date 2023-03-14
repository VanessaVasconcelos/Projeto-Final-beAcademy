<template>
<div>
    <div className="logoHamburguer"> 
        <h2 className="textLogoBurguer"> Atlas </h2>   
        <h3 className="textLogo"> Burguer </h3> 
    </div> 
    <div className="divSearch"> 
        <form> 
            <input className="inputSearch" type="text" placeholder=" Digitar pesquisa" /> 
            <button className= "buttonSearch">Pesquisar</button> 
        </form> 
    </div>
</div>
</template>

<script>
export default {
     name: 'HeaderSearch', 
     props: {
         msg: String }
}
 </script>
