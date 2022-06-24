<div class="wrapper wrapper_underline">
    <div class="row">
        <div class="col span12"><br /><br /></div>
    </div>
</div>
<div class="wrapper">
    <div class="raw">
        <div class="col span6 box offset-by-three">
            <h2><a href="AgePrediction.html">Predict your age App</a></h2>
            <p>Application which predicts your age based on your name</p>
        </div>
    </div>
</div>

<style>
    h2 {
        text-align: center;
    }

    .box {
        background-color: #7f55db;
        border-radius: 15px;
        word-break: break-word;
        max-height: 700px;
        padding: 2% 2% 2% 2%;
        overflow: auto;
        text-align: center;
    }

    /* each column is 130px or 6.77% */
    /* each gutter is 30px ot 1.56%  */
    .col {
        float: left;
        margin-left: 1.56%;
        width: 6.77%;
    }
    /* container for row */
    .row {
        clear: both;
    }
    /* most right gutter */
    .wrapper {
        padding-right: 1.56%;
    }
    /* merged columns */

    .col.span6 {
        width: calc((6.77% * 6) + (1.56% * 5));
    }

    .col.span12 {
        width: calc((6.77% * 12) + (1.56% * 11));
    }

    .offset-by-three {
        margin-left: calc(6.77% * 3 + (1.56% * 4));
    }

    a{
		color: white;
	}
</style>
