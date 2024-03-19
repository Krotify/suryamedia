<div class="wrapper">
    <header class="header"> 
        <b class="text-3xl">suryamedia</b>
    </header>
<div class="div div-mid">
    <b class="text-1xl">keep in Touch</b>
    ​<form action="/action_page.php">
        <input type="text" id="fname" name="fname"><br><br>
      </form>
    <button>Touch</button>
</div>

<div class="div div2">
    <b class="text-1xl">Social Media</b>
    <p>social media</p>
    <p>social media</p>
    <p>social media</p>
</div>

</div>

    <b class="text-1xl">COPY RIGHT</b>

<style>
    .wrapper {
        display: flex;
        flex-flow: row wrap;
        text-align: left;
        background-color: #white;
        border-radius: 15px;
        margin: 40px;
        height: 600px;
        padding: 80px;
        -webkit-text-fill-color: black;
        
        
        
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