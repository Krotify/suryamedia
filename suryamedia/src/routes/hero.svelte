<div class="flex-container">
    <div class="column left">
        <b class="text-3xl">Iklankan bisnis anda bersama kami!</b>
        <p>Cetak dan pasang iklan untuk bisnis anda! Kami menyediakan layanan periklanan terbesar di jawa tengah. Mari segera buat iklan dan pilih lokasi untuk bisnis anda bersama kami!</p>
    </div>
    <div class="column right">
        <img src="hero.svg">
    </div>
</div>
<style>
    .flex-container {
        display: flex;
        background-color: #F4D000;
        margin: 40px;
        border-radius: 15px;
        height: 450px;
        padding: 80px;
        align-items: center;
    }
    .column {
        flex: 1;
    }
    .left {
            flex: 2;
            padding: 20px;
            text-align: left;
        }
        .right {
            flex: 1;
            padding: 20px;
            text-align: right;
        }
    @media (max-width: 950px) {
        .flex-container {
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
    
        img {
            max-width: 300px;
            margin-bottom: 20px;
        }
    }


</style>