<style>
/* Float four columns side by side */
.column {
  float: left;
  width: 40%;
  padding: 0 10px;
}
/* Remove extra left and right margins, due to padding in columns */
.row {margin: 0 -5px;}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
.card {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  margin-bottom: 30px;
  width: 300px;
}

/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

/* Add some padding inside the card container */
.container {
  padding: 2px 16px;
}
</style>

<div class="row">
  <div class="column">
    <div class="card">
        <a href="" target="">
        <img src="/images/code.jpg" alt="Avatar" style="width:100%">
        </a>
        <div class="container">
            <h4><b>Coming soon!!!!</b></h4>
            <p></p>
        </div>
    </div>
  </div>
  <div class="column">
    <div class="card" >
        <a href="" target="">
        <img src="/images/code.jpg" alt="Avatar" style="width:100%" >
        </a>
        <div class="container" >
            <h4><b>Coming soon!!!!</b></h4>
            <p></p>
        </div>
    </div>
  </div>
</div>
