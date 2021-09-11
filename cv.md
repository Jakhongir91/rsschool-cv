# Nishonboev Jakhongir

# Contacts:
- Phone number: <a href="tel:998999016280">+*998(99) 901-62-80*</a>
- Telegram: [*@jakhong*](https://t.me/jakhong "Telegram")
- Twitter: [*@Jakhong17324300*](https://twitter.com/Jakhong17324300 "Twitter")
- Github: [*@jakhongir91*](https://github.com/jakhongir91 "Github")
# About me:
Hi there, I am backend developer. I have 5+ year experience in developing backend systems using Laravel, php 7+, redis, Linux, MySql 8 and I always try to learn something new in IT development.
I try to follow SOLID and KISS principles, OOP and Design Patters. I am interested in designing complex projects using architecture based on microservices. At the moment I decided to take RsSchool courses to improve my basic frontend skills to become a fullstack developer.
# Skills:
<table>
<th>Skill</th>
<th>Experience</th>

<tr>
    <td>
        <b>Laravel framework</b>
    </td>
    <td>
        <i>5+ years using, about 3 completed projects</i>
    </td>
</tr>
<tr>
    <td>
        <b>Yii2 framework</b>
    </td>
    <td>
        <i>1 completed project, worked in team of 3 developers</i>
    </td>
</tr>
<tr>
    <td>
        <b>PHP framework</b>
    </td>
    <td>
        <i>supported admin panel, which had about 5-6 entities and CRUD operations for each one</i>
    </td>
</tr>
<tr>
    <td>
        <b>Slim framework</b>
    </td>
    <td>
        <i>one small application, which gets trailers from iTunes trailers and showing them on main page</i>
    </td>
</tr>
<tr>
    <td>
        <b>PHP</b>
    </td>
    <td>
        <i>about 5 years of working experience</i>
    </td>
</tr>
<tr>
    <td>
        <b>Html, css, js</b>
    </td>
    <td>
        <i>very basic knowledge</i>
    </td>
</tr>
<tr>
    <td>
        <b>GIT</b>
    </td>
    <td>
        <i>using GIT during almost all my working experience</i>
    </td>
</tr>
<tr>
    <td>
        <b>node.js</b>
    </td>
    <td>
        <i>developed online chat and online game for 2 players, using socket.io</i>
    </td>
</tr>
</table>

# Code sample
Below is `javascript` code sample, which is written by me for `Postman` application, to retrieve cookies from authorization response and store them in cookies manager, so that basic web authorization can be passed for each of api methods defined in same collection.

```javascript
// 1. Get response headers
let headers = pm.response.headers.all();

// 2. Create cookie jar
const cookieJar = pm.cookies.jar();

function setAuthCookies(header) {
    if (header.key === "Set-Cookie") {
        let responseHeader = header.value.substr(0, header.value.indexOf(';'));
        let [cookieName, cookieValue] = responseHeader.split('=');
        
        cookieJar.set(pm.environment.get('url'), cookieName, cookieValue, null);
    }
}

headers.forEach(header => setAuthCookies(header));
```
# Work experience
* 5 years experience in Laravel and php 7+,
* CRM systems support
* developing online shops,
* payment integration, integrations with third party services such as Telegram Bots, VK, WhatsApp and Instagram

# Education
Bachelor degree in programming engineering, Tashkent University of Information Technologies

# English level
* Able to read docs
* communicate in social chats dedicated to IT
