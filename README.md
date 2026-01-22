# HTML-PaymentForm
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Payment form</title>
    <link rel="StyleSheet" href="Style.css">
    
</head>
<body>
    <div class="container">
    <form action="" method="get" class="form-example">
        <div>
            <h1 class="Action">Payment Form</h1>
            <hr>
            
            <h2>Contact information</h2>
            <p>Name *: <input type="text" name="name" placeholder="Enter the name "></p>
            <p>
                Birth_Date:
                <input type="date" name="date of birth" id="date of birth" >
            </p>
            <p>
            Gender *:
            <fieldset>
                
                <p>
                    male <input type="radio" name="gender" id="male">
                    Female <input type="radio" name="gender" id="female">
                </p>
            </fieldset>
            </p>
            <p> address: <textarea name="address" id="address" cols="100" rows="8"></textarea></p>
            <p> Email *: <input type="email" name="email" id="email" placeholder="Enter Email"required> </p>
            <p> Pin Code *: <input type="number" name="pin_code" id="pin_code" required></p>

            <h2> Payment Form </h2>
            <p> Card type *:
                <select name="card_type" id="card_type">
                    <option value="">----select the card----</option>
                    <option value="visa">Visa</option>
                    <option value="rupees">rupees</option>
                    <option value="master card">master card</option>
                </select>

            </p>
            <p>
                Expiration date *: <input type="date" name="exp_date" id="exp_date" required>
            </p>
            <p>CVV * :<input type="password" name="CVV" id="CVV" required></p>
            <p1>
                <input type="Submit" value="pay Now">
            </p1>
        </div>
        
    </form>
</div>
</body>
</html>
