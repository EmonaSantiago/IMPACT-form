
    <div class="button-container">
        <a href="#" class="button1">CREATIVE</a>
        <a href="#" class="button">CREW</a>
        <a href="#" class="button">MODEL</a>
      </div>
      <body>
        <h1>IMPACT</h1>
        <div class="container">
            <form action="https://formspree.io/f/xrgnqojg" method="POST">
<!-- 

              <div class="row">
                <div class="col-25">
                    <label for="lname">Brandname</label>
                    <div class="col-75">
                        <input type="text" id="lname" name="Brandname" placeholder="Your Brandname..">
                      </div>
                </div>
              </div> -->

              <div class="row">
                <div class="col-25">
                  <label for="lname">Brandname</label>
                </div>
                <div class="col-75">
                  <input type="text" id="lname" name="Brand name" placeholder="Your Brand name?..">
                </div>
              </div>


              <div class="row">
                <div class="col-25">
                  <label for="lname">insta / website link?</label>
                </div>
                <div class="col-75">
                  <input type="text" id="lname" name="insta / website link" placeholder="Your insta / website link?..">
                </div>
              </div>

              <div class="row">
                <div class="col-25">
                  <label for="lname">Branch</label>
                </div>
                <div class="col-75">
                  <input type="text" id="lname" name="Branch" placeholder="Your branch?..">
                </div>
              </div>


              <div class="row">
                <div class="col-25">
                  <label for="lname">E-mail</label>
                </div>
                <div class="col-75">
                  <input type="text" id="lname" name="E-mail" placeholder="Your E-mail?..">
                </div>
              </div>

              <div class="row">
                <div class="col-25">
                  <label for="lname">Full name</label>
                </div>
                <div class="col-75">
                  <input type="text" id="lname" name="Full name" placeholder="Your Full name?..">
                </div>
              </div>


              <div class="row">
                <div class="col-25">
                  <label for="lname">Telefoon NR.</label>
                </div>
                <div class="col-75">
                  <input type="text" id="lname" name="Telefoon NR." placeholder="Your Phone number? +31..">
                </div>
              </div>


              <div class="row">
                <div class="col-25">
                  <label for="subject">Motivatie message</label>
                </div>
                <div class="col-75">
                  <textarea id="subject" name="subject" placeholder="Write something.." style="height:100px"></textarea>
                </div>
              </div>

              <div class="row">
                <div class="col-25">
                  <label for="subject">motivatie video [bestand]</label>
                </div>
                <div class="col-75">
                    <input id="bestand" type="file" name="attachment" accept="image/png, image/jpeg">
                </div>
              </div>

              

              <div class="row">
                <div class="col-25">
                  <label for="reclame">Hoe ben je hier terecht gekomen?</label>
                </div>
                <div class="col-75">
                  <select id="reclame" name="reclame">
                    <option value="Instagram">Instagram</option>
                    <option value="Tiktok">Tiktok</option>
                    <option value="Sticker">Sticker</option>
                    <option value="mutuals">Mutuals</option>
                  </select>
                </div>
              </div>


              <div class="row">
                <input type="submit" value="SUBMIT">
              </div>
            </form>
          </div>

        
</body>


<style>
* {
    margin: 0;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

:root {
    --main-yellow-: #F8F053;
}

h1 {
        font-size: 110px;
        color: #F8F053;
        text-align: center;
    }

body {
    background-image: url(/src/darkimg.png);
    margin: 1em;
    height: 1000px;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
}

/* button */
.button-container {
      display: flex;
      justify-content: space-between; /* Distribute buttons evenly */
      flex-wrap: wrap; /* Wrap buttons to next line if necessary */
      margin: 0 auto;
      max-width: 600px; /* Adjust max-width as needed */
    }
  
    .button {
      flex: 1; /* Each button takes equal space */
      max-width: 30%; /* Maximum width for each button */
      text-align: center;
      margin: 5px; /* Adjust margin as needed */
      padding: 10px;
      /* background-color: #F8F053; */
      color: white;
      text-decoration: none;
      border: none;
      border: solid #F8F053 1px;
      /* border-radius: 5px; */
      transition: background-color 0.3s;
    }
  
    .button:hover {
      background-color: #F8F053;
    }
  
    @media (max-width: 600px) {
      /* Adjust for smaller screens */
      .button {
        max-width: 100%; /* Full width on smaller screens */
      }
    }

    .button1 {
      flex: 1; /* Each button takes equal space */
      max-width: 30%; /* Maximum width for each button */
      text-align: center;
      margin: 5px; /* Adjust margin as needed */
      padding: 10px;
      background-color: #F8F053;
      color: black;
      text-decoration: none;
      border: none;
      /* border-radius: 5px; */
      transition: background-color 0.3s;
    }
  
    .button1:hover {
      background-color: #F8F053;
    }
  
    @media (max-width: 600px) {
      /* Adjust for smaller screens */
      .button1 {
        max-width: 100%; /* Full width on smaller screens */
      }
    }


    /* form */
    * {
  box-sizing: border-box;
}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  resize: vertical;
}

label {
  padding: 12px 12px 12px 0;
  display: inline-block;
  color: white;
}

input[type=submit] {
  background-color: #F8F053;
  color: black;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
  float: right;
  margin-top: 20em;
}

/* input[type=submit]:hover {
  background-color: #45a049;
} */

.container {
  border-radius: 5px;
  padding: 20px;
}

.col-25 {
  float: left;
  width: 25%;
  margin-top: 6px;
}

.col-75 {
  float: left;
  width: 75%;
  margin-top: 6px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .col-25, .col-75, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}

#bestand {
    color: grey;
}

</style>