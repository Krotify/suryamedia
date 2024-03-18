<div class="wrapper">
    <header class="header"> 
        <b class="text-3xl">Mekanisme Pemesanan</b>
    </header>
<div class="div div-mid">
    <b class="text-1xl">Samperin Langsung</b>
    <p>Apabila mau beli, bisa contact orang untuk make sure stok ready atau ngga, terus datang kesini</p>
</div>
<div class="div div1">
    <b class="text-1xl">Jelajahi Produk</b>
    <p>Kalo lagi ga deket toko atau ga ada waktu, bisa search online melalui website ini</p>
</div>
<div class="div div2">
    <b class="text-1xl">Beli!</b>
    <p>Hore</p>
</div>
  
</div>

<style>
    .wrapper {
        display: flex;
        flex-flow: row wrap;
        text-align: center;
        background-color: #FBA000;
        border-radius: 15px;
        margin: 40px;
        height: 500px;
        padding: 80px;
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


    @media all and (min-width: 800px){
        .main {
            flex: 3;
            text-align: center;
        }

    .main {
        order: 2;
    }
    @media all and (min-width: 600px){
        .div {
            flex: 1;
            text-align:center;
        }
    }
    }

</style>