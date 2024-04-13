### 𝙇𝙐𝙓𝙐𝙍𝙔 MD User Bot

A simple WhatsApp User bot.

[![Venocyber tech](https://readme-typing-svg.demolab.com?font=Anton&size=30&pause=998&color=F51FFF&background=F7F2F20A&vCenter=true&random=false&width=465&lines=Hello+Everyone%F0%9F%91%8B!;thank+you+for+visiting+my+site;I+am+venocyber+admin+founder+of+this;project;and+creator+too;i'm+looking+forwad+for+your+feedback;love+you+💖+🫂+💕;please!!;read+carefully+this+document;we+are+not+responsible+for+any;faults+or+mistakes+done;by+misbehaving+this+app+😕🙃)](https://github.com/Kingjux)


<p align="center">
  <a href="https://github.com/Kingjux/luxury-md">
    <img alt="venocyber docs" height="300" src="https://telegra.ph/file/dc496c7502ad45c468984.jpg">
  </a>
</p>

## Setup

1. Deploy on Heroku
   - Click [SCAN](https://qr-hazel-alpha.vercel.app/md) and scan the QR code through the "WhatsApp Linked Devices" option in your WhatsApp app.
   - You will get a session ID in WhatsApp, copy the ID only.
   - If you don't have an account on [Heroku](https://signup.heroku.com/), [create an account now](https://signup.heroku.com/).
   - If you don't have a GitHub account, [sign up](https://github.com/join) now.
   - [FORK](https://github.com/kingjux/luxury-md/fork) this repository.
   - Now [DEPLOY](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Fkingjux%2Fluxury-md).

2. Deploy on Koyeb
   - Create an account on [Koyeb](https://app.koyeb.com/auth/signup). [Sign up now](https://app.koyeb.com/auth/signup).
   - Get [DATABASE_URL](https://github.com/kingjux/luxury-md/wiki/DATABASE_URL). You'll need this while deploying.
   - Get [SESSION_ID](https://qr-hazel-alpha.vercel.app/md). Open Linked Devices in WhatsApp and [SCAN](https://qr-hazel-alpha.vercel.app/md) now.
   - Get the Koyeb API key. [Let's Go](https://app.koyeb.com/account/api).
   - [DEPLOY](https://qr-hazel-alpha.vercel.app/koyeb) now.
   - Enter [Environment Variables](https://github.com/kingjux/luxury-md/wiki/Environment_Variables). [Read More](https://github.com/kingjux/luxury-md/wiki/Environment_Variables).
   - Enter a name and click "Create Service."

3. Deploy on VPS or PC (Example here as in Ubuntu)

   - Install with script

         wget -N -O luxury.sh http://bit.ly/43JqREw && chmod +x luxury.sh && ./luxury.sh

   - Install without a script
       - Install git, ffmpeg, and curl:

             sudo apt -y update && sudo apt -y upgrade
             sudo apt -y install git ffmpeg curl

       - Install nodejs:

             sudo apt -y remove nodejs
             curl -fsSl https://deb.nodesource.com/setup_lts.x | sudo bash - && sudo apt -y install nodejs

       - Install yarn:

             npm install -g yarn

       - Install pm2:

             sudo yarn global add pm2

       - Clone the repository and install packages:

             git clone https://github.com/kingjux/luxury-md botName
              cd botName
               yarn install --network-concurrency 1

       - Enter Environment Variables: Copy-paste the lines below (remove SESSION_ID if not needed):

             echo "SESSION_ID = Session_Id_you_Got_After_Scan_Dont_Add_This_Line_If_You_Can_Scan_From_Terminal_Itself
             PREFIX = .
             STICKER_PACKNAME = Venocyber
             ALWAYS_ONLINE = false
             RMBG_KEY = null
             LANGUAG = en
             WARN_LIMIT = 3
             FORCE_LOGOUT = false
             BRAINSHOP = 159501,6pq8dPiYt7PdqHz3
             MAX_UPLOAD = 200
             REJECT_CALL = false
             SUDO = 255698101622
             TZ = Africa/Dodoma
             VPS = true
             AUTO_STATUS_VIEW = true
             SEND_READ = true
             AJOIN = true
             DISABLE_START_MESSAGE = false
             PERSONAL_MESSAGE = null" > config.env

    - [Read More](https://github.com/kingjux/luxury-md/wiki/Environment_Variables)

    - Edit the `config.env` using nano if needed. To save, press `Ctrl + O`, then press `Enter`, and to exit, press `Ctrl + X`.

    - Start and stop the bot:
        - To start the bot: `pm2 start . --name botName --attach --time`
        - To stop the bot: `pm2 stop botName`

### Thanks To

- [Venocyber](https://github.com/kingjux) for [Whatsbot](https://github.com/kingjux/luxury-md)
- [@happiness](https://github.com/venocybertech) for [he.is.me](https://github.com/kingjux)

