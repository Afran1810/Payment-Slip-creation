<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Form</title>
</head>
<body>
    <form>
        <h1>payment form</h1>
        <h2>Contruct Info</h2>
        <p>Name:* <input type="" name="name" required></input> </p>
        <fieldset>
            <legend>Gender</legend>
            <p>
                 Male <input type="radio" name="gender" id="Male"> Female <input type="radio" name="gender" id="Female">
            </p>
        </fieldset>
        <p>Address:* <textarea name="address" id="address" cols="100" rows="10" required></textarea></p>
        <p>Email:* <input type="email" name="email" id="email" col="50" row="10" required></p>
        <p>Pincode:* <input type="number" name="Pincode" id="Pincode" col="40" row="8" required></p>
        <hr>
        <h1>Payment Info</h1>
        <p>required filled by *</p>
        <p>
            Payment Mathod:
            <select name="payment method" id="payment method">
                <option value="Bkash">Bkash</option>
                <option value="Nagad">Nagad</option>
            </select>
        </p>
        <p>Number:* <input type="number" name="number" id="number"required></p>
        <p>Amount:* <input type="number" name="Amount" id="Amount" required></p>
        <p>Transection Id:* <input type="" name="transection id" id="transection id" required></p>
        <p>Pin Number:* <input type="number" name="Pin" id="Pin"></p>
        <P>Date:* <input type="date" required></P>
        <input type="submit" name="submit" value="Pay Now" id="submit">
    </form>
</body>
</html>`
