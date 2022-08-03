<template>
<div>
<header>
        <div class="container">
            <div class="logo">
                <a href=""><img src="/image/logo.png"/></a>
            </div>
            <div class="menu">
                <nav>
                    <div class="menumobile">
                        <div class="mm_line"></div>
                        <div class="mm_line"></div>
                        <div class="mm_line"></div>
                    </div>
                    <ul>
                       <li class="active"><a href="">PÁGINA INICIAL</a></li>
                       <li><a href="">INFORMAÇÕES</a></li> 
                       <li><a href="">TESTES</a></li>
                       <li><a href="">COMUNIDADE</a></li>
                       <li><a href="">SOBRE NÓS</a></li>                       
                       <li v-if="loginEmail != 'empty'" >
                        <a href=""  @click.prevent="$router.push('/')">{{ loginEmail }}</a>
                       </li>
                       <li v-else >
                        <a href=""  @click.prevent="$router.push('/auth/signin')"> Login </a>
                       </li>

                       
                    </ul>
                </nav>  
            </div>
        </div>
    </header>
    <section id="banner">
        <div class="container column">
            <div class="banner_headline">
                <h1>Projeto Salus</h1>
                <h2>Encontre a unidade mais próxima para realizar seu atendimento</h2>
            </div>
            <div class="banner_option">
                <div class="banner1">
                    <div class="baneer_title">Precisa de Ajuda?</div>
                    <div class="banner_desc">Texto texto mais texto</div>
                    <a href="">Clique Aqui</a>  
                </div>
                <div class="banner2">
                    <div class="baneer_title">Faça sua Doaçao</div>
                    <div class="banner_desc">Texto texto mais texto</div>
                    <a href="">Clique Aqui</a> 
                </div>
                <div class="banner3">
                    <div class="banner_title">Unidades gratuitas para teste HIV</div>
                    <div class="dia1">
                        <div>
                            UBS Reunidas
                        </div>
                        <div>
                            8:00 - 17:00
                        </div>
                    </div>
                    <div class="dia2">
                        <div>
                           UBS Jardim das Laranjeiras
                        </div>
                        <div>
                            9:00 - 17:00
                        </div>
                    </div>
                    <div class="dia3">
                        <div>
                            UBS Parque Arthur Alvim
                        </div>
                        <div>
                            8:00 - 15:00
                        </div>
                    </div>
                </div>
            </div>
        </div>   
    </section>
    <section id="geral">
        <div class="container">
            <section>
                <div class="widget">
                    <div class="widget_title">
                        <div class="widget_title_text">Notícias Recentes</div>
                        <div class="widget_title_bar"></div>
                    </div>
                    <div class="widget_body flex">
                        <article>
                        <a href=""> 
                            <div class="news_data">
                                 <div class="news_posted_at">02 junho</div>
                                 <div class="news_comments">22</div> 
                            </div>
                            <div class="news_thumbnail">
                                <img src="/image/dr.jpg"/>
                            </div>
                            <div class="news_title">
                                Lorem imput sit amat velum
                            </div>
                            <div class="news_resume">
                                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore fugiat repellat 
                                voluptatibus iusto. Quia harum soluta ratione. Debitis eum commodi veritatis sit
                                veniam soluta illo quibusdam provident voluptas, enim id! A campanha é organizada
                                por médicos britânicos, que buscam arrecadar dinheiro para importar equipamento 
                                 de proteção que está em falta no país.
                            </div>
                        </a> 
                        </article>
                        <article>
                            <a href="">  
                               <div class="news_data">
                                    <div class="news_posted_at">28 março</div>
                                    <div class="news_comments">22</div> 
                               </div>
                               <div class="news_thumbnail">
                                   <img src="/image/vacine.jpg"/>
                               </div>
                               <div class="news_title">
                                   Lorem imput sit amat velum
                               </div>
                               <div class="news_resume">
                                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore fugiat repellat 
                                    voluptatibus iusto. Quia harum soluta ratione. Debitis eum commodi veritatis sit
                                    veniam soluta illo quibusdam provident voluptas, enim id! A campanha é organizada
                                    por médicos britânicos, que buscam arrecadar dinheiro para importar equipamento 
                                    de proteção que está em falta no país
                               </div>
                            </a>  
                           </article>
                           <article>
                            <a href="">  
                               <div class="news_data">
                                    <div class="news_posted_at">05 Fevereiro</div>
                                    <div class="news_comments">22</div> 
                               </div>
                               <div class="news_thumbnail">
                                   <img src="/image/trasnfusion.jpg"/>
                               </div>
                               <div class="news_title">
                                   Lorem imput sit amat velum
                               </div>
                               <div class="news_resume">
                                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore fugiat repellat 
                                    voluptatibus iusto. Quia harum soluta ratione. Debitis eum commodi veritatis sit
                                    veniam soluta illo quibusdam provident voluptas, enim id! A campanha é organizada
                                    por médicos britânicos, que buscam arrecadar dinheiro para importar equipamento 
                                    de proteção que está em falta no país
                               </div>
                            </a>  
                           </article>
                           <article>
                            <a href="">  
                               <div class="news_data">
                                    <div class="news_posted_at">07 janeiro</div>
                                    <div class="news_comments">22</div> 
                               </div>
                               <div class="news_thumbnail">
                                   <img src="/image/friends.jpg"/>
                               </div>
                               <div class="news_title">
                                   Lorem imput sit amat velum
                               </div>
                               <div class="news_resume">
                                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore fugiat repellat 
                                    voluptatibus iusto. Quia harum soluta ratione. Debitis eum commodi veritatis sit
                                    veniam soluta illo quibusdam provident voluptas, enim id! A campanha é organizada
                                    por médicos britânicos, que buscam arrecadar dinheiro para importar equipamento 
                                    de proteção que está em falta no país
                               </div>
                            </a>  
                           </article>
                    </div>
                </div>
            </section>
            <aside>
                <div class="widget">
                    <div class="widget_title">
                        <div class="widget_title_text">Lorem</div>
                        <div class="widget_title_bar"></div>
                    </div>
                    <div class="widget_body">
                        
                    </div>
                </div>
                <div class="widget">
                    <div class="widget_title">
                        <div class="widget_title_text">Lorem</div>
                        <div class="widget_title_bar"></div>
                    </div>
                    <div class="widget_body">
                        ...
                    </div>
                </div>
            </aside>
        </div>
    </section>
    <footer> 
        <div class="container flexcolumn" >
            <div class="footer_menu">
                <div class="fm_1">
                    ...
                </div>
                <div class="fm_2">
                    ...
                </div>
                <div class="fm_3">
                    ...
                </div>
            </div>
            <div class="footer_area">
                <div class="footer_area_item">
                    <div class="widget">
                        <div class="widget_title">
                            <div class="widget_title_text">texto</div>
                            <div class="widget_title_bar"></div>
                        </div>
                        <div class="widget_body">
                            
                        </div>
                    </div>
                </div>
                <div class="footer_area_item">
                    <div class="widget">
                        <div class="widget_title">
                            <div class="widget_title_text">texto</div>
                            <div class="widget_title_bar"></div>
                        </div>
                        <div class="widget_body">
                            
                        </div>
                    </div>
                </div>
                <div class="footer_area_item">
                    <div class="widget">
                        <div class="widget_title">
                            <div class="widget_title_text">texto</div>
                            <div class="widget_title_bar"></div>
                        </div>
                        <div class="widget_body">
                            
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer_copy">
                Copyright - todosos direitos reservados
            </div>
        </div>
    </footer>
