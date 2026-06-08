<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Payment Verified</title>
<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family: Arial, Helvetica, sans-serif;
    }

    body{
        background:#f3f3f3;
        display:flex;
        justify-content:center;
        align-items:center;
        min-height:100vh;
    }

    .card{
        width:460px;
        background:#fff;
        border-radius:20px;
        padding:25px 22px;
        box-shadow:0 4px 20px rgba(0,0,0,0.08);
    }

    .logo{
        text-align:center;
        margin-bottom:15px;
    }

    .logo img{
        height:40px;
    }

    .check-box{
        width:70px;
        height:70px;
        margin:0 auto 15px;
        background:#edf4fb;
        border-radius:14px;
        display:flex;
        align-items:center;
        justify-content:center;
        font-size:36px;
        color:#0070ba;
    }

    .title{
        text-align:center;
        font-size:18px;
        font-weight:700;
        margin-bottom:5px;
    }

    .subtitle{
        text-align:center;
        color:#666;
        font-size:15px;
    }

    .success{
        text-align:center;
        color:#12a63b;
        font-size:16px;
        font-weight:700;
        margin-top:5px;
        text-transform:uppercase;
    }

    hr{
        margin:22px 0;
        border:none;
        border-top:1px solid #ddd;
    }

    .details{
        width:100%;
    }

    .row{
        display:flex;
        justify-content:space-between;
        padding:6px 0;
        font-size:16px;
    }

    .label{
        color:#444;
    }

    .value{
        font-weight:600;
        color:#111;
    }

    .total{
        margin-top:15px;
        padding-top:15px;
        border-top:1px solid #ddd;
        display:flex;
        justify-content:space-between;
        align-items:center;
    }

    .total .text{
        font-size:18px;
        font-weight:700;
    }

    .total .amount{
        color:#0070ba;
        font-size:30px;
        font-weight:700;
    }

    .btn{
        width:100%;
        border:none;
        border-radius:12px;
        padding:14px;
        font-size:17px;
        font-weight:600;
        cursor:pointer;
        margin-top:14px;
    }

    .support{
        background:#0070ba;
        color:#fff;
    }

    .secondary{
        background:#f5f7fb;
        color:#0070ba;
        border:1px solid #d8e0f0;
    }
</style>
</head>
<body>

<div class="card">

    <div class="logo">
        <img src="https://www.paypalobjects.com/webstatic/icon/pp258.png" alt="PayPal">
    </div>

    <div class="check-box">✓</div>

    <div class="title">Payment Verified</div>
    <div class="subtitle">Your transaction is confirmed</div>
    <div class="success">SUCCESS</div>

    <hr>

    <div class="details">
        <div class="row">
            <span class="label">Product</span>
            <span class="value">BTC (Bitcoin)</span>
        </div>

        <div class="row">
            <span class="label">Order ID</span>
            <span class="value">ORD-984512</span>
        </div>

        <div class="row">
            <span class="label">Order Date</span>
            <span class="value">24 April 2026</span>
        </div>

        <div class="row">
            <span class="label">Payment Method</span>
            <span class="value">PayPal Balance</span>
        </div>
    </div>

    <div class="total">
        <span class="text">Total Paid</span>
        <span class="amount">$479.85</span>
    </div>

    <button class="btn support">
        📞 Customer Support: +1-828-235-6271
    </button>

    <button class="btn secondary">
        📄 Download Invoice (PDF)
    </button>

    <button class="btn secondary">
        📦 View Full Order Details
    </button>

</div>

</body>
</html>
