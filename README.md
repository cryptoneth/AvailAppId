


سایت هایی که میری

https://goldberg.avail.tools/#/accounts

ولت پولکادات نصب کن

ولتت رو ریکاوری کن از فایل Json  یا هر چی 

https://polkadot.js.org/extension

وارد سایت زیر شو . وصل کن ولت رو . به خاطر آپدیت نبودن متا دیتا هی ارور میگیری . یا تو خود 
Golderg.Avail  از تو ستینگ ببین ولت PolkaDot  رو میشناسه که اپدیت کنی متا دیتا رو . یا 4 5 بار سایت زیر قطع و وصل شو . ولت رو قطع و وصل کن هی تراکنش Sign  کن آپدیت میشه متا دیتا

مثل فیلم دیگه اسمی که ثبت شد ایدی اپچین رو بگیر



https://app-id-gen.vercel.app




مثل باقی فیلم با این رشته کد



nano /root/.madara/app-chains/(YourAppChainName)/da-config.json



وارد فایل Json شو . قسمت App Id  رو تغیر بده رو ایدی خودت . 

Crtl X
بزن  y بزن سیو شه بعد اینتر بزن

دقت کن اشتباه وارد نکنی یه چیزی از اینور اونور پاک شه بعدا ارور میگیری

حالا مثل فیل وارد Screen  هات شو

کامند های مرسوم اسکرین

screen -ls  لیستشون


screen -x ورود بهش


screen -s ساختش

بعد همه این دستور ساخت و ورود باید ایدی بدی یا اسم

بعدش مجدد مثل فیلم 



./target/release/madara run



یه بار دیگه نود رو ران کن تو اسکرین مربوطش

یه بار دیگه اگر تراکنش زده بودی با داکومنت خود من میتونی وارد اسکرین تراکنش های اسپم بشی و دوباره با کد

go run main.go

چون نود ققطع شده و وصل کردیم اینم قطع میشه

هر جا اروری خوردی حواست باشه تو چه پوشه ای هستی و نکات رو هم گفتم


حالا میریم سراغ رشته کد بعدی





اپدیت نود به  node v20.5.1


sudo apt update

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash


sudo apt install curl


wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash


source ~/.bashrc


nvm --version  


nvm ls


nvm ls-remote


nvm install v20.5.1

نصب starkli


curl https://get.starkli.sh | sh


starkliup


starkli --version   


export STARKNET_RPC="http://localhost:9944/"


Madara Get Started نصب


git clone https://github.com/karnotxyz/madara-get-started


cd ./madara-get-started


npm i


cd


اجرای دستور ها


Declare  کانترکت 


node ./madara-get-started/scripts/declare.js ./madara-get-started/contracts/OpenZeppelinAccountCairoOne.sierra.json ./madara-get-started/contracts/OpenZeppelinAccountCairoOne.casm.json

ساخت کانترکت


node ./madara-get-started/scripts/deploy.js ./madara-get-started/contracts/OpenZeppelinAccountCairoOne.sierra.json 0x1  




ویدیو رو بادقت ببین . دقت کن گفتم اگر مشکل خوردی ورژن از نود بگیر حتما دیدی این ورژن نیست هی اپدیت کن