</div>
</template>
fff
<script>

export default {
    name: 'home',
   data() {
    return {
        loginEmail: 'empty'
    } 
},
mounted(){
    if($nuxt.$fire.auth.currentUser != null)
    this.loginEmail = $nuxt.$fire.auth.currentUser.email
}
}
</script>

<style scoped>
* {
    font-family: Arial, Helvetica, sans-serif;
}
body {
    margin: 0;
    padding: 0;
}
header {
    display: flex;
    justify-content: center;
    height: 120px;
}
.container {
    display: flex;
    justify-content: space-between;
    width: 990px; 
 
}
.logo {
 
    display: flex;
    align-items: center;
}

.logo img{
    margin-top: 55px;
    width: 200px;
}
.menu {
    display: flex;
    align-items:center ;
}
nav ul,
nav li {
    list-style: none;
    margin: 0;
    padding: 0;
}
nav ul {
    display: flex;
}
nav a {
    color: #727272;
    text-decoration: none;
    display: block;
    padding: 15px;
    text-transform: uppercase;
    font-family: Arial, Helvetica, sans-serif;
}
nav .active a,
nav a:hover {
    background-color: #E63946;
    color: white;
}
#banner {
    display: flex;
    justify-content: center;
    background-image: url('/image/img1.jpg');
    background-position: center;
    background-size: cover;
    height: 670px;
}
.column {
    flex-direction: column;
}
.banner_headline {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.banner_headline h1 {
    color: #ffffff;
    font-size: 70px;
    text-shadow: 2px 2px 2px#444444;
    font-family: Arial, Helvetica, sans-serif;
    margin: 0px;
    padding: 0px;
    max-width: 350px;
}
.banner_headline h2 {
    color: #ffffff;
    font-size: 25px;
    text-shadow: 2px 2px 2px#444444;
    font-family: Arial, Helvetica, sans-serif;
    margin: 0px;
    margin-top: 30px;
    padding: 0px;
    max-width: 350px;
}
.banner_option {
    height: 210px;
    display: flex;
   
}
.banner1,
.banner2,
.banner3 {
  flex: 1;  
  color: white;
  padding: 20px;
}
.banner1 {
    background-color:#A8DADC;
}
.banner2 {
    background-color:#457B9D;
}
.banner3 {
    background-color:#1D3557;
}
.banner_title {
    font-size: 21;

}
.banner_desc {
    font-size: 12px;
    margin-top: 20px;
    margin-bottom: 20px;
}
.banner_option a {
    display: inline-block;
    border: 1px solid #ffffff;
    padding: 5px;
    color: white;
    font-size: 12px;
    text-decoration: none;
}
.dia1,
.dia2,
.dia3{
    border-bottom: gray solid 1px;
    padding-top: 15px;
    padding-bottom: 15px;
    font-size: 13px;
    display: flex;
    justify-content: space-between;
}

#geral {
    display: flex;
    justify-content: center;
}

