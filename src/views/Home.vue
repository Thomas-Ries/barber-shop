<template>
    <header>
        <a class="navbar-brand" href="index.html" id="topPage">A.D </a>

        <img src="../../public/img/chair.jpeg" alt="Image de chaise de barbier" title="Chaise de barbier">


      <WhiteNavbar />

        <div class="title">
            <h1> ALEX DEFRANCQ</h1>
            <h2> Barbier & Coiffeur </h2>
        </div>
    </header>


    <section class="introduction">

        <h1> À PROPOS </h1>

        <article class="about">
            <p> Barbier & coiffeur en salon depuis maintenant 6 ans je me suis lancé à mon propre compte en fin d'année 2020.</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempore sint tempora numquam reiciendis odio nostrum, itaque voluptate quam fugiat voluptatem commodi rem autem est iure delectus. Voluptates architecto deleniti perspiciatis.</p>
            <p> Je serais ravi de vous accueillir au 3 rue de l'ail - 67100 Strasbourg </p>
            <a href="https://booking.wavy.pro/alexisdefrancq"><button type="button" class="btn btn-outline-dark">Réserver en ligne </button></a>
        </article>

        <img src="../../public/img/about.png" alt="Image personnel à propos" title="A propos">

        <a href="#topPage"> <h4> <i class="fas fa-angle-up"></i> Haut de page </h4></a>

    </section>

    <!-- <section class="products">

        <h1> MES PRODUITS </h1>

        <article class="products-text">
            <p> Très attentif à la qualité des produits avec lesquels je travaille, je vous garantie une qualité irréprochable sur tout mon matériel et produits de soin.</p>
            <p> Dans mon shop vous retrouverez des marques reconnues telles que Captain Fawcette / Wahl / Uppercut / L'Atelier Shelter et bien d'autre.</p>

        </article>


    </section> -->

  <Footer />


</template>

<script>
// @ is an alias to /src
import Footer from '@/components/Footer.vue'
import WhiteNavbar from '@/components/navbar/WhiteNavbar.vue'


export default {
  name: 'Home',

  components: {
    Footer,
    WhiteNavbar,
  }

}
</script>

<style scoped>

html {
    scroll-behavior: smooth;
}

/*  =========================================
/*  =========================================
          - INTRODUCTION -
/*  =========================================
    ========================================= */

.introduction {
    height: 100vh;
    position: absolute;
    top: 101rem;
    left: 0;
    right: 0;
    margin: auto;
    width: 140rem;
}

.introduction h1 {
    font-size: 5rem;
    font-weight: 600;
    font-family: 'Viaoda Libre', sans-serif;
    text-align: center;
    padding-top: 5rem;
    text-decoration: underline;
}

.introduction p {
    text-align: center;
    font-size: 1.8rem;
}

.introduction a {
    font-size: 1.8rem;
    color: #000;
}

.introduction a:hover {
    text-decoration: none;
    color: #000;
}

.introduction h4 {
    margin: 5rem 0 2rem 0;
}

.about {
    margin-top: 5rem !important;
    left: 0;
    right: 0;
    margin: auto;
    width: 90rem;
}

.btn-outline-dark {
    height: 4rem;
    width: auto;
    font-size: 2rem !important;
    margin: 2rem 0 2rem 36rem;
    color: #fff !important;
    background-color: #000 !important;
    font-weight: 600 !important;
}

.btn-outline-dark:hover {
    color: var(--liens) !important;
}

.introduction img {
    height: 60rem;
    margin-left: 35rem;
    margin-top: 3rem;
}

.fa-angle-up {
    font-size: 2rem;
}

/*  =========================================
/*  =========================================
          - PRODUCTS -
/*  =========================================
    ========================================= */

/* .products {
    height: 100vh;
    position: absolute;
    top: 220rem;
    left: 0;
    right: 0;
    margin: auto;
    width: 140rem;
    background-color: CYAN;
}

.products H1 {
    font-size: 5rem;
    font-weight: 600;
    font-family: 'Viaoda Libre', sans-serif;
    text-align: center;
    padding-top: 5rem;
    text-decoration: underline;
    margin-bottom: 5rem;
}

.products-text p {
    text-align: center;
    font-size: 1.8rem;
} */


  
</style>
