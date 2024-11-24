
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحه نمونه</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            direction: rtl;
            font-family: Arial, sans-serif;
        }
        header, footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 30px;
        }
        main {
            background-color: rgba(192, 151, 120, 1.00);
            padding: 20px;
        }
        .row {
            display: flex;
            gap: 20px;
        }
        .col {
            flex-basis: calc(25% - 20px); / Adjusted for more columns /
            height: auto; 
        }
    </style>
</head>
<body>
    <header>عنوان صفحه</header>
    <main>
        <article>
            <h2>مقاله نمونه</h2>
            <p>این یک متن نمونه برای مقاله است.</p>
        </article>

        <!-- New Aside Section -->
        <aside style="background-color:#f0f8ff; padding: 15px; margin-top: 20px;">
            <h3>اطلاعات جانبی</h3>
            <p>این یک متن جانبی است که اطلاعات اضافی را ارائه می‌دهد.</p>
        </aside>

        <section class="container">
            <div class="row">
                <!-- First Row -->
                <section style="background-color: gold; width: 100%; padding: 20px;">
                    <div style="background-color: purple; margin-top: 3px; padding: 10px;">محتوای بنفش</div>
                    <div style="background-color: black; margin-top: -10px; padding: 12px;">محتوای سیاه</div>
                </section>

                <!-- New Column -->
                <section style="background-color:red;" class="col">
                    <div style="background-color:white;margin-top :10px;padding :12px;">محتوای سفید</div>
                    <div style="background-color:black;margin-top :-10px;padding :12px;">محتوای مشکی</div>
                </section>

                <!-- Second Column -->
                <section style="background-color: blue;" class="col">
                    <div style="background-color: orange; margin-top: 10px; padding: 12px;">محتوای نارنجی</div>
                    <div style="background-color: gray; margin-top:-10px; padding :11px;">محتوای خاکستری</div>
                </section>

                <!-- Third Column -->
                <section style="background-color:pink;" class="col">
                    <div style="background-color:brown;margin-top :10px;padding :12px;">محتوای قهوه‌ای</div>
                    <div style="background-color :yellow;margin-top :-10px;padding :12px;">محتوای زرد</div>
                </section>

                <!-- New Column -->
                <section style="background-color:#ffcccb;" class="col">
                    <div style="background-color:#ffb6c1;margin-top :10px;padding :12px;">محتوای صورتی روشن</div>
                    <div style="background-color:#cd5c5c;margin-top :-10px;padding :12px;">محتوای قرمز تیره</div>
                </section>

            </div>

            <!-- Second Row -->
            <div class="row" style='margin-top;
