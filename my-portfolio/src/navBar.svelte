<header>
    <div class="wrapper">
        <div class="row">
            <div class="col span2 logo">
                <h3>Arseni Rusin's<br />portfolio</h3>
            </div>
            <div class="col navigation offset-by-seven">
                <h4><a href="../my-portfolio-Projects/public/index.html">Projects</a></h4>
            </div>
            <div class="col navigation">
                <h4><a href="../my-portfolio-CV/public/index.html">CV</a></h4>
            </div>
            <div class="col navigation">
                <h4><a href="../my-portfolio-aboutMe/public/index.html">About me</a></h4>
            </div>
        </div>
    </div>
</header>
<div class="wrapper wrapper_underline">
    <div class="row">
        <div class="col span12"><br /><br /></div>
    </div>
</div>

<style>
    header {
        text-align: center;
        margin-left: 2%;
        margin-right: 2%;
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
    /* Line for separating navigation block from main content */
    .wrapper_underline {
        border-bottom: 2px solid antiquewhite;
    }
    /* merged columns */
    .col.span2 {
        width: calc((6.77% * 2) + 1.56%);
    }

    .offset-by-seven {
        margin-left: calc(6.77% * 7 + (1.56% * 8));
    }

    .logo {
        font-style: italic;
        text-shadow: 4px 4px 5px antiquewhite;
        text-align: left;
        margin-bottom: 1%;
    }
    /* Buttons for navigation menu */
    .navigation {
        background-color: #7f55db;
        border-radius: 20px;
        margin-top: 2%;
        word-break: break-word;
    }

    .navigation h4 {
        margin: 10% 10% 10% 10%;
    }

    /* Animation for links */
    a{
        color: white;
    }

    a:hover {
        color: #53359f;
    }

    a:focus {
        background: #53359f;
    }

    .row a {
        font-family: "Trebuchet MS";
        text-decoration: none;
    }


</style>
