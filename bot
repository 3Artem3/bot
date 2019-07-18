const Discord = require("discord.js");
const client = new Discord.Client();
client.login("NTc2NzUxMDk5OTMyMDQ5NDA4.XQUD6g.uY8Hj2O2tMMq5mVuymLYE7HDPOQ");

var prefix = "О!";

client.on("message", (message) => {
if(message.content == prefix + "сервер инфо ") // /prefix
{
    message.channel.send("");
    message.channel.send("Информация о сервере");
    message.channel.send("Название сервера",message.guild.name);
    message.channel.send("Создание сервера",message.guild.createdAt);
    message.channel.send("Вы присоеденились к серверу",message.guild.joinedAt);
    message.channel.send("Кол-Во участников",message.guild.memberCount);
    message.channel.send("Регион",message.guild.region);
}
});

client.on("message", (message) => {
var msg = message.content;
if(msg.substr(0, 5) == prefix + "send")
{
var forwrite = msg.substr(6);
message.delete(1);
message.channel.send(forwrite);
console.log(message.author.tag + " написал /send " + forwrite);
console.log(message.author.tag + " Написал Спам " + forwrite)

}
});
