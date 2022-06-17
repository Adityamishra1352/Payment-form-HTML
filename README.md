# Payment-form-HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment form"</title>
</head>
<body>
    <form action="">
        <h1>Payment form</h1>
        <h2> Customers details</h2>
        <p>Name: *<input type="text" name="name" required></p>
        <p>Reuqired fields: *</p>
        <fieldset>
        <p>
            <legend>Gender*</legend>
            Male<input type="radio" name="gender" id="male">
            Female <input type="radio" name="gendre" id="Female">
        </p>
        </fieldset>
        <p>Address:* <textarea name="address" id="address" cols="100" rows="8"></textarea></p>
        <p>Email:* <input type="email" name="email" id="email"></p>
        <p>Pincode:* <input type="number" name="number" id="number"></p>
        <hr>
        <h2>Payment information</h2>
        <p>Card type*:
            <select name="card_type" id="card_type">
            <option value="">Select a card type</option>
            <option value="paytm">Paytm</option>
            <option value="vise">Visa</option>
            <option value="mastercard">Mastercard</option>
            <option value="phonepay">PhonePay</option>
            </select>
        </p>
        <p>Card number:* <input type="number" name="cardnumber" id="cardnumber"></p>
        <p>Card expiration:* <input type="date" name="expirationdate" id="expirationdate"></p>
        <p>CVV:* <input type="password" name="cvv" id="cvv"></p>
        <input type="submit" value="Paynow">

    
    </form>
</body>
</html>
