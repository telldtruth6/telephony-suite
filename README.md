# Telephony Suite

## 🚀 Easy VPS Install Instructions

### 1. Log in to your VPS

```bash
ssh root@your-server-ip
```

### 2. Install Git + Docker

```bash
apt update && apt install -y git docker.io docker-compose
```

### 3. Clone the Project

```bash
git clone https://github.com/telldtruth6/telephony-suite.git
cd telephony-suite
```

### 4. Set Up Config

```bash
cp .env.example .env
nano .env
```

Add your Twilio + DB info. Save and exit.

### 5. Run Everything

```bash
docker-compose up -d --build
```

### 6. Open in Browser

Go to `http://your-server-ip`

---

You now have your full IVR + Voicemail + SMS dashboard installed!