#geral section {
    flex: 2;
}

#geral aside {
    flex: 1;

}
.widget_title {
    margin-top: 30px;
    margin-bottom: 20px;
}
.widget_title_text {
    color: #000000;
    font-size: 21px; 
    font-weight: bold;
}
.widget_title_bar {
    width: 50px;
    height: 2px;
    background-color: #A8DADC;
    margin-top:10px ;
}

article a {
    text-decoration: none;
}
.flex {
    display: flex;
    flex-wrap: wrap;
}

article {
    flex: 1;
    min-width: 300px;
    margin-right: 20px;
}

article .news_data {
    display: flex;
}

article .news_posted_at {
    background-color: #457B9D;
    color: #ffffff;
    font-size: 12px;
    padding: 10px;
    margin-right:2px;
}

article .news_comments {
    background-color: #1D3557;
    color: #ffffff;
    font-size: 12px;
    padding: 10px;
}
article .news_thumbnail {
    margin-top: 30px;
}

article .news_thumbnail img{
    width: 100%;
    height: auto;
}

article .news_title {
    margin-top: 25px;
    margin-bottom: 25px;
    color: black;
    font-size: 28px;
}
 article .news_resume {
     color: #5c5c5c;
     font-size: 14px;
     line-height: 22px;
     margin-bottom: 30px;
 }
 footer {
     background-color: #403d39;
     display: flex;
     justify-content: center;

 }

 .footer_menu {
     display: flex;

 } 
 .fm_1 ,.fm_2 ,.fm_3 {
     flex: 1;
     color: #ffffff;
     padding: 20px;
 }

 .fm_1 {
    background-color:#A8DADC;
}
.fm_2 {
    background-color:#457B9D;
}
.fm_3 {
    background-color:#1D3557;
}
.footer_area {
    display: flex;
    color: #ffffff;
}
.footer_area_item {
    color: #ffffff;
    display: flex;
}
.flexcolumn {
    flex-direction: column;
}
footer .widget_title_text {
    color: #ffffff;
    flex: 1;
    padding: 20px;
}

.footer_copy {
    border-top: 1px solid #ffffff;
    height: 40px;
    line-height: 40px;
    color: #ffffff;
    margin-top: 30px;
}

.menumobile {
    display: none;
    width:40px;
    height: 40px;
    margin-top:40px;
    margin-bottom: 40px;
    margin-right: 20px;
    
}
.mm_line {
    height: 3px;
    background-color:#39aae1;
}

@media (max-width:600px){
    .banner_headline {
        padding: 20px;
    }
    .banner_headline h1 {
        font-size: 55px;
    }
    .banner_headline h2 {
        font-size: 17px;
    }
    .banner_option {
        height: auto;
        flex-direction: column;
    }
    .container {
        flex-direction: column;
    }
    #geral section,
    #geral aside {
        padding: 20px;
        
    }
    .footer_menu {
        flex-direction: column;
    }

    .footer_area {
        flex-direction: column;
        padding: 20px;
    }

    .footer_copy {
        padding: 20px;
    }
    header .container {
        flex-direction: row;
    }
    nav ul{
        flex-direction: column;
        display: none;
        position: absolute;
        left: 0;
        width: 100%;
        background-color: #ffffff;
    }
    header {
        height: auto;
    }
    .logo {
        padding-left: 20px;
    }
    .menumobile {
        display:flex;
        flex-direction: column;
        justify-content: space-around;
    }
}
@media (min-width:601px){
    .menu nav ul{
        display: flex;
    }
}
</style>