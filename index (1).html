<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ساخت وایرگارد</title>
    <style>
        body {
            background-color: orange;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        select, input, button {
            font-size: 18px;
            padding: 10px;
            margin: 10px;
            display: block;
            width: 300px;
            margin-left: auto;
            margin-right: auto;
        }
        button {
            cursor: pointer;
            color: white;
            border: none;
        }
        .blue-button {
            background-color: blue;
        }
    </style>
</head>
<body>
    <h2>ساخت کانفیگ وایرگارد</h2>

    <label>نوع کشور:</label>
    <select id="country">
        <option value="vip">آلمان وی آی پی</option>
        <option value="gold">آلمان طلا</option>
        <option value="silver">آلمان نقره</option>
    </select>

    <label>حجم کانفیگ (مگابایت):</label>
    <input type="number" id="configSize" placeholder="مثلاً 500">

    <label>مدت زمان استفاده (روز):</label>
    <input type="number" id="days" placeholder="مثلاً 30">

    <button class="blue-button" onclick="generateConfig()">وایر بساز کصکش</button>
    <button class="blue-button" onclick="copyConfig()">وایرتو کپی کن کونی</button>

    <pre id="output"></pre>

    <script>
        function generateRandomString(length) {
            const chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/=";
            let result = "";
            for (let i = 0; i < length; i++) {
                result += chars.charAt(Math.floor(Math.random() * chars.length));
            }
            return result;
        }

        function generateConfig() {
            const privateKey = generateRandomString(44);
            const publicKey = generateRandomString(44);
            const presharedKey = generateRandomString(44);
            const address = `185.101.${Math.floor(Math.random() * 256)}.${Math.floor(Math.random() * 256)}/24`;
            const endpoint = `185.101.76.${Math.floor(Math.random() * 256)}:${Math.floor(30000 + Math.random() * 20000)}`;
            const mtu = 1483;
            const dns = "10.202.10.10";

            const config = `[Interface]
PrivateKey = ${privateKey}
Address = ${address}
DNS = ${dns}
MTU = ${mtu}

[Peer]
PublicKey = ${publicKey}
PresharedKey = ${presharedKey}
Endpoint = ${endpoint}
PersistentKeepalive = 47`;

            document.getElementById("output").innerText = config;
        }

        function copyConfig() {
            const configText = document.getElementById("output").innerText;
            navigator.clipboard.writeText(configText).then(() => {
                alert("وایرگارد کپی شد!");
            }).catch(err => {
                alert("خطا در کپی کردن!");
            });
        }
    </script>
</body>
</html>
