<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Currency Converter</title>
    <link href="style.css" rel="stylesheet" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/money.js/0.1.3/money.min.js" integrity="sha512-wONtKxSNySBmha5jvJFjqWxzHFI4y5bGfPCz5B1VWvUrCf9xxOvlPaiGVG5a0LSvaKYoThRofSyt10mnHGw0GA==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
  </head>
  
  <body>
    <div class="container">
      <h2>Currency Converter</h2>
      <form>
        <div class="amount">
          <p>Enter Amount</p>
          <input value="1000" type="text" />
        </div>

        <div class="dropdown">

          <div class="from">
            <p>From</p>

            <div class="select-container">
              <img src="https://flagsapi.com/US/flat/64.png" alt="not found"/>
              <select name="from">
                <option value="USD">USD</option>
                <option value="INR">INR</option>
                <option value="AUD">AUD</option>
                <option value="PKR">PKR</option>
              </select>
            </div>
          </div>
          <i class="fa-solid fa-right-left"></i>
          <div class="to">
            <p>To</p>
            <div class="select-container">
              <img src="https://flagsapi.com/US/flat/64.png" alt="not found"/>
              <select name="to">
                <option value="USD">USD</option>
                <option value="INR">INR</option>
                <option value="AUD">AUD</option>
                <option value="PKR">PKR</option>
              </select>
            </div>
          </div>
          <div class="msg-container">IUSD=272PKR</div>
          <button>Get Exchange Rate</button>
        </div>
      </form>
    </div>
  </body>
</html>
