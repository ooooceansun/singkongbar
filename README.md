<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>星空纪民谣音乐酒馆 - 每日抽奖活动</title>
    <style>
        body {
            font-family: 'Microsoft YaHei', sans-serif;
            background-color: #1a1a2e;
            color: #fff;
            margin: 0;
            padding: 0;
            background-image: url('https://example.com/starry-sky.jpg'); /* 替换为您的星空背景图 */
            background-size: cover;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
            margin-top: 50px;
        }
        h1 {
            text-align: center;
            color: #f8c537;
            margin-bottom: 30px;
        }
        .prize {
            text-align: center;
            font-size: 24px;
            margin-bottom: 30px;
            color: #f8c537;
        }
        .time {
            text-align: center;
            font-size: 18px;
            margin-bottom: 30px;
        }
        .form-group {
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            border: none;
            background-color: rgba(255, 255, 255, 0.9);
        }
        button {
            background-color: #f8c537;
            color: #000;
            border: none;
            padding: 12px 30px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            display: block;
            margin: 0 auto;
            transition: all 0.3s;
        }
        button:hover {
            background-color: #ffd700;
            transform: scale(1.05);
        }
        .rules {
            margin-top: 30px;
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 5px;
        }
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 14px;
            color: #aaa;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>星空纪民谣音乐酒馆</h1>
        <div class="prize">每日抽奖：价值198元豪华威士忌套餐</div>
        <div class="time">每日开奖时间：下午5点 · 每日20位幸运顾客</div>
        
        <form id="lotteryForm">
            <div class="form-group">
                <label for="name">您的姓名：</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="phone">联系电话：</label>
                <input type="tel" id="phone" name="phone" required>
            </div>
            
            <button type="submit">立即参与抽奖</button>
        </form>
        
        <div class="rules">
            <h3>活动规则：</h3>
            <ul>
                <li>每日抽奖一次，开奖时间为下午5点</li>
                <li>每日产生20位幸运顾客</li>
                <li>中奖者将收到短信通知</li>
                <li>奖品为价值198元豪华威士忌套餐</li>
                <li>中奖后请在7天内凭短信到店领取</li>
                <li>每人每天限参与一次</li>
            </ul>
        </div>
        
        <footer>
            © 2023 星空纪民谣音乐酒馆 保留所有权利
        </footer>
    </div>

    <script>
        document.getElementById('lotteryForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            const phone = document.getElementById('phone').value;
            
            // 这里应该添加表单验证和提交到后端的代码
            // 实际应用中，您需要将数据发送到服务器进行处理
            
            alert('感谢参与！抽奖结果将在开奖后通过短信通知。');
            document.getElementById('lotteryForm').reset();
        });
    </script>
</body>
</html>
