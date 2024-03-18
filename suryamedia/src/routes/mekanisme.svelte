<div class="wrapper">
    <header class="header"> 
        <b class="text-3xl">Mekanisme Pemesanan</b>
    </header>
<article class="main">
    <b class="text-3xl">Samperin Langsung</b>
    <p>Apabila mau beli, bisa contact orang untuk make sure stok ready atau ngga, terus datang kesini</p>
</article>
<aside class="aside aside1">
    <b class="text-3xl">Jelajahi Produk</b>
    <p>Kalo lagi ga deket toko atau ga ada waktu, bisa search online melalui website ini</p>
</aside>
<aside class="aside aside2">
    <b class="text-3xl">Beli!</b>
    <p>Hore</p>
</aside>
  
</div>

<style>
    .wrapper {
        display: flex;
        flex-flow: row wrap;
        text-align: center;
        background-color: #FBA000;
        border-radius: 15px;
        margin: 40px;
        -webkit-text-fill-color: white;
    }

    .wrapper>* {
        padding: 10px;
        margin: 10px;
        flex: 1 100%;
        border-radius: 10px;
    }

    .header {
        height: 120px;
        padding: 30px;
    }

    .main {
        text-align: left;
        height: 300px;
        font-size: 24px;
    }

    .aside1 {
        order: 1;
    }

    .aside2 {
        order:2;
    }
    @media all and (min-width: 800px){
        .main {
            flex: 3;
            text-align: center;
        }

    .main {
        order: 2;
    }
    @media all and (min-width: 600px){
        .aside {
            flex: 1;
            text-align:center;
        }
    }
    }

</style>