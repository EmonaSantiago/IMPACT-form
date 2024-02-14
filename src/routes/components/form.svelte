<body>

    <div class="container">
      <div class="content">
        <h1>Form Title</h1>
        <p>This is the introduction text. You can add any information or instructions here.</p>
      </div>
      <div class="form">
        <form action="#" method="post">
          <label for="name">Name:</label><br>
          <input type="text" id="name" name="name"><br>
          <label for="email">Email:</label><br>
          <input type="email" id="email" name="email"><br><br>
          <input type="submit" value="Submit">
        </form>
      </div>
    </div>
    
    </body>

    <style>
        body {
          font-family: Arial, sans-serif;
          margin: 0;
          padding: 0;
          display: flex;
          justify-content: center;
          align-items: center;
          height: 100vh;
          background-color: #f0f0f0;
        }
        
        .container {
          display: flex;
          flex-wrap: wrap;
          max-width: 800px;
          background-color: #fff;
          border-radius: 10px;
          box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        
        .content {
          flex: 1;
          padding: 20px;
        }
        
        .form {
          flex: 1;
          padding: 20px;
          background-color: #f9f9f9;
          border-left: 1px solid #ccc;
        }
        
        h1 {
          margin-top: 0;
        }
        
        @media (max-width: 768px) {
          .container {
            flex-direction: column;
          }
          
          .form {
            border-left: none;
            border-top: 1px solid #ccc;
          }
        }
      </style>