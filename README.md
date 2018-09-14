const Discord = require('discord.js');
const client = new Discord.Client();
 
client.on('ready', () => {
  console.log(`${client.user.tag} olarak giriş yaptım. Hadi eyw`);
});
 
client.on('message', msg => {
  if (msg.content === 'ping') {
    msg.reply('Pong!');
  }
});
 
client.login('ÇOKGİZLİBİRŞEY');
