<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing Table</title>
    <style>
         body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #7e959992;
        }
        .pricing-table {
            display: flex;
            justify-content: space-around;
            width: 80%;
            max-width: 1200px;
        }
        .pricing-plan {
            background: #3b7975fe;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            text-aling:center;
            flex: 1;
            margin: 0 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .pricing-plan h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }
        .pricing-plan .price {
            font-size: 36px;
            color: #333;
            margin-bottom: 20px;
        }
        .pricing-plan .price span {
            font-size: 16px;
            color: #777;
        }
        .pricing-plan ul {
            list-style: none;
            padding: 0;
            margin-bottom: 20px;
        }
        .pricing-plan ul li {
            margin: 10px 0;
            color: #555;
        }
        .pricing-plan button {
            background: #39597a;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        .pricing-plan button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>

<div class="pricing-table">
    <div class="pricing-plan">
        <h2>Basic</h2>
        <div class="price">$10<span>/month</span></div>
        <ul>
            <li>1 Website</li>
            <li>10 GB Storage</li>
            <li>Basic Support</li>
        </ul>
        <button>Sign Up</button>
    </div>
    <div class="pricing-plan">
        <h2>Pro</h2>
        <div class="price">$25<span>/month</span></div>
        <ul>
            <li>5 Websites</li>
            <li>50 GB Storage</li>
            <li>Priority Support</li>
        </ul>
        <button>Sign Up</button>
    </div>
    <div class="pricing-plan">
        <h2>Premium</h2>
        <div class="price">$50<span>/month</span></div>
        <ul>
            <li>Unlimited Websites</li>
            <li>Unlimited Storage</li>
            <li>24/7 Support</li>
        </ul>
        <button>Sign Up</button>
    </div>
</div>

</body>
</html>
