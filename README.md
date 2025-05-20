## 🎯 Learning Objectives

- Build a basic username/password login flow
- Simulate brute-force login attempts
- Apply rate limiting and lockout protection
- Implement audit logging (console, file, remote)
- Understand how attackers exploit login endpoints

## 🔓 Security Audit Targets

- ❌ Unlimited login attempts  
- ❌ No logging of login events  
- ❌ No CAPTCHA or lockout timer  
- ❌ No MFA or user notifications  

## ✅ Features

- Flask-based login form
- Brute-force simulation and defense
- Rate limiting via `Flask-Limiter`
- Audit log written to file
- Optional remote logging (webhook/syslog)

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/flask-brute-force-lab.git
cd flask-brute-force-lab
python -m venv venv
source venv/bin/activate  # Windows: venv\\Scripts\\activate
pip install -r requirements.txt
flask run
