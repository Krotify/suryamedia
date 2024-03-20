<div class="flex-container">
    <div class="column left">
        <div class="mb-4">
            <b class="text-2xl mb-1">Surya Media Advertising</b>
        </div>
        <div class="mb-4">
            <b class="text-3xl" style="color: #FBA000;">Keep in touch</b>
        </div>
        <div class="mb-4">
            <input type="text" id="lname" name="lname" class="field">
        </div>
        <a href="" class="btn">Submit</a>
    </div>

    <div class="column right">
        <h2 class="text-xl mb-3">"Slogan"</h2>
        <b class="text-3xl mb-3" style="color: #FBA000;">Sosial Media</b>
        <h3 class="text-xl mb-3">Sosial Media</h3>
        <h3 class="text-xl mb-3">Sosial Media</h3>
        <h3 class="text-xl mb-3">Sosial Media</h3>

    </div>

</div>
<p class="copyright text-2xl">Copyright</p>
<style>
    .btn{
		color: #ffffff;
		background-color: #ff9500;
		font-size: 15px;
		padding: 10px 55px;
		cursor: pointer;
        border-radius: 10px;
    }
    .field{
        height: 35px;
        width: 300px;
        border: solid black 2px;
        border-radius: 5px;
    }
    .copyright{
        text-align: center;
        margin-bottom: 40px;
    }
    .flex-container {
        display: flex;
        border-radius: 15px;
        min-height: 250px;
        align-items: center;
    }
    .column {
        flex: 1;
    }
    .left {
            flex: 1;
            padding: 0 40px;
            text-align: left;
        }
        .right {
            flex: 1;
            padding: 0 40px;
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